<properties
	pageTitle="Create a virtual machine running Windows in Azure"
	description="Create a Windows virtual machine in the Azure classic portal."
	services="virtual-machines"
	documentationCenter=""
	authors="cynthn"
	manager="timlt"
	editor=""
	tags="azure-service-management"/>

<tags
	ms.service="virtual-machines"
	ms.workload="infrastructure-services"
	ms.tgt_pltfrm="vm-windows"
	ms.devlang="na"
	ms.topic="article"
	ms.date="08/11/2015"
	ms.author="cynthn"/>

# Create a virtual machine running Windows in the Azure classic portal

> [AZURE.SELECTOR]
- [Azure portal](virtual-machines-windows-tutorial.md)
- [Azure classic portal](virtual-machines-windows-tutorial-classic-portal.md)
- [PowerShell: Resource Manager deployment](virtual-machines-deploy-rmtemplates-powershell.md)
- [PowerShell: Classic deployment](virtual-machines-ps-create-preconfigure-windows-vms.md)

[AZURE.INCLUDE [learn-about-deployment-models](../../includes/learn-about-deployment-models-classic-include.md)] [Resource Manager deployment model](virtual-machines-windows-tutorial.md).

This tutorial shows you how easy it is to create an Azure virtual machine (VM) in the Azure classic portal. We'll use a Windows Server image as an example, but that's just one of the many images Azure offers. Note that your image choices depend on your subscription. For example, desktop images may be available to MSDN subscribers.

You can also create VMs using [your own images](virtual-machines-create-upload-vhd-windows-server.md). To learn about this and other methods, see [Different ways to create a Windows virtual machine](virtual-machines-windows-choices-create-vm.md).

[AZURE.INCLUDE [free-trial-note](../../includes/free-trial-note.md)]

## Video walkthrough

Here's a walkthrough of this tutorial.

[AZURE.VIDEO creating-a-windows-vm-on-microsoft-azure-classic-portal]

## <a id="createvirtualmachine"> </a>How to create the virtual machine

This section shows you how to use the **From Gallery** option in the Azure classic portal to create the virtual machine. This option provides more configuration choices than the **Quick Create** option. For example, if you want to join a virtual machine to a virtual network, you'll need to use the **From Gallery** option.

> [AZURE.NOTE] You can also try the richer, customizable Azure portal to create a virtual machine, use enhanced monitoring and diagnostics, use Premium storage, and more. The available options for configuring a virtual machine in the two portals overlap substantially but aren't identical. For example, use the Azure portal to configure a virtual machine with Premium storage.

[AZURE.INCLUDE [virtual-machines-create-WindowsVM](../../includes/virtual-machines-create-windowsvm.md)]

## Next steps

- Log on to the virtual machine. For instructions, see [How to log on to a virtual machine running Windows Server](virtual-machines-log-on-windows-server.md).

- Attach a disk to store data. You can attach both empty disks and disks that contain data. For instructions, see the [Attach a data disk tutorial](storage-windows-attach-disk.md).
