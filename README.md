# Disney-Fastpass-Bot
  
<h3>Setup:</h3>
<ul>
  <li>Step 1: Install python version 3.0+</li>
  <li>Step 2: Download Webdriver: http://chromedriver.chromium.org/downloads</li>
  <li>Step 3: Save source code to folder where webdriver is located</li>
  <li>Step 4: Open credentials and save webdriver location to chromedriver location variable at the bottom</li>
  <li>Step 5: pip install selenium</li>
  <li>Step 6 (Windows 10): make sure python and python 37 is in environmental variables</li>
  <li>Step 7: Go to https://disneyworld.disney.go.com/en_US/profile/family-friends/ . You will see your profile and the other guests you added. Right click on the guest and select Inspect element and find the guest id. Put that guest id in the credentials file</li>
  <li>Step 8: All ready to go! Launch fastpassfinder.py and follow the instructions on the console</li>
</ul>
<h3>Note:</h3><span>While looping through Morning, Afternoon and Evnening time slots the program will wait 60 seconds in between to avoid getting error page by Disney. The error page appears when we send lot of request in a short span of time.</span>
<h3>Disclaimer:</h3><span>This program is for educational purpose only. So use it at your own risk.</span>
