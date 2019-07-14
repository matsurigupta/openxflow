---
layout: post
author:
- parv
publish_date: 2019-07-14 13:52:12 +0000
categories: []
tags:
- Featured
title: How to install Vagrant
featured_image: ''

---
# How To Install Vagrant

Installing Vagrant is very easy, head over to the [official Vagrant download page](https://www.vagrantup.com/downloads.html) and download the installer or package appropriate for your system. Run the installer and follow the instructions to complete the installation.

Some additional ways to install Vagrant using the command line:

## How to Install Vagrant on Mac

Open Terminal on your Mac and enter the following commands:

**Note:** Make sure to check the latest version available on [Vagrant website](https://www.vagrantup.com/downloads.html) and change the command appropriately.

```bash
## Navigate to the home directory
cd ~

## Download the package
curl -O https://releases.hashicorp.com/vagrant/2.2.5/vagrant_2.2.5_x86_64.dmg

## Mount the image
sudo hdiutil attach vagrant_2.2.5_x86_64.dmg

## Run the package
sudo installer -package /Volumes/Vagrant/vagrant.pkg -target /

## Verify Vagrant
vagrant --version
```

## Windows





## Linux

