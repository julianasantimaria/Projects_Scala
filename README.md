# Individual Infrastructure as Code projects

This repository contains a series of Infrastructure as Code files that I made to allocate resources in the Cloud: AWS, Azure and GCP.

## Overview

There are individual projects for allocating resources in clouds through code. 

Each project has its particularity in the amount of resources, cloud, network, subnet, IAM, region of the allocated resource, etc. In some projects, the code may allocate resources to different characteristics at once. 

The advantage of increasing resources in this way is the guarantee of CI/CD control, cost control and greater control of all allocated resources, creating ease and agility in the process.

<br/><br/>
Project1 - Tools and Languages: AWS EMR, Apache Flink, Terraform - AWS.<br/>
Project Functions: Automation of scalable infrastructure for batch and streaming data pipelines with low latency.<br/>
Objective: Develop a robust solution for data processing, leveraging AWS EMR and Apache Flink, with IaC provisioning automated via Terraform.
<br/><br/>
Project2 - Tools and Languages: Terraform, AWS (EMR), PySpark, Apache Spark and Hadoop on AWS.<br/>
Project Functions: Automated deployment of a scalable cluster for distributed Machine Learning, Big Data model training, and resource optimization through distributed processing.<br/>
Objective: Train large-scale ML models using PySpark on EMR, ensuring efficient analysis of petabyte-scale data with advanced Data Science practices. All integration and result generation are automated in Terraform.
<br/><br/>
Project3 - Tools and Languages: Terraform, Azure.<br/>
Project functions: Deployment of a VM with network configuration, vnet, subnet, etc. And the creation of Grafh.<br/>
Objective: Do everything that was done in the previous projects, but now in the Azure cloud. All integration and result generation are automated in Terraform.
<br/><br/>
project4 - In this project, we will build the necessary scripts to deploy infrastructure on 2 Cloud Computing providers simultaneously. Each infrastructure will consist of a server instance including virtual network, subnet and IP address. Each server instance can be used, for example, to run applications. This Multi-Cloud Deployment was created on AWS and Azure.
<br/><br/>
Project5 - Implementation of a cluster in Databricks using Terraform for infrastructure automation. In this Project 5, I automated the deployment of the cluster, a notebook with a processing script in Python and an execution job.
<br/><br/>

## Infrastructure as Code (IaC)

 <img width="2500px" align="right"  src="https://github.com/julianasantimaria/ProjectsTerraform/blob/HTML/IaC.jpeg">

 <br/>
 <br/>


## Project Structure

The structuring of this repository is difficult and does not require Frontend, Backend, Data, Data Science or Machine Learning development, but within the resources, at times, there are application scripts and ML models, to exemplify the direct allocation of resources with projects or data.

These are IaC projects for allocating resources in the cloud through code. The other add-ons merely exemplify the possibility of allocating tools that already contain developed projects.

## Requisites

Make sure you have Docker and Terraform tools and accounts in the Azure, AWS and GCP clouds.

```bash
- Docker
- Terraform
- AWS
- GCP
- Azure