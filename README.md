# lab-spark
This project sharing Notebook on AI, Bigdata, Realtime analytic, Monitoring ... Instructions for building a lab test environment with multiple components. Include but not limit: haddoop, spark, kafka. 

## Structure
```python
├── jupyterlab -> contains config jupyterlab
├── share_storages
    ├── lab -> All notebook
    ├── data -> public data like image, ai-model, csv ..
        ├── dataset
            ├── dogs-vs-cats
            ...
        ├── image
        ├── model
├── docker-compose.yaml -> run server
...
```

## Posts and Notebooks
**Note:** Corresponding to each article is a Notebook of the same name in the path ```share_storages/lab```

#### 1. [Spark Distributed ML model with Pandas UDFs](https://viblo.asia/p/spark-distributed-ml-model-with-pandas-udfs-maGK7rWe5j2)    --->    [Notebook](https://github.com/dnguyenngoc/lab-spark/blob/main/share_storages/lab/Distributed%20ML%20model%20with%20Pandas%20UDFs.ipynb) (2022/03/22)

#### 2. [Cats vs Dogs Classification using CNN Keras](https://viblo.asia/p/cats-vs-dogs-classification-using-cnn-keras-1Je5EAx15nL)    --->    [Notebook](https://github.com/dnguyenngoc/lab-spark/blob/main/share_storages/lab/Cats%20vs%20Dogs%20Classification%20using%20CNN%20Keras.ipynb) (2022/03/28)

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

![Test](public/image.gif)


## Contact Us
- Email-1: duynnguyenngoc@hotmail.com - Duy Nguyen :heart: :heart: :heart: 