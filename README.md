# Operate First template for repositories

Derive new repositories from this template

List of featurese:

## License

This template ensures new repos are created compliant with [ADR 0001](https://www.operate-first.cloud/blueprints/blueprint/docs/adr/0001-use-gpl3-as-license.md) and use GNU GPL v3 license.

## AI-CoE CI Github application

AI-CoE CI provides easy and quick integration for build pipelines and checks for pull requests.

An empty [`.aicoe-ci.yaml`](.aicoe-ci.yaml) is created here, disabling all checks via this CI provider by default. Documentation can be found [here](https://github.com/AICoE/aicoe-ci/).

## Prow CI

Prow is a CI provider developed for Kubernetes needs. Provides chat-ops management of pull requests, issues and declarative management for labels, branches and many more.

We host our own deployment of Prow in Operate First available at [https://prow.operate-first.cloud/](https://prow.operate-first.cloud/).

Supported commands are listed [here](https://prow.operate-first.cloud/command-help). We have also enabled Prow to consume on-repository configuration files. You can specify your config in [`.prow.yaml`](.prow.yaml). Additional centralized configuration can be found in the [thoth-application repository](https://github.com/thoth-station/thoth-application/tree/master/prow/overlays/cnv-prod).

## Pre-commit

By extension to Prow, we define a default pre-commit config for new repositories. Default hook configuration can be found in [`.pre-commit-config.yaml`](.pre-commit-config.yaml). Pre-commit is executed via Prow, see [`.prow.yaml`](.prow.yaml) for details.

We enable yamllint hook by default, since most of our repositories use yaml files extensively. Default configuration for this hook is located at [`yamllint-config.yaml`](yamllint-config.yaml).

To install and enable pre-commit locally please follow the instructions [here](https://pre-commit.com/#quick-start).

It is advised for all contributors to enable pre-commit git hook via `pre-commit install` after cloning any repo within Operate First.
