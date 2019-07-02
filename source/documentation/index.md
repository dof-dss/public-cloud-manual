## Introduction

This document sets out how public cloud services should be consumed by teams developing and deploying cloud-native applications to a public cloud service.

## Using GOV.UK PaaS

[GOV.UK PaaS][1] provides UK-based web hosting for Government services. GOV.UK PaaS uses the open source [Cloud Foundry][2] project and runs on Amazon Web Services.

### Concepts

GOV.UK PaaS uses the concept of [organisations, spaces, and users][3] to manage resources available on the platform.

### Organisations and spaces model

#### Development and test environments

DSS has decided to use a single organisation for each of the following environments:

- development
- system test
- UAT

In this model each organisation will have a space for each application or service.

*insert diagram here*

#### Pre-production and production environments

Each application or service will have a dedicated organisation.

*insert diagram here*

### Users and roles

Users are assigned roles which have different permissions for accessing and managing orgs and spaces. A user can have one or multiple roles within the same or different orgs and spaces.

### Admin tool

The [admin tool][4] is a web portal that provides access to all the cloud resources available to you. It allows you to manage users and view billing information.

Although there are multiple roles, the 4 most common are:

- [Org manager][5]
- [Billing manager][6]
- [Space developer][7]
- [Space manager][8]

### Creating organisations and spaces

#### Creating organisations

Organisations for Development, System Test and UAT have been created already.

New organisations can only be created by the GOV.UK PaaS team. You must submit a request to the [DSS architecture team][9] to have a new organisation created.

#### Creating spaces

### Access to environments

### Deploying applications

### Monitoring costs

## Using Amazon Web Services

## Using Microsoft Azure

[1]:https://docs.cloud.service.gov.uk/
[2]:https://www.cloudfoundry.org/
[3]:https://docs.cloud.service.gov.uk/orgs_spaces_users.html
[4]:https://login.london.cloud.service.gov.uk/login
[5]:https://docs.cloud.service.gov.uk/orgs_spaces_users.html#org-manager
[6]:https://docs.cloud.service.gov.uk/orgs_spaces_users.html#billing-manager
[7]:https://docs.cloud.service.gov.uk/orgs_spaces_users.html#space-developer
[8]:https://docs.cloud.service.gov.uk/orgs_spaces_users.html#space-manager
[9]:mailto:ea-team@ea.finance-ni.gov.uk
