---
name: feature_request.md
about: Dep-Deploy
title: ''
labels: ''
assignees: ''

---

**Is your feature request related to a problem? Please describe.**

The current CI/CD pipeline only performs basic tasks (checkout, package update, simple test, and deploy message). It does not build the application, run real automated tests, or generate deployment artifacts. This limits the usefulness of the pipeline for continuous integration and delivery.

**Describe the solution you'd like**

I would like to improve the CI/CD pipeline by:

* Adding a build stage.
* Running automated tests.
* Publishing build artifacts.
* Using GitHub Secrets for sensitive information.
* Preparing the pipeline for deployment to development and production environments.

**Describe alternatives you've considered**

An alternative would be to keep the current pipeline as a demonstration workflow. However, implementing a complete CI/CD pipeline following DevOps best practices will better reflect a production environment and improve software quality.
