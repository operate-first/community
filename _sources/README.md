# Operate First community planning repository

This repository is used by all members of the Operate First community for managing the ongoing support and sustaining the community of persons and organizations around this initiative.

We plan and keep track of our efforts on the [Community Project Board](https://github.com/orgs/operate-first/projects/16), which is drives the status of the [program management page](https://github.com/operate-first/community/blob/main/program-management-tracker.md). Feel free to also follow our [blog](https://www.operate-first.cloud/blog/).

## Bootstrapping

This repository (https://github.com/operate-first/community) is the home to efforts to bring a formal _community architecture_ process to the Operate First initiative.
The scope of this initiative is large enough with a multi-community impact to warrant going from an organic community effort to a managed community.
This initiative is in the beginning stages (bootstrapping) of defining and performing this work.

# Contributing

All are welcome to contribute to this repository and our efforts.

Details beyond this README file can be found in the `contributing.md` file.

If you are interested in being involved in community projects and meetings make sure to join our [Slack](https://join.slack.com/t/operatefirst/shared_invite/zt-o2gn4wn8-O39g7sthTAuPCvaCNRnLww) and our [Operate First Community Google calender](https://calendar.google.com/calendar/u/0/embed?src=operate.first.community@gmail.com&ctz=America/New_York) to know when we meet.
## Processes

Until there is a Community Handbook to gather this content within, all of the processes for interacting with this repository and work around it are contained in this section, or held in the `contributing.md` file.

### Reviewing pull requests for this repository

All commits to this repository should use a [pull request process](https://github.com/operate-first/blueprint/blob/main/adr/0016-pr-review.md) for most changes.
This means under normal conditions, no one should commit directly to the repo.
Instead, they branch or fork the repo, make changes in the branch/fork, and then make a pull request against the main repo.

Because content in this repo is not in its final form, we do not need as stringent a review process for accepting pull requests into this repo. This repo is for project work that appears in its finished form in locations such as https://operate-first.cloud, https://twitter.com/OperateFirst, the Operate First [community mailing list](https://lists.operate-first.cloud/admin/lists/community.lists.operate-first.cloud/), and so forth.
This is generally not a final-form location, and we are often dumping in partially completed work to finish here openly.

However, we want to follow the PR process for several reason:
* it matches practices with the rest of the project;
* it makes sure commits are clean;
* it keeps more people involved and aware of what is happening;
* it helps us keep in the habit.

Early drafts tend to be collaborated on in Google Docs, via email, or on one's own until there is enough material to create a MarkDown file and generate a pull request.

We then work collaboratively in the PR review process to update the content for inclusion in the repo.
Sometimes we just touch the work briefly, sometimes we use the PR to edit heavily.

Once in the repo, we use the PR process to ensure commits are clean and things are double-checked.
With content, the initial commits are not required to adhere to any style guide.
In many cases, that is done during a later review and copyedit pass, to keep the focus on the accuracy and clarity of the content before going to the efforts to make changes for style and final grammar.

### Prow CI
This repository uses Prow for CI.
This section is here as a reminder to consider any custom configurations for the `.prow.yaml` file.

Prow is a CI provider developed for Kubernetes needs.
It provides chat-ops management of pull requests, issues, and declarative management for labels, branches, and many more.

We host our own deployment of Prow in Operate First available at [https://prow.operate-first.cloud/](https://prow.operate-first.cloud/).

Supported commands are listed [here](https://prow.operate-first.cloud/command-help).
We have also enabled Prow to consume on-repository configuration files.
You can specify your config in [`.prow.yaml`](.prow.yaml).
Additional centralized configuration can be found in the [thoth-application repository](https://github.com/thoth-station/thoth-application/tree/master/prow/overlays/smaug).

### Pre-commit
This repository uses the project-wide pre-commit hooks.

We enable yamllint hook by default, since most of our repositories use yaml files extensively.
Default configuration for this hook is located at [`yamllint-config.yaml`](yamllint-config.yaml).

To install and enable pre-commit locally please follow the instructions [here](https://pre-commit.com/#quick-start).

It is advised for all contributors to enable pre-commit git hook via `pre-commit install` after cloning any repo within Operate First.

## Using labels

There are a new set of labels available for the whole Operate First contributor community:

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

### Examples of labels in use

These labels are common for all projects in the [Operate First GitHub repository](https://github.com/operate-first).
This way, wherever you are in the project repos, you can mark a pull request or an issue with these labels to assist in community management.

Non-specific examples:

* A PR that signals the completion of an important Epic worthy of making some noise about and including in a newsletter can be labeled `area/community`, `kind/news`, and `kind/marketing`.
* An issue is related to the experience of users joining the project to become contributors is labeled `area/community`, `area/user`, `area/contributor`, `kind/experience`, and `kind/onboarding`.
* A write-up on how to setup a clone of a repository for doing work intended to be contributed to the community would be labeled `area/contributor`, `kind/documentation`, `kind/onboarding`, and `kind/handbook`.
