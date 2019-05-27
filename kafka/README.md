Role Name
=========

Ansible role to setup kafka cluster with JMX exporter to export matrices to prometheus and monitoring through grafana. 

1- Install kafka with zookeeper
2- Get JMX exporter
3- Run Kafka Cluster with JMX exporter to erxport cluster matrices to promethius
4- Install Promethius
5- Install Docker
6- Run Grafana in docker

Requirements
------------

Linux OS - Debian

Role Variables
--------------
kafka_version: 2.11

Example Playbook
----------------

   - hosts: localhost
  roles:
    - { role: kafka, become: yes }

Author Information
------------------

Shubh Joshi
