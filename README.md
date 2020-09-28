### ElasticSearch Kibana Map example

##### Taken from https://blog.bigdataboutique.com/2020/03/visualizing-covid-19-spread-with-elasticsearch-and-kibana-part-1-8hbp2u

#### Install Docker

```aidl
sudo snap install docker
```




1.  Clone this module both on ec2 and on your local machine

```aidl
   git clone https://github.com/marilynwaldman/docker-services
   cd docker-services
```

2.  Run docker-compose  up to start services
```aidl
    sudo docker-compose up -d
```
3.  Follow instructions from the above blog

```aidl
http://ec2-35-163-8-236.us-west-2.compute.amazonaws.com:5601
```

4.  Run docker-compose down to stop services
```aidl
    sudo docker-compose down -v
```


