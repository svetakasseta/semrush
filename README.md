# Running Test HTTP Server
---------------------------
## Test page
```
<!DOCTYPE html>
<html>
  <head>
    <title>Example</title>
   </head>
   <body>
    <p>This is an example of a simple HTML page with one paragraph.</p>
   </body>
 </html>
 ```
 In our scenario you may use **SimpleHTTPServer Python** module.
 You should do the following:
 1. Install Python. If you use Linux or Mac OS X, everything is done in our system by default. If you use Windows OS, you can download  a setup file from _Python.org_:
 * Go to [python.org](https://www.python.org/).
 * In **Downloads** section click on the link for **Python 3.xxx**. 
 * Scroll to the bottom of the page, select Windows x86 executable installer and download it.
 * Once you have downloaded an installer, run it.
 * When the dialog box appears, select the **Add Python 3.xxx to PATH** check box.
 * Click **Install**. Once the installation has been done, click **Close**.
 2. Run the command line/terminal (for Windows/Linux OS).To verify you Python installation, enter the following:
 3. The system will return you the version number of the installed program. If the **python-v** command is executed successfully, you shall use the **cd** command to head to directory containing your project.
 4. Inside of the directory add the Test.html text file.
 5. Execute the command to launch server in your directory.
 6. By default it starts serving the files from local web-server running on port 8000. To go to this server, type the _localhost:800_ in the **Address** bar of your browser.
 7. Open Test.html file in your browser.
