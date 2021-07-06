# Operate First community planning repository

This repository is used by all members of the Operate First community for managing the ongoing support and sustaining the community of persons and organizations around this initiative.

Bootstrapping ...

# Contributing

All are welcome to contribute to this repository and our efforts.

Details can be found in the CONTRIBUTING.md file.

# Processes

Until there is a Community Handbook to gather this content within, all of the processes for interacting with this repository and work around it are contained in this section.

## Reviewing pull requests for this repository

All commits to this repository should use a pull request process for most changes.
This means under normal conditions, no one should commit directly to the repo.
Instead, they branch or fork the repo, make changes in the branch/fork, and then make a pull request against the main repo.

We do not need a stringent review process for accepting pull requests into this repo because it is for project work that appears in its finished form in locations such as https://operate-first.cloud, https://twitter.com/operate-first, the Operate First community mailing list, and so forth.
This is generally not a final-form location, and we are often dumping in partially completed work to finish here openly.

However, we want to follow the PR process for several reason:
it matches practices with the rest of the project;
it makes sure commits are clean;
it keeps more people involved and aware of what is happening;
it helps us keep in the habit.

Early drafts tend to be collaborated on in Google Docs, via email, or on one's own until there is enough material to create a MarkDown file and generate a pull request.

We then work collaboratively in the PR review process to update the content for inclusion in the repo.
Sometimes we just touch the work briefly, sometimes we use the PR to edit heavily.

Once in the repo, we use the PR process to ensure commits are clean and things are double-checked, but it is expected that many of these PRs are going to be reviewed and passed pro-forma.

Supported commands are listed [here](https://prow.operate-first.cloud/command-help). We have also enabled Prow to consume on-repository configuration files. You can specify your config in [`.prow.yaml`](.prow.yaml). Additional centralized configuration can be found in the [thoth-application repository](https://github.com/thoth-station/thoth-application/tree/master/prow/overlays/cnv-prod).

## Pre-commit

* `area/contributor` Indicates an issue/PR is related to a project platform contributor.
* `area/user`: Indicates an issue/PR is related to a project platform user.
* `kind/experience:` Indicates an issue/PR is related to human interaction and experience of the platform, project, et al.
* `kind/governance`: Indicates an issue/PR is related to governance.
* `kind/handbook`: Indicates an issue/PR is related to a handbook.
* `kind/marketing`: Indicates an issue/PR is related to marketing.
* `kind/metrics`: Indicates an issue/PR is related to metrics.
* `kind/news`: Indicates an issue/PR is related to project news and outreach.
* `kind/onboarding`: Indicates an issue/PR is related to onboarding.
* `kind/website`: Indicates an issue/PR is related to project web presence.

### Examples of labels in use

* A PR that signals the completion of an important Epic worthy of making some noise about and including in a newsletter can be labeled `area/community`, `kind/news`, and `kind/marketing`.
* An issue is related to the experience of users joining the project to become contributors is labeled `area/community`, `area/user`, `area/contributor`, `kind/experience`, and `kind/onboarding`.
* A write-up on how to setup a clone of a repository for doing work intended to be contributed to the community would be labeled `area/contributor`, `kind/documentation`, `kind/onboarding`, and `kind/handbook`.
=======
We do not need as stringent a review process for accepting pull requests into this repo because it is for project work that appears in its finished form in locations such as https://operate-first.cloud, https://twitter.com/operate-first, the Operate First community mailing list, and so forth. This is generally not a final-form location, and we are often dumping in partially completed work to finish here openly.

Early drafts tend to be collaborated on in Google Docs, via email, or on one's own until there is enough material to create a MarkDown file and generate a pull request. We can then work collaboratively in the PR review process to update the content for inclusion in the repo. Sometimes we just touch the work briefly, sometimes we use the PR to edit heavily. Once in the repo, we use the PR process to ensure commits are clean and things are double-checked, but it is expected that many of these PRs are going to be reviewed and passed pro-forma.

## Using labels

There are a new set of labels available project wide:

* `area/community`: Indicates an issue/PR is related to the overall community.
* `area/contributor` Indicates an issue/PR is related to a project platform contributor.
* `area/user`: Indicates an issue/PR is related to a project platform user.
* `kind/experience:` Indicates an issue/PR is related to human interaction and experience of the platform, project, et al.
* `kind/governance`: Indicates an issue/PR is related to governance.
* `kind/handbook`: Indicates an issue/PR is related to a handbook.
* `kind/marketing`: Indicates an issue/PR is related to marketing.
* `kind/metrics`: Indicates an issue/PR is related to metrics.
* `kind/news`: Indicates an issue/PR is related to project news and outreach.
* `kind/onboarding`: Indicates an issue/PR is related to onboarding.
* `kind/website`: Indicates an issue/PR is related to project web presence.

 Examples of use:

 * A PR that signals the completion of an important Epic worthy of making some noise about and including in a newsletter can be labeled `area/community`, `kind/news`, and `kind/marketing`.
 * An issue is related to the experience of users joining the project to become contributors is labeled `area/community`, `area/user`, `area/contributor`, `kind/experience`, and `kind/onboarding`.
 * A write-up on how to setup a clone of a repository for doing work intended to be contributed to the community would be labeled `area/contributor`, `kind/documentation`, `kind/onboarding`, and `kind/handbook`.   