# Ansible Modules for Dell Technologies PowerMax

The Ansible modules for Dell Technologies (Dell) PowerMax allow data center and IT administrators to use RedHat Ansible to automate and orchestrate the configuration and management of Dell PowerMax arrays.

The capabilities of Ansible modules are managing volumes, storage groups, ports, port groups, hosts, host groups, masking views, initiators, snapshots, SRDF links, RDF groups, Metro DR environments, jobs, snapshot policies, storage pools and gathering high-level facts about the arrays. The options available for each capability are list, show, create, delete, and modify. These tasks are performed by running simple playbooks written in YAML syntax. The modules are written so that all the operations are idempotent, therefore making multiple identical requests has the same effect as making a single request.

## Table of contents

* [Code of conduct](https://github.com/dell/ansible-powermax/blob/2.1.0/docs/CODE_OF_CONDUCT.md)
* [Maintainer guide](https://github.com/dell/ansible-powermax/blob/2.1.0/docs/MAINTAINER_GUIDE.md)
* [Committer guide](https://github.com/dell/ansible-powermax/blob/2.1.0/docs/COMMITTER_GUIDE.md)
* [Contributing guide](https://github.com/dell/ansible-powermax/blob/2.1.0/docs/CONTRIBUTING.md)
* [Branching strategy](https://github.com/dell/ansible-powermax/blob/2.1.0/docs/BRANCHING.md)
* [List of adopters](https://github.com/dell/ansible-powermax/blob/2.1.0/docs/ADOPTERS.md)
* [Maintainers](https://github.com/dell/ansible-powermax/blob/2.1.0/docs/MAINTAINERS.md)
* [Support](https://github.com/dell/ansible-powermax/blob/2.1.0/docs/SUPPORT.md)
* [Security](https://github.com/dell/ansible-powermax/blob/2.1.0/docs/SECURITY.md)
* [License](#license)
* [Supported platforms](#supported-platforms)
* [Prerequisites](#prerequisites)
* [List of Ansible modules for Dell PowerMax](#list-of-ansible-modules-for-dell-powermax)
* [Installation and execution of Ansible modules for Dell PowerMax](#installation-and-execution-of-ansible-modules-for-dell-powermax)
* [Maintanence](#maintanence)

## License
Ansible collection for PowerMax is released and licensed under the GPL-3.0 license. See [LICENSE](https://github.com/dell/ansible-powermax/blob/2.1.0/LICENSE) for the full terms. Ansible modules and modules utilities that are part of the Ansible collection for PowerMax are released and licensed under the Apache 2.0 license. See [MODULE-LICENSE](https://github.com/dell/ansible-powermax/blob/2.1.0/MODULE-LICENSE) for the full terms.

## Supported platforms
Dell PowerMax and VMAX All Flash arrays support Unisphere version 9.1 and later.

## Prerequisites
This table provides information about the software prerequisites for the Ansible Modules for Dell PowerMax.

| **Ansible modules** | **Unisphere version** | **PowerMaxOS** | **Python version**            | **Python library version** | **Ansible**              |
|---------------------|-----------------------|----------------|-------------------------------|----------------------------|--------------------------|
| v2.1.0 | 9.1 <br> 9.2 <br> 10.0 | 5978.444.444 <br> 5978.669.669 <br> 5978.711.711 <br> 6079.xxx.xxx | 3.9.x <br> 3.10.x <br> 3.11.x | 9.1.x.x <br> 9.2.x.x <br> 10.0.x.x | 2.12 <br> 2.13 <br> 2.14 |

  * Follow PyU4V installation instructions on [PyU4V Documentation](https://pyu4v.readthedocs.io/)

## Idempotency
The modules are written in such a way that all requests are idempotent and hence fault-tolerant. This means that the result of a successfully performed request is independent of the number of times it is performed.

## List of Ansible modules for Dell PowerMax
  * [Volume module](https://github.com/dell/ansible-powermax/blob/2.1.0/docs/Product%20Guide.md#volume-module)
  * [Host module](https://github.com/dell/ansible-powermax/blob/2.1.0/docs/Product%20Guide.md#host-module)
  * [Host Group module](https://github.com/dell/ansible-powermax/blob/2.1.0/docs/Product%20Guide.md#host-group-module)
  * [Snapshot module](https://github.com/dell/ansible-powermax/blob/2.1.0/docs/Product%20Guide.md#snapshot-module)
  * [Masking View module](https://github.com/dell/ansible-powermax/blob/2.1.0/docs/Product%20Guide.md#masking-view-module)
  * [Port module](https://github.com/dell/ansible-powermax/blob/2.1.0/docs/Product%20Guide.md#port-module)
  * [Port Group module](https://github.com/dell/ansible-powermax/blob/2.1.0/docs/Product%20Guide.md#port-group-module)
  * [Storage Group module](https://github.com/dell/ansible-powermax/blob/2.1.0/docs/Product%20Guide.md#storage-group-module)
  * [Info module](https://github.com/dell/ansible-powermax/blob/2.1.0/docs/Product%20Guide.md#info-module)
  * [SRDF module](https://github.com/dell/ansible-powermax/blob/2.1.0/docs/Product%20Guide.md#srdf-module)
  * [RDF Group module](https://github.com/dell/ansible-powermax/blob/2.1.0/docs/Product%20Guide.md#rdf-group-module)
  * [Metro DR module](https://github.com/dell/ansible-powermax/blob/2.1.0/docs/Product%20Guide.md#metro-dr-module)
  * [Job module](https://github.com/dell/ansible-powermax/blob/2.1.0/docs/Product%20Guide.md#job-module)
  * [Snapshot Policy module](https://github.com/dell/ansible-powermax/blob/2.1.0/docs/Product%20Guide.md#snapshot-policy-module)
  * [Storage Pool module](https://github.com/dell/ansible-powermax/blob/2.1.0/docs/Product%20Guide.md#storage-pool-module)
  * [Process Storage Pool module](https://github.com/dell/ansible-powermax/blob/2.1.0/docs/Product%20Guide.md#process-storage-pool-dict-module)
  * [Initiator module](https://github.com/dell/ansible-powermax/blob/2.1.0/docs/Product%20Guide.md#initiator-module)
  * [Intelligent Volume Placement](https://github.com/dell/ansible-powermax/blob/2.1.0/docs/Product%20Guide.md#intelligent-volume-placement)

## Installation and execution of Ansible modules for Dell PowerMax
The installation and execution steps of Ansible modules for Dell PowerMax can be found [here](https://github.com/dell/ansible-powermax/blob/2.1.0/docs/INSTALLATION.md).

## Maintenance
Ansible modules for Dell Technologies PowerMax deprecation cycle is aligned with [Ansible](https://docs.ansible.com/ansible/latest/dev_guide/module_lifecycle.html).
