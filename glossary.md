# Operate First Glossary

**Operate First** is a concept to incorporate operational experience into software projects through the collaborative effort of both developers and operators. When operational knowledge is baked directly into the software, it results in a better overall project that can be trusted to run well in production.

**An Operate First Community Production Cloud** is a cloud environment in which you practice Operate First



The Operate First Community Production Cloud at **Massachusetts Open Cloud (MOC)**:


    MOC’s “zero cluster” is an Operate First Community Production Cloud that is open source. Those interested in operating first with their projects can do so in this environment.



**The Operate First Community of Practice** refers to the community that practices operating first, sets the guidance for the method, and continually improves upon that method



**Open Infrastructure Labs** is an upstream for open source cloud operations. They are a community of operators testing open source code in production, publishing complete, reproducible stacks for existing and emerging workloads, and generally advancing open source infrastructure. The Operate First Community of Practice lives at OpenInfra Labs because ???






# Basic terms



These 3 basic terms are fundamental for projects to understand as they consider adopting a development method incorporating Operate First.



**Operate First** is about bringing software under development to a production cloud so that operation of the software can be understood and developed. As such, Operate First is a concept and methodology, akin to open source.

It's not code. It does not have a license. It's not hardware or a cloud. It is a way of connecting all stakeholders of building, deploying, and operating software and sharing code, data, and knowledge - similar to open source communities, where users and developers of a piece of software come together.



An **Operate First Environment** is an instantiation of a production cloud environment where projects can bring their software to practice Operate First. The **Massachusetts Open Cloud (MOC) **provides an initial example of an Operate First environment through their “zero cluster.”



**Open Infrastructure Labs** is an open source upstream where cloud providers and operators work together with project developers to advance the state of the art for managing open source clouds. Its relation to Operate First is that it provides a place where projects that are operating first tend to work together. This work is done in an open community with collaboration from cloud operators as well as other projects in order to develop and evolve operations.


# Operate First background

In the age of cloud computing operational excellence needs to be encapsulated with the software products and services. To ensure that software projects address operational considerations, there must be a new method by which developers experience the operation of their projects in a real cloud setting. This is the idea behind Operate First. Operate your code in a cloud first, while still in development, then release.



Operate First is a **concept** where developers bring their projects to a production cloud during development where they can interact with a cloud provider’s operators and gain valuable feedback on the operational considerations of their project. They gain first-hand knowledge of the operations and take that knowledge back to factor into their ongoing development processes.

