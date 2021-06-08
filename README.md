# Demo Days 2021 - How GitHub uses infrastructure as code
##### Top
<img width="1500" alt="demo-days" src="https://user-images.githubusercontent.com/863198/120851502-e7118600-c546-11eb-9dc9-0171dd09b9ee.png">

An inside look at how the GitHub team uses Infrastructure as Code (IaC) to power a successful unified DevOps platform. We will demonstrate how we use the principles of shared ownership and rapid feedback, empowered by automation, to deploy GitHub safely and reliably at scale

![dot](docs/images/cut-here.png)


# Part-1

# Some *"thoughts"* about IaC

<br><br>

## ***Provisioning*** vs ***Configuring***

![cvc](docs/images/demodays-provision-config.png)

Many IaC tools provide no clear boundries between Provisioning and Configuring.

You can simply *"stretch"* them to do what you want

<br><br><br><br>

## IaC should give you an...

  - **Immutable** Infrastructure
    - unchangable, just destroy and rebuild it when needed

  - **Idemtoptent** Infrastructure 
    - no matter how many times you run it, you get the same (declared) results

<br><br><br><br>

## Where do you apply IaC in your Enterprise ?

#### *"Food for thought"*...

- Do you need the power of a full infrastructure for your build process ? Or would Docker be enough ?

- Use it when you need a "realistic" test environment !

- Use it to maintain a fully managed Production environemnt

<br><br><br><br>

## What's your Role in IaC ?

You can look at IaC from many different "angles", based on that IaC provides different benefits for each.

|User|vs|Maintainer|
|---|---|---|
|Standup infrastructure when, where and for how long, you need it !<br><br> <li>**Self-Service !** <br>  <li>**Rapid Feedback !**||Automated Intrastructure <br><br> <li>**Standardization** <br> <li> **Workflow** <br> <li> **Control**|

<br><br><br><br>

[:arrow_up: Top](#Top) - [:arrow_left: Previous](#Top) - [Next :arrow_right:](#Part-2)
![dot](docs/images/cut-here.png)

# Part-2

# IaC on GitHub

---
### The *"parts"* of IaC


![iac](docs/images/demodays-iac-parts.png)


<table  border="0px"><tr><td><img src=docs/images/workflow-customization.png></td><td><b>Self-Service + Rapid Feedback</b></td></tr></table>

<br><br><br><br>

[:arrow_up: Top](#Top) - [:arrow_left: Previous](#Part-1) - [Next :arrow_right:](#Part-3)
![dot](docs/images/cut-here.png)

# Part-3

# What can IaC do for you

<br><br><br><br>

## At GitHub we work asynchronously, and to make that possible we have to...
  - Prevent resource *"bottlenecks"*
  - Enable **global collaboration**. Location and timezone become a minor issue.

<br><br><br><br>

## We“centralize” our collaboration efforts through the GitHub Platform

<br><br><br><br>

[:arrow_up: Top](#Top) - [:arrow_left: Previous](#Part-2) - [Next :arrow_right:](#Part-4)
![dot](docs/images/cut-here.png)

# Part-4

# The *"Demo-Stack"*

<table  border="0px"><tr><td><img src=docs/images/service-account-engineer.png width="360px"></td><td><h3>GitHub Professional services uses IaC to setup GitHub Enterprise systems with a variaty of stack combinations, including 3rd party tools.</h3></td></tr></table>

![iac](docs/images/IaC-Hubot-concept.png)

<br><br><br><br>

[:arrow_up: Top](#Top) - [:arrow_left: Previous](#Part-3) - [Next :arrow_right:](#Part-5)
![dot](docs/images/cut-here.png)

# Part-5

### subtitle

[:arrow_up: Top](#Top) - [:arrow_left: Previous](#Part-4) - [Next :arrow_right:](#Part-6)
![dot](docs/images/cut-here.png)

# Part-6

### subtitle

[:arrow_up: Top](#Top) - [:arrow_left: Previous](#Part-5) - [Next :arrow_right:](#Part-7)
![dot](docs/images/cut-here.png)

## Part-7

### subtitle

[:arrow_up: Top](#Top) - [:arrow_left: Previous](#Part-6)
![dot](docs/images/cut-here.png)





