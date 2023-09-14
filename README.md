<h1>File Integrity Monitor with Powershell Script</h1>


 ### [YouTube](https://youtu.be/ISZ_DRmhj8o)


<h2>Description</h2>
This tool enables users to establish a baseline for their files by calculating and storing hash values for each file It then continuously monitors these files, recalculating their hash values. If any unintended alterations occur to the monitored files, the tool can detect these changes, record the details of the alterations, and log these events. 
<br />


<h2>Languages and Utilities Used</h2>

- <b>Windows Powershell</b> 


<h2>Environments Used </h2>

- <b>Windows 11</b> 

<h2>Program walk-through:</h2>

<p align="center">
 This powershell script can be used to monitor the integrity of target files on Windows Machine.
 <br/>
<img src="img/Screenshot 2023-09-10 141242.png" height="80%" width="80%" alt="without_rsa_module"/>
<br />

<br />
It firsts creates a baseline file which contains a file path and its hash value for each of the target files. <br/>
<img src="img/Screenshot 2023-09-10 141315.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />


<br />
When some event, modification, deletion or creation of a new file, happens, it displays alarm on the terminal. Also it outputs those events on the log CSV file  <br/>
<img src="img/Screenshot 2023-09-10 141750.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
