# Operate First community plan status

The status table has columns with the following meanings:

* **Workstream**: the interdependency being tracked, linking back to related issues on the [community board](https://github.com/orgs/operate-first/projects/16).
* **Status color**: At a glance indication of the status of the workstream:
  * ![RED][96] Workstream is in trouble, somehow seriously off-track, or significantly behind schedule
  * ![YELLOW][97] There is an increased risk of the workstream milestones being affected.
  * ![CHARTREUSE][98] When everything is going well but you have some reservations about calling it all the way Green.
  * ![GREEN][99] The project is on-track and on-schedule.
* **Notes**: Details about the status, listing blockers and actions.

## Statuses

**Workstream** | **Status** | **SIG :: Owner(s)** | **Notes**
---------------|------------|-----------------|----------
[Attracting users][1] | ![YELLOW][97] | **NONE** | Open source dev intake needs work<br/>SRE coop students process for _SRE Camp_ is OK for docs and mentoring, curriculum needed<br/>**Needs an SRE learning paths SIG**<br/>**Action:** Put out call for a SIG to handle open source dev intake path definition and laying out the vision for what the SRE learning paths will look like.
[Messaging][2] | ![GREEN][99] | Community SIG :: Karsten Wade, Gordon Haff | New next step is honing in the community with Gordon Haff, Jason Brooks, et al<br/>Needs community mailing list discussions and ODF-style to finalize<br/>**Action:**  As part of honing, start messaging thread on mailing list about the state of messaging and where decisions/consensus is needed
[Contributor experience][4] | ![YELLOW][97] | **NONE** | New contributor experience is rough and confusing<br/>Community Handbook effort should help, but a critical threshold in the Community Handbook is needed to make it through good-enough tiers: ready for experienced people, ready for some level of close assistance, ready for anyone, etc.<br/><br/>**Action:**  Continue to  drive thread on mailing list about the Handbook and *handbook-first* philosophy<br/>Ask for commitments, volunteers to get handbook rolling<br/>**We have the SMEs we need for this, a SIG or subproject is needed to work with SMEs, create a plan, and implement the changes.**
[Governance][5] | ![GREEN][99] | Community SIG :: Karsten Wade | [Discussion draft](https://github.com/operate-first/community/pull/107) is open and being worked for a Dec 2021/Jan 2022 closure. [Mailing list thread](https://lists.operate-first.cloud/archives/list/community@lists.operate-first.cloud/thread/MBYVORZOB63DMRK6QPLVDWFDJX3WFAQT/) contains more details and discussion.
[Learning paths][10] | ![CHARTREUSE][98] | **NONE** | New `operate-first/training` repo created, needs configuring with `owners`, `README`, and `contributing.md`<br/>A lot of internal alignment happening, will be looking to start SRE SIG in Op1st<br/>Need to start creating learning paths on website using new TBD format<br/>**Action:** Generate ADR about where the training pool will be; does SRE SIG keep all in [same SRE repo](https://github.com/operate-first/SRE)?
[Metrics plan][6] | ![YELLOW][97] | **NONE** | New efforts underway to capture the baseline, such as [this Jupyter Notebook](https://github.com/operate-first/community/pull/80).<br/>Need to move from ad-hoc to strategic<br/>**Action:** SIG needs to take responsibility to define and run this metrics effort.
[Documentation plan][7] | ![CHARTREUSE][98] | **NONE** | Working on plan now [in this issue](https://github.com/operate-first/SRE/issues/424#issuecomment-966354395)<br/>Project overall has the right idea, the Community Handbook should help a lot. User documentation needs organizing, gap analysis, and a plan.<br/>Part of the new contributor experience being rough is the UX around discovering and using documentation<br/>**Action** A SIG needs to take responsibility to define and run this effort.
[Infrastructure (visibility, resources)][9] | ![YELLOW][97] | **NONE** | All there, more visibility of what is where is needed<br/>More hardware needed but coming soon<br/>NOTE: we hear about 100x afterward when someone is held for no resources, it's bad for our reputation<br/>**Action:** Needs transparent update page to ease concerns and help with planning, reputation<br/>**Action** A SIG needs to take responsibility to define and run this effort.
[Marketing plan][8] | ![CHARTREUSE][98] | **NONE** | Needs to be converted entirely into a community document and see the project board is filled properly with all the aspects<br/>**Action** A SIG needs to take responsibility to define and run this effort.
[Event planning][11] | ![GREEN][99] | **NONE** | **Action:** CFP and event coordination underway for SCaLE 19x, KubeCon Valencia 2022, Red Hat Summit, and KubeCon Detroit 2022.<br/>**Action** A SIG needs to take responsibility to define and run this effort.
[Brand review][12] | ![YELLOW][97] | **NONE** | Need an open source designer and a logo review/refresh.<br/>**Action** A SIG needs to take responsibility to define and run this effort.<br/>**Blocked on people's time**
[Help wanted][13] | ![CHARTREUSE][98] | **NONE** | Fairly simple process, just beginning to use. Need to document how to use it, and spread the word about using these, as well as getting it into the Community Handbook.<br/>**Action** A SIG needs to take responsibility to define and run this effort.<br/>**Blocked on people's time**
[Good first issue][14] | ![CHARTREUSE][98] | **NONE** | Fairly straightforward process, just beginning to use. Need to document how to use it, and spread the word about using these, as well as getting it into the Community Handbook.<br/>**Action** A SIG needs to take responsibility to define and run this effort.<br/>**Blocked on people's time**

[1]:https://github.com/orgs/operate-first/projects/16?card_filter_query=label%3Aarea%2Fuser
[2]:https://github.com/orgs/operate-first/projects/16?card_filter_query=label%3Akind%2Fmarketing
[3]:https://github.com/orgs/operate-first/projects/16?card_filter_query=label%3Akind%2Fwebsite
[4]:https://github.com/orgs/operate-first/projects/16?card_filter_query=label%3Akind%2Fexperience+label%3Aarea%2Fcommunity
[5]:https://github.com/orgs/operate-first/projects/16?card_filter_query=label%3Akind%2Fexperience+label%3Aarea%2Fcontributor
[6]:https://github.com/orgs/operate-first/projects/16?card_filter_query=label%3Akind%2Fmetrics
[7]:https://github.com/orgs/operate-first/projects/16?card_filter_query=label%3Akind%2Fdocumentation
[8]:https://github.com/orgs/operate-first/projects/16?card_filter_query=label%3Akind%2Fmarketing
[9]:https://github.com/orgs/operate-first/projects/16?card_filter_query=label%3Aarea%2Fcommunity+label%3Akind%2Fexperience
[10]:https://github.com/orgs/operate-first/projects/16?card_filter_query=label%3Akind%2Ftraining
[11]:https://github.com/orgs/operate-first/projects/16?card_filter_query=label%3Aarea%2Fcommunity+label%3Akind%2Fmarketing
[12]:https://github.com/orgs/operate-first/projects/16?card_filter_query=label%3Aarea%2Fcommunity+label%3Akind%2Fmarketing
[13]:https://github.com/orgs/operate-first/projects/16?card_filter_query=label%3A%22help+wanted%22
[14]:https://github.com/orgs/operate-first/projects/16?card_filter_query=label%3A%22good+first+issue%22
[15]:https://github.com/operate-first/hitchhikers-guide
[96]:/pm-resources/red-100x50.png
[97]:/pm-resources/yellow-100x50.png
[98]:/pm-resources/chartreuse-100x50.png
[99]:/pm-resources/green-100x50.png
