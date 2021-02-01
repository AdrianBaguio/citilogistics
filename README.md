# Insix IT/Web work log

**2-1-2021**
Working on citilogistics app.
 - Working on generating manifest (Pending)
 
Working on Downstream App.
 - Created the database for the app
 - Implemented Login/Logout/ reset password feature.
 - Implemented importing CSV file to the database. 

**1-29-2021**

Internal client - Still seeing weird numbers when converting .csv file into .xslx. Looks like that they have to change the format as text to solve this issue. I also asked Web Dev to add constraints when uploading a CSV file or xslx to check all the reference rows. if there is deemed to be a typo, stop the import and show an error instead. 
Internal client - Printer does not work (Fixed)
Continue working on citilogistics app
- Testing drivers.citilogistics.app pages for the newly import pages.
- Started developing page for the manifest.

**1-29-2021**

Work on the citilogistics app
- Added a warning message when the browser doesn't support geo location.
- Added a feature to show a warning message when the driver isn't at the same location as the package address.
- Saved the addresses where the photo was taken.
Continue working on Andrew’s PC. 
-	Migrated the files(Completed)
-	Installed and tested connections through MSP N-Central(Completed)
-	Installing AV(Incomplete)
-   New computers for internal client warehouse Set up the 4 new laptops update drivers, pdf reader and office installed Old laptop trackpad still not working.
- Laptop does not turn on. They said it was damaged. Open up the laptop, remove the battery and cmos battery, still not working. Tried different battery chargers, it works. Updated the date and time. Battery is healthy. Just need new chargers.
- 2 laptops aren't working. Upgraded the bios and mousepad. Open the other laptop, everything seemed to be well tacked in. Laptop still won't power up.
- Phone issue with Internal Client. Software update keeps on failing. Tried different ethernet port. It successfully updated the phone. Fixed the date and time on the phone as well.

**1-28-2021**

Continue developing the Citilogistics app.
- Upload citi tracking clone database in drvapp.
- Upload citi packages clone database in drvapp.
added feature so that when the driver sets the package as delivered, it uses the photo’s address
- Continue integrating with shiptools.
- Create ethernet cable for Internal client computer at the warehouse (Fixed and tested). 
- Show Internal client how to add zeroes on libre calc 
- Installed TimeqPlus in - Internal client computer (No downloads available online. Have to reach their customer support to get the file) Installed. Saved the installer in the Citilogistics folder. 
- Issue with OpenLibre office. When opening a CSV file, the zeroes in front of integers are removed. I tried some other excel applications but all the apps I downloaded deleted the zeroes in front of integers. Provided a workaround for now. (Upon opening the CSV file, set the column as text). Will continue to find another way to set this as default though. 
- Internal client label printer not working (Fixed)
- Discussed Citilogistics Downstream app with Internal client
- Installed google chrome, pdf reader, to the laptop. Update driver


**1-26-2021**

Continue working on citilogistics app
Work on integration with shiptools. (In progress)
Found a bug that when uploading an image, it's submitting ajax multiple times. (In progress)
Created a tracking table for the driver app to keep track of events (Completed)
Integrating tracking to add a photo, completed, and undelivered packages (In Progress)
Internal client asked how to merge 2 columns in excel as this takes them hours to edit. Show how to do it in Excel but it's really complicated. Instead, install Visual Studio Code, and show how to edit multi lines in just 3 buttons.(Completed)

**1-25-2021**

Install Konica Minolta drivers to Internal client new PC. (Fixed)
Internal client computer has no internet. Determine that the fault was the ethernet cable. The boxes and carts have damaged the ethernet cable. I purchased a crimple and ethernet cable tester. Should arrive in a couple of days. (In Progress)
Continue integrating the Driver app with Shiptools. 

**1-22-2021**

•	Internal client and Internal client weren't able to login to the server via filezilla.(Fixed, wrong connection. they are connecting through FTP instead of sftp.
•	Internal client printer not printing correctly. (Fixed. adjust the printer configuration)
•	Help Internal client with Outlook being slow (Fixed. Problem with the internet)
•	Continue developing the Citilogistics drivers app
o	Talked to Web Dev about integration with shiptools
o	Talk to Internal client and Internal client about the integration with shiptools and some other feature.

**1-21-2021**

Internal client wasn't able to download the application from his old computer. (Fixed - Firewall is blocking the site where the files are hosted, find a way to get them on Internal client's new PC.)  - Done
Internal client was saying that the internet was slow. Confirm that the internet is stable. Seemed like the problem is with the EST Software from Canada Post. Called Canada Post software support. They advise reinstalling the software. (In process of re-installing one of the computers first to see if it will speed it up.) – Done
Continue working on the Citilogistics app / Driver side
•	Calculates how much data are spent to finish a route.
-	Needs to optimize the package-list.php page. (In progress)

**1-20-2021**

