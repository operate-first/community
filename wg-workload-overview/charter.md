# WG Operate First Workload Overview

## Scope

The goal of this working group is to set up a page that shows an overview of the workloads running on the Operate First fleet of clusters. This overview should include information like the project/application owner's github handles, pull request in which the project namespace was created and link to some kind of documentation pertaining to the applcation/workload.

### In scope

* Use available data like Prometheus metrics from workload namespaces
* Add annotations to existing service/app manifest to reflect project owners
* Update onboarding process so that project owner information is collected during project onboarding and added as annotations to manifests
* The information displayed should be dynamic and not need to be updated manually in dashboards

## Deliverables

* A url to a dashboard/jupyterbook that displays a dynamic overview of workloads running on Operate First clusters

## Stakeholders

* SIG Operations

## Disband criteria

If stakeholder SIGs and the WG decide all features described in the `In Scope` section are complete and no more discussions and investigations are needed in this WG, they may decide to disband this WG.
