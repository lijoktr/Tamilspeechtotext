**Speech to text in Tamil**

Welcome to Speech to text in Tamil project, this is a web application that allows users to convert Tamil speech into Tamil text using Google API. Our web application is designed solely for our Tamil speaking audience. Hence the language it will appear on will also be Tamil so our target users can use it to their full satisfaction. This application also has the capability to convert mp3 file into a text, so we are not limited only to the speech from the microphone. 

To download and launch our Speech to text in Tamil project, please follow the instructions below:

**Pre-requisites-**

•	**Download VS code:**__

Go to: https://code.visualstudio.com/download
Click Windows download button
After the file is downloaded, install it with default settings.

•	**Download Git bash:**__

Go to: https://git-scm.com/downloads
Click Windows in download section on top of the page and a installer will be downloaded.
Open the file and install with the default settings by keep clicking next.

•	**Download Node js:**__
Go to: https://nodejs.org/en/download/
Click Windows installer and an installer will be downloaded.
Open the file and install with the default settings by keep clicking next.

•	**Download Google cloud SDK:**__

Go to: https://cloud.google.com/sdk/docs/install

In the Installer instruction section, select windows tab and then click Cloud SDK Installer in first paragraph.
Open the file and install with the default settings by keep clicking next.
Once the installation is finished, click finish and a terminal will appear asking you to sign in to your google account. Type “y” to proceed and a browser will open where you can give in your gmail account associated with the Google API. Once signing in is complete return back to terminal and type “1” to choose the nth-clone key option and hit enter.



•	**Download Speech to text – Tamil source files from gitlab:**__

Go to https://gitlab.uwe.ac.uk/mi4-khan/speechtotext-tamil and download the project into your computer.

Adding Google cloud API key:
1.	Open windows PowerShell by searching in the search box in task bar.
2.	Run the following command:
$env:GOOGLE_APPLICATION_CREDENTIALS="KEY_PATH"

Note: Please replace KEY_PATH with the appropriate key path name.
Example: $env:GOOGLE_APPLICATION_CREDENTIALS="C:\Users\Moinlil\Desktop\Speech to text- Tamil\Speech to text – Tamil\my-key.json"
Note: Key can be found inside the folder Speech to text – Tamil in the name of “my-key.json”. 


**Running the web application:**
1.	Extract the Speech to text - Tamil.zip file, found in the same directory as this runbook.
2.	Once extracting is complete you will have a folder Speech to text – Tamil, open the folder and open git bash by right clicking anywhere inside the folder and then choose Git Bash here from the options.
3.	Git command prompt will appear, run command 

GOOGLE_APPLICATION_CREDENTIALS="<path-to-directory>\my-key.json" node server.js

Note: Please replace <path-to-directory> with the appropriate path name. Example: GOOGLE_APPLICATION_CREDENTIALS="/home/user/Downloads/my-key.json" node server.js

4.	After running the command if everything is successful, you should see a message in the terminal saying: Your api is running.

5.	Now its time to launch the application. We will open the application in VS code, by running the command < code . > in Git Bash terminal. Please make sure the git bash terminal is open in the  Speech to text – Tamil folder as shown in step 2. 
6.	Once VS code is open, from the left side panel expand the folder InTamil and open tamilindex.html  file. Then right click anywhere in that file and click open live server.
7.	A browser will open, and you will be able to see the homepage of our lovely Speech to text in Tamil web application.



