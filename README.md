# DEV269 - Universal Kubernetes Management for Private or Hybrid Cloud

This repository contains the material for the SAP TechEd 2020 session called DEV269 - Universal Kubernetes Management for Private or Hybrid Cloud.

## 📌 Overview

This session introduces attendees to the capabilities offered by the open source solution [Gardener](https://gardener.cloud). Gardener is used by SAP for centralized management of thousands of homogeneous Kubernetes clusters. They run on all the public hyperscalers like AWS, Azure, GCP, AliCloud, etc. in all their data centers around the globe, and also in private or restricted environments based on OpenStack, VMware vSphere, or Equinix Metal/Packet.

## 🚦 Requirements

The requirements to follow the exercises in this repository are:

- A UserID registered on www.sap.com
- At least basic knowledge on the following topics:
    - Cloud Technologies and Containerization
    - [Kubernetes](https://kubernetes.io)

## 👨🏼‍💻 Exercises

- [Getting Started and Registration](exercises/ex0_getting_started/registration.md)
- [Exercise 1 - Getting to know Gardener (Beginners)](exercises/ex1_beginners/README.md)
    - [Exercise 1.1 - Navigate into Gardener Dashboard](exercises/ex1_beginners/01_dashboard.md)
    - [Exercise 1.2 - Project Clusters](exercises/ex1_beginners/02_project_clusters.md)
    - [Exercise 1.3 - Cluster overview](exercises/ex1_beginners/03_cluster_overview.md)
- [Exercise 2 - Managing Gardener shoot clusters (Advanced)](exercises/ex2_advanced_ui/README.md)
    - [Exercise 2.1 - Create your first Gardener Project](exercises/ex2_advanced_ui/01_create_project.md)
    - [Exercise 2.2 - Create your first shoot cluster](exercises/ex2_advanced_ui/02_cluster_setup_ui.md)
    - [Exercise 2.3 - Cluster lifecycle operations](exercises/ex2_advanced_ui/03_cluster_ops.md)
    - [Exercise 2.4 - Using shoot clusters - deploy and add-on](exercises/ex2_advanced_ui/04_deploy_sample_addon.md)
    - [Exercise 2.5 - Clean up](exercises/ex2_advanced_ui/05_cleanup.md)
- [Exercise 3 - Using Gardener with kubectl (Advanced)](exercises/ex3_advanced_cli/README.md)
    - [Exercise 3.1 - Shoot cluster setup using YAML](exercises/ex3_advanced_cli/01_cluster_setup_yaml.md)
    - [Exercise 3.2 - Garden cluster](exercises/ex3_advanced_cli/02_garden_cluster.md)
    - [Exercise 3.3 - Editing shoot cluster through YAML](exercises/ex3_advanced_cli/03_edit_shoot.md)
    - [Exercise 3.4 - Gardener's controllers at work](exercises/ex3_advanced_cli/04_controllers_at_work.md)


:warning: If you have already registered your account on www.sap.com then start the exercises [here](exercises/ex1_beginners/01_dashboard.md). Otherwise, please [REGISTER](https://www.sap.com/registration/trial.908cb719-0e03-421c-a091-daca045f0acc.html) first.

## 📞 How To Obtain Support

This is an on-demand session and you can request support via the [Issues](../../issues) tab.

## 📚 [Learn More!](https://github.com/gardener/gardener#learn-more)

## 📑 License
Copyright (c) 2020 SAP SE or an SAP affiliate company. All rights reserved. This file is licensed under the Apache Software License, version 2.0 except as noted otherwise in the [LICENSE](LICENSES/Apache-2.0.txt) file.
