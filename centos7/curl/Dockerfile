FROM centos:7
MAINTAINER Yuya.Nishida.

# Following codes are modified from:
# https://github.com/docker-library/buildpack-deps/blob/b0fc01aa5e3aed6820d8fed6f3301e0542fbeb36/stretch/curl/Dockerfile

RUN yum update -y && yum install -y \
		ca-certificates \
		curl \
		netbase \
		wget \
	&& rm -rf /var/lib/apt/lists/*
