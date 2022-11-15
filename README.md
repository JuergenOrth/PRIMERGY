# PRIMERGY
## Links for tools regarding automating Fujitsu PRIMERGY server management.

* **iRMC** (integrated Remote Management Controller)
  * RESTful API: The legacy and vendor specific interface to automate all operations of an iRMC.
    * [iRMC RESTful API specification](https://support.ts.fujitsu.com/IndexDownload.asp?SoftwareGuid=6863BE99-5B75-48EF-9AD8-5751373482A6)
    * [iRMC REST API examples (*)](https://github.com/fujitsu/iRMC-REST-API)
  * Redfish: The [DMTF](https://www.dmtf.org/standards/redfish) standardized protocol to manage a BMC across vendors, such as iRMC, iDRAC, iLO, ...
    * [iRMC S5 Redfish API specification](https://support.ts.fujitsu.com/IndexDownload.asp?SoftwareGuid=D8B307C8-314D-4393-9ECF-A4D3B052F96F)
    * [iRMC S6 Redfish API specification](https://support.ts.fujitsu.com/IndexDownload.asp?SoftwareGuid=924FFF86-CD5C-433A-A0BB-91CD1CD6B29D)
    * [iRMC Redfish API examples (*)](https://github.com/fujitsu/iRMCtools)
    * [iRMC Redfish API examples (Python based)](https://github.com/mmurayama/fujitsu-redfish-samples)
  * Ansible: One of the leading tools for general configuration and administration of IT systems.
    * [Fujitsu Ansible iRMC integration](https://github.com/fujitsu/fujitsu-ansible-irmc-integration)
* **ISM** (Fujitsu Software Infrastructure Manager)
  * RESTful API: Available with the advanced version of ISM.
    * [ISM v2.8 REST API specification](https://support.ts.fujitsu.com/IndexDownload.asp?SoftwareGuid=1BC17707-0D8A-4DDA-81B3-A06BD7E0910B)
    * [ISM Rest API examples (*)](https://github.com/fujitsu/ISMtools)
  * Ansible
    * [Fujitsu Ansible ISM integration](https://github.com/fujitsu/ism-ansible)
 * **Nagios/Icinga**: A tool for monitoring complex IT landscapes.
   * [PRIMERGY Nagios PlugIn](https://support.ts.fujitsu.com/IndexDownload.asp?SoftwareGuid=A8AEEB69-F040-4C0E-A1D2-C5F812B32BFB)
 * **Patches/Drivers/Tools**: Where you can find all this stuff.
   * [Fujitsu Support Page](https://support.ts.fujitsu.com): User space where you can select patches, drivers, manuals, tools for your hardware or software.
   * [Fujitsu GlobalFlash](https://support.ts.fujitsu.com/DownloadManager/globalflash): The machine readable version of drivers and patches, used by eLCM, ISM, Content Collector, Repository Server, ...
   * [Fujitsu Linux OEM drivers repository](https://support.ts.fujitsu.com/linux/pldp): Repositories for OEM drivers of RHEL and SLES.
   * [Fujitsu MySupport](https://support.ts.fujitsu.com/IndexMySupport.asp)
   * Repository Manager: A tool to mirror *Fujitsu GlobalFlash* into your own location.
     * [RPM](https://support.ts.fujitsu.com/IndexDownload.asp?SoftwareGuid=A3BFCA8A-33A1-49BC-8B00-C3E795A2ED8B)
     * [Virtual appliance VMware](https://support.ts.fujitsu.com/IndexDownload.asp?SoftwareGuid=20E1532D-FE47-446E-BD39-6F2332C1C161)
     * [Virtual appliance Hyper-V](https://support.ts.fujitsu.com/IndexDownload.asp?SoftwareGuid=812CD74B-7514-4526-9EEB-5C846087DC18)
   * Content Collector: A tool to download a couple for drivers/patches and optionally create boot devices.
     * [Content Collector](https://support.ts.fujitsu.com/IndexDownload.asp?SoftwareGuid=3A992351-EE5E-4B3B-936D-BCC771C764F2)

  (*) written/maintained by me

Please be aware that there may be newer document/program versions available!
