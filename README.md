# AngkorGreen: Gateway Automatic Deployment

### Deployment Guide

1. [Create a new release](https://github.com/angkorgreen/angkorgreen-api-gateway/releases/new) at [angkorgreen/angkorgreen-api-gateway](https://github.com/angkorgreen/angkorgreen-api-gateway) repository, following the [semver](https://semver.org/) versioning specification.

> Given a version number MAJOR.MINOR.PATCH, increment the:
>
> 1. MAJOR version when you make incompatible API changes,
> 1. MINOR version when you add functionality in a backwards compatible manner, and
> 1. PATCH version when you make backwards compatible bug fixes.
>
> Additional labels for pre-release and build metadata are available as extensions to the MAJOR.MINOR.PATCH format.

2. [Create a new release](https://github.com/angkorgreen/gateway-deploy/releases/new) within this repository with the same version number as the [angkorgreen/angkorgreen-api-gateway](https://github.com/angkorgreen/angkorgreen-api-gateway) repository. This will trigger the automatic deployment process.
