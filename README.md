# Insix IT/Web work log
**3-31-2021**
- Continue working on updating the database while outputting whats being search from the Camera.
- Issue when selecting parcels from the database. 1-5 queries throws an error.
- Trying to use more optimize SQL Query for checking weather the parcel id is in the database.
- Setup a new e-mail account for the newly hired Employee
- Setup the laptop. Install 365 Office.
- Clean up the 2 phone landlines. Test they are working. Just need the phone splitter for FB to add more landlines.
- Added newly hired email to email group.
- Help Matthew with the issue with internet connection. Sometimes he could not see myfbx.net
- Issue a traceroute, looks like its pinging the right IP Address.
- Tried changing the DNS server to google.
- Fix folder permission for Internal Client.
- Remove the weird user that has long numbers on it.
- Trying to make so that only some internal clients can only access the Onyx Folder. (Fixed)
- Internal Client wanted to move Onyx folder to Admin Shared.(Fixed)


**3-24-2021**
- Added a feature to search by a specific client in the search-package page. (Fixed)
- Added a feature to search between dates in the search-package page (Fixed) 
- Internal Client inserted a wrong data to the driver app and shiptools. (Manually have to create SQL Query to fix the issue) (Fixed)

**3-23-2021**
- Internal Client computer Canada Post app not working (Fixed)
- Investigating the issue with manually releasing the packages. 
- Internal Client said it still not fixed. Confirmed working. (Fixed) 
- Internal Client asks for new feature. On the search page, add the driver name, and when the route was created. (Fixed) 
- Internal Client Add option to search between dates and have a calendar (In Progress)

**3-22-2021**
- Bug in the maps.php, Unable to the map in view map, Issue with apostrophies. (Fixed)
- Bugs on routes.php. driver release on the admin side not working. Issue with xCrud, needs to merge update_driver_release function and update_cid_after_edit function.(Fixed)
- Updated functions in xcrud/functions.php.
- Bugs on admin release (Fixed)
- Internal Client email got corrupted. Unable to open her e-mail.
- Make a back up of the corrupted file.
- Run Outlook PST File Repair Tool (Does not fix it)
- Do a workaround to fix the issue(Fixed)
- Re added e-mail for ezclear.
- Internal Client was having issues with outlook. After further investigation it was an issue that she was sending file exceeds the limit. Over 35 MB.
- Internal Client was having issues with the rules. Explain to her that it was a rules issue. Guide her to fix it.
- Internal Client was having issue with google chrome. Suddenly does not open in the morning. Fixed

**3-19-2021**
- Internal Client laptop keyboard not working. Let her used a keyboard for now.
(Proceed with system restore) - Check if this will fix the issue.
Still not working trying in safe mode.
Provided her with a keyboard (Fixed)
- Marking this as the keyboard hardware issue.
- Driver called in stuck in loading. Issue a call back (Fixed)
- Internal Client moved her computer to the corner and have access to wifi only. Unable to access her e-mail and no internet connection and not able to print (Fixed)
- FIX Integration with shiptools. Added features to support more clients like RRD and Reliable. (Fixed) 
- FIX issue when deleting temporary routes and packages. (Fixed)

**3-18-2021**
Fix layout for the pages. (Fixed) 
- Reduce icon (Fixed) 
- Problems with importing incorrect data that doesn't match to shiptools and driverapp. (Fixed) 
- Remove pieces in the package list page. (Fixed)
- Issue with the driverapp and shiptools. Reference and consignment ID mismatch Internal Client.(Fixed) 
- Created a query to fix this. (Fixed) - Issue with updating shiptools RRD and Reliable. 
- Working with Laurie on how to fix this issue (In Progress)

**3-17-2021**
- Internal Client ask for assistance to print longer paper. Showed how (Fixed)
- Internal Client ask for assistance about weird numbers in excel. Advised to use Librecalc (Fixed)
- Unable to generate an address in the generate-label page. (Fixed)
- After investigation, it seemed like they are typing the same Reference # but not case sensitive (Lowercase instead of uppercase). Applied a patch so that when a reference # is not found, it then tries to get a non-case-sensitive search.

