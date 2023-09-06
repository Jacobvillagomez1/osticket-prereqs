# osticket-prereqs
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>
<p align="center">
<img src="https://github.com/Jacobvillagomez1/post-install-config/assets/143027686/e57ef384-fb94-4fe2-a701-ebc1ab6d2b5a"/>
</p>
<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Installation Steps</h2>

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/fa537c14-03b8-4e30-9b39-8a87fa05dabf"/>
</p>
<p>
First go to Microsoft Azure and type Resource Group then click create Resource Group
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/4411c1f1-0cf9-4a78-aadc-3d27c6b34946"/>
</p>
<p>
Now type RG-osticket for the name of the Resource Group. Next for the region click US West US 3 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/eff6d1ee-3474-4ea3-b73a-87c97f082a6a"/>
</p>
<p>
Now go to the review and create tab and click the create button on the bottom left 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/df5e9844-91e1-440b-b3fe-fd29d9b5fa9e"/>
</p>
<p>
Now type Virtual Machines and click create azure virtual machine 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/cb8a5a02-b384-4980-aa1f-4b59802e6d30"/>
</p>
<p>
Now select the resource group we created RG-osticket then the virtual machine name type VM-osticket and the region select the same as the resource group US West US 3 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/74938101-497d-4fd2-98f2-a37d0c3593b9"/>
</p>
<p>
Now for the image select windows 10 pro version. For the size select standard Ec2 and the username type labuser and the password type a unique password remember to copy all this down on a notepad or physical paper
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/b50019f0-ddcf-4a12-919c-542c96d935e0"/>
</p>
<p>
Next click the licensing box and then click review and create 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/e37cdcfd-b0c4-49ec-a404-f857fd297230"/>
</p>
<p>
Now go to the networking tab and make sure virtual network, subnet, and public ip all says (new)
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/aa85a26a-ba88-4299-92f6-5102aac9bdec"/>
</p>
<p>
Next create the virtual machine and you will see the deployment process start 
</p>
<br />
