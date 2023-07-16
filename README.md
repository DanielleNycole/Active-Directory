# Active-Directory


<h2>Description</h2>

By setting up this enviornment, I was able to get an understanding of an Active Directory. I created a Domain Control VM. After installing the Active Directory, some of my first few steps were setting up a new Admin Organizational Unit and adding Users to that Organizational Unit. I used 1000 randomly generated names and used PowerShell in order to add each as a New User.  <br/>

<p align="center">
Added Users w/PowerShell:  <br/>
<img src="https://lh3.googleusercontent.com/pw/AIL4fc9bzzndNGE_wUGUs24OyBfwzIS8rm50Qb32pMqhj-WUj2jiYNJYLqLQCrSWh1qo_1M2fIs_Hp16K8NF1E5pkrxX8PJ6qziR-NgCMBrP-StbosDcmk3uqP7D7q9GHxXlcAV57NkSD29DJ8QGKdBu0aE=w395-h276-s-no?authuser=0" height="50%" width="50%" alt="Added Users w/ PowerShell"/>
<br />


I created a second VM that was to be used to mimic a corporate setting, this specifically was used to test user permissions. I connected the second VM to connect to the domain from the first VM.
<p align="center">
Connected the Second VM to the Domain Control VM:  <br/>
<img src="https://lh3.googleusercontent.com/pw/AIL4fc8acCQhkehUq7VsLrcIqZU7_qXcVVPhxXhTFwZpTm1Detfqx0y6jUGV5VJMdsOzLu6VYz2Wdsf2IEFMWnctoi_58rHk0bqrqc17FIi_OO3SrD4quhHdljXGP0B0eBOqi9tpF5DEM42GwGThqTj4U1I=w624-h437-s-no?authuser=0" height="80%" width="80%" alt="Connected the Second VM to the Domain Control VM"/>
<br />

From here I tested out user permissions, disabiling accounts, and reset passwords and how those actions translated to the user. 

<h2>Programs Used </h2>

- <b>Oracle VM VirtualBox </b> 
- <b>Windows 10</b>
- <b>Windows Server 2019 </b>

<h2>Problems I ran into and how I solved them</h2>
<b>When setting up the second VM, I kept getting met with a server set up. I deleted and re-set up the VM at least 6 times before realizing I wasn’t getting Windows 10, because I forgot to download the Windows 10 ISO and was using Server 2019. My error was using Server 2019 and was setting up the exact same parameters that I was using for the Domain Control VM, so of course it was going to produce the same result. Once I figured out what the issue was, I set up Windows 10 with no issue at all and was able to use the Client VM to test user permissions.
</b>
