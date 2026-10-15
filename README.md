# APPTAINER

> Anticloud offline package — upstream: apptainer/apptainer @ `main`.

## What This Project Does

Apptainer: Application containers for Linux

**Topics:** apptainer, containers, hpc, linux, rootless-containers, science, singularity, singularity-container

## Upstream README

# Apptainer

[![CI](https://github.com/apptainer/apptainer/actions/workflows/ci.yml/badge.svg)](https://github.com/apptainer/apptainer/actions/workflows/ci.yml)
[![Go Reference](https://pkg.go.dev/badge/pkg.golang.dev/github.com/apptainer/apptainer.svg)](https://pkg.go.dev/github.com/apptainer/apptainer)
[![Go Report Card](https://goreportcard.com/badge/github.com/apptainer/apptainer)](https://goreportcard.com/report/github.com/apptainer/apptainer)

- [Documentation](https://apptainer.org/docs/)
- [Support](#support)
- [Community Meetings / Minutes / Roadmap](https://drive.google.com/drive/u/0/folders/1npfBhIDxqeJIUHZ0tMeuHPvc_iB4T2B6)
- [Project License](LICENSE.md)
- [Guidelines for Contributing](CONTRIBUTING.md)
- [Code of Conduct](CODE_OF_CONDUCT.md)
- [Citation](#citing-apptainer)

## What is Apptainer?

Apptainer is an open source container platform designed to be simple, fast,
and secure. Many container platforms are available, but Apptainer is designed
for ease-of-use on shared systems and in high performance computing (HPC)
environments. It features:

- An immutable single-file container image format, supporting cryptographic
  signatures and encryption.
- Integration over isolation by default. Easily make use of GPUs, high speed
  networks, parallel filesystems on a cluster or server.
- Mobility of compute. The single file SIF container format is easy to transport
  and share.
- A simple, effective security model. You are the same user inside a container
  as outside, and cannot gain additional privilege on the host system by
  default.

Apptainer is open source software, distributed under the [BSD License](LICENSE.md).

Apptainer was formerly known as Singularity and is now [a part of the
Linux Foundation](https://apptainer.org/news/community-announcement-20211130).
When migrating from Singularity see the
[admin migration documentation](https://apptainer.org/docs/admin/main/singularity_migration.html)
and
[user compatibility documentation](https://apptainer.org/docs/user/main/singularity_compatibility.html).

## Getting Started with Apptainer

To install Apptainer from source, see the [installation
instructions](INSTALL.md). For other installation options, see [our
guide](https://apptainer.org/docs/admin/main/installation.html).

System administrators can learn how to configure Apptainer, and get an
overview of its architecture and security features in the [administrator
guide](https://apptainer.org/docs/admin/main/).

For users, see the [user guide](https://apptainer.org/docs/user/main/)
for details on how to run and build containers with Apptainer.

## Contributing to Apptainer

Community contributions are always greatly appreciated. To start developing
Apptainer, check out the [guidelines for contributing](CONTRIBUTING.md).

Please note we have a [code of conduct](CODE_OF_CONDUCT.md). Please follow it in
all your interactions with the project members and users.

We also welcome contributions to our [user
guide](https://github.com/ap

## License

Upstream terms preserved in `THIRD_PARTY_LICENSES/`. Overlay licensed under Anticommons 0.1.0.

## Verification

Recompute the SHA3-256 of `BENCH.json` and compare to this package’s register. Any drift = invalid package.
