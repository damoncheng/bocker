FROM damoncheng/centos:7

RUN mkdir /script && yum install -y epel-release && yum install -y stress

RUN yum install -y jq

COPY script /script
