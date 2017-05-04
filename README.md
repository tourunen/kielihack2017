# Digipalvelutehdas platform for Kielihack 2017

This repo acts as a hub for practical information about the container platform that
is provided by Digipalvelutehdas for Eduhack/Kielihack May 2017 in Turku.

## About the platform

[Digipalvelutehdas](http://www.digipalvelutehdas.fi/) provides a container platform for
the participants of Kielihack. You are able to build, run and publish containerized web 
applications on it. 

The platform is

- running [OpenShift Origin](https://www.openshift.org) 1.4.1
- reachable at https://eduhack.digipalvelutehdas.fi:8443
- dedicated for Kielihack participants
- temporary, destroyed after the event

Currently, we have a cluster with 
- 3 masters
- a load balancer
- 4 nodes with SSD disks for local storage
- persistent storage on NFS

The cluster is running on [CSC](https://www.csc.fi) [cPouta cloud](https://research.csc.fi/cpouta)

## How to use it?

We have anonymous accounts available at the workshops, where we show a demo of deploying
a simple application on the platform. Find Olli Tourunen or Marko Leppänen at the event
to get credentials.

## Ok, I've got credentials, how to get started?

Here are some links to get you hacking:

### OpenShift live tutorials on Katacoda

https://openshift.katacoda.com/

These are a very good starting point to get familiar with OpenShift quickly.

### OpenShift Developers Guide

https://docs.openshift.org/latest/dev_guide/

The reference documentation that goes deep.

### Gallery example app

Try deploying https://github.com/tourunen/gallery

## Contact

For technical info and assistance about the Kielihack platform
- find Olli Tourunen on site
- mail olli.tourunen@csc.fi
- chat: TBA

For collabaration, partnership and Digipalvelutehdas in whole,  
- find Marko Leppänen on site
- mail marko.leppanen@minedu.fi

## Links

- [Kielihack platform overview](https://presentations.oso-pilot.csc.fi/kielihack.html)
- [Happy Raccoons](https://presentations.oso-pilot.csc.fi/index.html)
