# Introduction
Litsing of common IT problems and the solutions for them.
The focus of this list will be over low level IT problems.
<br></br>
<br>In this listing I will be going over common problems that an IT professional might encounter and discussing various ways we might go about solving them. This is not a comprehensive list and there will be more possible solutions to the problem than I am providing. The purpose behind the creation of this repository is for myself and others who are going into IT to use as a checklist or Knowledge base for possible encounters in the future of their careers.</br>

## Third Party Software
<br>Always make sure that any third party software that you install is specifically allowed by the organization and the user has a subscription to use it.</br>

<b>PDF files</b>
<br>The reason PDF files might not be working are:</br>
* Adobe PDF reader not installed
* Wrong configuration

<br>Using File association we can see what is associated on the .pdf extension as a default. We can then make sure it is on the proper default of Adobe PDF reader.</br>

## Common Problems in IT
<b>Password Problems</b>
<br>There are many reasons in IT in which we will be required to reset a user's password. Sometimes this will be straightforward and others we will need to come to this solution on our own after listening to the needs of the user we are helping.</br>
<br>Some of the reasons we might need to reset a password are:</br>
<br>1. Forgotten password </br>
<br>2. Caps lock is on </br>
<br>Before we change the password we should make sure the user is not enabling anything that would affect their ability to enter their password correctly such as caps lock or mistyping keys.</br>
<br>3. Expired password </br>
<br>4. Suspended due to inactivity - The user might have been on leave or vacation and the account was disabled for security reasons.</br>
<br>As an IT professional we should be able to enable their account for them as they resume operations within the company.</br>
<br>5. Onboarding and Offboarding</br>
<br>It is inevitable that new users will join and leave the company. We must make sure that the users that have left will have their account info changed and disabled. For new users we must set up their new usernames, passwords, and other information as needed.</br>
<br>6. Security Reasons</br>
<br>There are a lot of reasons we would change a password to have better security hygiene. This includes Breaching of an account, unauthorized/suspicious activity on an account, Social engineering incidents, and lastly for compliance with password length and complexity. </br>
<br>Although there are many problems within the category of password resets, The end solution is the same. In some instances we might be able to send the user a password reset link. We can also utilize software tools like active directory to change passwords, usernames, and enable/disable accounts within our organization. </br>
<br></br>
<b>Slow Computer</b>
<br>A computer might be slow because of many reasons</br>
<br>What we can do to assist users is the following:</br>
* Using tools like TaskManager to check CPU and Ram: We will be able to see which applications are draining the computer's resources.
* Remove temporary files, Empty recycle bin, Remove any large unused programs on the device.
* Check for Viruses / Malware on the machine

<br></br>
<b>Internet Outage</b>
<br>We must make sure exactly the problem that the user is facing. We can verify the outage through the use of the following:</br>
* Pinging the affected host
* Checking network connectivity on the device
* Testing other devices on the same network
* Checking ISP outages
* Restarting the modem/router
* Lastly if the problem is too complex we can always escalate to a higher level


<br></br>
<b>Connected Device Problems</b>
<br>There are many devices that people will use and need help with. These can be keyboards, Mouse, Headphones, etc. </br>
* Check batteries of devices
* Make sure all connections are correct
* Make sure the attachment is configured and selected correctly
* Check drivers are installed and updated - Sometimes a new update will be the cause of the faulty performance and in that instance we will rollback the driver update
  
<br>The solution to this problem can vary a little bit through the difference of wireless vs wired. Overall the process will still be the same and we can use a checklist to help us go through the possible problems we face.</br>

<br></br>
<b>Printer Issues</b>
<br>Another most common issue is issues with the printer:</br>
* Check toner and paper
  
<br>If we are able to physically access the printer ourselves there is a lot more we can do as IT professionals. Checking toner and paper as well as the overall quality and connections on the printer will help us in our diagnostic of the problem we are facing.</br>
* Network connections
  
<br>Is the printer discoverable on the network, Is the hostname correct, Is it properly connected?</br>
* Up to date printer drivers (On the Host and the printer)
* Printer queue

<br>Stuck print queues can also be known to cause problems and make the printer stop responding. Clearing this up might allow the printer to work as the user needs.</br>
* Restarting the device and Testing on another device
  
<br>Sometimes there are limits to what we can do in IT, but a good troubleshooting technique is to test on different devices to verify this a localized issue. Restarting a device is always a viable path to try and resolve an issue that we are encountering on a device.</br>


## More Complex IT Problems
<b>Deleted Files / Data Loss</b>
<br>There will be times when users accidently delete data that they should not have or data that they were working on and could not save. Some of the techniques we can try to get the user their work back are: </br>
* Checking Recycle bin

<br>Recycle bin should always be the first place we look for files that have been believed to be deleted.</br>
* Searching

<br>Searching by file type and directory path might allow us to find the data they have lost if it has not been deleted but the user thinks they have</br>
* Escalate issue

<br>If the data is stored on a server then we could reinstate the user. Sadly there is not much to do when data has been deleted without being saved and the process to help them might be above what we can do which means we need to escalate the ticket to more advanced help.</br>

<br></br>
<b>Blue Screen Of Death</b>
<br>This is one of the scariest things we can face when trying to assist users with their problems. </br>
* Note the error message displayed on screen
* Ask the user about recent changes they have made
* Hardware issues

<br>Physically inspecting the device can let us see if there are any loose connections, faulty hardware, adequate ventilation, and visible damage.</br>
* Boot into Safe Mode

<br>In safe mode we are able to see if the cause might be related to software or driver issues on the affected device.</br>
* Malware and Virus Scan
* Windows up to date
* Escalation

<br>The BSOD is a very complex issue as many or compounding reasons could be the cause for the issue that is occuring. Sometimes we need to rely on colleagues that are on site or more equipped to handle the issues than we are.</br>
