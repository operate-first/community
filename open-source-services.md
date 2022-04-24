---
title: Minimum Open Source requirements for Services
description: The minimum requirements for Open Source when working on services, which then allow further progression.
---

# Minimum Open Source Requirements for Services

Here we document the minimum requirements for use of Open Source in services.
When a service meets this minimum requirements, it is then possible for contributors to further progress the service toward the complete Operate First methodology.
This represents what we expect from any _service_ claiming to be Open Source.

## Requirements

These requirements do not represent best practices, but are the bare minimum for Open Source development of services.
Most Open Source models (beyond “throw it over the wall” behavior) are covered by these requirements in one way or another:

 1. **All the service's code and assets necessary to operate the service are shared under an open source license, and publicly accessible.**
 2. **A public contributor can use the same workflow as a typical team member to make a change to the service.**

For many projects the above seem obvious; this is how we generally work together on Open Source projects.
Nevertheless such requirements are being explicitly specified, since services are a new area of work, and since the services and their sources are often not “distributed” for users to operate, and optionally modify, their own copy.

## Frequently Asked Questions:

Due to the variety of services, projects, teams, and workflows there is a lot of flexibility in the requirements.
Secondly, the requirements are a bare minimum, and best practices usually go beyond the requirements.
Thus we must address common questions about the requirements:

### Q: What defines a service?

A service is software operated for the user. Software the user is operating for themself is not considered a service. A service is defined by the context in which the software is operated and all of the assets required to operate the software for the user in that context.

### Q: What “assets” should be Open Source?

**A:** Make all parts of the service open by default, except where law, security, privacy, or common sense says otherwise.
A general rule of thumb is if you commit it to a repository, it should be open.
Assets that should not be shared are ones where you don’t have redistribution rights (such as a RHEL VM image, or private information, and personal identifiable information), or things that are actually secret: Don’t share keys, passwords, or tokens.

If changing configuration is an activity that a typical team member does in order to change the service, then you should share that configuration publicly, in order to meet **requirement #2**.

It is _not requried_ that all tooling dependencies and service dependencies used during the building, testing, deployment and operating of the service are themselves Open Source.

It is _recommended_ that you include sufficient configuration to operate the service, or some base default version of configuration. Putting secrets in your configuration is a bad practice that should be avoided, regardless of Open Source.

### Q: Should tests be shared with the code?

**A:** Tests that are used during operation the service (as per **requirement #1**), and tests that used when run when making a change to the service (as per **requirement #2**), _must be shared publicly_ under an Open Source license.

It is _recommended_ that tests which are independent of the service (eg: penetration tests or performance tests) are Open Source, but this is not required.

### Q: Should anyone be able to trigger CI or test suites?

**A:** The **requirement #2** above does _not require_ that any public contributor can trigger the test suite, if that activity is limited to certain known contributors.

It is common for Open Source projects to limit which contributors can trigger CI or run test suites on their provided infrastructure.
This is usually done to prevent abuse such as exfiltrating secrets or denial of service.
It’s _recommended_ that your project has a mechanism whereby a known contributor, or maintainer, can review a contribution from an arbitrary contributor and then allow the CI or test suite to run on it.

### Q: Must a contribution workflow be documented?

**A:** If such documentation is necessary for a typical team member to make a change to a service as described in **requirement #2**, then it is _required_ that such documentation be made available to the public.

It is _recommended_ that an Open Source project has a documented contribution workflow (eg: a simple CONTRIBUTING file, a wiki, or further documentation).

### Q: Must it be possible for anyone to Operate the service?

**A:** The minimal requirements above _do not require_ that a service can be operated by anyone.
The requirements serve to enable others to change the service code so that it can be operated by others, should that be desired.
It is by these means that these requirements accommodate the forking of the project, with all the usual tradeoffs and costs.

However, if a typical team member operates their own instance of the service in order to make changes to it, then **requirement #2** means that public contributors should also be able to do so as well.

It is a powerful, laudable goal for others to be able to operate an Open Source service, either by operating an instance on their own, or participating in operations of a common instance.
[Operate First](https://www.operate-first.cloud/) is a project that enables this, and even provides infrastructure.

### Q: Must all dependencies for a service be Open Source too?

**A:** It is _not required_ that all dependencies of a service are Open Source, or have Open Source alternatives.
For example, a service may interact with a proprietary authentication system, or run on a proprietary platform.

The requirements together serve to enable others to change the service code so that its proprietary dependencies can be replaced with Open Source ones, should that be desired.

### Q: Must there be a community for the service?

**A:** The minimal requirements above _do not require_ that the Open Source service lead a community built around it.

If your project grows bigger, and has many participants, then forming a community with the typical components (communication venues, code of conduct, governance, etc.) is _recommended_, and brings significant further Open Source benefits.

Among other things, having a community means sharing your documentation, issues, and a roadmap. It also means conducting most planning conversations about the service in the open, and not limiting participation to your team.
This is how you gain the advantages of the Open innovation process, where minds beyond your team can help work through problems and create solutions
Without these things, your community interaction will be more painful as crossing the boundary between community and Red Hat private has a high context switching cost.
