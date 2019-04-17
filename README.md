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
 <html>
 ```
 In our scenario you may use **SimpleHTTPServer Python** module.
 You should do the following steps:
 1. Install Python. If you use Linux or Mac OS X, everything is done in our system by default. If you use Windows, you can download  a setup file from _Python.org_:
 * Go to [python.org](https://www.python.org/)
 * In _Downloads_ section click on the link for Python **3.x.x** 
 * Scroll to the bottom of the page and select Windows x86 executable installer and download it
 * Once you have downloaded an installer, run it
 * In the appeared dialog check the box that says **Add Python 3.x to PATH**
 * Click _Install_. Once the installation has been done, click _Close_
 2. Run the command line/terminal (for Windows/Linux OS).To verify you Python installation, enter the following:
 3. The system will return you the version number of the installed program. If the _python-v_ command is executed successfully, you shall use _cd_ command to head to directory containing your project
 4. Inside of the directory add a text file called 'test.html'
 5. Execute the command to launch server in your directory
 6. By default it starts serving the files from local web-server running on port 8000. You can go to this server by entering URL-address: _localhost:800_ in your browser
 7. Open 'test.html' file in your browser.
