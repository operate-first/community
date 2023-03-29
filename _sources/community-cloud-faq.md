---
title: Operate First community cloud FAQ
description: Frequently asked questions (FAQ) about the Operate First community cloud
---

# Operate First community cloud FAQ

## Changes

### What is happening to the Operate First community cloud?

The project is shutting down this community cloud instance, decommissioning or returning community clusters to their provider.

The engineers responsible for maintaining the infrastructure supporting the Operate First community cloud have undergone a shift in their responsibilities, which has led to a decision to power down the OpenShift clusters and the supporting infrastructure behind the Operate First community cloud.
The shutdown is scheduled for April 15, 2023. 

### To be clear, what exactly is the Operate First community cloud?

The Operate First community cloud is a shared environment for Open Source projects and SRE practicioners.
It's been operated under a community service level expectation (SLE) to be as open and transparent as possible.

### So what is the Operate First project without the community cloud?

The Operate First project is a [community of practice (CoP)](https://en.wikipedia.org/wiki/Community_of_practice) that has been co-developing an Open Cloud implementation as a living reference model of principles and a laboratory of practices.

To this point, we have opted to maintain a set of community clusters as the "Operate First community cloud".
Going forward, the project will look to draw practitioners to Operate First through collaboration with other community clusters and community clouds of particular projects or organizations.

Operate First has been and remains a CoP comprised of developers, operators, and others — site reliability engineers (SRE), data scientists, University researchers, Open Source practitioners, and so forth — who believe in promoting this Open approach to operations. 

## Project migration

### Do we have documentation on migration steps?

Because of the quantity and relative differences in application deployment, there isn't a standard way to migrate.

For what steps you can initiate and follow, refer to the section on migration in the [Operate First community cloud sunset how-to](community-cloud-sunset-how-to.md).

As mentioned in the announcement, two of the main locations to migrate to are Red Hat OpenShift Service on Amazon (ROSA) and the New England Research Cloud (NERC).

### What is MOC Alliance and the NERC?

Originally the Mass Open Cloud, [MOC Alliance ](https://massopen.cloud) is a joint project of academia and research institutions, public sector interests, independent and foundation-based Open projects, and private corporations.
The goal was to build a regional research cloud, and develop toward how to do a national version.
The next evolution of the MOC Alliance is in the new [i-Scale, the Center for Systems Innovations at Scale](https://i-scale.org).

The latest released offering out of this project is the [New England Research Cloud (NERC)](https://nerc.mghpcc.org/), which is part of the [Massachusetts Green High-Performance Computing Center](https://mghpcc.org).

The NERC is a researcher and Open project-focused managed community cloud environment for running project applications.
It is designed to be more of a steady-state, rather than undergoing constant updates to the latest versions of services.
The NERC team seek to balance the value of a cloud environment with the desired features of a staged DevOps environment.

While it is theoretically possible for an Open Source project to be hosted on the NERC, current limitations for this new offering make it practical if you are part of a participating institution.
For example, any Red Hatter with a project can join using the Red Hat Google-based account.


### How do I decide between Red Hat OpenShift Service on Amazon (ROSA) and the New England Research Cloud (NERC) offerings?

Both provide a public cloud-like experience running OpenShift, but have some key differences.

ROSA is a managed OpenShift where the Red Hat Service Delivery team maintain and update the cluster as needed, so you only have to maintain your application layer.
For Operate First-hosted projects, the cost to the Open Source project for ROSA is zero.
However, you need to pay for the AWS compute underlying ROSA with operating budget or cloud credits.
Neither of these are available from the Operate First project, but rather should be sourced from your product business unit or directly from the public cloud provider.

NERC is a managed OpenShift community cloud where a combined team from Boston University, Harvard University, and others maintain and update the cluster for research purposes.
Open Source projects are welcome in this environment, as digital public goods.
This is a new OpenShift offering from the MOC Alliance and there may be some costs associated with using it.
The intake interview process will get into those details.

### Are there any access restrictions for ROSA or NERC?

For ROSA, you would have the access structure of an OpenShift customer.

For NERC, there are unique qualities to the environment, some of which are derived from the Operate First community cloud pattern.
Discovering meaningful differences for you is part of the intake interview process.

### How do we get AWS cloud credits and what happens when they are exhausted?

The Operate First project is no longer providing no-cost community cloud services, which includes AWS cloud credits.
You will need to obtain these elsewhere through existing or new relationships.

You can look for information on cloud credits via your product business unit or other marketing function related to your upstream project.

### How do I get started with NERC?

**Note: This is not a free-for-all offering, you must be associated with a participating institution for easier connection.
If you are not in a participating institution but are interested in the NERC, we will need to have a direct conversation about how to do that.
You can open a ticket with this question [here](https://github.com/operate-first/community/issues/new).**

If you are in a NERC-based project, there are a few useful [user guides](https://nerc.mghpcc.org/user-guides/) you can reference.
The [User Onboarding Process Overview](https://nerc-project.github.io/nerc-docs/get-started/user-onboarding-on-NERC/) explains the process and roles involved.
The [User Account Types](https://nerc-project.github.io/nerc-docs/get-started/create-a-user-portal-account/) document explains roles and getting an account.
You only need to obtain a ***General User*** account when you [request a NERC account](https://regapp.mss.mghpcc.org/).  

Once these accounts are created, the Operate First project will do any needed follow-up interviews before allocating resources.
This also is a chance to discover if there is a service needed that is not yet available, and to look for solutions to that.

## Do you have additional questions not covered? Ask yours [here](https://github.com/operate-first/community/issues/new?assignees=quaid&labels=area%2Fcommunity%2C+kind%2Fdocumentation%2C+kind%2Fquestion&template=question-for-operate-first-community-cloud-faq.md&title=What+is+a+short+version+of+your+question%3F++%5Bquestion+for+FAQ%5D).