- Fixed Internal Client laptop not connecting to the internet. 
- Reset Internal Client's e-mail password 
- Installed office 360 to Internal Client's PC.
- Diagnose issue with the big printer at the back. 
- Continue working on Citilogistics app Added feature to show # of wrong-delivered packages on the route page. 
- Added a page where the admin user can update the wrong delivered package in bulk. 
- Added highlights to column records for Address and Photo Address better readability(list-package page) 
- Add StopNumber in the package-list page. With circle ones. The same as what they can see from the driver app.

**1-19-2021**

- Continue working on Citilogistics app admin/driver side Fixed the loading bug when marking the package as delivered. (Spinning icon won’t toggle off) 
- Fixed up tooltip in the routes page for admin side Use PHP sessions for checking driver's authorization to the package and routes. Now the app is first checking the authorization in the session if it finds it, it uses the session instead of always hitting the database with the request( Which can slow down the site when there are many manifests saved in our database). The pages are affected by these changes. 
    • add-note.php 
    • add-photo.php 
    • add-undeliverable.php 
    • index.php 
    • package-details.php 
    • package-list.php 
    • scan-package.php 
    • submit.php

**1-18-2021**

- Continue working on citilogistics app. 
- Show the photo taken by the driver on the list-packages page. 
- Added tooltip and easy to access explanation to the important fields/column: Routes page, Search Package Page and Upload Routing File page Removed download csv in routes page and upload-routing-file page. 
- Fixed some code in routes page. 
- Enhance the page when viewing routes. 
- Added view photo in search-package and list-packages page. 
- Fixed column names in search-package page. 
- Fixed navbar for the drivers app. 
- Fixed displaying photo addresses. 
- Changed Add Parcel button color to green. 
- Added feature to show packages specifically by driver. 
- Change SESSIONS with GET to maximize length of login time for the drivers. 
- Add openSSL authentication on the driver login side. Setup PC in Internal Client office. Desktop, Monitors, Keyboards and Mouse.

**1-15-2021**

- Added feature to scan packages via cellphone and Bluetooth. 
- Ability to scan unique packages ( Avoid savings parcels that are already in our database ) 
- Created an e-mail for Internal Client. 
- Added feature to see uploaded photos on the admin page. 
- Added icons to the pages (Easier to navigate) Added scan package link to the navigation bar. 
- Added feature to upload route and package specifically by the drivers. 
- Fixed sorting in the list-package page.
-  Added sort by delivered time stamp DESC on the Search Package page

**1-14-2021**

- Update firmware to the scanner. Re program scanner.
- Continue working on Citilogistics app drivers side and admin side. 
    • Add scanned/unscanned package list pages. 
    • Add a feature in the route list page to see how many packages have been released to the drivers. (not done) 
    • Add feature to scan parcels and adds the parcel to the database.

**1-13-2021**

- Factory reset the scanners.(Does not work) 
- Update the firmware of the scanners to the latest one. 
- reconfigure the scanner. 
- Open another ticket for zebra to help resolve the issue. (Still fixing the other scanner) it may be fault with the battery.
- Working on citilogistics app 
- Fixed font sizes for custom buttons. 
- Added route progress animation. 
- Fixed table labels on the users page. 
- Added options so that the driver can take photos with 1 click. 
- Enable options to display xcrud performance. 
- Removed xcrud in the admin page. It has been merged. 
- Created page for mobile bluetooth scanners (Incomplete)

**1-12-2021**

- Created 365 e-mail. Added 365 Business to the account and link the computers.
- Continue working on the citilogistics app. 
- Added photo address to the group in the list-packages page 
- Fixed the admin app that when uploaded to the server, it stopped working. 
- Added design to the selected active navbar. 
- Changed and update the admin xcrud location. 
- Change how the updating photo address location works so that when the photo was taken at the correction location, it adds Address Matched. 
- Fixed up some codes Fixed the laptop not booting correctly.

**1-11-2021**

- Work on the citilogistics app 
- Added a warning message when the browser used doesn't support geo location. 
- Added a feature to show a warning message when the driver isn't at the same location as the package address. 
- Saved the addresses where the photo was taken. Continue working on Internal Client's PC. 
- Migrated the files(Completed) 
- Installed and tested connections through MSP N-Central(Completed) 
- Installing AV(Incomplete)

**1-08-2021**

- Clean up the boxes from work desk. 
- Continue working on the citilogistics app. Implement Tracking of Location when taking pictures (Not Completed) 
- Installed N-Central to Intenral Client's computer. 
- Setup office application to Intenral Client's computer.

**1-07-2021**

