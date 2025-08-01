# Kubernetes

## About

A group of roles used to deploy and configure various containers on a Kubernetes cluster.

## Roles

- cert_manager
- ddclient
- heimdall
- helm
- longhorn
- longhorn_node
- rancher
- traefik
- wireguard

## Installation

### Prerequisite Collections

`ansible-galaxy install collections -r requirements.yml`

### Download from Galaxy

`ansible-galaxy collection install rmasters270.kubernetes`

---

## Depreciate Roles

The respective roles will be depreciated in favor of this collection.

### Variables

A small number of variables were moved from their respective roles to common_defaults.  The values can be superceded in your inventory.
