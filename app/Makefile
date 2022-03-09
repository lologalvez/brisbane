#!/bin/bash
include ../Makefile

UID = $(shell id -u)
DOCKER_BE = brisbane-app

initialize:
	$(MAKE) build
	$(MAKE) start
	$(MAKE) composer-install

