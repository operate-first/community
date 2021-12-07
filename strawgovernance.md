# strawgovernance `DRAFT WIP`

Elements to complete:
- 1.0 lightweight features (Minimal Viable Governance)
  - SIGs
  - Working Groups
  - Code of Conduct
  - Principles
  - Community membership
  - Community groups
  - Architectural Decision Records
  - Community Handbook DRAFT
- 1.1 oversight creation
  - lightweight elections for Technical Steering Committee
  - Addition of committees, working groups, and sub-projects
  - Addition of Values
  - Community Handbook RELEASED
    - Contains full contributor get started information
  -
----
## Op1st Community Governance 1.0 (MVG)

Welcome, overview

A healthy open source project is one that demonstrates open practices, uses open infrastructure, and cultivates an open culture with the goal of becoming more sustainable.

### Principles
As a new cloud-native community growing up at the footsteps of massively scaled and successful projects such as Kubernetes and OpenInfra, we want to be careful to learn from those who came before us, while forging our own path into the challenges we've chosen to undertake.

To stand up this Governance for a 1.0 good-enough minimal-viable-governance (MVG), we are looking to our key predecessors for some of our starting points.
As an initial set of principles we are combining elements of the [Kubernetes community principles](https://github.com/kubernetes/community/blob/master/governance.md#principles) and the [OpenInfra Foundations Four Opens](https://openinfra.dev/four-opens/).

#### Op1st Community Principles 1.0
Our mission requires us to use open source principles in ways beyond licensing the code we write, but at the core we are an open source community and want to adhere to the best possible principles for creating an open, welcoming, and inclusive community.

These are the Op1st community principles we adhere to:
1. **Open Source** : Any content we create is released under an open source license. Content includes software, documentations, configuration files, and training materials.
  - This is crucial to fulfilling our mission around open sourcing operations
2. **Welcoming and respectful** : We intend to be an open, welcoming, and inclusive community.
Diversity is our strength.
We have and follow a Code of Conduct.
  - We currently follow the OpenInfra Foundation Code of Conduct as a member of the OpenInfra Labs.
3. **Open Design** : We follow a transparent and open process for planning and designing any content, services, and features of Op1st.
Ideas and contributions are accepted according to their technical merit and alignment with project objectives, scope, and design principles.
4. **Open Work** : Two of our core tools for successful community building are transparency and accessibility.
To support that, work and collaboration must be done in public to the greatest degree possible.
Refer to the section on Community Groups and SIGs in particular for details on how this is performed.
5. **Truly Open Community** : The best way to build a sustainable open source community is to ensure the community is a cohesive, inclusive, and equitable place where all the voices are heard and anyone can rise to leadership positions.

### Code of Conduct

We are using the [upstream OpenInfra Foundation Code of Conduct](https://openinfra.dev/legal/code-of-conduct) until we can convene the new Community SIG to lead an open effort to create our own, modern code of conduct.

### Community membership
**Note:** This document is a work in progress, especially these membership guidelines

We are opening the Governance 1.0 directly borrowing from the [Kubernetes community group definitions](https://github.com/kubernetes/community/blob/master/community-membership.md), then reviewing and refining for the Governance 1.1.

This doc outlines the various responsibilities of contributor roles in Op1st.
The Op1st project is subdivided into subprojects under SIGs.
Responsibilities for most roles are scoped to these subprojects.

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
Anyone is welcome to participate and contribute provided they follow the Op1st Code of Conduct.
The purpose of a SIG is to own and develop a set of subprojects.

A SIG can have its own policy for contribution, described in a README or CONTRIBUTING file in the SIG folder in this repo (e.g. sig-community/CONTRIBUTING.md), and its own mailing list, chat channel, etc.

#### Governance 1.1 future groups
[These descriptions](https://github.com/kubernetes/community#governance) are borrowed from [Kubernetes governance around community groups](https://github.com/kubernetes/community/blob/master/governance.md#community-groups).
They are good-enough placeholders for discussions.

* **Committees** are named sets of people that are chartered to take on sensitive topics. This group is encouraged to be as open as possible while achieving its mission but, because of the nature of the topics discussed, private communications are allowed. Examples of committees include the Technical Steering Committee or an overarching Steering Committee, and things like security or code of conduct.
* **Subprojects** Each SIG can have a set of subprojects. These are smaller groups that can work independently. Some subprojects will be part of the main Kubernetes deliverables while others will be more speculative and live in the kubernetes-sigs github org.
* **Working Groups** are temporary groups that are formed to address issues that cross SIG boundaries. Working groups do not own any code or other long term artifacts. Working groups can report back and act through involved SIGs.
* **User Groups** are groups for facilitating communication and discovery of information related to topics that have long term relevance to large groups of Kubernetes users. They do not have ownership of parts of the Kubernetes code base.
See the full governance doc for more details on these groups.

### Decision making

While the project is in the early stages, we are favoring a balance of including all voices and keeping a rapid pace of progress.
To accomplish this balance, we are using a _consensus decision model_ that gives time and space for everyone to voice concerns with the proposal.

There are two types of consensus models we use, the lightweight and the full:

* **Lightweight consensus** occurs when a decision does not have wide or sweeping effects and is considered approved if no one raises any blocking objections after several days.
In practice, an email is sent to a SIG or main community list, and if no one raises an objection after three days, the proposal passes.
* **Full consensus** decisions require 3 yes votes (+1) and no objections (-1’s) and votes should be left open for at least 72 hours.
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

TBD

### Selecting initial "Technical Steering Committee"

TBD

### Addition of project Values

TBD

### Community Handbook RELEASED with contributor getting-started information

TBD
