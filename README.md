# For Intro Automation Workshop

DOWNLOAD AND INSTALL
=====================
Java 8 (JDK): http://www.oracle.com/technetwork/java/javase/downloads/index.html

Chrome Browser: https://www.google.com/chrome/

IntelliJ (the Community version): https://www.jetbrains.com/idea/download

This project. Download it by clicking the green Clone or Download button above -> Choose Download. Unzip once downloaded.

Download the version of chromedriver that corresponds to your Chrome web browser version and operating system:
https://sites.google.com/a/chromium.org/chromedriver/downloads

Create a 'resources' directory under automation-workshop -> project -> resources

Unzip chromedriver archive and move the executable file to the 'resources' directory  
(automation-workshop -> project -> resources)


CONFIGURE
============
In Intellij, import downloaded project:<br>
1. File -> New Project from Existing Sources 
2. Browse to downloaded project folder, automation-workshop -> project, and select the pom.xml under there and click Open  
3. Click Next on the Import Project from Maven prompt   
4. Ensure workshop:bookstore:0.0.1-SNAPSHOT is checked   
5. Click Next  
6. Ensure JDK 1.8 is selected  
7. Click Next  
8. Click Finish  

If you get stuck at any point, no worries! We'll make sure everyone is good to go during the workshop.

### Andrea questions

- Importing the pom.xml doesn't bring over all the other project folders. Can I import it all in one shmear?
- Why do I have two .idea folders, is that normal
- Right click index.html > build(? I don't think the option is showing up anymore, so I'm not sure) and now it shows up as a configuration I can run and it will launch on Chrome on my local
- OR - just right click > open in Chrome
- Now, where should I put tests? lol