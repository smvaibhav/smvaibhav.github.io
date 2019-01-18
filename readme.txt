Deploy Angular Web App on GitHub Pages

Hey in this Research I’m discuss about deployment (to Live on Server or Executable Code ) on GitHub.
In there you need:

GitHub Account
The Project on Angular (what you want to deploy)
Terminal Emulator or Command Prompt

Let Follow the steps in below :

Step 1 : Create GitHub Account or Login in to Your git account.


Step 2 : Create New Repository Name of Repository shoud be <username>.github.io


Step 3 :  Open Your Angular Project to be Deploy code 
    
 	Here the file structure is 
	[+] docs
	[+] e2e
	[+] node_modules
	[+] src
	[.]  xyz ...


Step 4 : Open Your Terminal Emulator in Project dir Press [ Ctrl+Alt+T ]
 
Step 5: Build your Angular type “ng build” 

Step 6 : Type “cd/dist” command.

Step 7 : Type git commands to build first type “git init”.
 
Step 8 : Type “ git add . ”

Step 9 : Type “ git commit -m “Your Message” ”

Step 10 : type “ git remote add origin < git repo url > ”

Step 11 : type “ git push -f origin master ”  it ask git username and password insert your github username and password. and hit Enter. 

All Done Open Your Web Browser  
and Type Your GitHub Url 
“https://<username>.github.io” 
My is 
https://smvaibhav.github.io

---------------------------------------------------------------------------
Vaibhav Yadav
Full Stack Developer
SurmountSoft
vaibhavyadav@surmountsoft.in
www.surmountsoft.com
