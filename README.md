<h1>Active Directory Users and Computers (ADUC)  AND  File Explorer (Security Group) - Create And Setup A Security Or Distribution Group In Active Directory Users And Computers.  Creating A Security Group Adds A Shared Folder In File Explorer With A Network Path</h1>


<h2 style="font-family: Arial, sans-serif; font-size: 20px; font-weight: bold; margin-top: 24px; margin-bottom: 12px;">
⏹️ Description</h2>

<p style="font-family: Georgia, serif; font-size: 16px; margin-top: 12px; margin-bottom: 12px;">
This project goes over how to create and setup a security or distribution group in Active Directory Users and Computers.  When you create a Security Group, it adds a Shared Folder in File Explorer that has a Network Path. In Active Directory Users and Computers (ADUC), a security group is a container for users, computers, and other groups, used to control access to resources like shared folders, applications, and printers.  You can assign permissions to the group, and those permissions will be inherited by all members of the group.  A distribution group is used for email distribution to streamline communication by enabling mass email sending, but they don't manage security access rights.  In File Explorer, a Shared Folders Network Path (also known as a network share) allows you to access files and folders stored on another computer on the same network. It essentially makes those resources available as if they were local to your computer. 
</b>



<h2 style="font-family: Arial, sans-serif; font-size: 20px; font-weight: bold; margin-top: 24px; margin-bottom: 12px;">
⏹️ Utilities Used</h2>
  
<p style="font-family: Georgia, serif; font-size: 16px; margin-top: 12px; margin-bottom: 12px;">
 
 - <b>Active Directory Users And Computers  AND  File Explorer (Secuirty Group Network Path)</b>



<h2 style="font-family: Arial, sans-serif; font-size: 20px; font-weight: bold; margin-top: 24px; margin-bottom: 12px;"> 
⏹️ Environments Used </h2>

<p style="font-family: Georgia, serif; font-size: 16px; margin-top: 12px; margin-bottom: 12px;">
 
- <b>Windows 10 & Windows Server 2016</b>



<h2 style="font-family: Arial, sans-serif; font-size: 20px; font-weight: bold; margin-top: 24px; margin-bottom: 12px;"> 
<h2>
⏹️ Project Walk-Through:</h2>
 <br/>

<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Use Search Bar at the bottom of Windows Server and Type: Users and Computers.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/T7D5REV.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/BxG3YGN.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Double-Click  (OR)  Click: The domain you want to use.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/a2HZ9oY.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Right-Click: The organizational unit  (OR)  folder you want to put this distribution group (OR) security group in.  Ex: Users folder.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/fSV4VTV.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/HDsc4Ed.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Hover over: New.  Click: Group.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/ImQq4hX.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/UMw8zIA.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Type: Group Name.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/FGCfymr.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/7oUBIL6.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Select: Group scope.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/21Mh5tk.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/KyJyYds.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Select: Group type (Distribution  (OR)  Security).  NOTE: After done setting up a Security Group, you want to go to the folder in File Explorer to get the: Network Path (How To: below).</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/pMOkL1D.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/nklRDYh.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click: OK.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/mUMEoem.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>•	NOTE: After creating a Security Group, you want to go to the folder in File Explorer to get the: Network Path.</b></span>  
<br/><br/>

<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>By default Active Directory Users and Computers puts your created Security Group in this File Explorer Path: C:\Shares</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/jEp6eti.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/JuXiMtM.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>To get the Network Path of A Security Group: Right-Click: The Group folder (by default Microsoft puts them in path: C:\Shares).  Click: Properties.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/wMjGltb.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/TRXFa7r.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click: Sharing tab (top).</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/rOMkVH1.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/XD4ZFq7.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Highlight and copy the path below: Network Path:</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/2ghYxSm.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/j7uikE2.png" height="50%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/mx3H4Zu.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Go to Active Directory Users and Computers. Right-Click: The Group you just copied the Network Path of from File Explorer. Click: Properties.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/sp4Y1Rr.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/BIkAHGQ.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Paste: The Network Path into the Description section (General tab). Type: (share folder) after the Network Path.  This will allow you to easily be able to find and use the Network Path in the future, if you want to share a folder (paste the Network Path in the File Explorer of another user’s computer).  <a href="https://github.com/RashadHagen/File-Explorer-Share-A-Folder-Using-A-File-Explorer-Network-Path" style="font-family: Arial, sans-serif; font-size: 16px; font-weight: bold;">How To Share A Folder Using A File Explorer Network Path</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/06nfb6t.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/5UcDVGA.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click: Apply.  Click: OK.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/P9hA9BM.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />
