#!/bin/bash
include ../Makefile

UID = $(shell id -u)
DOCKER_BE = brisbane-oauth-app

initialize:
	$(MAKE) build
	$(MAKE) start
	$(MAKE) composer-install
	$(MAKE) npm-install
	$(MAKE) encore