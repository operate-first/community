# Operate First Glossary

**_Operate First_** is a concept to incorporate operational experience into software projects through the collaborative effort of both developers and operators.
By bringing software under development to a production cloud, that operation of the software can be better understood and developed.
When operational knowledge is included directly into the software, it results in a better overall project that can be trusted to run well in production.
As such, Operate First is a concept and methodology, akin to Open Source.

The term _Operate First_ when used alone should refer to the general concept.
Other nouns can be used to modify the term, such as "Operate First community cloud" and "Operate First mindset".

**_The Operate First community production cloud (community cloud)_** is a prototype Open cloud environment practicing the Operate First principles, and run as part of the Operate First project.

Since most clouds, like university or company-run services, have stricter legal requirements, it’s necessary to disconnect the Operate First community cloud from those environments to prevent leakage of data.
When working in a non-commercial environment such as an Open Source project, the data privacy and retention rules such as GDPR may be different.
These need to be understood and managed as part of this community resource.

This community resource is operated by active contributoes with a best-effort community support expectation (_Service Level Expectation (SLE)_).
This is similar to how Open Source community projects provide best-effort community support.

The environment spans multiple data centers and multiple geographies, i.e., it’s a decentralized setup without hard dependencies on certain data-center requirements.

**_The Operate First community_** refers to the people who make up the Operate First project.
This is the community practicing operating first, setting the guidance for the method, and continually improving upon that method

**_The Operate First project_** is the formal group run by the Operate First community, which is made up of the code, content, systems, procedures, logo marks, brand and identity, workshops and Slack channels, and all the myriad parts needed by a community to conduct an Open Source project.

**_[MOC Alliance](https://massopen.cloud)_** (formerly _Massachusetts Open Cloud (MOC)_) is an organization aiming "to accelerate the pace of discovery and innovation in an open production research-focused cloud." The MOC Alliances’s “zero cluster” is a part of the Operate First commmunity cloud.


**_[Open Infrastructure Labs](https://openinfralabs.org)_** is an upstream for open source cloud operations. They are a community of operators testing open source code in production, publishing complete, reproducible stacks for existing and emerging workloads, and generally advancing open source infrastructure. The Operate First community of practice lives at OpenInfra Labs, as the origin and place to cultivate the Operate First concept.

**_[New England Research Cloud (NERC)](https://nerc.mghpcc.org/)_** is a new cloud environment for researchers, students, and others.
The creation and running of this production cloud is an effort within the Operate First project, consisting of team members from multiple organizations.

The NERC is the first cloud to directly benefit from the knowledge, tooling, and best-practices created in the Operate First community.
It’s disconnected from the Operate First community cloud services, but its implementation mimics what the Operate First community cloud provided.
It’s operated by a large number of people, some of whom are also active in operating the Operate First community cloud.

Data created in MOC is meant to be shared with the research community, but it’s not generally available to the public.

# Open Source services

Link coming soon:  https://operate-first.cloud/community/open-source-service

# FAQ

**Q:** Are projects like Quay or 3Scale already operating first? They are running an instance as a service and are available as a product and an open-source project.

**A:** To some extent yes. They already capture operational knowledge in a production environment. On the other hand, the production environment is not open for customers or a community to be freely examined or open for direct contributions. The contribution funnel is still via the open-source code base.

**Q:** Is OpenShiftDedicated an implementation of operate first for OpenShift?

**A:** To some extent yes. By opening up most of the configuration and tooling being used to run OSD there is a direct feedback loop to OCP. But it’s still missing out on opportunities for direct contributions since there is no second or Nth deployment of OSD and it’s supporting services.

[link](https://iquaid.org)
