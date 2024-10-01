# Getting Started
This file describes the process of getting started with this repository. Feel free to open issues with further questions after reviewing the provided documentation.

## Requirements

- [ ] z/VM or KVM 
- [ ] Local HTTP server
- [ ] Utility s390x virtual guest
- [ ] Host for running Ansible
- [ ] Properly licensed RedHat credentials for pulling OpenShift install images

## Project Set-Up

- [ ] Clone down the hcit-ocp-install-automation repository
- [ ] Install recent versions of python and Ansible on your local system
- [ ] Clone the z/VM Ansible collection from public GitHub [here](https://github.com/IBM/zvm_ansible_collection)
- [ ] Build the z/VM Ansible collection as described [here](https://github.com/IBM/zvm_ansible_collection?tab=readme-ov-file#installing)
- [ ] Add the location of the built z/VM Ansible collection to your ansible.cfg
- [ ] Allocate IP Addresses and create DNS records for the OpenShift cluster
- [ ] Copy a template inventory and replace generic parameters with your data

Recommended IDE: VS Code

