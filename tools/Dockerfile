FROM centos:7.3.1611

RUN yum -y install wget && \
    yum -y install epel-release && yum -y install patchelf && \
    yum -y install gcc make python-devel && \
    yum clean all && \
    curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py && \
    python get-pip.py && rm get-pip.py
