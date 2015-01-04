# Base CentOS 7
# Includes epel repo for local build

FROM centos:latest

MAINTAINER Eric Weber

RUN yum update -y && yum install net-tools tar wget unzip perl -y && yum clean all && \
    wget http://dl.fedoraproject.org/pub/epel/7/x86_64/e/epel-release-7-2.noarch.rpm -q && \
    yum localinstall epel-release-7-2.noarch.rpm -y && \
    rm epel-release-7-2.noarch.rpm && \ yum update -y && yum clean all

RUN yum -y install pwgen && yum clean all
RUN yum -y update -y
