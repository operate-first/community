# Operate-First: SIG/SRE Infrastructure Services

## Introduction

Are you an Open Source developer or organization looking to revolutionize the way you develop, operate, and manage your software? Look no further! Our OperateFirst SIG/SRE Infrastructure Cluster offers a unique approach that enhances collaboration, streamlines operations, and drives innovation. Discover how adopting Operate-First principles can empower your team and take your projects to new heights.

SIG/SRE, the Special Interest Group (SIG) for Site Reliability Engineering (SRE) in the Operate First project focuses on a core part of the Operate First goal to improve managed services by fully Opening all aspects of the cloud environment. In particular, we focus on observability, managing fleets, incident response, operability, and similar core disciplines.

## The Operate-First Infrastructure Cluster Advantage

### Seamless Collaboration

By providing an Open Source-based service deployment, the Operate-First Infrastructure Cluster (OFIC | Op1stIC) encourages collaboration between developers, operators, SREs, and other Open Source practitioners. This ecosystem promotes the sharing of knowledge, best practices, and innovation, leading a to a more robust and efficient development process.

### Openly-Operated Infrastructure Services

Our infrastructure services are designed to be transparent and accessible, fostering a learning-while-in-production environment. Developers can gain valuable insights into operational considerations for their projects, enabling them to fine-tune their code and more easily contribute to a continuously improving infrastructure.

### Flexible Service Level Expectations (SLEs)

The Operate-First Infrastructure Cluster allows app teams to adapt the service level expectations according to their needs. Whether you need a higher uptime or customized support, our community-driven approach ensures that your team gets the desired level of service.

### Scalable and Reliable Performance

Our infrastructure cluster is built to scale as your projects grow. Developers and operators work hand-in-hand to maintain and optimize the SIG/SRE Infrastructure Services (CIS), delivering the performance and reliability you need for your projects.

### Community-Driven Innovation

By participating in the Operate-First community, your team will have access to a network of Open Source professionals, each contributing their unique expertise and perspective. This collective intelligence fuels innovation and accelerates problem-solving.

## Conclusion

Embrace the future of Open Source development by joining the Operate-First Infrastructure Cluster. Experience unparalleled collaboration, openly-operated infrastructure services, and a scalable, reliable platform that evolves with your needs. Don't miss the opportunity to be at the forefront of the Open Operations movement. Adopt the Operate-First principles and revolutionize the way you develop and manage your software today!

## Operate-First SIG/SRE Infrastructure Services - ITIL-like Overview

The following table presents an ITIL-like overview of the Operate-First SIG/SRE Infrastructure Services, highlighting the key aspects of service strategy, service design, service transition, service operation, and continual service improvement.

<table>
  <tr>
   <td><strong>ITIL Phase </strong>
   </td>
   <td><strong>Description</strong>
   </td>
  </tr>
  <tr>
   <td>Service Strategy
   </td>
   <td>
<ul>

<li>Establish a community-driven approach to infrastructure management

<li>Align infrastructure services with the needs and expectations of the community

<li>Encourage collaboration and knowledge sharing between developers, operators, SREs, and other Open Source practitioners
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Service Design
   </td>
   <td>
<ul>

<li>Utilize GitHub App for source code maintenance, issue tracking, and project management

<li>Implement Prow for CI/CD jobs and Tekton for CI/CD pipelines&lt;br>- Use ArgoCD for continuous delivery

<li>Establish service level expectations (SLEs) based on community needs and contribution

<li>Ensure scalability and reliability of the infrastructure services
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Service Transition
   </td>
   <td>
<ul>

<li>Onboard new projects and applications through a streamlined process

<li>Utilize GitHub and Slack for seamless communication and collaboration

<li>Continuously integrate, test, and deploy code changes using Prow, Tekton, and ArgoCD

<li>Encourage documentation and knowledge transfer during transitions
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Service Operation
   </td>
   <td>
<ul>

<li>Monitor and maintain the infrastructure services using community-driven efforts

<li>Address issues and incidents through collaborative problem-solving

<li>Utilize Slack channels for real-time communication and support

<li>Ensure ongoing collaboration between app teams and operators to meet service level objectives (SLOs)
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Continual Service Improvement
   </td>
   <td>
<ul>

<li>Regularly assess and adapt service level expectations (SLEs) and objectives (SLOs)

<li>Encourage feedback from community members on infrastructure services

<li> Learn from operational experiences and apply improvements to the infrastructure

<li>Share best practices, documentation, and lessons learned with the community
</li>
</ul>
   </td>
  </tr>
</table>

By adopting an ITIL-like approach, the Operate-First SIG/SRE Infrastructure Services ensures a structured, organized, and efficient management of the infrastructure services. This promotes collaboration, innovation, and continuous improvement within the community-driven cloud environment.

## Empowering Operate-First SIG/SRE Infra with GitHub App, Prow, Tekton, and ArgoCD

### Introduction

The Operate-First SIG/SRE Infrastructure Services (Infra) is committed to providing a robust and efficient development environment. To achieve this, the community incorporates various tools designed to streamline the development process and enhance collaboration. These tools include the GitHub App for source code maintenance, Prow for CI/CD jobs, Tekton for CI/CD pipelines, and ArgoCD for continuous delivery.

### GitHub App for Source Code Maintenance

The GitHub App is an essential component of the Operate-First SIG/SRE Infrastructure Services, providing a central platform for managing code repositories, issue tracking, and project management. With the GitHub App, developers can:

* Collaborate on code changes through pull requests
* Track revisions with version control
* Utilize issue tracking for bug reporting and feature requests
* Create and maintain documentation

### Prow for CI/CD Jobs