**3-16-2021**
Added a feature in the list-packages page to view exactly all the history from the package. Internal Client
Fixed bugs when Internal Client mark packages as released and suddenly change the driver (Fixed)
Update Internal Client office to 365. (Fixed)
The issue with the app. The driver is unable to start after changing drivers in the admin menu (Fixed)

**3-15-2021**
- Internal Client called at 7:30 in the morning calling a driver weren't able to deliver a package. (Fixed)
- Code issue. Went early to work this morning since I don't have access to the drvapp code at home. Call back the drivers to confirm that the issue are fixed. Internal Client (Fixed)
- Continue working on fixing Internal Client corrupted outlook file (Run the outlook scan tool multiple times) able to recover her personal inbox and rules (Fixed)
- Internal Client outlook freezing. Force exit. Run 365 Office Repair Tool (Still Under Investigation)

**3-12-2021**
- Internal Staff called at 7:30 in the morning calling a driver weren't able to deliver a package. (Fixed)
- Code issue. Went early to work this morning since I don't have access to the drvapp code at home. Call back the drivers to confirm that the issue are fixed. (Fixed)
- Continue working on fixing Internal Staff corrupted outlook file.
- Internal Staff outlook freezing. Force exit. Run 365 Office Repair Tool (Still Under Investigation)
- Internal Staff email not working (Run the outlook scan tool multiple times) able to recover her personal inbox and rules (Fixed)
- Internal Staff teams is not working. Issue with privilege. Removed Plan 1 license from the exchange server (Fixed)
- Internal Staff computer error of death when printing. Issue with newly installed windows update. Run a system restore. (Fixed)
- Completely migrating files of Internal Staff over to her new laptop. (Fixed)
- Setup monitors keyboard and mice for Internal Staff laptop(Completed) 
- Internal Staff printer is not working. Known issue from Microsoft updates (Fixed)
- Started working on integrating c# with shiptools to get parcel status.

**3-11-2021**
- Internal Staff asks if we can continue with the server update. Waiting for confirmation as not everyone in the office yet.
- Confirmed with the girls and Internal Staff to run the server update at around 4 PM.
- Update the .net framework on the server. (Fixed)
- Run windows update as well (Fixed)
- There was no internet at the operations in a warehouse. Restarted the switch(Fixed)
- Finished running the server update. Make sure that the share drives are accessible. (Confirmed and Fixed)

**3-10-2021**
- Internet Staff asks if we can continue with the server update. 
- Waiting for confirmation as not everyone in the office yet. 
- Confirmed with the internal staff to run server update at around 4 PM. 
- Update the .net framework on the server. (Fixed) 
- Run windows update as well (Fixed) 
- There was no internet at the operations in warehouse. Restarted the switch(Fixed) 
- Finished running the server update. Make sure that the share drives are accessible. (Confirmed and Fixed)
- Continue working with the telnet app. 
- When exiting the app, the app stays on the background (Bug) (Fixed) 
- Created another form to separate app connected and not connected. 
- Fixed it so that the recent scanned parcels will be on the top. 
- Saved the time when the parcel was scanned. 
- Searching for which database to use for this project. MySQL, SQL Lite, NoSQL or MSSQL.

**3-9-2021**
- Go with Internal Staff to show a basic fundamental on how e-tower works. She provided me with the credential using Internal Staff e-mail.
- Read e-tower documentation and manual to get a better understanding of the system 
- Sit with Other DEV on how to change the name of the companies in shiptools. 
  - Requires changing of the name in the code, and name in FTP access too. 
- Issue with the driver app. One of the drivers complains that he wasn't able to mark the package as delivered. The issue with the code javascript / fixed.
- Download Cognex Dataman SDK. (Fixed)
- Created the first project on c# to connect via telnet (Fixed)
- Test Cognex Scanners, it's shows the actual barcodes correctly. (Fixed)
- Need to change the code so that it displays the new one from the top. (In Progress)
- Maybe add a scroll bar to the telnet response? (In Progress)

