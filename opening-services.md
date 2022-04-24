---
title: Open Source Services: checklist for making one
description: A clear tasklist if you want to open an internal service to the public so it complies with Open Source Services definition.
---
# Open Source Services: checklist for making one

This document is a checklist how you can open an internal service to the public to comply with [Open Source Services](open-source-services.md) guidelines.

* [ ] Create a repository on a gitforge of your choice (GitHub, Gitlab, or others) to host the source code.
  * Create as many as you want: you are free to separate deployment from the service's source code.
  * These repositories need to contain: complete service source-code, assets, deployment scripts and all need to be licensed under an open source license.
  * Since everything will be open, please make sure that you are not leaking any information to the public which should remain private: commit history could be such an example.

* [ ] (optional) Set up Continuous Integration and Continuous Deployment for all the repositories created above.

* [ ] Document contribution process.
  * [ ] Document local service setup.
  * [ ] It is required for team members and public contributors to use the same contribution mechanism.

* [ ] Document operation of the service.
  * [ ] Secrets management.

* [ ] Document interaction with public instances: including development instance, staging/test and production.

* [ ] Make sure you comply with your internal guidelines for opening projects up.
