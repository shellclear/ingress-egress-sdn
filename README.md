# Ingress/Egress with OpenShiftSDN Pattern

This repository is a patter that deploys some applications and deploy ingress/egress resources using OpenShiftSDN.

## How to start working

1) Fork the repository.

2) Modify the *values-hub.yaml* file accordingly to your environment.

## How to update common/ repository

This repository includes a common/ repository as subtree that includes the main capabilities of the framework.

- https://github.com/validatedpatterns/common

To update it:

- rm -rf common/

- git subtree add --prefix common https://github.com/validatedpatterns/common.git main
