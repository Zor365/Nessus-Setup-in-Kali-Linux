# Nessus-Setup-in-Kali-Linux

<h2>Download Nessus</h2>
Search Nessus Tenable Downloads on google and go to the page with that corresponding name
<br>
<img src="folder/1google_download_nessus.PNG">
Since we are downloading for linux/or using linux make sure you choose linux Debian amd64 at the Platform
<br>
<img src="folder/2linux_debian_amd64_Download.PNG">
<br>
Click on download and agree on the License Agreement pop up.
<img src="folder/3agree.PNG">
<h2>Unpacking Nessus</h2>
Open terminal and navigate to the Downloads directory where nessus is downloaded at.
<i>sudo su</i> to become the root user 
Next is extracting and activating nessus.
<img src="folder/4Unpacking_nessus.PNG">
<i>dpkg -i Nessus....</i>
<br>
<i>system ctl status nessusd</i> (to find out if active or inactive)
<img src="folder/4Unpacking_nessus.PNG">
<i>system ctl start nessusd</i> (to activate nessus)
<img src="folder/8active_nessus.PNG">
Open firefox in kali and copy the link provided when activating nessus
<img src="folder/9copy_link_address_to_browser.PNG">
<br>
<img src="folder/10advanced_acceptrisk.PNG">
Click on advanced scroll down and accept to continue into nessus framwork
<img src="folder/11advanced_acceptrisk.PNG">
Click on advanced scroll down and accept to continue into nessus framwork
<br>
Copy the activation code and save it on editor
<img src="folder/12save_activation_key.PNG">
Continue and create an account with username and password
<br>
Let it initialize and setting up all the plugins we need for us to peform a successfull vulnerability analysis

