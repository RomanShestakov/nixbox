NixOS box for Vagrant
=======================

This project builds [vagrant](http://vagrantup.com) .box

// cutdown version of original project https://github.com/nix-community/nixbox

Usage
-----

packer build --only=virtualbox-iso nixos-x86_64.json
vagrant box add nixbox64 nixos-19.09-virtualbox-x86_64.box --force
vagrant up
vagrant ssh