**3-6-2021**
- Unable to scan parcels with the new scanners.
- Test scanning parcels with the old scanners still does not work.
- After investigating the labels, it seemed like that the faulty was the label itself. A portion of the label is blanked, thus scanners weren't able to read them correctly.
- Fixed skip addresses for google geo API. mapObj for Cres, Dr., Blvd, Cres., Cr, Crt.
- Fixed submitting photo. A little slow. Check the queries being done when submitting a photo. Gets rid of redundancy on using the update package function.

**3-5-2021**
- Internal Staff asks that citi back up aren't working because Altaro VM Back-Up is 2 updates behind
  - Update may require the server to reboot. 
  - Asked everyone first for permission when this can be done.
- Driver called, Internal Staff says that the driver app is not working on his google pixel phone. Asked to do a hard reset of the phone. Assist the driver on how to do it on his phone. Fixed
- Another driver who has iPhone called in, after taking a picture, it doesn't work. (Previously able to deliver 4 routes with no problem. Suspected to have change settings on his phone). 
- Ask to install Chrome, Opera still does not work. After troubleshooting the issue was that his location was off. Fixed.
- Taking over task #3 from a web dev (Found out that they are also having issues with the reference value kept on changing) Not anyone's fault but Excel, advise to use OpenOffice to deal with this specific client.
- Discussed task #5, looking for a temporary fixed since FB isn't uploading their manifest to shiptools on time. Advised not to create an app for this.
Working on the driver app.
- Fixed postal code on generate-label page
- Added a feature to automatically archive routes that are a month old. (Cronjobs)
- Force devices to enable high accuracy when using gps on the phone.

**3-4-2021**
- Installed monitor for internal staff
- Monitor is too dark internal staff (Reset monitor settings) 
- Set the configuration for PDF to print barcodes correctly 
- Staff called saying the printer not working when printing 75 labels. Troubleshoot, found out that someone uplugged the USB. 
Working on citilogistics.
- Add barcode generator in driverapp cause some packages have missing barcodes and drivers are having a hard time putting these in manually. 
- Integrated with shiptools so that when the barcode is generated, it automatically prints out the Name, and Package destination as well.
- Added a feature so that it doesn't generate the same label even though the reference is inputted twice.
- Troubleshooting image location ( In Progress )
- Check the accountant's computer.
- I don't see any sign of slowing down. She said the computer slows down once in a while.
- Gather information and send it to the main office to get a better understand of what upgrade she needs.

**3-3-2021**
- Discussed the issue with marking multiple packages before starting with Internal Client.
- Issue with shiptools. Updating with incorrect data to the pin column.
- Added a link to the driver's account on the Routes page.
- Fixed integration with citi_packages. Updating PIN with "1-Delivered"
- Updated all other deliveries PIN with "1-Delivered"
- One big tablet android keyboard is not working when the Bluetooth is connected. Advise to scan all the packages first then when done, disable the scanner and type in the barcode manually.
- Bluetooth scanners are not showed on the list of Bluetooth devices of the driver. Hard reset (Fixed)

**3-2-2021**
Continue working on citilogistics app.
- Fixed Shiptools POD database table. before it was using ./LINK(Which was used for the driver app). Change all these occurrences with the actual link (LINK)
- Added a feature to add notes to the driver's account.
- Working on another feature to delivered multiple package at once. (Pending not too sure if this is possible though, as there’s a lot of conflict with updating the shiptools)
- Internal Staff computer is slow. Run indexing on the computer and will leave it overnight.
- Ask to install another screen. will do it tomorrow.


