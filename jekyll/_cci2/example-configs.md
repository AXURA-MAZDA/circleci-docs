---
layout: classic-docs
title: "Example Public Repos"
short-title: "Example Public Repos"
description: "Starting point for CircleCI 2.0 docs"
categories: [getting-started]
order: 1
---

Refer to the following documents and linked `.circleci/config.yml` files for complete examples of public and open source projects that run on CircleCI.

* TOC
{:toc}

## Example CircleCI files and public repos
{: #example-circleci-files-and-public-repos }

Example Name | Description | Link
----|----------|--------
Sample `config.yml` Files | Four sample `config.yml` files using concurrent Workflows, sequential Workflows, fan-in/fan-out Workflows, and building Linux and iOS in one configuration file. | <a href="{{ site.baseurl }}/2.0/sample-config/">Sample `config.yml` Files</a>
Example Database Configurations | Three example `config.yml` files using PostgreSQL/Rails, Go/PostgreSQL, and Ruby/MySQL | [Example Database Configurations]({{ site.baseurl }}/2.0/postgres-config/)
Parallel | Concurrent job run workflow configuration. | [parallel-jobs/.circleci/config.yml](https://github.com/CircleCI-Public/circleci-demo-workflows/blob/parallel-jobs/.circleci/config.yml)
Sequential | Sequential job run workflow configuration | [sequential-branch-filter/.circleci/config.yml](https://github.com/CircleCI-Public/circleci-demo-workflows/blob/sequential-branch-filter/.circleci/config.yml)
Fan-in / Fan-out | Workflow configuration with sequenced jobs followed by concurrent jobs chained to a final sequenced job. | [fan-in-fan-out/.circleci/config.yml](https://github.com/CircleCI-Public/circleci-demo-workflows/blob/fan-in-fan-out/.circleci/config.yml)
Workspace Forwarding | Jobs configured to share data with workspaces. | [workspace-forwarding/.circleci/config.yml](https://github.com/CircleCI-Public/circleci-demo-workflows/blob/workspace-forwarding/.circleci/config.yml)
circleci-docs | A static website generated by Jekyll for CircleCI documentation. | [circleci-docs/.circleci/config.yml](https://github.com/circleci/circleci-docs/blob/master/.circleci/config.yml)
circleci frontend | Mirror of the code that is running CircleCI's frontend Clojure app. | [frontend/.circleci/config.yml](https://github.com/circleci/frontend/blob/master/.circleci/config.yml)
circleci-images | Contains the official set of container images that CircleCI maintains. | [circleci-images/.circleci/config.yml](https://github.com/circleci/circleci-images/blob/master/.circleci/config.yml)
circleci image-builder | Uses Docker for building container images. | [image-builder/.circleci/config.yml](https://github.com/circleci/image-builder/blob/master/.circleci/config.yml)
circleci-demo-docker | This is an example application showcasing how to build Docker images in CircleCI 2.0. | [.circleci/config.yml](https://github.com/CircleCI-Public/circleci-demo-docker/blob/master/.circleci/config.yml)
{: class="table table-striped"}

## Open source projects by feature
{: #open-source-projects-by-feature }

The following projects provide examples of using features and functionality of CircleCI configuration syntax:

Example Description | Project | config.yml link
------|-----------|------------
Caching with templates, using workspaces, concurrent workflow jobs | Build mobile apps with **React**. | [react-native/.circleci/config.yml](https://github.com/facebook/react-native/blob/master/.circleci/config.yml)
Build and test with custom container image for ARM and x64 with `xvfb` and mocha | The **Electron** framework lets you write cross-platform desktop applications using JavaScript, HTML and CSS. It is based on Node.js and Chromium. |[electron/.circleci/config.yml](https://github.com/electron/electron/blob/master/.circleci/config.yml)
Build, test, and upload run for macOS and Linux | **Conda** is a platform- and language-independent package manager that sports easy distribution, installation and version management of software. | [bioconda-recipes/.circleci/config.yml](https://github.com/bioconda/bioconda-recipes/blob/master/.circleci/config.yml)
Build and register a Docker image, deploy to AWS ECS | **Taco** is a next generation repository system for DLSS. | [taco/.circleci/config.yml](https://github.com/sul-dlss-labs/taco/blob/master/.circleci/config.yml)
Docker compose and `docker cp` with `store_artifacts` | **Mayflower** is the enterprise design system for the Commonwealth of Massachusetts. | [mayflower/.circleci/config.yml](https://github.com/massgov/mayflower/blob/develop/.circleci/config.yml)
Remote Docker, Docker Layer Caching, build and push Docker images | **Epoch** is a new blockchain for æpps. | [epoch/.circleci/config.yml](https://github.com/aeternity/epoch/blob/master/.circleci/config.yml)
Multi-platform build, test, deploy run with fan-out/fan-in workflow | **Canary** is universal serverless single-command deployment. | [canary/.circleci/config.yml](https://github.com/zeit/now-cli/blob/canary/.circleci/config.yml)
Build and test on multiple platforms with tagged releases | **Crystal** is a programming language. | [crystal/.circleci/config.yml](https://github.com/crystal-lang/crystal/blob/master/.circleci/config.yml)
Tagged and scheduled workflow jobs | Node.js idiomatic client for **Cloud Pub/Sub**. | [nodejs-pubsub/.circleci/config.yml](https://github.com/googleapis/nodejs-pubsub/blob/master/.circleci/config.yml)
{: class="table table-striped"}

## Open source projects by language
{: #open-source-projects-by-language }

The following projects provide examples for particular programming languages, testing mechanisms, and deployment targets:

Example Description | Project | config.yml link
------|-----------|------------
Bazel build and testing with `xvfb` | **Angular** is a development platform for building mobile and desktop web applications using Typescript/JavaScript and other languages. | [angular/.circleci/config.yml](https://github.com/angular/angular/blob/master/.circleci/config.yml)
Salesforce DX | This repository shows one way you can successfully set up **Salesforce DX** with CircleCI. | [sfdx-circleci/.circleci/config.yml](https://github.com/forcedotcom/sfdx-circleci/blob/master/.circleci/config.yml)
Golang build with `junit` and Kubernetes tests for prod and master job workflow | The **Azure Container Service Engine** (acs-engine) generates ARM (Azure Resource Manager) templates for Docker enabled clusters on Microsoft Azure with your choice of DC/OS, Kubernetes, Swarm Mode, or Swarm orchestrators. | [acs-engine/.circleci/config.yml](https://github.com/Azure/acs-engine/blob/master/.circleci/config.yml)
Go and Node build, package, and deploy run | **Ignition** is a landing page for developers to self-service their way onto your Pivotal Cloud Foundry (PCF) deployment(s). | [ignition/.circleci/config.yml](https://github.com/pivotalservices/ignition/blob/master/.circleci/config.yml)
Java build and publish with `sbt` | **Scio** is a Scala API for Apache Beam and Google Cloud Dataflow inspired by Apache Spark and Scalding. | [scio/.circleci/config.yml](https://github.com/spotify/scio/blob/master/.circleci/config.yml)
Javascript Node frontend build with `junit` and end-to-end Webdriver screeshot tests | This is the frontend code for **cBioPortal** using React, MobX and TypeScript. | [cbioportal-frontend/.circleci/config.yml](https://github.com/cBioPortal/cbioportal-frontend/blob/master/.circleci/config.yml)
Node and Yarn with manual deploy gate | **Docusaurus** is a project for easily building, deploying, and maintaining open source project websites. | [Docusaurus/.circleci/config.yml](https://github.com/circleci/circleci-images/blob/master/.circleci/config.yml)
Node and Yarn test and deploy website with caching | **NEO•ONE** makes coding, testing and deploying your NEO blockchain solutions easier. | [neo-one/.circleci/config.yml](https://github.com/neo-one-suite/neo-one/blob/master/.circleci/config.yml)
Build and test with NPM and Yarn, deploy to S3 | The official **CLARK Platform** client | [clark-client/.circleci/config.yml](https://github.com/Cyber4All/clark-client/blob/master/.circleci/config.yml)
Python build with Postgres database, Selenium tests, and CodeClimate | **CALC** (formerly known as "Hourglass"), which stands for Contracts Awarded Labor Category, is a tool to help contracting personnel estimate their per-hour labor costs for a contract, based on historical pricing information. | [calc/.circleci/config.yml](https://github.com/18F/calc/blob/develop/.circleci/config.yml)
Python build with `apt` for concurrent job run with webhooks notification | **SunPy** is an open-source Python library for solar physics data analysis. | [sunpy/.circleci/config.yml](https://github.com/sunpy/sunpy/blob/master/.circleci/config.yml)
Scala and `sbt` build, test, and release with three workflows | **Arweave4s** is a lightweight modular HTTP client for the Arweave blockchain. | [arweave4s/.circleci/config.yml](https://github.com/toknapp/arweave4s/blob/master/.circleci/config.yml)
{: class="table table-striped"}

## See also
{: #see-also }

Refer to [Tutorials and Sample Apps]({{ site.baseurl }}/2.0/tutorials/) for configuration walkthroughs with commented examples and detailed explanations for basic applications written in 11 different languages.
