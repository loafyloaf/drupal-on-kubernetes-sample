[![Build Status](https://travis-ci.org/mlangbehn/drupal-on-kubernetes-sample.svg?branch=master)](https://travis-ci.org/mlangbehn/drupal-on-kubernetes-sample)

# Deploy Drupal on Kubernetes

In this Code Pattern, we will setup a Drupal site using Kubernetes and Postgres. Drupal is a popular free and open source content management system used as the backend for millions of web sites worldwide. By splitting out the services into containers, we have the ability to leverage the power of Kubernetes.

```
 +---------------+-----------------------------------------+
 | Client device | Provider cloud                          |
 |               |                                         |
 | Web user      | +-Kubernetes--------------------------+ |
 |               | |                                     | |
 |               | | +-Docker-----------+ +-Docker-----+ | |
 |               | | |                  | |            | | |
 |               | | | Drupal interface | | PostgreSQL | | |
 |               | | |                  | |            | | |
 |               | | +------------------+ +------------+ | |
 |               | |                                     | |
 |               | +-------------------------------------+ |
 |               |                                         |
 +---------------+-----------------------------------------+
```
