<h1>Building a Three-Tier Network VPC from Scratch in AWS</h1>

<h2>Description</h2>
In this lab, I successfully built a three-tier network VPC from scratch in AWS, demonstrating comprehensive network configuration skills. I started by creating a VPC, then proceeded to create public and private subnets. 
Following that, I set up an internet gateway and attached it to the VPC, and created a NAT gateway for secure internet access from private subnets. I created route tables, adding the internet gateway to the public route table and the NAT gateway to the private route table. 
Next, I associated the public subnets with the public route table and the private subnets with the private route table. 
Finally, I created network ACLs and associated the subnets with the appropriate ACLs, ensuring proper network security and traffic management. This lab provided a thorough understanding of VPC architecture, subnet management, and routing in AWS.
<br />


<h2>Concepts and Utilities Used</h2>

- <b>AWS - VPC</b>
- <b>Subnetting</b>
- <b>Route Tables</b>
- <b>Network ACLs</b>

<h2>Environments Used </h2>

- <b>AWS</b>
- <b>VPC</b>

<h2>Environment walk-through:</h2>

<p align="center">
Create VPC: <br/>
<img src="https://imgur.com/dIMIfeW.png" height="80%" width="80%" alt="VPC Steps"/>
<br />
<br />
Create Subnets:  <br/>
<img src="https://imgur.com/K39cI2D.png" height="80%" width="80%" alt="VPC Steps"/>
<br />
<br />
Subnets Created:  <br/>
<img src="https://imgur.com/vjUBbwu.png" height="80%" width="80%" alt="VPC Steps"/>
<br />
<br />
Create Internet Gateway and attach:  <br/>
<img src="https://imgur.com/MMO15Aa.png" height="80%" width="80%" alt="VPC Steps"/>
<br />
<br />
Create NAT Gateway:  <br/>
<img src="https://imgur.com/SnmfF0T.png" height="80%" width="80%" alt="VPC Steps"/>
<br />
<br />
Create Public Route Table:  <br/>
<img src="https://imgur.com/ZADkjrl.png" height="80%" width="80%" alt="VPC Steps"/>
<br />
<br />
Create Private Route Table:  <br/>
<img src="https://imgur.com/aYbEldN.png" height="80%" width="80%" alt="VPC Steps"/>
<br />
<br />
Add internet gateway to the public route:  <br/>
<img src="https://imgur.com/OySfVns.png" height="80%" width="80%" alt="VPC Steps"/>
<br />
<br />
Add NAT gateway to the private route:  <br/>
<img src="https://imgur.com/l0DEaja.png" height="80%" width="80%" alt="VPC Steps"/>
<br />
<br />
Public route table -> subnet associations -> edit subnet associations:  <br/>
<img src="https://imgur.com/OzSMD7t.png" height="80%" width="80%" alt="VPC Steps"/>
<br />
<br />
Create Network ACLs:  <br/>
<img src="https://imgur.com/lV0IsZs.png" height="80%" width="80%" alt="VPC Steps"/>
<br />
<br />
Associate subnets with appropriate ACL:  <br/>
<img src="https://imgur.com/wQZdKQB.png" height="80%" width="80%" alt="VPC Steps"/>
<br />
<br />
Success:  <br/>
<img src="https://imgur.com/hLwWCDC.png" height="80%" width="80%" alt="VPC Steps"/>
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
