FROM python:3.9.7

LABEL author="Duy Nguyen <duynguyenngoc@hotmail.com>"

WORKDIR /work

# Install OpenJDK-11
RUN apt update && \
    apt-get install -y openjdk-11-jdk && \
    apt-get install -y ant && \
    apt-get clean;


# Set JAVA_HOME
ENV JAVA_HOME /usr/lib/jvm/java-11-openjdk-amd64/
RUN export JAVA_HOME


# Copy lab config
COPY ./config/jupyter_lab_config.py /root/.jupyter/jupyter_lab_config.py
COPY ./config/jupyter_server_config.py /root/.jupyter/jupyter_server_config.py


# Install Requirement python3 pip
COPY ./requirements.txt ./requirements.txt 
RUN pip install jupyterlab==3.2.9
RUN pip install -r requirements.txt


EXPOSE 8888

# ENTRYPOINT ["jupyter-lab", "--ip 0.0.0.0", "--allow-root"]