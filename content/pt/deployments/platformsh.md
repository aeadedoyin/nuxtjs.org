---
template: guide
title: Platform.sh
description: How to deploy Nuxt on Platform.sh?
target: Static & Server
category: deployment
logo:
  light: "/img/companies/square/dark/Platformsh_Dark.svg"
  dark: "/img/companies/square/light/Platformsh_Light.svg"
---
# Deploy Nuxt on Platform.sh

How to deploy Nuxt on Platform.sh?

---

[Platform.sh](https://platform.sh/) is a full-featured end-to-end continuous deployment cloud hosting system for both staging and production environments. It is capable of hosting both static and dynamic applications in a variety of languages.

Platform.sh includes the following features:

- Build, deploy, manage, and scale applications.
- Any branch can be a staging environment; create and delete environments with ease.
- Support for almost any Node.js, PHP, Python, Ruby, Go, or Java application, in your choice of version, or mix and match.
- Automatic TLS certificates.
- Integrated build pipeline to customize your application's build process however you need.
- Infrastructure-as-code: define three YAML files and your entire cluster is created on demand. Add and remove services with ease.
- Deploy code directly from your GitHub and GitLab repositories.

## Setup

Platform.sh has a pre-made template for Nuxt available. The link below will create a new Platform.sh project and pre-populate it with a sample Nuxt application that you can then customize.

<p align="center">
<a href="https://console.platform.sh/projects/create-project?template=https://raw.githubusercontent.com/platformsh/template-builder/master/templates/nuxtjs/.platform.template.yaml&utm_content=nuxtjs&utm_source=nuxtjs_orgb&utm_medium=button&utm_campaign=deploy_on_platform" target="_blank">
    <img src="https://platform.sh/images/deploy/lg-blue.svg" alt="Deploy on Platform.sh" height="40px" width="180px" />
</a>
</p>

The `README.md` file includes details of the provided default configuration. New Platform.sh accounts are free for the first 30 days.
