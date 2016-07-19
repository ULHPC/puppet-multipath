-*- mode: markdown; mode: visual-line;  -*-

# ULHPC/multipath Puppet Module 

[![Puppet Forge](http://img.shields.io/puppetforge/v/ULHPC/multipath.svg)](https://forge.puppetlabs.com/ULHPC/multipath)
[![License](http://img.shields.io/:license-GPL3.0-blue.svg)](LICENSE)
![Supported Platforms](http://img.shields.io/badge/platform-debian|centos-lightgrey.svg)
[![Documentation Status](https://readthedocs.org/projects/ulhpc-puppet-multipath/badge/?version=latest)](https://readthedocs.org/projects/ulhpc-puppet-multipath/?badge=latest)

      Copyright (c) 2016 S. Varrette, H. Cartiaux, V. Plugaru, S. Diehl aka. UL HPC Management Team <hpc-sysadmins@uni.lu>

| [Project Page](https://github.com/ULHPC/puppet-multipath) | [Documentation](http://ulhpc-puppet-multipath.readthedocs.org/en/latest/) | [Issues](https://github.com/ULHPC/puppet-multipath/issues) |


-----------
The [ULHPC/multipath](https://github.com/ULHPC/puppet-multipath) puppet module has been designed to configure multipath to detect multiple paths to devices for fail-over or performance reasons and coalesces them

This is the main page of the documentation for this Puppet module, which is hosted and managed by [Read the Docs](http://ulhpc-multipath.readthedocs.org/en/latest/).
It proposes to detail the following elements:

* An [Overview](overview.md) of the module is proposed, describing the puppet classes and/or definitions it implements.
     - you might also wish to check the `tests/` directory for sample test cases 
* How to [test this module with Vagrant](vagrant.md)
* How to [contribute](contributing/index.md) to this puppet module development. In particular, we detail:
     - the [directory tree structure](contributing/layout.md)
	 - the steps to follow to [setup this repository](contributing/setup.md)
	 - information as regard the [semantic versioning](contributing/versioning.md) of this Puppet module. 
     - Apart form the directory layout, we will cover various configuration aspects ([git-flow](https://github.com/nvie/gitflow), [RVM](https://rvm.io/), [Bundler](http://bundler.io/) etc.)
* Details on the [Read the Docs](http://ulhpc-puppet-multipath.readthedocs.org/en/latest/) management.

