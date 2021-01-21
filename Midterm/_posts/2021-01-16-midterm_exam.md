---
layout: post
title:  "Hands-on Midterm Exam"
date:   2021-01-20 22:57:58 +0800
category: Midterm
image: /assets/midterm/Mexam.png
---
1. Fork this repository https://github.com/ajcanlas-tip/sysad2-12021.git (Links to an external site.)

2. Clone your new repository in your VM https://github.com/< your username >/sysad2-12021.git

3. Create a branch named "midterm-exam" and checkout in that branch. 

4. Create an Ansible playbook that does the following with an input of a config.yaml file and arranged Inventory file:

4.1 Install and configure Elastic Stack in separate  hosts (Elastic Search, Kibana, Logstash)

4.2 Install Nagios in one host

4.3 Install Grafana,Prometheus and Influxdb in seperate hosts (Influxdb,Grafana,Prometheus)

4.4 Install Lamp Stack in seperate hosts (Httpd + Php,Mariadb)

5. push and commit your midterm-exam branch in the VM (no need for ansible.cfg upon pushing)

6. request a pull request from that branch in GitHub

7. For your midterm exam to be counted, please paste your repository link as an answer in this exam.

OUTPUT: https://github.com/mcarangan-tip/sysad2-12021/tree/midterm-exam

```
.  
├── README.md  
├── \  
├── ansible.cfg  
├── centos  
│   ├── elk  
│   │   ├── README.md  
│   │   ├── defaults  
│   │   │   └── main.yml  
│   │   ├── files  
│   │   ├── handlers  
│   │   │   └── main.yml  
│   │   ├── meta  
│   │   │   └── main.yml  
│   │   ├── tasks  
│   │   │   └── main.yml  
│   │   ├── templates  
│   │   ├── tests  
│   │   │   ├── inventory  
│   │   │   └── test.yml  
│   │   └── vars  
│   │       └── main.yml  
│   ├── gpi  
│   │   ├── README.md  
│   │   ├── defaults  
│   │   │   └── main.yml  
│   │   ├── files  
│   │   ├── handlers  
│   │   │   └── main.yml  
│   │   ├── meta  
│   │   │   └── main.yml  
│   │   ├── tasks  
│   │   │   └── main.yml  
│   │   ├── templates  
│   │   ├── tests  
│   │   │   ├── inventory  
│   │   │   └── test.yml  
│   │   └── vars  
│   │       └── main.yml  
│   ├── lamp  
│   │   ├── README.md  
│   │   ├── defaults  
│   │   │   └── main.yml
│   │   ├── files  
│   │   ├── handlers  
│   │   │   └── main.yml  
│   │   ├── meta  
│   │   │   └── main.yml  
│   │   ├── tasks  
│   │   │   └── main.yml  
│   │   ├── templates  
│   │   ├── tests  
│   │   │   ├── inventory  
│   │   │   └── test.yml  
│   │   └── vars  
│   │       └── main.yml  
│   └── nagios  
│       ├── README.md  
│       ├── defaults  
│       │   └── main.yml  
│       ├── files  
│       ├── handlers  
│       │   └── main.yml  
│       ├── meta  
│       │   └── main.yml  
│       ├── tasks  
│       │   └── main.yml  
│       ├── templates  
│       ├── tests  
│       │   ├── inventory  
│       │   └── test.yml  
│       └── vars  
│           └── main.yml  
├── config.yaml  
├── elasticksearch.repo  
├── files  
│   ├── 02-beats-input.conf  
│   ├── 10-syslog-filter.conf  
│   ├── 30-elasticsearch-output.conf  
│   └── filebeat.yml  
├── grafana.repo  
├── influxdb.repo  
├── logstash.conf  
├── midterminv  
├── playbookmidterm.yml  
├── prometheus.repo  
├── roles  
│   ├── centos  
│   └── ubuntu  
└── ubuntu  
    ├── elk  
    │   ├── README.md  
    │   ├── defaults  
    │   │   └── main.yml  
    │   ├── files  
    │   ├── handlers  
    │   │   └── main.yml  
    │   ├── meta  
    │   │   └── main.yml  
    │   ├── tasks  
    │   │   └── main.yml  
    │   ├── templates  
    │   ├── tests  
    │   │   ├── inventory  
    │   │   └── test.yml  
    │   └── vars  
    │       └── main.yml  
    ├── gpi  
    │   ├── README.md  
    │   ├── defaults  
    │   │   └── main.yml  
    │   ├── files  
    │   ├── handlers  
    │   │   └── main.yml  
    │   ├── meta  
    │   │   └── main.yml  
    │   ├── tasks  
    │   │   └── main.yml  
    │   ├── templates  
    │   ├── tests  
    │   │   ├── inventory  
    │   │   └── test.yml  
    │   └── vars  
    │       └── main.yml  
    └── lamp  
        ├── defaults  
        │   └── main.yml  
        ├── files  
        ├── handlers  
        │   └── main.yml  
        ├── meta  
        │   └── main.yml  
        ├── tasks  
        │   └── main.yml  
        ├── templates  
        ├── tests  
        │   ├── inventory  
        │   └── test.yml  
        └── vars  
            └── main.yml  
```