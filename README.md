<p align="center">
 <img src="https://i.imgur.com/OFMboaL.jpg" height="80%" width="80%" alt="Raid Array logo"/>
</p>

<h1>Adding a user in Active Directory</h1>


<h2>Description</h2>

Are you ready to take control of your domain? Active Directory is here to help! With its centralized management and organization of user accounts, computers, and applications, you'll be able to streamline your resources like never before. Plus, with robust security policies, you can rest easy knowing your domain is protected. Today, we'll show you how to add a new user account to your Active Directory domain and then we will configure their logon hours. Let's get started!

<br />

<h2>Environments Used </h2>

 <b>Windows Server 2019 </b> <p>
 <b>Hyper-V</b></p>

<h2>Program walk-through:</h2>

<p align="center">
From the left pane of Hyper-V Manager, select your Hyper-V host server, mine is "CORPSERVER". From the Virtual Machines pane, right-click your domain controller, mine is "CorpDC" and then select Connect.

<br/>
<img src="https://i.imgur.com/EWVN4H0.png" height="80%" width="80%" alt="Adduser"/>
<br />
<br />
From Server Manager's menu bar, select Tools then select Active Directory Users and Computers.
Select Next.
 <br/>
<img src="https://i.imgur.com/SJRqx6y.png" height="80%" width="80%" alt="Adduser"/>
<br />
<br />
Expand your domain controller folder which in this case is CorpNet.xyz and for this user we will be adding him to Sales>Users OU.
To do this Highlight "users" under Sales, right click > new> user. Follow the arrows I have posted in the picture below.
 <br/>
<img src="https://i.imgur.com/tcT2KPW.png" height="80%" width="80%" alt="Adduser"/>
<br />
<br />
Enter first and Last name. The Logon name is what the user will use to logon to the domain. Click next.

 <br/>
<img src="https://i.imgur.com/EAIC4m4.png" height="80%" width="80%" alt="Adduser"/>
<br />
<br />
Add a password for your user and click next.
<br/>
<img src="https://i.imgur.com/gwKXMTm.png" height="80%" width="80%" alt="Adduser"/>
<br />
<br />
Click finished.

 <br/>
<img src="https://i.imgur.com/xz1ElLI.png" height="80%" width="80%" alt="Adduser"/>
<br />
<br />
Now to configure the user's logon hours. Right click the user and select properties.
 <br/>
<img src="https://i.imgur.com/SXHpnbX.png" height="80%" width="80%" alt="Adduser"/>
<br />
<br />
Here you can adjust the user's logon hours. The blue bars are the hours the user can operate his workstation. Click ok when finished. CLick ok again to close and finish.
 <br/>
<img src="https://i.imgur.com/AdulRWU.png" height="80%" width="80%" alt="Adduser"/>
<br />
<br />
That's it, we're done! Simple, right? <br/>
<img src="https://i.imgur.com/9cuTjD2.png" height="60%" width="60%" alt="Adduser"/>
<br />
<br />
Hope you enjoyed this demonstration. <br/>
<img src="https://i.imgur.com/3gMbo9H.jpg" height="80%" width="80%" alt="Adduser"/>
<br />
<br />



</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
