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
around transfer of ownership and warranty of homes. It manages walk-thrus, 
documentation, warranty periods, and service requests.

The platform was created by a passionate entrepreneur in Vancouver that saw
the needs for better solutions. He employed a solutions firm to build his
vision, but the resulting platform was full of problems:

* There were a significant number of defects
* Defects were taking months to correct
* Routine operations like onboarding new customers were taking weeks to complete
* Infrastructure costs incredibly high

## Role

I was contracted to help Juniper become independent from the original 
developers. This was tricky for a number of reasons. 

* Short timeline
* No developer support
* Need for a seamless transition between the two systems

Lucky, Juniper maintained control of the domains and had access to the underlying
data. So, our task was straight-forward despite the difficulties.
Our approach was the following:

* Build the Infrastructure using modern DevOps techniques like IaC
* Automate everything
* Dry-run the migration with our automation and fix problems as they arise
* Notify customers of scheduled maintenance
* Preform the migration and test in `maintenance mode`
* If everything is successful, update the top level domains

## Technologies

* Terraform/Terragrunt
* Bash, Make, Python, Docker
* AWS
* C#/.net
* Postgres

## Outcome

We had three weeks to complete this. We ended up taking six. While we 
were successful, there were a number of hitches along there way where
our automation wasn't as complete as we needed it to be.

Even with those problems, the owner of Juniper was very happy with the
resulting technology stack. I trained his engineering in DevOps and
with the use of Terraform and AWS and with complete documentation, enabled
him to continue developing and maintaining the project on his own.
