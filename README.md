![Generic Badges](https://img.shields.io/github/languages/code-size/JuanPabloJimenezEsclusa/elasticsearch?style=plastic)
![GitHub top language](https://img.shields.io/github/languages/top/JuanPabloJimenezEsclusa/elasticsearch?style=plastic)
![GitHub commit activity](https://img.shields.io/github/commit-activity/y/JuanPabloJimenezEsclusa/elasticsearch?style=plastic)
![GitHub tag (latest SemVer)](https://img.shields.io/github/v/tag/JuanPabloJimenezEsclusa/elasticsearch?style=plastic)
![GitHub All Releases](https://img.shields.io/github/downloads/JuanPabloJimenezEsclusa/elasticsearch/total?style=plastic)

# elasticsearch

## About

Project to test Elastic Stack

## Estructure 
```
.
├── docker-compose.yml
├── elasticsearch
│   ├── config/elasticsearch.yml
│   ├── Dockerfile
│   └── storage
├── filebeat
│   ├── config/filebeat.yml
│   └── Dockerfile
├── kibana
│   ├── config/kibana.yml
│   └── Dockerfile
├── logstash
│   ├── config/logstash.yml
│   ├── Dockerfile
│   ├── logfile
│   └── pipeline
│       ├── 01.apache.conf
│       └── 02.nginx.conf
├── nginx
│   ├── data
│   ├── etc/nginx.conf
│   ├── log
│   └── public/index.html
└── README.md
```

## Usage

```
docker-compose up -d --build
```
