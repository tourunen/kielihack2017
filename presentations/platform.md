% Digipalvelutehdas platform for Kielihack
% Olli Tourunen/CSCfi 2017

# Overview

## Digipalvelutehdas

http://www.digipalvelutehdas.fi

Provides support and tooling for open source, containerized service development using
national service architecture.

Run by Ministry of Education and Culture

## Kielihack platform in short

- container orchestration system
- running [OpenShift Origin](https://www.openshift.org) 1.4.1
- reachable at https://eduhack.digipalvelutehdas.fi:8443
- dedicated for Kielihack participants
- temporary, destroyed after the event

## Containers?
![](images/container_stack.jpg)

(image source: Wikimedia, author: Maersk Line)

## Container

- all dependencies of the application in one package
- operating system virtualization (vs. virtual machine)
- isolated from other processes on the same host
- lightweight, fast to start
- Docker, Rkt, LXC, (Solaris Zones, FreeBSD Jails)
- great for running microservices

## OpenShift
 
- open source, developed by RedHat
- based on Kubernetes (developed by Google, CoreOS, RedHat, ...)
- takes care of 
  - running the containers on multiple hosts
  - network and storage abstraction
- automates source to deployment 

# Why should I care?

## I want to hack already!

![](images/raccoon.jpg)

(image source: Wikimedia)

## The Magic called SEP

## Somebody Else's Problem

## Developer point of view

- network isolation - SEP
- container and project isolation - SEP
- process keepalive - SEP
- capacity management - SEP
- CD/CI orchestration - SEP
- service location - SEP
- HA load balancing - SEP
- storage - SEP
- DNS - SEP (unless you want to have custom domain name)
- server certificates - SEP (without custom domain name)
- authorization for delegating management rights - SEP

## Thanks!
