<h1> Utilizing Azure to encrypt internet traffic across the globe. </h1>

![Screenshot 2024-05-21 215141](https://github.com/RalphgoldIT/VPN/assets/170049429/7c5476ed-3e92-48dc-b45f-d758d46ddf75)



<h2>Introduction </h2>
In this project, I set up a VPN using ProtonVPN while working with Azure's virtual machines to make the computer that I'm using to appear as though I am surfing the internet in another country. I did this by  

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- Proton VPN
- Azure
- Virtual machines

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- ProtonVPN
- Windows 10
- Azure
<h2>(Create Virtual Machine in Azure)</h2>
<h2>Configuration Steps</h2>
<p>
1. Create a Resource Group
</p>

![Screenshot 2024-05-21 211833](https://github.com/RalphgoldIT/VPN/assets/170049429/87b3f536-affd-460b-836f-0ee10995c97a)

<p>
2. Create a virtual machine using Azure but change the location to any other region that is not your precise location 
</p>

![Screenshot 2024-05-21 211952](https://github.com/RalphgoldIT/VPN/assets/170049429/3ad49cd8-2733-4360-82be-240e04361233)

![Screenshot 2024-05-21 212111](https://github.com/RalphgoldIT/VPN/assets/170049429/01edabf5-6c31-4193-9633-2f3343c97e08)


<p>
3. Copy the virtual machine public ip and Log into the VM with Remote Desktop 
</p>

![Copy Public IP on Virtual Machine](https://github.com/RalphgoldIT/VPN/assets/170049429/1836070e-0af1-49b5-983e-99a93e74c48f)

![Login to VM via Remote Desktop](https://github.com/RalphgoldIT/VPN/assets/170049429/6ff05200-7b9c-47af-9e1e-8fb1a971031c)


<p>
4. Browse to https://whatismyipaddress.com/  and take note of this
</p>

![Checking my IP without VPN](https://github.com/RalphgoldIT/VPN/assets/170049429/b1f8221e-baae-439d-9f4a-a5669de501ba)


<h2>(Sign up for ProtonVPN and test the VPN connection)</h2>

<p>
5. On your actual computer, sign up for the free version of Proton VPN 
</p>

![create account on proton VPN](https://github.com/RalphgoldIT/VPN/assets/170049429/1f5a0100-a697-4249-84bb-a667da05890c)

<p>
6. Back within your VM, download the Proton VPN client 
</p>

![download the free version of proton VPN](https://github.com/RalphgoldIT/VPN/assets/170049429/19eca304-3068-40e7-8a4d-38ee08ebeff7)

<p>
7. Login to the VPN and choose a VPN server in yet another country 
</p>

![Login to Proton VPN](https://github.com/RalphgoldIT/VPN/assets/170049429/a4167a45-e4f6-4b15-b126-0ff63514d1af)

<p>
8. Browse to https://whatismyipaddress.com/  and take note of this 
</p>

![checking my Ip address after connecting VPN](https://github.com/RalphgoldIT/VPN/assets/170049429/b70225a2-2850-40d7-959f-6a8577bf3f20)


<h2>(Clean up Azure resources)</h2>

<p> 9. Delete the resource group you created </p>

![Screenshot 2024-05-21 211020](https://github.com/RalphgoldIT/VPN/assets/170049429/e470f2bb-17b4-4e61-9b02-8c03f27f55ba)


![Screenshot 2024-05-21 211020](https://github.com/RalphgoldIT/VPN/assets/170049429/facbd76f-a6b9-484c-897d-a26792dcc9f3)

![Screenshot 2024-05-21 211132](https://github.com/RalphgoldIT/VPN/assets/170049429/a40b780b-885d-4f15-9265-fb97a47eb949)

![Screenshot 2024-05-21 211205](https://github.com/RalphgoldIT/VPN/assets/170049429/7e4a6ac8-7048-436c-9154-72fd4400e464)


<p> 10. Ensure the resources/Resource Group has been deleted </p>  



