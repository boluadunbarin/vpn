<p align="center">
</p>

<h1>Virtual Private Network Setup and Usage</h1>



<h2>Project Summary: Environments and Technologies Used</h2>
-In this tutorial, we observe how VPNs work. We will understand how to 'sit' at a server anywhere on the planet. This can be used to mask your identity. We will also see how VPNs can filter content that appears as you browse the web.
- 
<h3> </h3>
Microsoft Azure (Virtual Machines/Compute) with Windows 10 in a foreign country
-<h4></h4> Remote Desktop
-<h5></h5> Text file,Proton VPN
-<h6></h6> whatismyipaddress.com, google.com, disney.com, amazon.com

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
<h2>High-Level Steps</h2>

- Create a windows 10 virtual computer
- Check the ip address of your main computer and that of the virtual computer
- Install Proton VPN and use it to connect to a server somewhere else on the planet
- Check your ip address and several websites to notice the change in source country of your internet searches

<h2>Media(images)</h2>

![Screenshot 2024-02-02 110352](https://github.com/boluadunbarin/vpn/assets/157642328/c674a478-04cb-47b7-9088-91ef67770da7)

Go to whatismyipaddress.com to see your public ip address

![Screenshot 2024-02-02 110639](https://github.com/boluadunbarin/vpn/assets/157642328/e9e5d95d-5133-4d21-adfd-d297ba2c7a17)

Create a resource group for another country

![Screenshot 2024-02-02 111237](https://github.com/boluadunbarin/vpn/assets/157642328/52f7f90a-9d45-4507-bfc5-41c74e7e7d8d)

![Screenshot 2024-02-02 111625](https://github.com/boluadunbarin/vpn/assets/157642328/3481fcfe-23ff-47ef-b253-96499e4c00e7)

Create a virtual computer and network for the same country as above

![Screenshot 2024-02-02 123539](https://github.com/boluadunbarin/vpn/assets/157642328/1c548faf-9744-405e-8e5f-5176df027303)

Log into remote desktop as the user

![51](https://github.com/boluadunbarin/vpn/assets/157642328/378666bc-b3ba-4d0f-97fe-438d762df3f0)

Go to whatismyipaddress.com and look at the new ip address. It'll be from the country you chose earlier.

![Screenshot 2024-02-02 123025](https://github.com/boluadunbarin/vpn/assets/157642328/b92a0d42-fae7-406a-844c-b4801b8acc5e)

![Screenshot 2024-02-02 113455](https://github.com/boluadunbarin/vpn/assets/157642328/ff6cd836-e114-497c-a86d-0ebc53c67be8)

Download and install Proton VPN on your main computer

Log into Proton VPN and connect to a server in another country

![Screenshot 2024-02-02 113641](https://github.com/boluadunbarin/vpn/assets/157642328/b919922c-9ade-45f3-b546-e7e0d770599e)

Go to whatismyipaddress.com and look at the new ip address. It'll be from the country you connect to

![Screenshot 2024-02-02 125544](https://github.com/boluadunbarin/vpn/assets/157642328/d86e773a-b26a-4d0d-a70d-b5c669ef1b84)

Check google.com. Notice the Japanese content

![Screenshot 2024-02-02 125737](https://github.com/boluadunbarin/vpn/assets/157642328/a4dc5c72-b1b1-4bf1-9261-e50afebd689c)

Check disney.com. Notice the Japanese content

![Screenshot 2024-02-02 130008](https://github.com/boluadunbarin/vpn/assets/157642328/7f13843b-b419-47f8-a44d-7f8bd716d72a)

Check amazon.com. Notice the shipping is for Japanese regions.

<h2>Demonstration </h2>

Uses for VPN:

- File sharing: You can access company specific content in this environment. This can be beneficial when transfering or sharing data over the internet to a remote location.
- View material that may be censored, essentially bypassing government restrictions. 

- Privacy: VPNs mask your ip address making it harder for websites to monitor your online activity/
anonymous internet activity.
- Access content that is geographically based: if you want to access services from another country.

-VPNs can also shield you from cyber threats, safeguarding sensitive data.
