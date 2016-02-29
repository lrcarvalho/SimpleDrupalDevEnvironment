# SimpleDrupalDevEnvironment
A simple Drupal environment build with Vagrant, based on [https://github.com/mattandersen/vagrant-lamp] project. 

In this fork, we added options to import SSH keys and configure GIT credentials. 

1. Download the files
2. Extract the ZIP file.
3. Edit the file "provision.sh"
4. At the line 12 of "provision.sh" file, put you private key content
3. From the command-line, into your current downloaded files:
```
$ vagrant up
```

Requirements
------------
* VirtualBox <http://www.virtualbox.com>
* Vagrant <http://www.vagrantup.com>
* Git <http://git-scm.com/>

Technical Details
-----------------
* Ubuntu 14.04 64-bit
* Apache 2.4
* PHP 5.5
* MySQL 5.5
* XDebug
* PHPUnit 4.8
* Composer
