# AWS Network Configuration

This repository contains a [Crossplane configuration](https://docs.crossplane.io/latest/concepts/packages/#configuration-packages) that deploys fully managed [AWS networking](https://aws.amazon.com/products/networking/) resources.

## Deployment

```shell
apiVersion: pkg.crossplane.io/v1
kind: Configuration
metadata:
  name: aws-network-dual-stack
spec:
  package: xpkg.upbound.io/febarbosa/aws-network-dual-stack:v0.0.1
```