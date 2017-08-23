# Awesome-openstack

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list for awesome OpenStack links!

![OpenStack logo](http://zdnet1.cbsistatic.com/hub/i/2016/10/25/e2569fbb-c7f8-4f5c-9b81-f841816e5261/3f600859cc306db262eac96303101a34/openstack-logo-2016.png)

## Table of Contents

<!-- TOC depthFrom:2 depthTo:4 -->

- [Table of Contents](#table-of-contents)
- [What is OpenStack?](#what-is-openstack)
- [Try OpenStack](#try-openstack)
- [Learn about OpenStack](#learn-about-openstack)
- [Deploy OpenStack](#deploy-openstack)
- [Contribute to OpenStack](#contribute-to-openstack)
- [Project Navigator](#project-navigator)
- [Projects](#projects)
    - [Nova](#nova)
    - [Neutron](#neutron)
    - [Glance](#glance)
    - [Swift](#swift)
    - [Heat](#heat)
    - [Cinder](#cinder)
    - [Keystone](#keystone)
    - [Kuryr](#kuryr)
    - [Zun](#zun)
    - [Kolla](#kolla)
    - [Horizon](#horizon)

<!-- /TOC -->

## What is OpenStack?

![OpenStack overview](https://www.openstack.org/software/images/diagram/overview-diagram.svg)

> OpenStack is a cloud operating system that controls large pools of compute, storage, and networking resources throughout a datacenter, all managed through a dashboard that gives administrators control while empowering their users to provision resources through a web interface.

More details at [OpenStack homepage](https://www.openstack.org/software/)

## Try OpenStack

1. [Public Clouds on the Marketplace](https://www.openstack.org/marketplace/)
1. [Local Dev Environment with devstack](http://devstack.org/)
1. [TryStack - OpenStack sandbox](http://trystack.org/)

## Learn about OpenStack

1. [OpenStack Documentation](http://docs.openstack.org/)
1. [OpenStack User Stories](https://www.openstack.org/user-stories/)
1. [OpenStack Summit Videos](https://www.openstack.org/videos/)
1. [Books](http://docs.openstack.org/ops/)

## Deploy OpenStack

1. [Manual Step-by-step guides](https://docs.openstack.org/ocata/install/)
1. Deploy OpenStack with Kolla-ansible
    - [Documentation](https://docs.openstack.org/developer/kolla-ansible/quickstart.html)
    - [Kolla deployment guide](https://docs.openstack.org/project-deploy-guide/kolla-ansible/ocata/)
1. Deploy OpenStack with Packstack 
    - [RHEL deploy guide](https://access.redhat.com/documentation/en-US/Red_Hat_Enterprise_Linux_OpenStack_Platform/2/html/Getting_Started_Guide/part-Deploying_OS_using_PackStack.html)
    - [Platform9 - How to install OpenStack using RDO Packstack](https://platform9.com/blog/install-openstack-using-rdo-packstack/)
1. Deploy OpenStack-on-OpenStack(TripleO)
    - [Documentation](https://docs.openstack.org/tripleo-docs/latest/install/)
    - [Platform9 - How to install OpenStack using TripleO](https://platform9.com/blog/install-openstack-using-tripleo/)
    - [Mirantis blog - As Container rise, OpenStack TripleO slides](https://www.mirantis.com/blog/containers-rise-openstack-tripleo-slides/)
1. Deploy OpenStack with Openstack-ansible
    - [Documenation](https://docs.openstack.org/openstack-ansible/latest/)
    - [Openstack-ansible deployment guide](https://docs.openstack.org/project-deploy-guide/openstack-ansible/ocata/)
1. Deploy OpenStack with scripts
    - [Vietstacker(Vietnam OpenStack Community) OpenStack-Ocata-Scripts](https://github.com/vietstacker/OpenStack-Ocata-Scripts)
    - [Tigerlinux - Openstack-ocata-installer-ubuntu1604lts](https://github.com/tigerlinux/openstack-ocata-installer-ubuntu1604ts)
    - [Tigerlinux - Openstack-ocata-installer-centos7](https://github.com/tigerlinux/openstack-ocata-installer-centos7)

## Contribute to OpenStack

1. [OpenStack Documentation Contributor Guide](https://docs.openstack.org/contributor-guide/)
1. [OpenStack Developer's Guide](https://docs.openstack.org/infra/manual/developers.html)

## Project Navigator

| Compute  |                                             |
| -------- | ------------------------------------------- |
| Nova     | Compute Service                             |
| Glance   | Image Service                               |
| Ironic   | Bare Metal Provisioning Service             |
| Storlets | Computable Object Store                     |
| Zun      | Container Management Service                |
| Magnum   | Container Orchestration Engine Provisioning |

| Storage, Backup & Recovery |                                          |
| -------------------------- | ---------------------------------------- |
| Swift                      | Object Storage                           |
| Cinder                     | Block Storage                            |
| Manila                     | Shared Filesystems                       |
| Karbor                     | Application Data Protection as a Service |
| Freezer                    | Backup, Restore, and Disaster Recovery   |

| Networking & Content Delivery |                                                    |
| ----------------------------- | -------------------------------------------------- |
| Neutron                       | Networking                                         |
| Designate                     | DNS Service                                        |
| Dragonflow                    | Neutron Plugin                                     |
| Ocatvia                       | Load Balancer                                      |
| [Kuryr](### Kuryr)            | Container Plugin                                   |
| Tacker                        | NFV Orchestration                                  |
| Tricircle                     | Networking Automation for Multi-Region Deployments |

| Security, Identity & Compliance |                  |
| ------------------------------- | ---------------- |
| Keystone                        | Identity service |
| Barbican                        | Key Management   |
| Congress                        | Goverance        |
| Mistral                         | Workflow service |

| Management Tools       |                              |
| ---------------------- | ---------------------------- |
| Horizon                | Dashboard                    |
| Openstack client (CLI) | Command-line client          |
| Rally                  | Benchmark service            |
| Senlin                 | Clustering service           |
| Vitrage                | Root Cause Analytics service |
| Watcher                | Optimization service         |

| Deployment Tools  |                                 |
| ----------------- | ------------------------------- |
| Chef OpenStack    | Chef cookbooks for OpenStack    |
| OpenStack Charms  | Juju Charms for OpenStack       |
| OpenStack-ansible | Ansible Playbooks for OpenStack |
| Puppet Openstack  | Puppet modules for OpenStack    |
| TripleO           | Deployment service              |

| Application services |                                            |
| -------------------- | ------------------------------------------ |
| Heat                 | Orchestration                              |
| Zaqar                | Messaging Service                          |
| Murano               | Application Catalog                        |
| Solum                | Software Developement Lifecycle Automation |

## Projects

### Nova

### Neutron

### Glance

### Swift

### Heat

### Cinder

### Keystone

### Kuryr

1. [Official Documentation](https://docs.openstack.org/kuryr/latest/)
1. [Gal Sagie Bog](http://galsagie.github.io/tags/#Kuryr)

### Zun

### Kolla

### Horizon