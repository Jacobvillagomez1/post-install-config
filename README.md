# post-install-config
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>
<p align="center">
<img src="https://github.com/Jacobvillagomez1/post-install-config/assets/143027686/e57ef384-fb94-4fe2-a701-ebc1ab6d2b5a"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://youtu.be/fX-EOyscj6w)
- This link is to log into OsTicket http://localhost/osTicket/scp/login.php

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- OsTicket

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Log into OsTicket with account 
- Add Roles / Departments in OsTicket
- Create new Teams in OsTicket
- Create new Agents in OsTicket
- Give one new agent Supreme Admin Role
- Create new SLA
- Create new Help Topics 

<h2>Configuration Steps</h2>

<p>
<img src="https://github.com/Jacobvillagomez1/post-install-config/assets/143027686/a23b0ccb-ccd9-48a4-a76d-b72fa4fbed7f"/>
</p>
<p>
Going based off https://github.com/Jacobvillagomez1/osticket-prereqs first go to the link to log into OsTicket Browse to your help desk login page: http://localhost/osTicket/scp/login.php 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/post-install-config/assets/143027686/dafce69a-ab55-4634-af6b-9916dea89631"/>
</p>
<p>
Next type the name of your user then the password then click log in 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/post-install-config/assets/143027686/0b3c2beb-797d-4973-8efb-071e953f0491"/>
</p>
<p>
Next click Admin panel in the top right corner 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/post-install-config/assets/143027686/19317425-9df8-4978-972c-2ba032e3687f"/>
</p>
<p>
Now click the Agents tab then click Roles 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/post-install-config/assets/143027686/715b1a78-a1e7-482b-b349-b2816683fbc1"/>
</p>
<p>
Next click add new role 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/post-install-config/assets/143027686/c6aa4ec8-0a06-46ee-af9b-237c3ec435fd"/>
</p>
<p>
Now type Supreme Admin then go to the permissions tab 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/post-install-config/assets/143027686/a94087de-81d0-40ff-8f93-69cdc767a804"/>
</p>
<p>
Next click all the permissions boxs for the role then click add role 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/post-install-config/assets/143027686/161467df-d22c-4884-af6b-161e3f45c2d0"/>
</p>
<p>
Now go to departments in the agents tab and click Support
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/post-install-config/assets/143027686/2993cf3b-deaf-45bc-b07c-ff174d4abf5c"/>
</p>
<p>
From the settings just make sure the type is on public and the name System Administrator then click add role at the bottom 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/post-install-config/assets/143027686/50d3e399-5127-4858-a1ab-f83ae4e4a10e"/>
</p>
<p>
You will then be greeted with a loading screen 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/post-install-config/assets/143027686/6fd2cde5-b14b-46db-ac27-079cd9d3f53d"/>
</p>
<p>
Next go to the department tab and click System Administrators the one we created
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/post-install-config/assets/143027686/96823767-3622-429e-b320-0eae50a4c2a9"/>
</p>
<p>
Now click the Teams tab then click add new team 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/post-install-config/assets/143027686/61a1cb53-e0b1-4903-9e1f-e14316ebc0a7"/>
</p>
<p>
Next type Level 2 Support then go to the members tab 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/post-install-config/assets/143027686/53a02058-8796-4be6-b9ce-10783c500b2f"/>
</p>
<p>
Next in the members tab click josh garcia then click add. Then click create team 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/post-install-config/assets/143027686/6022e6f8-4252-41f6-8d31-6cc5392e3c7f"/>
</p>
<p>
Now click the settings tab then go to the users section 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/post-install-config/assets/143027686/a4bf07d6-962a-4350-8435-f778b0b067dd"/>
</p>
<p>
Next make sure the registration methos is under public and then click save changes 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/post-install-config/assets/143027686/1b89a536-2048-4afd-b098-d1340572ede5"/>
</p>
<p>
Now click the agents tab then click agents 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/post-install-config/assets/143027686/967a9f2e-d11d-4c04-ad08-64abb041c4f2"/>
</p>
<p>
Next click add new agent
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/post-install-config/assets/143027686/dd9515d0-75f2-4dbb-94a3-17a3249c1b61"/>
</p>
<p>
Next for the name click Jane Doe then for the email type janedoe@osticket.com then for the username type jane doe. Finally click set password 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/post-install-config/assets/143027686/95f3b3a5-ded8-4521-b40f-36e189e0735b"/>
</p>
<p>
Now uncheck the box at the top then type your password I will type Password1 for this example 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/post-install-config/assets/143027686/ebb1e4a8-2915-4d9f-818f-7148a517aa3e"/>
</p>
<p>
Now uncheck the bottom box as well then click set 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/post-install-config/assets/143027686/c78c96ef-7a12-41e3-bfaf-d3e31d81e887"/>
</p>
<p>
Next click access then for the primary department click System Administrators then click Supreme Admin then click create at the bottom 
</p>
<br />