- Trying to format Internal Client pc using windows 10 windows reinstall (Doesn't work, keeps getting blue screen of death) Trying to use HP recovery tool instead. Back up files through 365 OneDrive, and sync it to his new work computer. 
- Set up the new computer for Internal Client

**1-06-2021**

- Laptop touchpad does not work.
- Work on the citilogistics admin app. 
- Reformat the computer but its throwing an error

**1-05-2021**

- Working on citilogistics admin app. 
- Added feature to see completed projects in the route list page. 
- Added feature to show # of active routes on the driver list page. 
- Added instruction on how to upload csv file. 
- Added search by package. Back up Internal Client's computer files.

**1-04-2021**

Work on the citilogistics app
- Broken monitor. Its super dark. Confirmed that the monitor vga cable might be broken. However it is integrated with the monitor. Replaced a monitor fixed. Work on the citiogistics admin app. 
- Removed edit from the packages list. 
- Added functionality to show packages by drivers. 
- Fixed the routes list page. 
- Add a feature to import csv file to import route packages.

**12-31-2020**

- Outlook stopped working. Remove old account. Readd the account account. Add office license to the account
- Work on citilogistics app.

**12-30-2020**

- Setup new laptop. 
- Work on the citilogistics admin side. 
- Discussed the database information for the admin app.

**12-24-2020**

- Fix label printer throwing an red error code. 
- Installed wireless ethernet card to the computer outside. 
- Working for the citilogistics app admin side.

**12-23-2020**

- Working on citilogistics admin side.

**12-22-2020**

- Fix Scanners 
- Clean up some codes for the citilogistics app. 
- Develop the management side of the citilogistics app.
- Update the scanner and reconfiguration.

**12-21-2020**

- Outlook throws an error. Unable to open. Run quick fix to Microsoft Office.
- Create a prototype for the app, 
- Finish up Internal Client deep scan that was left from last week. 
- Work on the design of the app. 
- Move javascript templates to app.js for better SEO. 
- Fixed the printer at the back. It was blinking red and not printing. 
- Change the debug feature of the app. Instead of spitting out the query on each page. Now it added the SQL query to the error_log. This way we can easily trace what queries are running on a specific page.

**12-19-2020**

Set up the rack. Install the SAM to the rack.

**12-18-2020**

-Continue working on the app Created documents

**12-17-2020**

- Craddle is not communicating properly with the scanner. Reconfigured.
- Have a discussion with Internal Client to better understand the columns from the Excel file data for the app. 
- Resolve issue with Internal Client's computer still keeps getting pop ups (Removed adware) 
- Internal client's computer still getting pop ups. It looks like that the adware already infected her browser. Reset google chrome settings. (Without removing her passwords) 
- Continue working on citilogistics app. 
- Improved the way we displayed packages (Ryan suggestions)

**12-16-2020**

- Replaced battery and reconfigure the scanner.
- Ran CCleaner. 
- Find which application eats all the space on the laptop (Outlook) 
- Compressed the outlook file -Run powercfg /h off Clean up 21GB of space from 200MB.
- Continue working on Citi App. 
- Added feature to open google maps (MAP IT) 
- Mark As Delivered function is done 
- Undeliverable feature is done.

**12-15-2020**

- Internal Client lost her internet on laptop since yesterday. Turn off airplane mode. (Fixed) 
- Fixed add_undeliverable page. 
- Fixed displaying complete/incomplete packages for package list page and package details page. 
- Fixed Mark Delivered page.

**12-14-2020**

- Drive to the internal client's place to troubleshoot Dead Computer. Plug out all unnecessary usb that are used to plugin to the computer.
- Fix internal client's laptop. Some keys on the keyboard not working (Fixed) 
- Continue working on the citilogistics app. Added content to add_undeliverable

**12-11-2020**

- Fix internal client screen in light blue contrast. Fixed. 
- Internal client's Laptop has broken keyboard (Pending Fix) 
- Citilogistics App add note feature done. 
- Fix up some more codes.

**12-10-2020**

- Working on the packages page. 
- Look at Internal client's computer. Windows update is not working. (Incomplete) 
- Installed Wireless AC1300 PCI-E Adapter to Dona's computer (Completed) - Installed the Access Point

**12-09-2020**

- Added feature to crop the image before it gets uploaded to the server. 
- Added functionality to upload images to the server. 
- Added drivers app database to citilogistics. 
- Added functions to show the routes, and gets the route page completed. 
- Working with displaying the package details INCOMPLETE.

**12-08-2020**

- Working on generating a forgot password link to the requester. 
- Added password validation when creating a new password 
- Added feature to the save password to save DATE and time 
- Fix update user profile. Added checks to confirm their password. 
Also, make sure that the password is greater than 8 characters. 
- Added variable sanitation to prevent SQL injection to the SQL queries

**12-07-2020**

- Finish the update profile page including changing of password frontend/backend 
- Clean up the code 
- Created tables for reset password 
- Added send email feature (To be used for requesting a password) 
- Added loading gifs when sending ajax requests.

**12-04-2020**

- Check the ethernet wire connections. Confirmed that they are connected to the same switch. Purolator said its connecting fine now. 
- also check the phone it wasn't receving calls. Resta
- Check that the server drives are okay. - Implementing login mechanism to the app

**12-03-2020**

- Clean up spare laptop, setup a new system. 
- Setup scanners 
- Setup 2 new laptops 
- Troubleshoot laptop that has a non working touchpad -> Upgraded the drivers, but it seemed like the issue old tech from Lenovo didn't put in the hardware correctly. Advise Internal employee to continue with the issue.

**12-02-2020**

- Set up the rack. Install the SAM to the rack.
- recycled all old hardware boxes. Moved the lights to the other storage. Tidy things up.
- Finished building the template for the app. Tested in iPhone X, Samsung Galaxy S9 and iPad.

