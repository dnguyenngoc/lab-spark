# lab-spark
This project sharing Notebook on AI, Bigdata, Realtime analytic, Monitoring ... Instructions for building a lab test environment with multiple components. Include but not limit: haddoop, spark, kafka. 

## Structure
```python
├── jupyterlab -> contains config jupyterlab
├── share_storages
    ├── lab -> All notebook
    ├── data -> public data like image, ai-model, csv ..
        ├── image
        ├── model
├── docker-compose.yaml -> run server
...
```

## Start Lab

### 1. Clone repo

```shell
git clone https://github.com/dnguyenngoc/lab-spark.git \
    && cd lab-spark 
```

### 2. Build with docker

```shell
docker-compose -f <docker-compose file .yaml> up
```

| Service               | URL                              |  user/pass   |
| :-------------------: | :------------------------------: | :----------: |
| Jupyterlab            | http://localhost:8888            | 1q2w3e4r     |

![Test](public/test.png)


## Contact Us
- Email-1: duynnguyenngoc@hotmail.com - Duy Nguyen :heart: :heart: :heart: 