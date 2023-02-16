<p align="center">
<img src="https://pbs.twimg.com/card_img/1622700386913259520/ZR-iCTVk?format=png&name=medium" alt="ProtonVPN Logo"/>
</p>

<h1>Setting up a VPN inside of a Azure Virual Machine</h1>
This tutorial outlines the implementation of a VPN within an Azure Virtual Machine.<br />

<h2>What is a VPN?</h2>
<p>
<img src="https://i.imgur.com/2FQjYiP.png" height="80%" width="80%" alt="VPN Steps"/>
</p>
<p>
In the diagram above, you can see a very clear picture of how a VPN works. Simply put, a VPN or Virtual Private Network is a secure direct tunnel between a computing device and a computer network.
</p>
<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- ProtonVPN

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (Windows 10 Pro)

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/0dXOJCZ.png" height="80%" width="80%" alt="VPN Steps"/>
</p>
<p>
Step 1: On your local PC, browse to https://whatismyipaddress.com/ and take note of the IPv4 in a text file, I use NotePad for example. In this scenario you can see my actual location (Manitowoc, WI) and my IP address is 73.37.187.30.
</p>
<br />

<p>
<img src="https://i.imgur.com/HtSmyCG.png" height="80%" width="80%" alt="VPN Steps"/>
</p>
<p>
Step 2: In our active Azure subscription, we are going to create a Virtual Machine using Windows 10 (Windows 10 Pro). For this scenario we want to use a different geographic location. You can see in the picture above I am using East Asia.
</p>
<br />

<p>
<img src="https://i.imgur.com/Pdp3p7V.png" height="80%" width="80%" alt="VPN Steps"/>
</p>
<p>
Step 3: Next we are going to remote desktop to our Virtual Machine using the highlighted Public IP address above, you can see it is 104.208.116.174. Again we are going to head over to https://whatismyipaddress.com/ and take note of this in a text file.
</p>
<br />

<p>
<img src="https://i.imgur.com/TIuxbb1.png" height="80%" width="80%" alt="VPN Steps"/>
</p>
<p>
Step 4: On your local computer, open your browser and signup for the free version of ProtonVPN. https://account.protonvpn.com/signup?plan=free&language=en
</p>
<br />

<p>
<img src="https://i.imgur.com/Z0NYRce.png" height="80%" width="80%" alt="VPN Steps"/>
</p>
<p>
Step 5: Back to our virtual machine, we are going to download the ProtonVPN client and chose yet another VPN server in a different country. In this case, I am using the Netherlands as it is a free location provided by ProtonVPN.
</p>
<br />

<p>
<img src="https://i.imgur.com/JRCnhle.png" height="80%" width="80%" alt="VPN Steps"/>
</p>
<p>
Step 6: Open your browser within the Virtual Machine, and again browse to https://whatismyipaddress.com/. We are going to again take note of this in a text file. If you notice, the VPN's IP address is 149.34.244.156 and is located in the UK.
</p>
<br />

<p>
<img src="https://i.imgur.com/o7QVOu6.png" height="80%" width="80%" alt="VPN Steps"/>
</p>
<p>
Step 7: In this step we are going to browse to Netflix and see if anything is different. Most of the time, you will immediately notice the language or URL is different. 
</p>
<br />