<img src="https://github.com/Jacobvillagomez1/post-install-config/assets/143027686/b490a5ea-276a-465a-b25f-93a30b438535"/>
</p>
<p>
Now you will see it was succesffully added 
</p>
<br />

<img src="https://github.com/Jacobvillagomez1/post-install-config/assets/143027686/f3ed53b1-5215-43d6-8677-f9a95928f37f"/>
</p>
<p>
Next go to agents tab then agents again you will see Jane Doe was created. Then click add new agent 
</p>
<br />

<img src="https://github.com/Jacobvillagomez1/post-install-config/assets/143027686/892da9b1-8da6-4fcd-b668-0397d5dd38d2"/>
</p>
<p>
Now go to the account tab then type john doe. For the email type johndoe@osticket.com then for the username type john doe.
</p>
<br />

<img src="https://github.com/Jacobvillagomez1/post-install-config/assets/143027686/86dae7ab-f562-4615-a1d2-3be0ed9b78db"/>
</p>
<p>
Next click the access tab then for the primary department click support then click view only. Click the create tab 
</p>
<br />

<img src="https://github.com/Jacobvillagomez1/post-install-config/assets/143027686/ed6972b6-2b9d-4cf0-b7cc-f659693f86a8"/>
</p>
<p>
Now go to the agents tab and you will see john doe then click add new agent 
</p>
<br />

<img src="https://github.com/Jacobvillagomez1/post-install-config/assets/143027686/2c2a5761-30f7-483b-a704-31d994ee1b52"/>
</p>
<p>
Next type karen karen then for the email address type karenkaren@osticket.com. Then for the username type karenkaren 
</p>
<br />

<img src="https://github.com/Jacobvillagomez1/post-install-config/assets/143027686/2c9610f9-2ca4-452b-9ad6-1826c33d720d"/>
</p>
<p>
Now go to the access tab and for the primary department click support then click view only. Then click create 
</p>
<br />

<img src="https://github.com/Jacobvillagomez1/post-install-config/assets/143027686/5380aa44-b445-4124-aae1-30c08d3ff466"/>
</p>
<p>
Next go back to the agents tab and you will see that karenkaren was created. Click add new agent 
</p>
<br />

<img src="https://github.com/Jacobvillagomez1/post-install-config/assets/143027686/39400b35-6b5a-49d2-a183-60e92354f18a"/>
</p>
<p>
Type ken ken for the name section. Then for the email section type kenken@osticket.com followed by the username under kenken 
</p>
<br />

<img src="https://github.com/Jacobvillagomez1/post-install-config/assets/143027686/b4bfb33d-1f30-4616-a3a2-8907eb9fbcec"/>
</p>
<p>
Go to the access tab and for the primary department click support then click view only now click create 
</p>
<br />

<img src="https://github.com/Jacobvillagomez1/post-install-config/assets/143027686/5cfac814-5ef9-43b1-bf4d-c88b4d4842cd"/>
</p>
<p>
Click the manage tab then click SLA 
</p>
<br />

<img src="https://github.com/Jacobvillagomez1/post-install-config/assets/143027686/fcfb9ca9-d3e3-47ce-b62b-34291686bbc4"/>
</p>
<p>
Next click add new SLA plan 
</p>
<br />

<img src="https://github.com/Jacobvillagomez1/post-install-config/assets/143027686/18b6c4eb-3059-46a3-85a5-009950a5a6d1"/>
</p>
<p>
Now type SEV-A and the grade period type 1. For the schedule click 24/7 then click add plan
</p>
<br />

