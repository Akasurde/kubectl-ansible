# kubectl-ansible-playbook

[![kubectl plugin](https://img.shields.io/badge/kubectl-plugin-blue.svg)](https://github.com/topics/kubectl-plugin)

A Kubectl plugin to run Ansible Playbook on Pods using Ansible K8S Dynamic Inventory Plugin and Kubectl connection plugin

**Table of Content**
<!-- TOC -->

- [kubectl-ansible-playbook](#kubectl-ansible-playbook)
    - [Pre-requisites](#pre-requisites)
    - [Installation](#installation)
        - [Manual Installation](#manual-installation)
    - [How to use](#how-to-use)
        - [Usage](#usage)
        - [Examples](#examples)
    - [Useful Links](#useful-links)
    - [Contributing](#contributing)

<!-- /TOC -->

## Pre-requisites
This plugin needs the following programs:
* Kubectl
* Ansible
* Ansible Kubernetes community collection (community.k8s)

## Installation

* Install Ansible - https://docs.ansible.com/ansible/latest/installation_guide/index.html
* Install Ansible Kubernetes Collection using - https://github.com/ansible-collections/community.kubernetes#installation-and-usage

### Manual Installation

Install the plugin by copying the script in the $PATH of your shell.

```sh
# Get source
$ git clone https://github.com/Akasurde/kubectl-ansible-playbook.git
$ cd kubectl-ansible-playbook
$ chmod +x kubectl-ansible_playbook
# Add kubectl-ansible to the install path.
$ sudo cp -p kubectl-ansible_playbook /usr/local/bin
```

## How to use

### Usage

### Examples


## Useful Links

- [Extend kubectl with plugins](https://kubernetes.io/docs/tasks/extend-kubectl/kubectl-plugins/)
- [Write your own kubectl subcommands](https://ahmet.im/blog/kubectl-plugins/)
- [Ansible](https://www.ansible.com/)
- [Ansible Kubernetes Collection](https://github.com/ansible-collections/community.kubernetes)

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/Akasurde/kubectl-ansible-playbook
