FROM ansible/centos7-ansible

WORKDIR /playbook

RUN yum install -y sshpass nc

RUN pip install zabbix-api

VOLUME /playbook
