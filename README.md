### ElasticSearch Kibana Map example

##### Taken from https://blog.bigdataboutique.com/2020/03/visualizing-covid-19-spread-with-elasticsearch-and-kibana-part-1-8hbp2u

#### Install Docker

sudo snap install docker

```aidl
sudo apt install default-jre            
sudo apt install openjdk-11-jre-headless
sudo apt install openjdk-8-jre-headless 
```
1.  Clone this module

```aidl
   git clone https://github.com/marilynwaldman/docker-services
   cd docker-services
```

2.  Run docker-compose  up to start services
```aidl
    sudo docker-compose up -d
```
3.  Follow instructions from the above blog

4.  Run docker-compose down to stop services
```aidl
    sudo docker-compose down -v
```


