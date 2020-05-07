FROM centos:8
MAINTAINER knik "nikita.hldm@gmail.com"

RUN dnf -y install https://download-ib01.fedoraproject.org/pub/epel/epel-release-latest-8.noarch.rpm \
    && dnf -y update \
    && dnf -y groupinstall 'Development Tools' \
    && dnf -y --enablerepo=PowerTools install \
        kernel-devel \
        ImageMagick-devel \
        bzip2-devel \
        libcurl-minimal \
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
    && dnf -y clean all