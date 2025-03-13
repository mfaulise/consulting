+++
authors = ["Marc Faulise"]
title = "Patient Signs"
date = "2025-02-01"
description = ""
tags = [
    "project",
    "development",
    "direction",
    "tech-debt",
    "testing",
    "mentoring",
]
categories = [
    "project",
    "consulting",
]
series = ["Projects"]
+++

**2022-2025**

## Patient Signs

[Patient Signs](https://www.patientsigns.com/) builds a platform to deliver
up-to-the-minute medical details to e-ink signs that can be installed at
patient beds, rooms and in other critical areas. The goal is to replace the
manual and error prone system which requires healthcare workers to update
signage as patient information changes.

## Role

I was brought onto this project as a DevOps and Software engineer. My
original objectives included learning and evaluating the existing software
for maintainability, extensibility, scalability and stability. After 
my appraisal, the decision was reached to completely rewrite the software.
It is very rare that I will encourage this approach, but unfortunately, it 
was the only safe path forward for the organization.

I planned and staffed the rewrite initiative. I set the direction and let
the engineer responsible run with it. At the same time, I coordinated with
Hospital IT to build and manage onsite instances that would run our software.
I built tooling for building, deploying, testing and operating third-party 
services. I created IaC (Infrastructure as Code) projects for managing
users, security, and other resources in our cloud environments. I built
script for backing up and restoring our services as well. And finally, I
planned our observability strategy.

## Technologies

* C#/.net
* Windows Server
* Linux
* Docker
* SQL Server
* Bash
* AWS
* Terraform/Terragrunt

## Outcome

The project rewrite was extremely successful. We had feature parity in weeks
and we were deploying in the second month. We experienced some difficulty with
the deployment but were able to resolve it quickly.

The team was working very well together, but due to circumstances outside our 
control, funding for the project was pulled.
