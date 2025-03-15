+++
authors = ["Marc Faulise"]
title = "Molecular You"
date = "2024-04-01"
description = ""
tags = [
    "project",
    "direction",
    "tech-debt",
    "devops",
]
categories = [
    "project",
    "consulting",
]
series = ["Projects"]
+++

**2024**

## Molecular You

[Molecular You](https://www.molecularyou.com/) is a platform to allow
users to submit samples for analysis and review the results. They
examine a key set of bio-markers that generate a health score and
provide a list of nutrition and exercise recommendations that may
improve quality of life.

## Role

I was contracted to review the current state of DevOps and to help
them improve their overall productivity.

## Technologies

* Terraform/Terragrunt
* AWS
* Make/Bash/Ruby

## Outcome

Molecular You was at its 10-year mark when I was asked to help. At
this point, they had a well established process of authoring and deploying
changes. These process were inline with the technologies of the time.
I quickly identified the following problems:

* The single DevOps engineer was overloaded with addition responsibilities
such as overseeing security and handling IT requests
* Developers were not enabled to make changes, and everything needed to go through DevOps
* Change control was very piecemeal
* Environments are unique and managed manually

The easiest change with the greatest potential for impact was
to introduce IaC (Infrastructure as Code). The Engineering Team at
Molecular You already suspected this, so they were ready for this to
begin.

Over the next 3 months, I worked with the Developers to create a new
environment using Terraform. The application consisted of two major
services, so they were deployed to ECS. Years of undocumented, piecemeal
configuration made our work difficult, but in the end we were able to
fully launch the services in the new environment. With that done, I
helped a new DevOps Engineer learn the new system, and they were ready to
continue the remainder of the development on their own.
