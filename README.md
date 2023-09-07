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

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/d11832b6-49a0-49e6-805b-f72a9069c83b"/>
</p>
<p>
Now the process will be done when you see a green check mark 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/e4a242f3-04f1-4f2b-8d95-2caa45bb360a"/>
</p>
<p>
Next go back to the virtual machine home page and click VM-osticket then copy the public IP address
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/54a098be-e769-43ab-a3b0-0d96aa70e7c7"/>
</p>
<p>
Next type Remote Desktop Connection in the search bar of your PC then click to open the app
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/27639ad0-fd28-4511-9e20-26f49b2e6c36"/>
</p>
<p>
Paste the public IP of VM-osticket into the computer section then click connect 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/16f1cecb-7064-45ad-98a2-f9efa9bb89c8"/>
</p>
<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/cbbc0261-d0f2-475f-9cf5-6579f2cca14b"/>
</p>
<p>
now for the user name type labuser and the password type the password you made for the VM
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/c14f377c-ff81-4314-98ce-a3cdbcd715aa"/>
</p>
<p>
Next click yes to connect to the VM
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/b00ae585-36e3-49b2-ba7b-012404b2f796"/>
</p>
<p>
Now you will see the virtual machine log into labuser load
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/9ffead6c-4b08-444a-8223-8c2f5d16661d"/>
</p>
<p>
Now click no for all the following in the image above 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/081fb0bc-7143-403c-9b80-6cf81c7c2491"/>
</p>
<p>
Now once the networks tab shows on the right side of the screen then click yes 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/7626cf37-a8d9-4020-882f-0c15148e0d5f"/>
</p>
<p>
Next right click the windows icon on the bottom left then click run 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/595c1128-d938-4e92-a399-d86804ef641a"/>
</p>
<p>
Now type control type then click ok 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/82a026ed-526c-45f7-8562-9c7406d04d12"/>
</p>
<p>
Now click programs 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/5a0f17a5-dbcd-49f8-aabe-a84207a13387"/>
</p>
<p>
Click programs and features
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/ea423df3-a563-4f17-b17a-8007de3e9c64"/>
</p>
<p>
Now click Internet Information Services
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/d42c75c7-4921-4219-aeda-c299198931b5"/>
</p>
<p>
Now click world wide web services 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/c71c54ff-8fc8-43fc-9c27-d93263712547"/>
</p>
<p>
Next click application development features 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/ecbffb91-0e4c-45fa-992b-c9fbd532e067"/>
</p>
<p>
Next click the box for CGI
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/f114579a-ceb8-4ecb-8b48-656b1d63dcc8"/>
</p>
<p>
Next click Common HTTP Features 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/f577be71-ef65-4554-b40f-0088df36f689"/>
</p>
<p>
Now in Common HTTP Features click the box for everything then click ok 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/f951f632-2872-4816-b339-7586ea44d7e8"/>
</p>
<p>
Then you will see a loading screen process 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/d3c8f6d1-b2f1-40f0-bb90-fcf03e41ec72"/>
</p>
<p>
Now open up microsoft excel and click start without your data
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/175c71d1-f746-4507-adeb-946718c85528"/>
</p>
<p>
Now click continue without this data 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/4e728615-2d5f-4c21-b43b-c4d1cf9bbcb1"/>
</p>
<p>
Next click confirm and continue 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/a5ea5ff4-09a3-4213-b9e3-d5d281f3623b"/>
</p>
<p>
Finally click continue and start browsing 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/9851b44c-23d1-4d32-a61b-6ce5ad7526c1"/>
</p>
<p>
Next once the process is complete click close 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/6a79a3e7-d690-4a16-9b19-cd313e78ed8e"/>
</p>
<p>
Now in order to see if the process worked type 127.0.0.1 in the search bar and you will see the same image above 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/d9d66946-ecfc-41dd-903c-ae3fd8c27811"/>
</p>
<p>
Next open the link and download PHP Manager for IIS ...................
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/4ee1cfa4-ea63-4e84-91a7-040377595f02"/>
</p>
<p>
Then click download 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/1214e292-d905-4194-a1cb-81e54df479c3"/>
</p>
<p>
Then click download anyway
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/557bc0ab-6ed6-4b2c-947c-c445bd5f0b53"/>
</p>
<p>
Now open up file explorer and go to your downloads folder then double click PHP manager 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/f716cf3e-09b0-4626-99df-38eaa1e3af29"/>
</p>
<p>
Next click next 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/282eeedf-144b-4e5a-8f3b-5e10c680f1c5"/>
</p>
<p>
Next click I agree and then next 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/bf7f526b-81bf-4bb4-ad28-c7c21fac535a"/>
</p>
<p>
Finally click close 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/eb2c85c8-e5ea-4604-b93a-1cdd30129c98"/>
</p>
<p>
Next go back to the link and download Rewrite Module ...............
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/c8fd9932-8434-4100-b317-77a6653eca1a"/>
</p>
<p>
Next click the blue download button 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/31a97940-c2ee-4d9f-91f6-bef0ee9125ce"/>
</p>
<p>
Now click download anyway 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/69b4befa-4082-4076-99b6-fa5726f2be5b"/>
</p>
<p>
Go back to file explorer and double click rewrite 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/d8577920-628a-493c-bf85-6c23f01e8a48"/>
</p>
<p>
Click I accept then install 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/092f4b48-9225-4a7f-9674-aa9569bb6d04"/>
</p>
<p>
Now let the process start 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/46a693bc-84bb-4023-a4d4-ffa5ae957512"/>
</p>
<p>
Next click finish
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/645bcdd5-b691-4107-8447-e65d9804c894"/>
</p>
<p>
Next go back to the link and download PHP 7.3.8 .................
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/d0f3c248-df2e-47c1-b0ec-12246cb19d29"/>
</p>
<p>
Now click the download button on the top right 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/c10e3dc0-4e13-43b9-ade7-d569f3b56190"/>
</p>
<p>
Go back to file explorer and you will see the file in the download folder 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/a02af26e-5491-4005-938e-ff743d86e07e"/>
</p>
<p>
Now click on Windows (C) 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/14176c62-b5c9-43c8-8bd4-4e9177aa22ef"/>
</p>
<p>
From here right click anywhere and click new then select folder 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/7889b411-2c14-4dc2-92b9-c6b6228adfb3"/>
</p>
<p>
Now name the folder PHP
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/de31d752-c9a0-48e5-a9c4-f0308f22d181"/>
</p>
<p>
Go back to the download folder and right click php folder then click Extract All
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/1e3de15f-05df-40a2-94ef-90223a2dc1a1"/>
</p>
<p>
Now click browse 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/de6ff1d7-429c-4a19-8678-72315387fd0e"/>
</p>
<p>
Next go to Windows (C) then click the PHP folder we created 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/db4b6ead-5edc-47d6-9b8a-2e223f4a9178"/>
</p>
<p>
Now once you are in the folder click select folder on the bottom right 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/288c3d65-7bff-47c0-8161-1b50fe62a534"/>
</p>
<p>
Now click the extract button
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/912c3522-5954-42fa-a380-933cd7957a99"/>
</p>
<p>
Next you will see all the files load into the PHP folder
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/osticket-prereqs/assets/143027686/cab30e2a-cecc-443a-9625-ec4e55c8c93f"/>
</p>
<p>
Next go to the link and click the link to download VC RedistX86.exe 
</p>
<br />
