FROM centos:centos7
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
        libxml2-devel \
        libxslt-devel \
        zlib-devel \
        libyaml-devel \
        glibc-static \
        libstdc++-static \

        wget \
        which \
        mercurial \
        git \
        tar \
    && yum clean all

