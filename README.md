# MyIEP Installation

## Ubuntu 12.04/MySQL 5.5.54/PHP 5.3.10

`sudo apt-get update`

`sudo apt-get upgrade`

`sudo apt-get install lamp-server^ php5-gd php5-mysql`

`sudo git clone https://github.com/ghoulmann/MyIEP.git /var/www/myiep/`

## MySQL

`CREATE DATABASE myiep;`

`CREATE USER 'myiep'@'localhost' IDENTIFIED BY '<some secure passcode>;`

`GRANT ALL ON myiep.* TO 'myiep'@'localhost';`

## Install and Config

1. navigate to localhost/myiep
  
2. see that dependencies are filled, click next
  
3. set the db into as entered above
  

## Log In as Admin

Default Credentials

- username: admin
  
- password: admin

# Under Development

This is a fork of IEP-IPP, an open source project last updated in 2007.

This fork, **MyIEP** is under active development by students at [Chelsea School](http://chelseaschool.edu) in Hyattsville, MD. Contact rgoldman@chelseaschool.edu for more information.

## About Changes

All changes to the original code base captured in this repository are Copyright  © 2013 Chelsea School (Hyattsville, MD).

The original license, GPLv2, carries on. Of course.

# Legacy Code: IEP-IPP

* See LICENSE.md (GPLv2)

## Homepage

This is the home of the original project: [http://www.iep-ipp.com/](http://www.iep-ipp.com/)
	
## Summary of project by the original dev / dev team:

IEP-IPP is open source software, license granted under GPL version 2, and is available free of charge. IEP-IPP was designed as a collaborative effort by K-12 special education teachers, graphic design, and K-12 technology staff as an effort to produce a program planning system for managing individual education/program plans for students in Pre-Kindergarten to grade 12, students in ESL and students in gifted programs. Efforts and suggestions to improve the system are always appreciated. 	

	*from the site, where there is also documentation.*

## Tarball on Sourceforge

Tarball of IEP-IPP, the project forked in this repo, is here: [http://sourceforge.net/projects/iep-ipp/](http://sourceforge.net/projects/iep-ipp/)

## Copyright of Original Codebase

IEP-IPP is Copyright © 2005 Grasslands Regional Division #6.
	
IEP-IPP is released under the GNU GPL License*

## Before the fork

Last recorded release was 2007. 
