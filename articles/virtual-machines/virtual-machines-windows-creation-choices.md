---
title: Different ways to create a Windows VM in Azure | Microsoft Docs
description: Lists the different ways to create a Windows virtual machine with Resource Manager.
services: virtual-machines-windows
documentationcenter: ''
author: cynthn
manager: timlt
editor: ''
tags: azure-resource-manager

ms.assetid: 809ba8f4-b54e-43c5-bbe3-8e710c49971f
ms.service: virtual-machines-windows
ms.devlang: na
ms.topic: article
ms.tgt_pltfrm: vm-windows
ms.workload: infrastructure-services
ms.date: 09/27/2016
ms.author: cynthn
ms.custom: H1Hack27Feb2017

---
# Different ways to create a Windows virtual machine

Azure offers different ways to create a virtual machine because virtual machines are suited for different users and purposes. This means that you need to make some choices about the virtual machine and how to create it. This article gives you a summary of these choices and links to instructions.

## Azure portal
Using the Azure portal is a simple way to try out a virtual machine, especially if you're just starting out with Azure. 

[Create a virtual machine running Windows using the portal](virtual-machines-windows-hero-tutorial.md?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json)

## Template
Virtual machines require a combination of resources (such as a availability sets and storage accounts). Rather than deploying and managing each resource separately, you can create an Azure Resource Manager template that deploys and provisions all of the resources in a single, coordinated operation.

* [Create a Windows virtual machine with a Resource Manager template](virtual-machines-windows-ps-template.md?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json)

## Azure PowerShell
If you prefer working in a command shell, you can use Azure PowerShell.

* [Create a Windows VM using PowerShell](virtual-machines-windows-ps-create.md?toc=%2fazure%2fvirtual-machines%2fwindows%2ftoc.json)

## Visual Studio
Use Visual Studio to build, manage, and deploy VMs with the Azure Tools for Visual Studio and the Azure SDK.

[Azure Tools for Visual Studio](https://www.visualstudio.com/features/azure-tools-vs)