**3-1-2021**
- Continue working on citilogistics app.
- Fixed Shiptools POD database table. before it was using "Photo Link" (Which was used for the driver app). Change all these occurrences with the actual link (Photo Link)
- Added a feature to add notes to the driver's account. (Completed)
- Working on another feature to deliver multiple package at once. (Pending not too sure if this is possible though, as I'm seeing conflict with updating the shiptools)
- Internal client computer is slow. Run indexing on the computer and will leave it overnight. (Pending)
- Ask to install another screen. will do it tomorrow. (Pending)

**2-26-2021**
- FIXED image rotation after optimizing it.
- Add Shiptools integration for new POD uploaded by the driver.
- Added undeliverable after undeliverable reason.
- Changed "completed" to "delivered" when displaying delivered packages on the list-packages page
- Changed "completed" to "delivered" when displaying delivered packages on the search-package page
- Move Google Geo API to its page (Hide API key from bad people. It was used to be vulnerable. Now its completely hidden)
- Fix search package to add an undeliverable message before undeliverable reasons.
- Change integration with Shiptools. Instead of using ./, it's now using the actual driver app URL.

**2-25-2021**
- Received a laptop from FB. The user was not able to log in. Requires admin password.
- Deleted the user and create a new user. The computer is running too slow. Reformatting the PC.
- Printer issue, the technician ask to update the driver from the server. Was just informed that FB has no server.
- Set up the new laptop for the driver app.
- Check and set up new mobile phone scanners.
- Continue working with ship tools.
- Discussed with Laurie to check integration with ship tools. The app is not updating both the Pin and Pin Date.
- Export driver app tracking history and update the Pin Date and PIN accordingly. 
- Apply the patch to the driver app to update the pin and pin date.
- Fix issue when uploading photo sideways. Make it to upload upfront.
- Fixed issue displaying photos, not upside down.

**2-24-2021**
- Continue working on citilogistics app.
- Added a Narrow Search feature to search by the number of minutes, the number of hours, and the number of months or show all in the search package page.
- Add feature to show actual deliveries on the map using OpenStreetMap
- Add a link to show the map on the routes page.
- Fixed search-package page to automatically display the package information when searching for a specific package.
- Add maps to the navigation.
- Add another fix for Google Maps. crescent, court, boulevard and west.

**2-23-2021**
- Continue working on citilogistics app.
- Trying to resolve issue with iphone not being able to type manually when the Bluetooth scanner is connected. ( Found a solution to scan a barcode when the keyboard does not show up. Print multiple copies to be displayed in the warehouse. Fixed )
- Add feature to archive routes.  (Fixed)
- Fix driver side so that it won't show archive routes. (Fixed)
- When using the app on moto g8 phone it doesn't provide accurate user address. (Still under investigation)
- Add search by days/months/years in the report page (In Progress)
- Internal Client said that the Toledo Weight Scale is not working. Try different USB Port. USB port detected, reconfigure it with the UPS software.
- Add Internal Client to email group
- Move inbox messages to archieve for admin e-mail.


**2-22-2021**
- Internal Client's computer is freezing. Tested her computer and it doesn't show any sign of slowing down. Ask her to call me when it freezes again.
- Internal Client's asks to fix the computer at the warehouse. CanadaPost app doesn't sync into one of the computers. Change the settings to sync into the CanadaPost server instead of local. (Fixed)
- Internal Client was not able to connect to nology server using FTP Client. Incorrect connections settings (Fixed)
- Continue working on citilogistics app.
- Undeliverable status updating shiptools is working.
- Continue working on the maps page.
- Added a feature to view the route name on the Search Package page.
- Clean up the search-package page. Limits the view to Route Name, Parcel ID, Status and Delivery Date and puts other essential information to view more.

**2-19-2021**
- Working on citilogistics app.
- Automatic fast navigation issue with IOS. IOS just hangs up looks like compatibility issue with google and apple. (Fixed set it to use the old way on IOS and fast way for android)
- Changed updating images. Since these photos are very important to us, I'll be just archiving the old ones with different names.
- Added a fix option on alignment on print-manifest.
- Add Photo Feature on add undeliverable package.
- Working on maps.php page.
- Test another 150 packages to Android Phones.

**2-18-2021**
- Make the spinner bigger on package-details.
- Disabled sending notification when the driver maybe be in the wrong location 
- Fixed photo always front (On IOS). 
- Fixed address match on google. (Added Crescent on the check)
- Update shiptools on bulk release packages
- Added longitude and latitude in the package-details page. 
- Added search by package id in the search-package page. 
- Update shiptools when the admin set the parcels as scanned (Manual Scanned) 

**2-17-2021**
- Check if shiptools get updated when the driver scanned packages in the warehouse. (Working as intended)
- Check if shiptools gets updated when the driver had delivered the package (Working as intended)
- Fix Bug when resubmitting packages that have the image uploaded already, Wasn't able to complete delivery (Fixed) 
- Working on showing drivers deliveries on google map. (In progress)

**2-16-2021**
Continue working on the citilogistics app.
- Capture the longitude and latitude to be used later on google map drops.
- Fix Avenues and Circle in addresses.
- Change the undeliverable page to capture longitude and latitude.
- Change add photo page to capture longitude and latitude.
- Change package list page on marking as delivered to capture longitude and latitude.
- Update the parcel's status as delivered in shiptools.
- Add missing tracking information in shiptools
- Driverapp is now connected with shiptools.
- Will conduct another test.

**2-12-2021**
Conducted another test with Internal Client. Asked Internal Client to test the app.
- Problem with the scanner. When plugged in on the phone, the keyboard went missing (Unable to type the reference number manually on IPHONE ONLY)
- Temporarily solution, disconnect the scanner.
- Changed Route List page, Show the newest one on the top.
- Routes that haven't been scanned yet will be redirected to Scan Package.
- Routes that have been scanned will be redirected to Start Route.
- Scan Package Changes
- Ability for the drivers to scan package by Route Name or scan package for all their routes.
- [Needs fixed]
- Address match, but names are slightly different from the package to google addresses.
- On Safari phone always asks for permission every time the driver takes a photo (Ask Mehroj to use firefox instead.)
- When taking pictures, the camera on the iPhone always opens at the front.
- Add email address to internal client group e-mail. Check why they are unable to sign in with email address. After further investigation, the are actually using a wrong e-mail address.
- Reset e-mail password for internal client.

**2-11-2021**
- Added a vibration when the package was not found (Only compatible with androids phone for now)
- Added a feature to alert the driver when the package is not found. This is very important because when the driver is scanning, I noticed that they are not looking on the phone
- Vibrate the phone (Only works on some android compatible device)
- Added a siren sound and disable the scan package button for 5 seconds when the package is not found. There will also a sound notification when the app has completed scanning the package.
- Showed Internal Client the app.
- So far so good, but a complaint about the image quality. Making it a bit bigger.
- Install Webcam and Speakers to Internal Client

**2-10-2021**
Working on Citilogistics app.
- Send an e-mail to Internal Client about the costs of using geo API from google
- Fixed printing manifest. Internal Client was saying we could add more packages per page.
- Modify print-manifest to print 12 packages per page. Trimmed the name and address if it's too long.
- Test the app with the driver
                - Initial login error(Fixed)
                - Unable to take camera pictures. due to lack of permission on the phone. (This is a known issue with older android phones. It's either they have to update their Android OS or use Firefox.)
- App closes when standing by for a long time (Pending)
- Most of the time the driver isn't looking at the phone while scanning.    Adding a sound when failed to add a package. (Pending)
- Add a sound if could not find a package (Pending)
- Show packages that are missing (Pending)
- Added shortcut to drivers.citilogistics.ca in android (Fixed)
- There will be no more POD Photo page, instead it is now part of the package details page. Opens up a Camera and when finished, redirected back to the Package List Page. This will shorten the time when using the app (Fixed)
- Help to fix the speaker

**2-9-2021**
Continue working on the citilogistics app.
- Uploaded changes to live server for testing.
- Print-manifest is showing weird things (Fixed up some code fixed.)
- Removed unnecessary CSV download on the driver's list page.
- Removed CSV download in the search package page.
internal client asks to find the IP address by the email address cause the customer apparently pay on the phone.
- Could find the customer by package ID, but it doesn't seem that we have her IP Address. Asked other dev, he could not see it either.
- Install label printer at internal client workstation
- Missing USB. found one in the warehouse
- Internal client new printer not printing correctly needs modification. (Pending it was busy in the warehouse couldn't use her laptop.)
- Walk through with the internal client about the Citilogistics app. Admin/Driver side.

**2-8-2021**
Internal client was having a problem updating EST. (Open with admin access fixed)
Still not fixed, the application goes in the loop on updating the EST app.
- Find out that software update is installing a new app(Update) to a different directory(Programming fault from Canada Post, not us)
- Find the new directory and add a shortcut to the desktop (It's now working)
- One of the scanner's cradle is broken. The battery is changed already, but when charging on the cradle, the scanner is lit red and won't charge. Try another cradle, it's charging fine.
Continue working on citilogistics app
- Working on generating PDF for printing manifest.
- Added information so that it shows the actual time when the package was delivered.
- Added information to show the actual time when the package was scanned by the driver from the Facility.
- Added option customize print. For example, hide Driver Name, Date, Job# and manually entering the field.
- Added footer to the login page.


**2-5-2021**
Continue working on Downstream App.
- Show the app to Internal Client the Admin/Scanner side. He likes it. (Completed)
- Show the app to Internal Client Admin side. She likes it, and just ask to add the mono ID for scanned packages. (Completed)
- Send Downstream credential to Internal Client (Completed)
- Started developing a page that generates a barcode. Internal Client suggests we could also just use the current labels they got here. (Pending)
- Working on the citilogistics app admin side.
- Working on print-manifest. (Pending)
- Unable to login to outlook. Reset outlook password (Completed) Remove e-mail from the following groups in internal client e-mail
- Setup an account for Newly hired - Added her e-mail to Internal Client Email Groups
- Setup a new e-mail 
- Setup the computer 
- Fix Time 
- Update Drivers 
- Install Office 365 
- 1 Monitor is not working.
- Tried a working cable still does not work. 
- Tried a different monitor it works. Found a replacement monitor.

**2-4-2021**
- Show the app to Internal Client Admin/Scanner side. He likes it. (Completed)
- Show the app to Internal Client Admin side. She likes it, and just ask to add the mono ID for scanned packages. (Completed)
- Send Downstream credential to Internal Client (Completed)
- Started developing a page that generates a barcode. Internal Client suggests we could also just use the current labels they got here. (Pending)
- Working on citilogistics app admin side.
- Working on print-manifest. (Pending)

**2-3-2021**
Internal Client e-mail not receiving e-mail messages: troubleshoot the issue, stuck in synchronizing e-mail. Run 365 repair. does not fix the issue, reinstalled the 365. 
Added outlook.com onto her desktop and ask to use that for now while we are fixing the issue.
- After reinstallation, she's getting the e-mail now but does not appear on the inbox. Maybe because it hasn't downloaded all the messages yet. Asked that I will come back at noon to fix the issue.
- Remove the old excel app from the pcs in the warehouse. (Not completed. They want me out cause clients are there.)

**2-2-2021**
Downstream Admin App
- Create a new page Master Page that shows lists of Master Airway Bill. (Completed)
- Packages page will be the secondary page. (Completed)
Downstream Scanner App
- Implemented Scan Mono (Completed)
- Implemented Scan package and show where the destination of the package  (Completed)
- Created a function for postal code split. (Completed)
    - Scan Mono ID first
    - Scan the package.
    - Added a way to change Mono ID when the user is done scanning.
- Modify CSV Upload so that the app knows who uploaded the CSV file.
- Modify CSV Upload so that it updates the destination of all packages instead of when the user is scanning the parcel. (Completed)
- Created the app on 2 pages. Admin and Regular User (Use the template from citilogistics drvapp)

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

