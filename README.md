# C# Cloud Azure Day Three

## Learning Objectives

- Understand what an Azure Function is and why we might use it
- Understand how to create and deploy an Azure Function
- Understand what Terraform is and why we might use it
- Introduce Azure Bastion Development Tier

## Instructions

1. Fork this repository
2. Clone your fork to your machine

## Setup

1. Terraform setup

   - Run `terraform version` to check what version you have installed.
   - Installation details can be found [here](https://developer.hashicorp.com/terraform)

2. Azure Setup

   - Run `az version` to check what version you have installed.
   - Run `az upgrade` to upgrade your current version.
   - Installation details can be found [here](https://learn.microsoft.com/en-us/cli/azure/install-azure-cli)

## Core Activity

For this exercise you should:

- Create a series of Azure functions to perform some basic mathematic calculations e.g. Add, Subtract
- Write a Terraform script to initialise this in Azure

## Extension Activity

- Store an audit history of your calculations in suitable Azure storage. You should include a when the call was made, with what parameters and what was the result.
- Create a function to return all of this audit history

## Notes

We will be only using free tiers to create Azure items.

- Use [Terraform](https://developer.hashicorp.com/terraform/install)
- Use [Azure CLI](https://learn.microsoft.com/en-us/cli/azure/install-azure-cli)
- Use the [Microsoft Azure Storage Explorer](https://azure.microsoft.com/en-us/products/storage/storage-explorer/)
