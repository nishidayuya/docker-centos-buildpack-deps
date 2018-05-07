FROM nishidayuya/centos-buildpack-deps:centos7-curl
MAINTAINER Yuya.Nishida.

# Following codes are modified from:
# https://github.com/docker-library/buildpack-deps/blob/b0fc01aa5e3aed6820d8fed6f3301e0542fbeb36/stretch/scm/Dockerfile

# procps is very common in build systems, and is a reasonably small package
RUN yum update -y && yum install -y \
		bzr \
		git \
		mercurial \
		openssh-clients \
		subversion \
		\
		procps \
	&& rm -rf /var/cache/yum/*