Prow, a Kubernetes-native CI/CD system, is used for managing CI/CD jobs within the Operate-First SIG/SRE Infra. Prow offers several benefits, including

* Seamless integration with GitHub, providing automatic triggering of jobs upon events such as pull requests and merges
* Scalable and extensible architecture that can handle a wide range of tasks
* Support for Kubernetes-native plugins and custom plugins
* Automation of tasks like code review, issue management, and testing

### Tekton for CI/CD Pipelines

Tekton is a Kubernetes-native framework for creating and managing CI/CD pipelines. In the Operate-First SIG/SRE Infra, Tekton plays a critical role in streamlining the development process, offering:

* Customizable and reusable pipelines that automate build, test, and deployment processes
* Integration with various tools and platforms, including GitHub and Prow
* Enhanced collaboration through shared pipeline components and tasks
* A cloud-native and scalable solution for managing CI/CD workflows

### ArgoCD for Continuous Delivery (CD)

ArgoCD is a declarative, Kubernetes-native continuous delivery tool that automates the deployment and management of applications. Within the Operate-First SIG/SRE Infra, ArgoCD offers:

* Simplified application deployment through GitOps, ensuring consistency across environments
* Support for Kubernetes-native manifests and Helm, Kustomize, and other templating systems
* Real-time monitoring and automatic synchronization of application states
* Role-Based Access Control (RBAC) for secure and controlled application management

### Backstage (unsure, maybe phase2??)

### Conclusion

By leveraging the GitHub App, Prow, Tekton, and ArgoCD, the Operate-First SIG/SRE Infrastructure Services (Infra) creates an efficient and collaborative development ecosystem. These tools enable developers to maintain source code, manage CI/CD jobs and pipelines, and automate continuous delivery, ultimately driving innovation and enhancing the quality of Open Source projects.

## Service Level Agreement for Operate-First SIG/SRE Infrastructure Services

The Operate-First SIG/SRE Infrastructure Services (Infra) is dedicated to providing a reliable and transparent platform for Open Source developers and organizations. This Service Level Agreement (SLA) outlines the expectations and responsibilities of both the service maintainers and users to ensure a mutually beneficial relationship.

### Service Level Expectations (SLEs)

The Operate-First SIG/SRE Infra operates under Service Level Expectations (SLEs) rather than traditional SLAs. SLEs are determined by the community itself and serve as guidelines for the expected quality of service. These expectations may vary based on the needs and contributions of the app teams and operators involved in maintaining the cloud infrastructure.

### Availability and Uptime

While the Operate-First SIG/SRE Infra aims to provide a high level of availability and uptime, specific guarantees are not provided due to the community-driven nature of the platform. However, the infrastructure team and app teams work collaboratively to minimize downtime and maintain a stable environment.

### Support and Response Time

The Operate-First SIG/SRE Infra offers community-based support, with response times depending on the availability and engagement of community members. While the infrastructure team and app teams actively work to address issues and provide assistance, formal response time guarantees are not provided.

### Service Level Objectives (SLOs)

Service Level Objectives (SLOs) are set in accordance with community needs and contributions. App teams looking for higher uptime or specific support can work with the community to establish and meet these SLOs.

### Maintenance and Updates

The Operate-First SIG/SRE Infra is maintained through collaborative efforts between operators, app teams, and other community members. Regular maintenance and updates are carried out to ensure the stability and security of the infrastructure. Users will be notified of any scheduled maintenance or updates that may impact their services.

### Conclusion

The Operate-First SIG/SRE Infrastructure Services (Infra) SLA is designed to provide a flexible and collaborative environment for Open Source developers and organizations. By fostering a community-driven approach, the platform encourages shared responsibility, knowledge exchange, and innovation, ultimately creating a stronger and more resilient infrastructure.

## Project Request: Deploying OpenShift and SIG/SRE Infrastructure Services’ Components

### Project Purpose

The primary objective of this project is to deploy an OpenShift environment along with the necessary infrastructure components on a cluster of up to eight servers. This deployment will provide the Operate-First SIG/SRE Infrastructure Services with a robust, scalable, and efficient platform for Open Source developers and organizations to collaborate, develop, and deploy their applications. By leveraging the capabilities of OpenShift and the chosen infra components, the project aims to enhance the overall development and operational experience for the community members.

### Key Project Goals

1. Set up servers with the required hardware and network configurations to support the OpenShift environment and infrastructure components.
2. Deploy OpenShift to create a Kubernetes-based platform that enables seamless container orchestration, management, and scaling.
3. Implement infrastructure components such as the GitHub App, Prow, Tekton, and ArgoCD to streamline source code maintenance, CI/CD jobs, CI/CD pipelines, and continuous delivery.
4. Validate the successful deployment and functioning of OpenShift and infra components, ensuring that they meet the requirements and expectations of the Operate-First SIG/SRE Infrastructure Services.
5. Document the deployment process, best practices, and lessons learned to assist future deployments and provide guidance for the community members.

### Sizing Considerations

Given the Operate First experience, we would like to request:

8x PowerEdge R620, 128Gi memory, min 2 NIC, 300Gi storage, see [metal3.io~v1alpha1~BareMetalHost/oct-03-04-compute](https://console-openshift-console.apps.smaug.na.operate-first.cloud/k8s/ns/openshift-machine-api/metal3.io~v1alpha1~BareMetalHost/oct-03-04-compute/yaml) for a good example

By successfully deploying OpenShift and the required infrastructure components on the servers, the project will contribute to the ongoing growth and development of the Operate-First SIG/SRE Infrastructure Services. This deployment will enable a more efficient, collaborative, and innovative environment for Open Source developers and organizations.
