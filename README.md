# Pythia [![Build Status](https://travis-ci.org/pythia-project/pythia.svg?branch=master)](https://travis-ci.org/pythia-project/pythia) [![Documentation Status](https://readthedocs.org/projects/pythia-core/badge/?version=latest)](http://pythia-core.readthedocs.org/en/latest/?badge=latest) [![Join the chat at https://gitter.im/pythia-project/pythia](https://badges.gitter.im/pythia-project/pythia.svg)](https://gitter.im/pythia-project/pythia?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Pythia is an application that executes code safely, within UML virtual machines.

## Requirements

- Make 4.0 or later
- Go 1.2.1 or later
- Squashfs
- gcc-multilib
- fakeroot
- bc

## Quick Install

- Clone the repository

        $ git clone --recursive https://github.com/pythia-project/pythia.git

- Get into the directory

        $ cd pythia

- Launch installation

        $ make

## Deployment with Docker

- Change fstab to have shm in no-exec mode for UML

        TODO

## Contributors

- Sébastien Combéfis
- Vianney le Clément de Saint-Marcq
- Charles Vandevoorde
- Virginie Van den Schrieck