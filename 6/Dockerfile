FROM centos:centos6
MAINTAINER knik "nikita.hldm@gmail.com"

RUN yum -y update && yum -y groupinstall 'Development Tools' && yum -y install \
        kernel-devel \
        ImageMagick-devel \
        bzip2-devel \
        libcurl \
        libcurl-devel \
        openssl-devel \
        libevent-devel \
        libffi-devel \
        glib2-devel \
        libjpeg-devel \
        mysql-devel \
        postgresql-devel \
        ncurses-devel \
        readline \
        readline-devel \
        sqlite-devel \
        openssl \
        openssl-devel \
        libxml2-devel \
        libxslt-devel \
        zlib-devel \
        glibc-static \
        libstdc++-static \
        wget \
        git \
        bzr \
        mercurial \
        tar \
    && yum clean all

RUN rpm --import http://dl.fedoraproject.org/pub/epel/RPM-GPG-KEY-EPEL-6 \
    && rpm -Kih http://dl.fedoraproject.org/pub/epel/6/x86_64/epel-release-6-8.noarch.rpm \
    && yum -y install libyaml-devel \
    && yum clean all
    
