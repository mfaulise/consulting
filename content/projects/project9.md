+++
authors = ["Marc Faulise"]
title = "Juniper"
date = "2025-01-01"
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

**2023-2025**

## Juniper

Juniper is a platform for Home Owners and Builders to organize the activities
around transfer of ownership and warranty. It manages walk-thrus, 
documentation, warranty periods, and service requests.

The platform was created by a passionate entrepreneur in Vancouver that saw
the need for better tools in this area. He employed a solutions firm to build his
vision, but the resulting platform was full of problems:

* There were a significant number of defects
* Defects were taking months to correct
* Routine operations like onboarding new customers were taking weeks to complete
* Infrastructure costs were incredibly high

## Role

I was contracted to help Juniper become independent from the original 
developers. This was tricky for a number of reasons. 

* Short timeline
* No developer support
* Need for a seamless transition between the two systems

Lucky, Juniper maintained control of the domains and had access to the underlying
data. So, our task was straight-forward despite the difficulties.
This was our approach:

* Build the Infrastructure using modern DevOps techniques like IaC
* Automate everything including all steps of the migration
* Dry-run the migration and fix problems as they arise
* Notify customers of scheduled maintenance
* Preform the migration and test in `maintenance-mode`
* If everything is successful, update the top level domains

## Technologies

* Terraform/Terragrunt
* Bash, Make, Python, Docker
* AWS
* C#/.net
* Postgres

## Outcome

We had three weeks to complete the migration. It took six. While we 
were successful, there were a number of hitches along there way where
our automation wasn't as complete as we needed it to be.

Even with those problems, the owner of Juniper was very happy with the
resulting technology stack. I trained his engineer in DevOps, Terraform
and AWS. With the help of complete documentation, this enabled
him to continue developing and maintaining the project on his own.
