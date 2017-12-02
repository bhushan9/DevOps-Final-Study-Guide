# DevOps-Final-Study-Guide

### Configuration Management/Core Concepts/Build


<h5> Understand core concepts related to Configuration Management </h5>
It is a set of tracking and controlling activities that are initiated when software engineering process begins and terminates when software is taken out of operation.
<h5> Identity traditional and modern components and practices related to configuration management</h5>

Traditional <br>
- Identify all items related to software.
- Manage changes to those items.
- Enable variations of items and changes. 
- Maintain quality of versions and releases.
- Provide traceability between changes and requirements.

Modern <br>

- configuration tools
- git, branches
- package managers
- task and build managers
- build machines, virtual environments (dev stacks)
- containers
- data migration
- Other issues: orchestration, inventory, compliance
<h5> Explain issues related to (not using configuration management)</h5>

- Tracking application dependency would be pain

<h5> Design and apply configuration management concepts to a project.</h5>
<h5> Explain differences between continuous integration, deployment, and delivery</h5>

- continuous integration: A practice where developers automatically build, test, and analyze a software change in response to every software change committed to the source repository.
- continuous deployment: ready to be deployed
- continuous delivery: deployed
<h5> Explain operations responsibility models and team values</h5>
<h5> 10 Adages Paper</h5>
<h5> Explain concepts related to vagrant, and ansible</h5>
Vagrant: An interface for interacting with virtual machines.

- Works with a VM provider (e.g. VirtualBox)
- Public repository of images.
- Vagrantfile is a specification that configures image

Ansible: Ansible is software that automates software provisioning, configuration management, and application deployment

<h5> Describe principles, benefits, and issues related to adopting continuous integration</h5>
Principles:

- Maintain code repo
- Automate build, test
- Everyone commit gets built
- Automate deployment

Benefits:

- Enforce discipline of automated testing
- Immediate feedback
- Developers write good quality code becase of different metrics in the pipeline

Issues:

- Constructing pipeline requires significant amount of work
- Not needed if the project is small.
- Value added depends on the quality of tests and how testable the code really is.

<h5> Design a build server</h5>

### Testing

<h5> List and define different types of testing (e.g. acceptance testing vs integration testing)</h5>
Unit Testing: testing each function
Integration: testing multiple modules and their connectivity
System: Testing whole system
Acceptance: System does what it is intented for
<h5> Compare and contrast testing methods</h5>
<h5> Explain flaky tests, test priorization, and test management concepts.</h5>
Flaky tests: Tests fail randomly
Test Priortization: Random ordering, Effectiveness i.e time since last failure, order by test coverage and metrics i.e cost etc.

<h5> Explain automated test generation </h5>
Tests generation is automated i.e constraint based testing.

<h5> Calculate basic constraints for test generation</h5>
<h5> Compare different fuzzing techniques.</h5>
<h5> List ways to seed fuzzing.</h5>
<h5> Explain Benefits and problems of fuzzing.</h5>
<h5> Understand alternative testing techninques such as natural language techniques.</h5>

### Analysis

<h5> Understand metrics, including complexity, OO, and other techniques.</h5>
<h5> Understand and derive program graph from code snippet.</h5>
<h5> Define line, branch, condition, coverage.</h5>
line: how many loc were executed.
branch: how many branches were executed.
condition: how many conditions were executed.
<h5> Explain subsumption and why and when one type of coverage may subsume another.</h5>
branch & condition coverage -> branch coverage -> statement coverage
branch & condition coverage -> condition coverage
<h5> Calculate line, branch, condition coverage.</h5>
<h5> Identify other kinds of coverage: path coverage, mutation testing, data-flow coverage.</h5>
Path Coverage:
mutation testing:
data-flow coverage:
<h5> Identify several uses cases for static analysis.</h5>

- message chains
- nested loop limit
- long methods
<h5> Explain issues and benefits related to static analysis (e.g. versus dynamic analysis or verification.).</h5>
static analysis
- easy to implement because it is done on source code


dynamic analysis:
- difficult to implement since it looks for program behaviour

<h5> Implement static analysis for measuring errors or code quality measures.</h5>


### Deployment/Infrastructure

<h5> Identity Deployment Strategies</h5>
<h5> Compare and contrast deployment strategies (issues/benefits)</h5>
<h5> Feature Flags</h5>
<h5> Understand staging and feature branch deployment</h5>
<h5> Understand how to use docker for deployment and infrastructure design</h5>
<h5> Identity components of cloud infrastructure</h5>
<h5> Explain underlying issues related to infrastructure components</h5>
<h5> Understand microservices</h5>
<h5> Implement basic redis commands</h5>
<h5> Design and apply infrastructure concepts for the design of a scalable and resilence application.</h5>
<h5> Describe how to implement a deployment strategy</h5>

### Analysis + Monitoring

<h5> Understand monitoring concepts and metrics</h5>
<h5> Understand resilience testing, failure injection, and chaos engineering</h5>
<h5> Implementing a flame graph representation from data</h5>
<h5> Describing how to implement basic monkey concepts</h5>
<h5> Design a monitoring and analysis system</h5>
