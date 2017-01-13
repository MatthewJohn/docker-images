# This Dockerfile is used to build an image for CentOS 6 with base applications
FROM centos:centos6
MAINTAINER Matthew John <matthew@dockstudios.co.uk>

RUN yum -y update && yum -y groupinstall Base

# Default command
CMD ["/bin/bash"]
