# MacaroniOS
MacaroniOS is MacOS Catalina* &amp; Tiger OS Copies for VM's.
## Table Of Contents
| Name | Link |
|--|--|
| Download MacaroniOS Base | [Click Here](#macaroni-os-base) |
| MacOS Catalina - ISO Image | [Click Here](#macos-catalina-iso-image-download) |
| MacOS Tiger - VMDK | [Click Here](#macos-tiger-vmdk-download) |
| Converting VMDK to VHD(X) | [Click Here](#how-to-convert-vmdk-to-vhdx) |

#
#
#

## Macaroni OS Base
 To download Macaroni OS' Base, you would have to get proper applications. Go [Download .NET Framework](https://go.microsoft.com/fwlink/?linkid=2186537), and install it.
 ![.net installation](https://s3.studytonight.com/tutorials/uploads/pictures/1662316867-106730.png)
 ######
 Second, download the Base Downloader in this repository ([Here to download!](/md/basedownloader.zip)) and open the app. Open the search bar and type "`3456543-23454-32135-94862-56789-4738910-48203-381023-2123401_git`". This is the resource key for the download of MacaroniOS Base. If you type this and press Download, an popup will appear asking you where to put it. Choose the area, and there you go! Macaroni OS Base is downloaded.

## MacOS Catalina ISO Image Download
> WARNING: File may take up to 9GiB of data.
######
 To download MacOS Catalina ISO Image, you would have to get proper applications. Go [Download .NET Framework](https://go.microsoft.com/fwlink/?linkid=2186537), and install it.
 ![.net installation](https://s3.studytonight.com/tutorials/uploads/pictures/1662316867-106730.png)
 ######
 Second, download the Downloader in this repository ([Here to download!](/md/downloader.zip)) and open the app. Open the search bar and type "`234-31-342313-213243-212-3123-12323-2124535-45435-3468483_git`". This is the resource key for the download of MacOS. If you type this and press Download, an popup will appear asking you where to put it. Choose the area, and there you go! MacOS Catalina is downloaded.

## MacOS Tiger VMDK Download
######
 To download MacOS Tiger VMDK, you would have to get proper applications. Go [Download .NET Framework](https://go.microsoft.com/fwlink/?linkid=2186537), and install it.
 ![.net installation](https://s3.studytonight.com/tutorials/uploads/pictures/1662316867-106730.png)
 ######
 Second, download the Downloader in this repository ([Here to download!](/md/downloader.zip)) and open the app. Open the search bar and type "`4231-231-4256787654-34348652-87456-3463-13465-32_git`". This is the resource key for the download of MacOS. If you type this and press Download, an popup will appear asking you where to put it. Choose the area, and there you go! MacOS Tiger is downloaded.

## How to convert VMDK to VHDX
######
 If you are running virtual machines on both VMware ESXi/Workstation and Microsoft Hyper-V, in some cases you may need to convert a VMware virtual machine to Hyper-V format. You can use different V2V migration tools for this. However, it is much faster to simply convert the VMware virtual machine VMDK file to the VHDX format. This is how to.
 #### Powershell
You can use a special PowerShell module to convert VMware virtual disks (vmdk) to Hyper-V format (vhdx). Download and install the [Microsoft Virtual Machine Converter](http://download.microsoft.com/download/9/1/E/91E9F42C-3F1F-4AD9-92B7-8DD65DA3B0C2/mvmc_setup.msi) module on your computer.
######
Open a PowerShell console as an administrator and import the MVMC module into your session:
`Import-Module 'C:\Program Files\Microsoft Virtual Machine Converter\MvmcCmdlet.psd1'`
######
To convert your VMDK file to VHDX format, run the command:
`ConvertTo-MvmcVirtualHardDisk -SourceLiteralPath "C:\SharedVMDK\shareddisk01.vmdk" -VhdType DynamicHardDisk -VhdFormat vhdx -destination C:\VHD`
######
This is how to convert VMDK to VHDX.
