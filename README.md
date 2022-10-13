<h1> - IDENTITY AND ACCESS MANAGEMENT</h1>

 ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)

<h2>Description</h2>
In this lab I	Used IAM AWS service to create users and grant permissions and attach policies to users




<h2>Environments Used </h2>

- <b>AWS CONSOLE </b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Launch AWS CONSOLE AND LOG IN: <br/>
<img src="https://i.imgur.com/j9g8KMv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
On AWS console home navigate to AWS IAM:  <br/>
<img src="https://i.imgur.com/eDT2vgd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
On IAM dashboard click on user: <br/>
<img src="https://i.imgur.com/f5Xmssl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Click on 'Add Users :  <br/>
<img src="https://i.imgur.com/fJXaETa.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Set User details by inputing the username, access type and custom password for first log in, tick Require password reset as best practise the click on 'Next: Permissions :  <br/>
<img src="https://i.imgur.com/lpIw1hl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Permissions can be set either by adding the user to an existing group or by clicking on attach existing policies directly, I attached policies directly :  <br/>
<img src="https://i.imgur.com/uor077H.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Click on attach policies directly and tick on the policy you want the user to have and click on 'Next:Tags"  <br/>
<img src="https://i.imgur.com/tXBwdzR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 Then configure alerts by selecting 'Add alert threshold'  <br/>
<img src="https://i.imgur.com/lsFC7Gk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 Set the percentage of your threshold, In my case I set it to 80% so When your actual cost is greater than 80.00% ($0.80) of your budgeted amount ($1.00), the alert threshold will be exceeded,Also input an E-mail that would be notified if you have exceeded your threshold.. After that click on 'Next'  <br/>
<img src="https://i.imgur.com/YM7fnf8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 Review all you have inputed if correct scroll down and click on 'Create Budget'  <br/>
<img src="https://i.imgur.com/FvrkLiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Budget successfully created!:  <br/>
<img src="https://i.imgur.com/tYKXCYP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
