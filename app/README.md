## Wordpress Installation

### Prerequisites
#### Packages Requirements:
```
Wordprss Version: 5.7.2
PHP Version: 7.4 or greator
Mysql Version: 5.6 or greator
MariaDB Version:  10.1 or greator
Apache/2.4.37 (centos)
```
### Server Requirements
Webserver
```
Operating System: CentOS 8
CPU/RAM: 1 / 1GB
Storage: 10 GB or more
### Diagram

### Directory Structure

```
.
├── dev_inventory.yaml
├── playbooks
│   ├── add_ansible_user.yaml
│   ├── database.yaml
│   ├── packages.yaml
│   ├── ping.yaml
│   └── webserver.yaml
├── README.md
└── variables
    ├── database_vars.yaml
    ├── ping_vars.yaml
    └── webserver_vars.yaml
    
```

# Packages
# webserver:

PHP 7.2.24
Apache/2.4.37
mysql  Ver 8.0.21