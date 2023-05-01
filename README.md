<p align="center">
 <img src="https://i.imgur.com/d6K0zpl.jpg" height="60%" width="60%" alt="Raid Array logo"/>
</p>

<h1>Creating Organizational Units</h1>


<h2>Description</h2>

Are you ready to take control of your domain? Active Directory is here to help! With its centralized management and organization of user accounts, computers, and applications, you'll be able to streamline your resources like never before. Plus, with robust security policies, you can rest easy knowing your domain is protected. Today, we'll show you how to add some new user accounts to your Active Directory domain and place them in the perfect organizational unit for your needs. Let's get started!

<br />

<h2>Environments Used </h2>

 <b>Microsoft Server 2016</b> 

<h2>Program walk-through:</h2>

<p align="center">
For this demonstration we already have our virtual machines and domain controller set up. 
From the left pane of Hyper-V Manager, select CORPSERVER. From the Virtual Machines pane, right-click CorpDC and then select Connect.


<br/>
<img src="https://i.imgur.com/jLl9Z4k.png" height="80%" width="80%" alt="Create OU's"/>
<br />
<br />
From Server Manager's menu bar, select Tools then select Active Directory Users and Computers.
Select Next.
 <br/>
<img src="https://i.imgur.com/xipIW1F.png" height="80%" width="80%" alt="Create OU's"/>
<br />
<br />
From the left pane, right-click CorpNet.xyz and then select New then Organizational Unit.
 <br/>
<img src="https://i.imgur.com/7hUq1U7.png" height="80%" width="80%" alt="Create OU's"/>
<br />
<br />
Enter the name of the OU to be created.

 <br/>
<img src="https://i.imgur.com/iw6j2za.png" height="80%" width="80%" alt="Create OU's"/>
<br />
<br />
Repeat those steps until you've inserted all your OU's. For this demo I've added the following OU's: Accounting,
Admins, Marketing, Research-Dev, Servers Support, Workstations, & Sales.
<br/>
<img src="https://i.imgur.com/ZFwlWZL.png" height="80%" width="80%" alt="Create OU's"/>
<br />
<br />
From the left pane, select CorpNet.xyz and highlight Sales.
From the menu bar, select the Create a new organizational unit in the current container icon.

 <br/>
<img src="https://i.imgur.com/tGmjcOi.png" height="80%" width="80%" alt="Create OU's"/>
<br />
<br />
Enter the name of the OU to be created. For this demo we will be nesting the following OU's within the Sales OU: SalesManagers & TempSales.

 <br/>
<img src="https://i.imgur.com/6PSXVB0.png" height="80%" width="80%" alt="Create OU's"/>
<br />
<br />
And that's it we are finished. This is what our result looks like:
 <br/>
<img src="https://i.imgur.com/on0ltiK.png" height="80%" width="80%" alt="Create OU's"/>
<br />
<br />
Hope you enjoyed my demonstration. <br/>
<img src="https://i.imgur.com/Ow3Mrgj.jpg" height="60%" width="60%" alt="Create OU's"/>
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
