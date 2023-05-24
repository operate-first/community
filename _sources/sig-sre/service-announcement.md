# Release Note: Operate First SIG/SRE Infrastructure Services

We are thrilled to announce the general availability of four new services, all part of the Operate First initiative.
These services, operated and maintained by the [#B4mad partition of Operate First](https://github.com/b4mad/op1st-emea-b4mad),
are designed to bring state-of-the-art DevSecOps to your open-source projects.

1. **[Peribolos](https://github.com/apps/peribolos)** is a GitHub organization management tool that treats your
organization settings as code
2. **[op1st Prow](https://github.com/apps/op1st-prow)** is a Kubernetes-based CI/CD system that provides declerative
automation, github-comment-ops, and automatic PR merging
3. **[op1st Tekton](https://github.com/apps/op1st-tekton)**, a powerful and flexible open-source framework for creating
CI/CD systems with a special 'pipeline as code' twist.
4. **[op1st ArgoCD](https://github.com/apps/op1st-argocd)** is a declarative, GitOps continuous delivery tool for
Kubernetes and OpenShift

These services offer immense value to open source communities by fostering collaboration, enhancing security, and
streamlining development processes!

With Peribolos, you can manage your GitHub organization settings as code, enabling a more collaborative and transparent
way of organization management. op1st Prow automates containerized tasks, providing a platform for efficient CI/CD
workflows. op1st Tekton's 'pipeline as code' approach empowers developers with more control and flexibility in their
CI/CD systems. Lastly, op1st ArgoCD delivers a GitOps approach to continuous delivery on Kubernetes and OpenShift,
promoting traceability and repeatability in deployments.

Operate First, by offering these services, is helping open source projects adopt DevSecOps practices and cloud-native
technologies. The Operate First initiative represents a shift towards a transparent and community-driven approach to
managing open-source projects. These services are deployed on the [Nostromo environment](https://github.com/b4mad/op1st-emea-b4mad/blob/main/manifests/environments/nostromo/kustomization.yaml),
a testament to the Operate First initiative's commitment to providing infrastructure services to the open source community!

We invite you to install and use these services in your projects. For any support needed or general questions with
regards to Operate First, please direct your inquiries [here](https://github.com/operate-first/support/issues/new/choose).
Make your open-source project management more effective and collaborative with Operate First services. Try them out today!

This set of services is operated by the _#B4mad partition of Operate First_ and implements the [Operate First SIG/SRE Infrastructure Services](https://github.com/operate-first/community/blob/63223f33e40aecf37f8197e576990ecd24bbeec3/sig-sre/proposal-infra-services.md) proposal and [#251](https://github.com/operate-first/community/issues/251).
