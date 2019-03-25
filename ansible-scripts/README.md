# OCI Ansible Modules

Oracle Cloud Infrastructure Ansible Modules provide an easy way to create and provision resources in Oracle Cloud Infrastructure (OCI) through Ansible. These modules allow us to author Ansible playbooks that help as automate the provisioning and configuring of Oracle Cloud Infrastructure services and resources, such as Compute, Load Balancing, Database, and other Oracle Cloud Infrastructure services.

**Services supported**
- Block Volume
- Compute
- Container Engine for Kubernetes Service (OKE)
- Database (including support for Autonomous Transaction Processing and Autonomous Data Warehouse Services)
- Domain Name System (DNS)
- IAM
- Load Balancing
- Networking
- Object Storage
- File Storage
- Email Delivery

The OCI Ansible modules are built using the [Oracle Cloud Infrastructure Python SDK] when available.

## Installation

$ git clone https://antonio.d.esposito@innersource.accenture.com/scm/oct1/ansible-scripts.git
$ cd ansible-scripts
Run one of the following commands:
If Ansible is installed as a user: $ ./install.py
If Ansible is installed as root: $ sudo ./install.py

## Scripts

This project includes a catalog of Oracle Cloud Infrastructure Ansible module scripts that illustrate using the modules to carry out common infrastructure provisioning and configuration tasks. :
- Block Volume
- Compute
- Container Engine for Kubernetes Service (OKE)
- Database (including support for Autonomous Transaction Processing and Autonomous Data Warehouse Services)
- Domain Name System (DNS)
- IAM
- Load Balancing
- Networking
- Object Storage
- Search
- File Storage


