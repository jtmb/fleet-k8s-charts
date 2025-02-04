# Rancher WordPress Deployment

This repository contains the resources for deploying **WordPress** and **Traefik** on a Kubernetes cluster using **Fleet**.

## Structure
- **charts**: Contains Helm chart values for WordPress and Traefik.
- **apps**: Contains app definitions for WordPress and Traefik in the cluster.
- **fleet.yaml**: Defines the Fleet bundle for deploying the apps.
- **README.md**: Documentation for using this repo.

## Deployment Steps

1. **Add Fleet bundle** to Rancher.
2. **Deploy Traefik and WordPress** using the `fleet.yaml` bundle.
3. **Check the WordPress site** at `https://rancher.jtmb.cc`.
4. **Monitor Traefik dashboard** at `https://traefik.jtmb.cc` (if enabled).
