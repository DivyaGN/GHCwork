# DockerWorkshop-GHC
Docker Workshop for GHC

This is a workshop intended for GHC conference happening @ Bangalore on 3rd December 2015.

We have added all necessary things in the repo starting from documentation of Installation steps,Docker Commands,Docker References, Docker Troubleshooting , Tips and tricks,Sample example Docker applications to demonstrate in  the workshop.

We have given it to our best to put all the details to make it self explanatory :).

Tip:

Make sure that you have at least 8 GiBs of free disk space, so that you won't fill up your disk with container images ( this is due to downloading many different docker images which we will use in our examples and excercises. Of course you can remove these images right after moving from one excercise to another and/or rebuilt the container later on,

Setup:

We are using the below setup:

1. VM ware Player
2. Direct OVA For Photon VM creation

Windows:

You can easily set up your environment through VMware player:

1.1	INSTALL VMWARE PHOTON OS ON VMWARE WORKSTATION

		OS Template to choose: Other Linux 3.x 64bit
	
Windows: (Through VMware player)

1.	VMware Player download : http://www.vmware.com/products/player/playerpro-evaluation.html 


2.	Back UP : Both for windows 32 and 64 bit OS :
	https://my.vmware.com/web/vmware/free#desktop_end_user_computing/vmware_player/6_0|PLAYER-607|product_downloads 

3.	Download photon ISO 1st, https://dl.bintray.com/vmware/photon/iso/1.0TP2/x86_64/photon-1.0TP2.iso 

      a.	Steps to install Photon on player :       
      
      http://www.virten.net/2015/04/guide-to-install-photon-in-vmware-workstation-and-deploy-a-container/ 
      
      b.	Reference video : https://www.youtube.com/watch?v=YTzel0Y0lTU 

1.2	DEPLOY OVA DIRECTLY FOR PHOTON VM CREATION

1.	Download OVA :  https://dl.bintray.com/vmware/photon/ova/1.0TP2/x86_64/photon-1.0TP2.ova 
2.	Creating a Photon OS VM by Importing the OVA Using the OVA is the easiest way to create a Photon OS VM. 
3.	Once you’ve downloaded the OVA, open VMware Fusion and select, “Import …” from the File menu. 
4.	This will open the “Choose an Existing Virtual Machine” wizard. 
5.	Use the “Choose File …” button to locate and select the Photon OS OVA. Note: The “Import” operation is specific to Fusion. 
6.	For Workstation player users, simply double-clicking on the OVA will start the import.



Mac OS :

1.VMware fusion
2.If you use Mac OS X and don't want VM's -> https://github.com/noplay/docker-osx

Option1:
MAC OS (Through Fusion)
1.	Download VMware fusion on your MAC Laptop (similar as player) : http://www.vmware.com/products/fusion/fusion-evaluation?productId=361 
2.	Steps to install Photon on fusion : https://github.com/vmware/photon/wiki/Running-Project-Photon-on-Fusion 
3.	Reference YouTube video : https://www.youtube.com/watch?v=lHW795iSpNs 

Option2:
If you use Mac OS X and don't want VM's -> https://github.com/noplay/docker-osx


2	HOW TO ACCESS BIOS AND ENABLE INTEL VIRTUALIZATION TECHNOLOGY ON WINDOWS 8/8.1/10
2.1	CONFIRM VIRTUALIZATION TECHNOLOGY IS ENABLED OR DISABLED?

Option 1:
1.	Intel® Processor Identification Utility: It is a software to verify if VT is enabled or not for Intel processor. 
2.	Download pidenu42.msi and install it on your desktop : https://downloadcenter.intel.com/download/7838 
Option 2:
3.	MICROSOFT® HARDWARE-ASSISTED VIRTUALIZATION DETECTION TOOL 
4.	Following tool to verify VT enabled status for both Intel and AMD processor. Just download exe and run it, it shows pop up and says VT is not enabled or enabled. 
5.	http://www.microsoft.com/en-us/download/confirmation.aspx?id=592&6B49FDFB-8E5B-4B07-BC31-15695C5A2143=1
Option 3:
6.	When installing player, it shows pop up as vt is not enabled so no vms can be powered on.


Note: download_deps_before.workshop.sh
The script will help you make sure that docker is up and running, we want to go swiftly through excercises, it will also download everyting before so we won't have to rely on the internet connection.

Note: There is a repo on github with useful aliases for docker
https://github.com/GHCwork/DockerWorkshop


