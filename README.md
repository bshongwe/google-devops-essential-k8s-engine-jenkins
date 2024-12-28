![Visits Badge](https://badges.pufler.dev/visits/bshongwe/google-devops-essential-k8s-engine-jenkins)
![GitHub Repo Stars](https://img.shields.io/github/stars/bshongwe/google-devops-essential-k8s-engine-jenkins)
![GitHub Forks](https://img.shields.io/github/forks/bshongwe/google-devops-essential-k8s-engine-jenkins)
![GitHub Issues](https://img.shields.io/github/issues/bshongwe/google-devops-essential-k8s-engine-jenkins)
![GitHub License](https://img.shields.io/github/license/bshongwe/google-devops-essential-k8s-engine-jenkins)

# Continuous Delivery with Jenkins in Kubernetes Engine

Overview

In this lab, you will learn how to set up a continuous delivery pipeline with Jenkins on Kubernetes engine. Jenkins is the go-to automation server used by developers who frequently integrate their code in a shared repository.

# What you'll learn

In this lab, you'll complete the following tasks to learn about running Jenkins on Kubernetes:

    Provision a Jenkins application into a Kubernetes Engine Cluster
    Set up your Jenkins application using Helm Package Manager
    Explore the features of a Jenkins application
    Create and exercise a Jenkins pipeline

# Prerequisites

This is an advanced level lab. Before taking it, you should be comfortable with at least the basics of shell programming, Kubernetes, and Jenkins. Here are some labs that can get you up to speed:

    Introduction to Docker
    Hello Node Kubernetes
    Managing Deployments Using Kubernetes Engine
    Setting up Jenkins on Kubernetes Engine

Once you are prepared, scroll down to learn more about Kubernetes, Jenkins, and Continuous Delivery.

# What is Kubernetes Engine?

Kubernetes Engine is Google Cloud's hosted version of Kubernetes - a powerful cluster manager and orchestration system for containers. Kubernetes is an open source project that can run on many different environments—from laptops to high-availability multi-node clusters; from virtual machines to bare metal. As mentioned before, Kubernetes apps are built on containers - these are lightweight applications bundled with all the necessary dependencies and libraries to run them. This underlying structure makes Kubernetes applications highly available, secure, and quick to deploy—an ideal framework for cloud developers.
What is Jenkins?

Jenkins is an open-source automation server that lets you flexibly orchestrate your build, test, and deployment pipelines. Jenkins allows developers to iterate quickly on projects without worrying about overhead issues that can stem from continuous delivery.
What is Continuous Delivery / Continuous Deployment?

When you need to set up a continuous delivery (CD) pipeline, deploying Jenkins on Kubernetes Engine provides important benefits over a standard VM-based deployment.

When your build process uses containers, one virtual host can run jobs on multiple operating systems. Kubernetes Engine provides ephemeral build executors—these are only utilized when builds are actively running, which leaves resources for other cluster tasks such as batch processing jobs. Another benefit of ephemeral build executors is speed—they launch in a matter of seconds.

Kubernetes Engine also comes pre-equipped with Google's global load balancer, which you can use to automate web traffic routing to your instance(s). The load balancer handles SSL termination and utilizes a global IP address that's configured with Google's backbone network—coupled with your web front, this load balancer will always set your users on the fastest possible path to an application instance.

# Setup and requirements
Before you click the Start Lab button

Read these instructions. Labs are timed and you cannot pause them. The timer, which starts when you click Start Lab, shows how long Google Cloud resources will be made available to you.

This hands-on lab lets you do the lab activities yourself in a real cloud environment, not in a simulation or demo environment. It does so by giving you new, temporary credentials that you use to sign in and access Google Cloud for the duration of the lab.