Operate First is inspired by[ Upstream First](https://www.redhat.com/en/blog/what-open-source-upstream), which emphasizes working in the open, and extends it to a part of the codebase that teams typically keep closed, even when deploying open source projects: their operations code.

Operate First wants to leverage the community contributor funnel of Open Source to establish a flow of knowledge from users to maintainers and operators of software and services to enable the above and grow new talent.

The motivation for the Operate First initiative is the shift of focus from software availability to operating services: Open Source removed the access to software as a limiting factor for businesses and individuals. However, with software proliferating into every aspect of the business - and our world in general - resulting in ever growing complexity of software stacks, the challenge now is operationalizing software.

Making software available is not sufficient unless we are also making available the capability to operate the software in production. This is why cloud has become the dominant operational paradigm of IT, and is posing a growing challenge to Open Source. Proprietary services based on Open Source are undermining the Open Source model itself and the lack of capability to operate is the new limiting factor for ourselves and our users.

In order to address this issue, the software development and productization process must include building the required operational knowledge and encapsulating it in the software itself. Development teams must build a practical understanding of what it means to put their software into operations, in order to serve their users’ needs.





The concept goes beyond software, with many different places and ways the Operate First concept helps beyond just improving the code:



* Upstream and Downstream - e.g. Kubevirt and CNV
* Platforms - e.g. OpenShift or OpenStack
* Features of those platforms - e.g. Istio or KubeVirt
* Supporting services - e.g. ArgoCD for workloads
* Cloud-native projects - e.g. Kubeflow or OpenDataHub
* Workloads - e.g. community hosted websites
* Incubating community projects - e.g. SigStore or IBM Mesh-4-Data
* Living Reference Architectures - e.g. MANUela edge demo
* Software as a Services - e.g. RedHat Insights or Managed Kafka
* Configuration data - e.g. deployment manifests
* SRE content - e.g. SLI/SLOs, Dashboards, scripts, and tools
* Automation - e.g. Bots, Pipeline definitions
* Operational data sets - e.g. Logs, Metrics, Incidents
* Architectural Decision Records - Documents describing a thought process
* Community Building - enabling contribution and growing talent


# An Operate First cloud environment

An Operate First cloud environment is as[ open as possible](https://github.com/operate-first/blueprint/issues/78)—an environment where anonymous visitors can read as much as possible and signup for accessing the environment is as easy as for any other modern service.  Of course all within legal boundaries. The setup should mimic the setup of open source code repositories.



Since most clouds, like university or company-run services, have stricter legal requirements, it’s necessary to disconnect the Operate First Cloud from those environments to prevent leakage of data. [Assertion needs clarification to explain that when in a non-commercial dynamic working on open source, the data retention requirements are different. For example, GDPR has exceptions that open source projects use to exempt themselves from tracking PII that is part of openly published data, such as an email address being available in an open mailing list archive is a business requirement for the project; this is different from a commercial cloud environment. By having an Operate First community cloud environment separate from a commercial cloud, you don’t get e.g. a user address from the commercial side end up in the community dataset and thus exposed publicly.]



The environment is operated by a community with a best-effort support SLA. Similar to the best-effort support that community projects provide.

The environment spans multiple data centers and multiple geographies, i.e. it’s a decentralized setup without hard dependencies on certain data-center requirements.



**The community aims to be as inclusive as possible, especially in terms of the required skills to contribute.**



**The community consists of all stakeholders of all the aspects that make up the Operate First concept, such as developers, operators and data-scientists. It can be considered as the upstream version of other cloud setups, where community members leverage the knowledge learned in the Operate First Cloud and vice versa.** [highlighting as a particularly excellent summary of the Operate First community vision.]



You might call it the Fedora in the relationship of  Fedora, Centos and RHEL.


# MOC / NERC

The Mass Open Cloud is the first cloud to directly benefit from the knowledge, tooling and best-practices created in the Operate First community.  It’s disconnected from the Operate First Cloud services, but its implementation mimics what the Operate First Cloud provided. It’s operated by a large number of people that are also active in operating the Operate First Cloud.

Data created in MOC is meant to be shared with the research community, but it’s not generally available to the public.

Projects that need higher SLAs or tighter legal requirements might choose to come to the MOC instead of the Operate First Cloud.

This means MOC is also applying the Operate First concept for operations, but it has tighter legal requirements and higher SLAs than the community-operated Operate First Cloud.

You might call it the Centos in the relationship of  Fedora, Centos and RHEL.


# Mass Open Cloud (Bill)

The Mass Open Cloud is the first cloud to provide what can be called an “operate first environment”.  It welcomes projects that adhere to the methodologies of open source and operate first to experience their projects in a production cloud. It provides an OpenStack based cloud, which could be duplicated elsewhere. And other clouds could provide the ability to operate first on other platforms. Call them "operate first environments", but not just "operate first".

To enable this, along with their other partners, The Massachusetts Open Cloud (MOC) has stepped up to provide the inaugural production cloud environment for projects to operate first. The projects that are operating first there have been doing their work in the open with the OpenInfra Labs community.


# Open Infrastructure Labs (Bill)

Open Infrastructure Labs is an upstream founded to be a home for

open source cloud operations. It hosts multiple distinct, independent

open source projects that are all related to cloud operations. Since the

operate first concept is about using software in a production environment it is a

natural place for teams that are standing up open source production clouds

for any purpose to do their work in the open. The team that is operating

the Mass Open Cloud's "operate first environment" is doing their work there.

It's also a legitimate place to do work on any project software that involves operations.

While it's reasonable for a software project to directly incorporate

operations into their upstream, things that are useful for multiple

upstreams make a lot of sense to put in a common place like OI Labs.


# Operate First Artifacts / Content / Assets

All **code** created in the Operate First Cloud or by other clouds that operate first, should eventually make it into the projects that are operated first.

For other code that has no fit yet will go into repositories maintained by the Operate First Cloud Community.

Configuration and blueprints for setting up the cloud and services are maintained by the Operate First Cloud Community and available for public inspection.

The operational data created is available for public inspection.

A suggestion: Suggest: The intent is that operational code created as a result of a project operating first is brought back to the project when it is project specific. When code is developed that is not project specific, ideally that code will be put in a place where other projects and benefit and contribute to it as well.


# Operate First Services / Open Source Services

TBD


# Managed First Delivery

TBD


# FAQ

**Q:** Are projects like Quay or 3Scale already operating first? They are running an instance as a service and are available as a product and an open-source project.

**A:** To some extent yes. They already capture operational knowledge in a production environment. On the other hand, the production environment is not open for customers or a community to be freely examined or open for direct contributions. The contribution funnel is still via the open-source code base.

**Q:** Is OpenShiftDedicated an implementation of operate first for OpenShift?

**A: **To some extent yes. By opening up most of the configuration and tooling being used to run OSD there is a direct feedback loop to OCP. But it’s still missing out on opportunities for direct contributions since there is no second or Nth deployment of OSD and it’s supporting services.
