#Rails Nginx Manager

## What is Rails Nginx Manager?

This software is designed for remote management of Nginx using key authenticated ssh on a server running Ubuntu Server 18.04 LTS.

### Application System Requirements
- Must have ruby v2.5.0 with Bundler
- Must have network access to ssh into remote system (ip/hostname and port are configurable)

### Remote System Requirements

- Must use systemd for services, specifically using the systemctl command for controlling service state
- Must have a version of sudo that supports nopasswd
- Must have nginx configurations located at, or linked to /etc/nginx

### Configuration options

Rails Nginx Manager can be run on a separate system to the nginx instance you wish to manage, or it may be run on the same system (with the remote server set to localhost or 172.0.0.1)

## Installation

*This will be updated when the software reaches a usable state*
