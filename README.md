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
Open terminal and navigate to the Downloads directory where nessus is downloaded at.
sudo su to become the root user 
Next is extracting and activating nessus.
<img src="folder/4Unpacking_nessus.PNG">
dpkg -i Nessus....
system ctl status nessusd (to find out if active or inactive)
<img src="folder/4Unpacking_nessus.PNG">
system ctl start nessusd (to activate nessus)
<img src="folder/8active_nessus.PNG">
open firefox in kali and copy the link provided when activating nessus
<img src="folder/9copy_link_address_to_browser.PNG">

