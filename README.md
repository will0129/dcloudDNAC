# dcloudDNAC
7 router topology for doing config templates and bulk device updates

The best way to access this lab is either via WebRDP to the windows 10 station, from which you can access DNAC or Devices. Or Anyconnect to the lab. Either option is good. 

The purpose of this lab and topology is to allow you to onboard the devices into DNAC, setup Sites, and validate how information is automatically configured for PNP and day 2 automation work flows. It also allows for multiple device roles (like a leaf and spine, although these are using c8k's as of today, so no evpn), to show how templates can be used to provision, with variables, multiple devices. 

The use case being you want to configure a site with 2 spine and 2 leaf, or 2 distribution and 2 access. And you want to have "all devices get a loopback1, but only some devices get a loopback 2, and OSPF). Applying templates and composite templates, will allow this. 

Either access the lab using VPN, or the jumphost via webRDP. From here you can access dnac via the browser, and the routers are setup in Putty. The credentials and IP of all devices are below.

Happy labbing!



<img width="680" alt="topo01" src="https://user-images.githubusercontent.com/32154829/209151375-8a36caf6-7101-436e-9384-7160bf6e5f46.png">


<img width="681" alt="topo1" src="https://user-images.githubusercontent.com/32154829/209150938-55c9933a-1bd2-44d1-b416-3f13b2cd5ce0.png">


<img width="676" alt="topo03" src="https://user-images.githubusercontent.com/32154829/209151392-3a8230f8-56a2-4e61-afce-74f080c72947.png">
