# NGINX Sablier NJS

This repository contains an NGINX NJS script named `sablier.js`, forked from [acouvreur/sablier (nginx plugin)](https://github.com/acouvreur/sablier/blob/main/plugins/nginx/njs/sablier.js). The script dynamically manages feature branch deployments using session-based strategies in NGINX.

## Overview

This NJS script integrates with the Sablier service to manage deployment sessions for feature branches. The script uses HTTP subrequests to communicate with the Sablier service and controls session management using cookies based on the feature branch version.

The script has been tested on Kubernetes and [NGINX Ingress by NGINX Inc](https://github.com/nginxinc/kubernetes-ingress).

To learn more about Sablier or how this script works and how to set it up, please read the following:

- [Sablier Docs](https://acouvreur.github.io/sablier/#/)
- My medium article [Scaling on Demand: How Sablier Can Optimize Feature Branch Deployments for Frontend Applications](https://medium.com/@mostafahussein/scaling-on-demand-how-sablier-can-optimize-feature-branch-deployments-for-frontend-applications-c2cda3bdccd2).
