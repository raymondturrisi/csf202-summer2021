# Assignment 07: Week 07

Before attempting this assignment, please make sure you have completed all of the material in the lessons tab.

Create a copy of this google document [lastname_A07](https://docs.google.com/document/d/1ggbaq0Sq77pBpPB2w630mpDxGeOrNlABuJLzoXPafpI/edit?usp=sharing)(File > Make a Copy) to record all of your assignment answers in.

> :warning: Failure to use answer document properly will result in a 10pt deduction from final score.

The table of contents for this lab is found below.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Part 1: Windows 7, 8, 10 <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Part 2: Microsoft Network, Administrative, and Command Line Tools <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Part 3: Submission <br>

## Part 1: Windows 7, 8, 10

:interrobang: Question 1 - Why do you need an operating system? <br>

:interrobang: Question 2 - What are some standard operating system features? <br>

:interrobang: Question 3 - Which operating system has the most market presence? <br>

:interrobang: Question 4 - List some advantages and disadvantages for using Microsoft Windows.<br>

:interrobang: Question 5 - List some advantages and disadvantages for using macOS.<br>

:interrobang: Question 6 - List some advantages and disadvantages for using Linux.<br>

:interrobang: Question 7 - What is the difference between a 32-bit vs. 64-bit operating system? <br>

:interrobang: Question 8 - Name four common mobile operating systems. <br>

:interrobang: Question 9 - What are the six main versions of Windows 7? <br>

:interrobang: Question 10 - Is Windows 7 still supported by Microsoft today?<br>

:interrobang: Question 11 -  What are some main differences between Windows 7 and Windows 8?<br>

:interrobang: Question 12 -  What are some main differences between Windows 8 and Windows 10?<br>

:interrobang: Question 13 -  Fill out the minimum specifications for each operating system listed below: <br>

#### Windows 7

<img src="images/fig1.png" width=600px>

* label A: `__________`
* label B: `__________`
* label C: `__________`
* label D: `__________`
* label E: `__________`
* label F: `__________`

#### Windows 8 / 8.1

<img src="images/fig2.png" width=600px>

* label A: `__________`
* label B: `__________`
* label C: `__________`
* label D: `__________`
* label E: `__________`
* label F: `__________`

#### Windows 10

<img src="images/fig3.png" width=600px>

* label A: `__________`
* label B: `__________`
* label C: `__________`
* label D: `__________`
* label E: `__________`
* label F: `__________`

:interrobang: Question 14 - What are BitLocker and EFS used for? <br>

:interrobang: Question 15 -  What is the Windows 10 feature Active Directory Domain Services? <br>

:interrobang: Question 16 - What are some some different boot methods that we can use to install a fresh operating system on a machine? <br>

:interrobang: Question 17 -  Define the differnt types if OS installs below:<br>

* Unattended installation
* In-place upgrade
* Clean install
* Image
* Repair installation
* Multiboot
* Recovery partition
* Refresh / restore

:interrobang: Question 18 - What is a disk partition? <br>

:interrobang: Question 19 -  What is the MBR and the different between Primary vs Extended? <br>

:interrobang: Question 20 -  How do Basic disk storage and Dynamic disk storage differ?<br>

:interrobang: Question 21 - Describe what a file system is. <br>

:interrobang: Question 22 - How does the FAT32 file system differ from NTFS? <br>

:interrobang: Question 23 - Which is more secure ~ Quick Format vs. Full Format? Why? <br>

:interrobang: Question 24 - What is Windows CMD? <br>

:interrobang: Question 25 - What are Windows user privileges? What are the different Windows privileges classifications? <br>

## Part 2: Microsoft Network, Administrative, and Command Line Tools

:interrobang: Question 26 - Describe what each of the below Windows terminal commands / tools does: <br>


<table border="0">
 <tr>
    <td><b style="font-size:30px"></b></td>
    <td><b style="font-size:30px"></b></td>
    <td><b style="font-size:30px"></b></td>
    <td><b style="font-size:30px"></b></td>
 </tr>
 <tr>
    <td> help dir <br> help chkdsk <br> [command] /? <br> exit <br> dir <br> cd <br> .. <br> shutdown </td>
    <td>shutdown /s /t nn <br> shutdown /r /t nn <br> shutdown /a<br> dism <br> sfc <br>  sfc /scannow <br> chkdsk /f</td>
    <td>chkdsk /r <br> diskpart <br> tasklist<br> taskkill <br> TASKKILL /IM notepad.exe <br>  TASKKILL /PID 1234 /T <br> gpupdate</td>
    <td>gpresult <br> format c: <br> copy (/v, /y)<br> xcopy /s Documents m:\backups </td>
 </tr>
</table>


:interrobang: Question 27 - Describe what each of the below Windows network terminal commands / tools does: <br>

<table border="0">
 <tr>
    <td><b style="font-size:30px"></b></td>
    <td><b style="font-size:30px"></b></td>

 </tr>
 <tr>
    <td> ipconfig <br> ping <br> tracert<br> netstat <br> netstat -a <br> netstat -b <br> netstat -n <br> nslookup </td>
    <td>net <br> net view \\&ltservername&gt <br> net view /workgroup:&ltworkgroupname&gt <br> net user &ltusername&gt <br> net user &ltusername&gt * /domain <br>  net use h: \\&ltservername&gt\&ltsharename&gt</td>

 </tr>
</table>

:interrobang: Question 28 - Describe what each of the below Windows administrative tools are used for: <br>

<table border="0">
 <tr>
    <td><b style="font-size:30px"></b></td>
    <td><b style="font-size:30px"></b></td>

 </tr>
 <tr>
    <td> Computer Management <br> Device Manager <br> Local users and groups<br> Local Security Policy <br> Performance Monitor <br> Services  </td>
    <td>ODBC Data Sources <br> Print Management <br> Memory diagnostics <br> Event Viewer <br>Task Scheduler <br> Component Services </td>

 </tr>
</table>

:interrobang: Question 29 - What is Windows Defender?  <br>

:interrobang: Question 30 - What are firewall inbound rules? <br>

:interrobang: Question 31 -  What are firewall outbound rules? <br>

:interrobang: Question 32 -  What is a firewall ACL? <br>

:interrobang: Question 33 -  Can you block individual programs and protocols in Windows defender? <br>


## Part 3: Submission

Export your answer document to a .PDF and upload a single `lastname_A07.pdf` answer document containing all of your answers to the lab questions to Brightspace through the attachment uploads option.
