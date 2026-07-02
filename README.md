# Deployment (deployment)
An index and topic collection covering application deployment platforms, Platform-as-a-Service (PaaS) providers, and CI/CD-as-a-service tools that expose APIs for shipping code to production. Deployment platforms automate the path from source repository to running application, handling build, release, promotion, rollback, and continuous delivery. This collection spans modern PaaS providers like Vercel, Netlify, Render, Railway, Fly.io, and Heroku; cloud platform deployment services like AWS Elastic Beanstalk, Google Cloud Run, and Azure App Service; hosted CI/CD platforms like GitHub Actions, GitLab CI, CircleCI, Travis CI, Buildkite, and Harness; and GitOps and continuous delivery tools like Argo CD, Flux CD, Spinnaker, Octopus Deploy, Jenkins, Tekton, and Werf.

**URL:** [https://apievangelist.com](https://apievangelist.com)

## Tags:

 - Deployment, CI/CD, Continuous Deployment, Continuous Integration, Continuous Delivery, PaaS, GitOps, Build, Pipeline, Release Management

## Timestamps

- **Created:** 2026-05-19
- **Modified:** 2026-05-19

## Common Properties

- [Portal](https://apievangelist.com)
- [GitHubOrganization](https://github.com/api-evangelist)
- [JSONSchema - Deployment Schema](https://raw.githubusercontent.com/api-evangelist/deployment/refs/heads/main/json-schema/deployment-deployment-schema.json)
- [JSONSchema - Pipeline Schema](https://raw.githubusercontent.com/api-evangelist/deployment/refs/heads/main/json-schema/deployment-pipeline-schema.json)
- [JSON-LD](https://raw.githubusercontent.com/api-evangelist/deployment/refs/heads/main/json-ld/deployment-context.jsonld)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/deployment/refs/heads/main/vocabulary/deployment-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Git-Driven Deployment | Modern PaaS providers like Vercel, Netlify, Render, and Railway connect directly to Git repositories and automatically deploy on every push, branch, or pull request. |
| Continuous Integration Pipelines | CI/CD-as-a-service platforms like GitHub Actions, GitLab CI, CircleCI, and Buildkite provide hosted runners that execute build, test, and packaging pipelines triggered by source control events. |
| Continuous Delivery and Release Orchestration | Continuous delivery tools like Spinnaker, Harness, and Octopus Deploy coordinate multi-stage rollouts across environments with approval gates, canary analysis, and automated rollback. |
| GitOps and Declarative Sync | GitOps controllers like Argo CD and Flux CD continuously reconcile cluster state with declarative manifests stored in Git, treating the repository as the source of truth for deployments. |
| Build Pipelines and Artifacts | Build-focused services like AWS CodeBuild, Google Cloud Build, Dagger, Earthly, and Buildpacks compile source code into deployable artifacts in reproducible environments. |
| Preview Environments | Platforms like Vercel, Netlify, Railway, and Qovery automatically spin up isolated preview environments for every pull request. |
| Managed Application Runtimes | PaaS offerings like Heroku, AWS Elastic Beanstalk, Google App Engine, and Azure App Service abstract away infrastructure, scaling deployed applications based on traffic. |
| Release Promotion and Approval Gates | Pipeline tools like Octopus Deploy, Harness, and Azure DevOps model environments and promotion stages with role-based approval gates between development, staging, and production. |

## Use Cases

| Name | Description |
|------|-------------|
| Push-to-Deploy Frontend Hosting | Frontend teams connect a Git repository to Vercel, Netlify, or Cloudflare Pages and every commit automatically builds and deploys a new version, with preview URLs for every pull request. |
| Multi-Stage CI/CD for Backend Services | Engineering teams use GitHub Actions, GitLab CI, or CircleCI to build, test, scan, and publish backend services through promotion stages from development to production. |
| GitOps Continuous Deployment to Kubernetes | Platform teams use Argo CD or Flux CD to declaratively sync Kubernetes manifests from Git repositories into clusters, with drift detection and automated reconciliation. |
| Legacy Application Modernization on PaaS | Organizations migrate legacy web applications to managed runtimes like Heroku, AWS Elastic Beanstalk, or Azure App Service to offload patching, scaling, and load balancing. |
| Progressive Delivery with Canaries | SRE teams use Spinnaker, Harness, or Argo Rollouts to release new versions to a small percentage of traffic, observe key metrics, and automatically promote or roll back based on health. |
| Enterprise Release Orchestration | Release engineering teams use Octopus Deploy or Harness to coordinate complex multi-service releases across hybrid environments with approvals, runbooks, and audit trails. |
| Edge and Serverless Container Deployment | Teams deploy containerized microservices to managed runtimes like Google Cloud Run, AWS App Runner, Fly.io, or Koyeb to get autoscaling and global distribution without managing Kubernetes. |

## Integrations

| Name | Description |
|------|-------------|
| Vercel | Frontend cloud platform optimized for Next.js and other JavaScript frameworks, with Git-driven deployments, preview URLs, and a global edge network. |
| Netlify | Web platform for modern static and Jamstack sites with built-in CI/CD, edge functions, and preview deployments for every pull request. |
| GitHub Actions | Native CI/CD service for GitHub repositories with hosted runners, a marketplace of reusable actions, and tight integration with the GitHub event model. |
| Argo CD | GitOps continuous delivery tool for Kubernetes that continuously reconciles cluster state with declarative manifests stored in Git. |
| Spinnaker | Multi-cloud continuous delivery platform from Netflix and Google supporting advanced deployment strategies, manual judgments, and pipeline-as-code. |
| Heroku | Original Platform-as-a-Service with a polyglot buildpack model, dyno-based runtime, and add-on marketplace for managed databases and services. |
| Octopus Deploy | Release orchestration and deployment automation platform focused on enterprise environments, approvals, and complex multi-target releases. |
| Harness | AI-driven software delivery platform spanning CI, CD, feature flags, cloud cost, and chaos engineering with adaptive verification. |

## Artifacts

Machine-readable specifications organized by format.

### JSON Schema

- [Deployment Schema](json-schema/deployment-deployment-schema.json)
- [Pipeline Schema](json-schema/deployment-pipeline-schema.json)

### JSON Structure

- [Deployment Structure](json-structure/deployment-deployment-structure.json)
- [Pipeline Structure](json-structure/deployment-pipeline-structure.json)

### JSON-LD

- [Deployment Context](json-ld/deployment-context.jsonld)

## Vocabulary

- [Deployment Vocabulary](vocabulary/deployment-vocabulary.yaml) - Taxonomy mapping resources, actions, workflows, and personas across deployment platforms, CI/CD pipelines, and GitOps tooling.

## Network

This index references the following deployment platform and CI/CD repositories:

- Modern PaaS: [Vercel](https://github.com/api-evangelist/vercel), [Netlify](https://github.com/api-evangelist/netlify), [Render](https://github.com/api-evangelist/render), [Railway](https://github.com/api-evangelist/railway), [Fly.io](https://github.com/api-evangelist/fly-io), [Heroku](https://github.com/api-evangelist/heroku), [Koyeb](https://github.com/api-evangelist/koyeb), [Northflank](https://github.com/api-evangelist/northflank), [Porter](https://github.com/api-evangelist/porter), [Qovery](https://github.com/api-evangelist/qovery)
- Cloud Platform Deployment: [AWS App Runner](https://github.com/api-evangelist/aws-app-runner), [AWS Elastic Beanstalk](https://github.com/api-evangelist/aws-elastic-beanstalk), [Google Cloud Run](https://github.com/api-evangelist/google-cloud-run), [Google Cloud App Engine](https://github.com/api-evangelist/google-cloud-app-engine), [Google Cloud Deploy](https://github.com/api-evangelist/google-cloud-deploy), [Microsoft Azure App Service](https://github.com/api-evangelist/microsoft-azure-app-service), [Cloud Foundry](https://github.com/api-evangelist/cloud-foundry)
- Hosted CI/CD: [GitHub Actions](https://github.com/api-evangelist/github-actions), [GitLab CI](https://github.com/api-evangelist/gitlab-ci), [Bitbucket Pipelines](https://github.com/api-evangelist/bitbucket-pipelines), [CircleCI](https://github.com/api-evangelist/circleci), [Travis CI](https://github.com/api-evangelist/travis-ci), [Buildkite](https://github.com/api-evangelist/buildkite), [TeamCity](https://github.com/api-evangelist/teamcity), [Drone CI](https://github.com/api-evangelist/drone-ci), [Azure DevOps](https://github.com/api-evangelist/azure-devops)
- Build Services: [AWS CodeBuild](https://github.com/api-evangelist/aws-codebuild), [Google Cloud Build](https://github.com/api-evangelist/google-cloud-build), [Dagger](https://github.com/api-evangelist/dagger), [Earthly](https://github.com/api-evangelist/earthly), [Buildpacks](https://github.com/api-evangelist/buildpacks)
- Continuous Delivery and Release: [Spinnaker](https://github.com/api-evangelist/spinnaker), [Harness](https://github.com/api-evangelist/harness), [Octopus Deploy](https://github.com/api-evangelist/octopus-deploy), [Codefresh](https://github.com/api-evangelist/codefresh), [CloudBees](https://github.com/api-evangelist/cloudbees), [Jenkins](https://github.com/api-evangelist/jenkins), [Jenkins Pipeline](https://github.com/api-evangelist/jenkins-pipeline)
- GitOps and Declarative: [Argo CD](https://github.com/api-evangelist/argo-cd), [Flux CD](https://github.com/api-evangelist/fluxcd), [Tekton](https://github.com/api-evangelist/tekton), [KubeVela](https://github.com/api-evangelist/kubevela), [GitOps](https://github.com/api-evangelist/gitops), [Werf](https://github.com/api-evangelist/werf)
- Platform Engineering: [Cycloid](https://github.com/api-evangelist/cycloid), [env0](https://github.com/api-evangelist/env0), [Spacelift](https://github.com/api-evangelist/spacelift), [Gitea](https://github.com/api-evangelist/gitea)
- Standards: [Continuous Delivery Foundation](https://github.com/api-evangelist/continuous-delivery-foundation)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
