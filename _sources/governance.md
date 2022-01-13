---
title: Operate First Community Governance 1.0
description: Initiating governance for the Operate First project community
---
# Operate First Community Governance 1.0

This document contains the initial governance (Governance 1.0) for the community-formed project around the _[Operate First concept](https://openinfralabs.org/operate-first-manifesto/)_.
In this document, the community and project are referred to by the shorthand _Op1st_ (spoken as "op first").

It also has a roadmap for additions coming in the next iteration of the governance (Governance 1.1).

## Summmary

The community works in special interest groups (SIGs), that form around a common topic.

SIGs are operated by consensus and can self-organize.
One common organizational structure is for the group to appoint a chair and vice-chair by consensus.
The chair and vice-chair organize and run meetings, and take charge of getting the group to consensus.

The overall project is operated by all SIGs in consensus.
The future roadmap includes the idea of committees, which are elected or selected bodies that operate outside of the SIG structure and may direct the project above and beyond the SIGs.
For example, a future Technical Steering Committee might decide all overall technical directions based on the advice and consent of the SIGs.

To start, we are initiating the Community SIG and the Operations SIG. All parts of the project fall under these SIGs.
The SIGs then self-organize and decide to sub-divide into further SIGs and to form subprojects within one or more SIGs to actually do things.

The subprojects are where the work happens, and the SIGs organize and guide their subprojects.

## Op1st Community Governance 1.0 (MVG)

A healthy open source project is one that demonstrates open practices, uses open infrastructure, and cultivates an open culture with the goal of becoming more sustainable.

### Principles
As a new community with a vision to grow, we are following in the footsteps of many massively scaled and successful projects. We want to take care to learn from those who came before us, while forging our own path into the challenges we've chosen to undertake.

To stand up this Governance for a 1.0 good-enough minimal-viable-governance (MVG), we are looking to our key predecessors for some of our starting points.
As an initial set of principles we are combining elements of the [Kubernetes community principles](https://github.com/kubernetes/community/blob/master/governance.md#principles) and the [OpenInfra Foundations Four Opens](https://openinfra.dev/four-opens/).

#### Op1st Community Principles 1.0
Our mission requires us to use open source principles in ways beyond licensing the code we write, but at the core we are an open source community and want to adhere to the best possible principles for creating an open, welcoming, and inclusive community.

These are the Op1st community principles we adhere to:
1. **Open Source** : Any content we create is released under an open work license. Content includes but is not limited to all software, documentations, configuration files, data, and training materials.
"All software" includes the code necessary to operate software, AKA _operational code_.
  - This is crucial to fulfilling our mission around open sourcing operations
2. **Welcoming and respectful** : We intend to be an open, welcoming, and inclusive community.
Diversity is our strength.
We have and follow a Code of Conduct.
  - We currently follow the OpenInfra Foundation Code of Conduct as a member of the OpenInfra Labs.
3. **Open Design** : We follow a transparent and open process for planning and designing any content, services, and features of Op1st.
Ideas and contributions are accepted according to their technical merit and alignment with project objectives, scope, and design principles.
4. **Open Work** : Two of our core tools for successful community building are transparency and accessibility.
To support that, work and collaboration must be done in public to the greatest degree possible.
Refer to the section on [Community Groups](#community-groups) and [SIGs](#sigs) in particular for details on how this is performed.
5. **Sustainable Open Community** : The best way to build a sustainable open source community is to ensure the community cohesion is through openness and transparency, ensuring all the voices are heard and anyone can rise to leadership positions.
The more diversity of voices at the decision table, the better our ability to improve conditions such as inclusion and equity.
Sustainable comes through continuous improvement of those areas, such as through centering the agenda of those people most marginalized and at risk in each given context (which results in things being more accessible for everyone.)

### Code of Conduct

We are using the [upstream OpenInfra Foundation Code of Conduct](https://openinfra.dev/legal/code-of-conduct)(CoC).
In creating the next Governance 1.1 we will have an actual process to make decisions as a community. We can then either formally ratify this same CoC, or the Community SIG can convene a cross-project working group to discuss and decide an inclusive and equitable process for a new code of conduct.

### Community membership
> :notebook: **Note** This document is a work in progress, especially these membership guidelines

We are opening the Governance 1.0 directly borrowing from the [Kubernetes community group definitions](https://github.com/kubernetes/community/blob/master/community-membership.md), then reviewing and refining for the Governance 1.1.

This section outlines the various responsibilities of contributor roles in Op1st.
The Op1st project is subdivided into subprojects under SIGs.
Responsibilities for most roles are scoped to these subprojects.

A contribution can take many, many forms, such as: documentation, code, best-practices content, marketing materials, running a meeting, helping a user in chat, operating a cluster, responding to a `help wanted` flag, reviewing and commenting on contributions of all these types when in a proposed-state (a _pull request_ or _PR_), giving a talk at a conference, staffing a booth at a conference, and so forth.
For a longer list, refer to this chapter, "[What Is A Contribution?](https://www.theopensourceway.org/the_open_source_way-guidebook-2.0.html#_what_is_a_contribution)", which includes these definitions:

> An open source **Contribution**
>
> Any original, intentional, and substantive object given freely to an open source community, under the licensing of that community. A contribution can come from an individual or a community.

> An open source **Contributor**
>
> Any individual person involved in making Contributions to the community. Communities are interpersonal by their nature. They consist of humans, not organizations. Organizations can send their members, staff, leaders, and so forth out to make contributions to a community as a contributor

One reason this project runs so many processes through a git workflow is to raise the visibility on all types of contributions and contributor roles.
These interactions by a contributor help qualify and quantify their activities.
It is never a full picture of one's activities, but it is a useful and helpful one.

| Role | Responsibilities | Requirements | Defined by |
| -----| ---------------- | ------------ | -------|
| Member | Active contributor in the community | Sponsored by 2 reviewers and multiple contributions to the project | Op1st GitHub org member|
| Reviewer | Review contributions from other members | History of review and authorship in a subproject | [OWNERS] file reviewer entry |
| Approver | Contributions acceptance approval| Highly experienced active reviewer and contributor to a subproject | [OWNERS] file approver entry|
| Subproject owner | Set direction and priorities for a subproject | Demonstrated responsibility and excellent technical judgement for the subproject | [sigs.yaml] subproject [OWNERS] file *owners* entry |

### Community groups
The Op1st community is initiating Governance 1.0 with only one type of community group, Special Interest Groups (SIGs).
The purpose of doing so is to empower SIGs to gather interested people around a subject area, then decide and implement that into governance.
For example, one of the first acts of the Community SIG is to establish a milestone schedule for defining and holding elections for future steering committee(s).
Governance 1.1 will therefore include details on new community groups (subprojects and working groups).

#### SIGs
Special Interest Groups (SIGs) are persistent open groups that focus on a part of the project. SIGs must have open and transparent proceedings.
Anyone is welcome to participate and contribute provided they follow the Op1st [Code of Conduct](https://www.operate-first.cloud/code_of_conduct).
The purpose of a SIG is to own and develop a set of subprojects.

A SIG can have its own policy for contribution, described in a README or CONTRIBUTING file in the SIG folder in this repo (e.g. sig-community/CONTRIBUTING.md), and its own mailing list, chat channel, etc.

#### Initiating SIGs

In order to get things started in a way to encourage transparency and participation, we are going to only initiate two SIGs to start, the Community SIG (`sig-community`) and the Operations SIG (`sig-ops`).
These two SIGs are immediately empowered through this governance to create new SIGs and/or subprojects.

To create subprojects, a SIG only needs to have consensus within itself.

To create a new SIG:

1. A SIG recognizes there is a need for a new SIG.
2. For example, the Community SIG decides to create the Data Science SIG right away, to formalize the already existing activity there.
3. Once the individual SIG is in consensus, the proposal is brought to all SIGs.
4. With all SIGs in consensus, the new SIG is formally created.

A similar process is followed when the Community SIG is ready to present recommendations for Governance 1.1 that creates committees.

#### Deprecating SIGs

This section is intentionally incomplete for the Governance 1.0.
The reason is social: while it makes sense to have initiating a SIG to be relatively easy, we want to take more care with deprecating or closing a SIG.

This is a topic the Community SIG can put on the priority agenda to resolve soon after forming, so the process is created within the space of community input and voices.

If it is not resolved in a patch to 1.0 it must be delivered in the Governance 1.1 minor update.

#### Governance 1.1 potential future groups
[These descriptions](https://github.com/kubernetes/community#governance) are borrowed from [Kubernetes governance around community groups](https://github.com/kubernetes/community/blob/master/governance.md#community-groups).
They are only placeholders for discussions, lightly edited.

* **Subprojects** Each SIG can (or may? or should?) have a set of subprojects. These are smaller groups that can work independently. Some subprojects will be part of the main project Op1st deliverables while others will be more speculative.
* **Working Groups** are temporary groups that are formed to address issues that cross SIG boundaries. Working groups do not own any code or other long term artifacts. Working groups can report back and act through involved SIGs.
* **User Groups** are groups for facilitating communication and discovery of information related to topics that have long term relevance to large groups of Op1st users. They do not have ownership of parts of the Op1st code base, but they may contribute to other types of content and open works.

### Decision making

While the project is in the early stages, we are favoring a balance of including all voices and keeping a rapid pace of progress.
To accomplish this balance, we are using a _consensus decision model_ that gives time and space for everyone to voice concerns with the proposal.

There are two types of consensus models we use, the lightweight and the full:

* **Lightweight consensus** occurs when a decision does not have wide or sweeping effects and is considered approved if no one raises any blocking objections after several days.
In practice, a proposal email with sufficient detail is sent to a SIG or main community list, and if no one raises an objection after three working days (i.e., Saturdays and Sundays are not counted), the proposal passes.
* **Full consensus** decisions require 3 yes votes (+1) and no objections (-1’s) and votes should be left open for at least 72 hours (not counting weekend days) to ensure all voices are heard.
72 hours is a minimum and should be increased for decisions with a likely broad impact, that involve contentious issues, or for any other reason that increases fairness in reaching consensus.
Specifically, these rules must **not** be used to intentionally or accidentally disenfranchise contributors.
For example, if a 72 hour window goes over a weekend and means a significant decision closes on a Monday, it may disenfranchise contributors who cannot watch the project daily.
In such cases, a full calendar week is a fair minimum window for decision making, balancing the needs to give people enough time and to keep the process moving along.
All -1s votes require reason/ explanation, -1’s with no substantiation may be overturned.
Thus a single -1 vote can block achieving consensus, so it forces the group to take care of the blocking person rather than outvoting.

SIGs decide by consensus within themselves whatever they are doing, and which model is used for a particular decisions.

Anything needing wider discussion and approval goes to mailing list for either group or SIG roll-up consensus.

When we are ready, we use this power to form a technical and/or overall steering committee, with corresponding election system.

#### Consensus decision making

One practice of meritocracy is the consensus-based decision model.
From http://en.wikipedia.org/wiki/Consensus_decision-making, “Consensus decision-making is a group decision making process that seeks the consent of all participants.”
In practice, it is different from a majority-vote-wins approach.
In the Op1st project a discussion toward a decision follows this process:

1. A proposal is put forth and a check for consensus is made.
   1. Consensus is signified through a +1 vote.
1. A check is made for any dissent on the proposal.
   1. Reservations? State reservation, sometimes with a ‘-1’ signifier
      1. Reservations about the proposal are worked through, seeking consensus to resolve the reservations.
      2. A reservation is not a vote against the proposal, but may turn into a vote against if unresolved.
      It is often expressed with an initial -1 vote to indicate reservations and concerns.
      This indicates there is still discussion to be had.
   1. Stand aside?
      No comment, or state concerns without a -1 reservation; sometimes the ‘-0’ signifier is used.
      1. This option allows a member to have issues with the proposal without choosing to block the proposal, by instead standing aside with a +/-0 vote.
      1. The stated concerns may influence other people to have or release reservations.
   1. Block?
   Vote ‘-1’ with reasons for the block.
     1. This is a complete block on a proposal, refusing to let it pass.
     A block is a -1 vote and must be accompanied with substantive arguments that are rooted in the merit criteria of the Project – protecting the community, the upstream, technical reasons, and so forth.


### Use of Architectural Decision Records (ADR)
Architectural decisions are design decisions with some level of architectural significance.
At Op1st, we track architectural decisions using lightweight architectural decision records.
More information on the format we follow is available at https://adr.github.io/madr/.

ADR page: https://www.operate-first.cloud/blueprints/blueprint/

ADR repository: https://github.com/operate-first/blueprint

### Use of the Community Handbook
The Community Handbook is intended to serve as a resource for all Operate First community contributors.
It contains documentation on how to perform contributor-related tasks and encourages input and contributions from the community.
The covenant of the Community Handbook is that if contributors must figure out a task for themselves, they should submit that solution to the handbook for the benefit of future contributors.

Content for the Community Handbook is drawn from all across the project, allowing documentation to live close to the place it's used.
There is a core repository for structure, guidelines, and all content that does not fit or belong in another repository.

Community Handbook page: https://www.operate-first.cloud/community-handbook/

Community Handbook repository: https://github.com/operate-first/community-handbook

## Governance roadmap: 1.1 and beyond

This section contains content being worked on for the next iteration, Governance 1.1.

### Addition of committees, subprojects, and working Groups

It is the purview of the initiating Community SIG to manage the Governance 1.1 process, including the responsibility to decide which types of groups get added, how they are created and ended, and where future responsibility for these type of decisions shifts once Governance 1.1 is ratified.

### Selecting initial "Technical Steering Committee"

TBD

### Addition of project Values

TBD

### Community Handbook RELEASED with contributor getting-started information

TBD
