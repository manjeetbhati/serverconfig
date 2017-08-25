Install Pre required Packages
-----------------------------

This is an example, how to install packages on multiple
servers via ansible scripts. This scipt has roles to install
following packages:

 - pip
 - docker
 - ansible
 - pyjinja

The role initconfig is for installing packages required to manage pip
packages and required packages for ansible script to work properly.


Note: This is written to install pre required packages for Kolla
      but can be used as an reference as well to build similar
      preconfiguration scripts 
