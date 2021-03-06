---
copyright:
  years: 2017, 2018
lastupdated: "2018-02-08"

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}
{:pre: .pre}
{:table: .aria-labeledby="caption"}

# About software

{{site.data.keyword.BluSoftlayer_full}} has strategic relationships with vendors to provide month-to-month licenses on 32-bit and 64-bit compatible software.  When you order a device, you select the type of operating system and software for your device. You can add more software to your device within the {{site.data.keyword.slportal_full}} and change to another operating system by performing an OS reload <!-- (../managing/perform-os-reload-device.html)--> on your existing device. The IBM automated system provisions software onto your server by using best practice guidelines of each vendor to ensure maximum stability and availability.

See the following list of currently supported software: [Cloud server software ![External link icon](../../icons/launch-glyph.svg "External link icon")](https://www.ibm.com/cloud-computing/bluemix/cloud-server-software){: new_window}.

If you need software that is not currently supported, use your root access to the server to install and configure your own version of that software.  To return to a supported version on your device, perform an OS reload.

For software documentation, refer to the documentation of the vendor who produces the software.

In the cases that are described in this section, IBM includes instructions or considerations for using products in the {{site.data.keyword.BluSoftlayer_notm}} environment.

## Supported operating systems for IBM Cloud virtual servers
IBM Cloud virtual servers support the following operating systems.

- Cent OS 6 (PV)
- Cent OS 7 (HVM)
- Debian 7 (PV)
- Debian 8 (HVM)
- RHEL 6 (PV)
- RHEL 7 (HVM)
- Ubuntu 14 (PV/HVM) defaults to PV boot mode, but you can to toggle to HVM boot mode
- Ubuntu 16 (PV/HVM) defaults to PV boot mode, but you can to toggle to HVM boot mode
- Windows 2012 (HVM)
- Windows 2012 R2 (HVM)
- Windows 2016 (HVM)

**Note:** Boot disc sizes vary by operating system:<br>  
Linux OS supports 25 GB and 100 GB
Windows supports only 100 GB

For more information about toggliing between PV and HVM boot modes, see the following links:
* [Virtual guest supported boot modes](https://sldn.softlayer.com/reference/services/SoftLayer_Virtual_Guest_Block_Device_Template_Group/getSupportedBootModes)
* [Add boot mode option](https://github.com/softlayer/softlayer-python/pull/936/files/09c35a9595651d66f3e117a055efe585745ba2b3)


