# bulk-upload-to-opensea-with-recaptcha-solution
A cross platform python IDE implementing selenium 4<BR>

If you want to support this project or me, <b>please check out my NFTs</b> <BR>
<b>https://opensea.io/collection/tece</b> and wish give it a little love or grab it.<BR>
Thank you.

I use <b>infotrex</B>'s main code and modify <b>xeonsim</b>'s recaptcha-solution for this.

Please also support.<br>
Main code: infotrex-bulk-upload-to-opensea https://github.com/infotrex/bulk-upload-to-opensea <BR>
Recaptcha-solution: xeonsim-opensea-upload-with-recaptcha-solution https://github.com/xeonsim/opensea-upload-with-recaptcha-solution<br>


  Tutorial video v1.0<BR>
  https://www.youtube.com/watch?v=yEowEDfTSpA<BR>
  ~ or ~<BR>
  Easy step by step<BR>
  https://www.youtube.com/watch?v=j0WguSodGf8<BR>

# Warning
  High Risk of IP to be block by recaptcha Audio. Use at your own discretion!
  Change IP to continue...
  
# Disclaimer
  This free version script are not collect or capture any information while it running.
  Make sure you are understand the all coding and process before running, please read line by line the original code before start running.
  We will not be liable for any losses and/or damages for using of our script. Use at your own risk.
  
# Changelog
  <ul>
     <li><b>Version 1.0 (upload_g.py)</b>
      <ul>
        <li>Standard version</li>
      </ul></li>
    </li>
  </ul>

# Instructions
<ul>
  <li>Download and extract this project in your local device (keep all files and folders that come with the repo in this folder)</li>
  <li>Unzip ffmpeg, ffplay & ffprobe in the same folder</li>
  <li>Download and update Python. My python version is 3.8.10 * https://www.youtube.com/watch?v=9o4gDQvVkLU</li>
   <li>Put all the NFTs images into folder “src/images” (etc 1.png), and NFTs properties metadata .json file put into folder src/json. (etc 1.json)</li>
   <li>Open this project folder with any code editor and click "open powershell " or "Terminal"</li>
   <li>Pip install requirements.txt by running the following command (pip install -r requirements.txt) <BR>
       Please install PIP for Python if “pip is not recognized as an internal or external command</li>
   <li>Run the script, type "python upload_g.py"</li>
   <li>Once running the script, will pop-up the application </li>
   <li>Fill in the variable for your project upload properties, </li>
     <ul>
       <li>Opensea collection link: https://www.opensea.io/collection/yourcollectionsname/<B>assets/create</b></li>
        <li>Start number 1</li>
        <li>End number 9999 or any number</li>
        <li>Default price: 0.005</li>
        <li>Title with end “#” symbol</li>
        <li>Description</li>
        <li>NFT image format "png"</li>
        <li>External link start with http….</li>
     </ul>
   <li>Click and Select the “src” folder.</li>
   <li>Click and “save this form”</li>
     <li>Click “open chrome browser” will popup a new chrome browser, login / sign-in your metamask account. Download metamask extension if don’t have</li>
     <li>Download I'm not robot captcha clicker extension link: https://chrome.google.com/webstore/detail/im-not-robot-captcha-clic/ceipnlhmjohemhfpbjdgeigkababhmjc/related?hl=en-US</li>
     <li>And click “start” to let it run.</li>
  </ul>

 
# Checklist before press "start" button
 <p><ul>
   <li>Disabled opensea night mode</li>
   <li>Opensea collection link must end with "assets/create", <BR>
     look like this : https://www.opensea.io/collection/yourcollectionsname/<B>assets/create</b></li>
  <li>If polygon please tick "polycon blockchain</li>
  <li>Please check "complete listing" for listing and unchecked for create NFT without listing step</li>
  <li>If polygon please tick "polygon blockchain!</li>
  <li>Select your images & json "src" folder</li>
   <li>double check your image / json format: 1.png or 1.json</li>
   </ul>
  </p>

# Alternative (manual recaptcha)
  <p><ul>
  <li>Add extension "Buster: Captcha Solver for Humans" to chrome</li>
   <li>Add API to the solver (optional)</li>
   <li>Run <b>upload18_m.py</b></li>
   <li>Run the recaptcha manually using "Buster: Captcha Solver for Humans"</b></li>
  </ul>
  </p>
  
# ChromeDriver - WebDriver for Chrome	
Download your compatible chromedriver.exe https://chromedriver.chromium.org/downloads
     
# Message for a MacOS user
Currently this script only tested in Windows 10. Not compatible for MacOS

# Advise
Use VPN to to avoid IP blacklist from reCaptcha Audio.
  
# Thanks
Please share and leave your star<BR>
If you found it useful, please purchase my NFTs <BR>
https://opensea.io/collection/tece <BR>
Thank you very much </p>
