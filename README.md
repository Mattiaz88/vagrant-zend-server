# Zend Server 8.5 Vagrant Box

This Vagrant setup configures an Ubuntu 12.04 (Precise) 64-bit box with Zend
Server 8.5.1 and PHP 5.5.26.

## Quick Start

Run `vagrant up` from the `vagrant` directory, eg

    (cd vagrant; vagrant up)
    
## Forwarded Ports

* 8080 => 80 (Webapp)
* 10084 => 10084 (Zend Server Console)
* 10085 => 10085 (Zend Server HTTPS Console)

## Shared Folders

The `app` directory is shared as `/home/vagrant/app`

## Apache

Apache is configured with the MPM-ITK module with document root set to
`/home/vagrant/app`


