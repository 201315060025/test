FROM centos:latest
MAINTAINER lixr
RUN yum -y update
RUN yum -y install systemd systemd-libs
RUN yum clean all;
VOLUME [ "/sys/fs/cgroup" ]
CMD ["/usr/sbin/init"]

