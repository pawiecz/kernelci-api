---
title: "Configuration"
date: 2024-05-08
description: "Files use to store build/execution options"
weight: 5
---

## Kernel build environment

* [`Dockerfile` templates](https://github.com/kernelci/kernelci-core/tree/main/config/docker)
* [Container image build Workflow](https://github.com/kernelci/kernelci-core/blob/main/.github/workflows/docker_images.yml)

## Execution environment (rootfs)

* [Build tool configuration](https://github.com/kernelci/kernelci-core/blob/main/config/core/rootfs-configs.yaml)
* [Image data (overlays, scrits)](https://github.com/kernelci/kernelci-core/tree/main/config/rootfs)
* [Buildroot fork (used for `baseline` images)](https://github.com/kernelci/buildroot)
* [Rootfs image build Workflow](https://github.com/kernelci/kernelci-core/blob/main/.github/workflows/rootfs.yml)
* [Image storage/archive](https://storage.kernelci.org/images/rootfs/)

## Test definitions

* [`test-definitions` fork](https://github.com/kernelci/test-definitions)
* [TestJob templates](https://github.com/kernelci/kernelci-core/tree/main/config/runtime)
* [Maestro Job templates](https://github.com/kernelci/kernelci-pipeline/tree/main/config/runtime)