<img src="https://github.com/Jacobvillagomez1/post-install-config/assets/143027686/078199f8-df6e-4525-bea5-6233cd933371"/>
</p>
<p>
Now type SEV-B and the grade period type 4. For the schedule click 24/7 then click add plan
</p>
<br />

<img src="https://github.com/Jacobvillagomez1/post-install-config/assets/143027686/eb6f6e24-e592-4b0d-a02f-57cac4551604"/>
</p>
<p>
Click SLA nad you will see SEV-A and SEV-B was created. Next click add new SLA Plan
</p>
<br />

<img src="https://github.com/Jacobvillagomez1/post-install-config/assets/143027686/88dac918-dc19-4a48-baad-169002e6a1bd"/>
</p>
<p>
Now type SEV-C and the grade period type 8. For the schedule click Monday to Friday 8am to 5pm with US Holiday then click add plan
</p>
<br />

<img src="https://github.com/Jacobvillagomez1/post-install-config/assets/143027686/7e1d5a68-6c8a-48c7-bb16-820608b036c2"/>
</p>
<p>
Click SLA nad you will see SEV-A, SEV-B, and SEV-C was created. Now click help topics 
</p>
<br />

<img src="https://github.com/Jacobvillagomez1/post-install-config/assets/143027686/d48a32fd-7fe1-49e0-833d-f7dde259c7bc"/>
</p>
<p>
Click add new help topic
</p>
<br />

<img src="https://github.com/Jacobvillagomez1/post-install-config/assets/143027686/17bb25a1-f871-4486-ac16-3400d4a056ca"/>
</p>
<p>
Type Business Critical Outage then click add topic 
</p>
<br />

<img src="https://github.com/Jacobvillagomez1/post-install-config/assets/143027686/d1c7f172-184e-4277-8932-a01f4e65b681"/>
</p>
<p>
Click create new help topic then type Personal Computer Issues then click add topic 
</p>
<br />

<img src="https://github.com/Jacobvillagomez1/post-install-config/assets/143027686/0c38a950-4009-4b35-9020-f551ec5b8392"/>
</p>
<p>
Next click new ticket options and for the priority section lcik normal and the SLA plan click SEV-C then click add topic 
</p>
<br />

<img src="https://github.com/Jacobvillagomez1/post-install-config/assets/143027686/111deac2-7632-419d-b13d-805620af1249"/>
</p>
<p>
Now go back to help topics menu and click Business Ciritical Outage 
</p>
<br />

<img src="https://github.com/Jacobvillagomez1/post-install-config/assets/143027686/8d0109d3-530d-4f0a-bf3d-880860fcf507"/>
</p>
<p>
Next click new ticket options, for the department click Support. The priority section click Emergency and the SLA plan click SEV-A. Finally click save changes 
</p>
<br />

<img src="https://github.com/Jacobvillagomez1/post-install-config/assets/143027686/3466fbaa-10d3-4539-9fa3-74c7f49240af"/>
</p>
<p>
Click new ticket then click next type Equipment Request 
</p>
<br />

<img src="https://github.com/Jacobvillagomez1/post-install-config/assets/143027686/b5e40983-31b0-478f-a169-27edff5a7754"/>
</p>
<p>
Now click new ticket options for department click Support. Now for priority click low then for SLA plan click SEV-C. Finally click add topic 
</p>
<br />

<img src="https://github.com/Jacobvillagomez1/post-install-config/assets/143027686/74a649cf-0203-4502-8559-587c79d98ad0"/>
</p>
<p>
Go back to help topics, you will see Equipment request was created then click add new help topics
</p>
<br />

<img src="https://github.com/Jacobvillagomez1/post-install-config/assets/143027686/cb134a86-4f34-4641-9338-ebd1372d0077"/>
</p>
<p>
Type Password Reset 
</p>
<br />

<img src="https://github.com/Jacobvillagomez1/post-install-config/assets/143027686/e67187fa-62fa-49e2-bcab-dac168ef718a"/>
</p>
<p>
Next click new ticket options. For department click support next for priority click normal. For SLA plan click SEV-C then finally click add topic. Next click the link to continue the Ticket Lifecycle Examples https://github.com/Jacobvillagomez1/ticket-lifecycle
</p>
<br />
