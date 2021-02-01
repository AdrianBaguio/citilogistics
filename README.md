# Citi App
1-29-2021

Internal client - Still seeing weird numbers when converting .csv file into .xslx. Looks like that they have to change the format as text to solve this issue. I also asked Web Dev to add constraints when uploading a CSV file or xslx to check all the reference rows. if there is deemed to be a typo, stop the import and show an error instead. 
Internal client - Printer does not work (Fixed)
Continue working on citilogistics app
- Testing drivers.citilogistics.app pages for the newly import pages.
- Started developing page for the manifest.
1-28-2021


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
1-26-2021


Continue working on citilogistics app
Work on integration with shiptools. (In progress)
Found a bug that when uploading an image, it's submitting ajax multiple times. (In progress)
Created a tracking table for the driver app to keep track of events (Completed)
Integrating tracking to add a photo, completed, and undelivered packages (In Progress)
Internal client asked how to merge 2 columns in excel as this takes them hours to edit. Show how to do it in Excel but it's really complicated. Instead, install Visual Studio Code, and show how to edit multi lines in just 3 buttons.(Completed)
1-25-2021


Install Konica Minolta drivers to Internal client new PC. (Fixed)
Internal client computer has no internet. Determine that the fault was the ethernet cable. The boxes and carts have damaged the ethernet cable. I purchased a crimple and ethernet cable tester. Should arrive in a couple of days. (In Progress)
Continue integrating the Driver app with Shiptools. 
1-22-2021


•	Internal client and Internal client weren't able to login to the server via filezilla.(Fixed, wrong connection. they are connecting through FTP instead of sftp.
•	Internal client printer not printing correctly. (Fixed. adjust the printer configuration)
•	Help Internal client with Outlook being slow (Fixed. Problem with the internet)
•	Continue developing the Citilogistics drivers app
o	Talked to Web Dev about integration with shiptools
o	Talk to Internal client and Internal client about the integration with shiptools and some other feature.
1-21-2021


Internal client wasn't able to download the application from his old computer. (Fixed - Firewall is blocking the site where the files are hosted, find a way to get them on Internal client's new PC.)  - Done
Internal client was saying that the internet was slow. Confirm that the internet is stable. Seemed like the problem is with the EST Software from Canada Post. Called Canada Post software support. They advise reinstalling the software. (In process of re-installing one of the computers first to see if it will speed it up.) – Done
Continue working on the Citilogistics app / Driver side
•	Calculates how much data are spent to finish a route.
-	Needs to optimize the package-list.php page. (In progress)
1-20-2021


- Fixed Internal client laptop not connecting to the internet.
- Reset Internal client e-mail password
- Installed office 360 to Internal client PC. 
- Diagnose issue with the big printer at the back.
- Continue working on Citilogistics app
•	Added feature to show # of wrong-delivered packages on the route page.
•	Added a page where the admin user can update the wrong delivered package in bulk.
•	Added highlights to column records for Address and Photo Address better readability(list-package page)
•	Add StopNumber in the package-list page. With circle ones. The same as what they can see from the driver app.
1-19-2021


Continue working on Citilogistics app admin/driver side
Fixed the loading bug when marking the package as delivered. (Spinning icon won’t toggle off)
Fixed up tooltip in the routes page for admin side
Use PHP sessions for checking driver's authorization to the package and routes.
Now the app is first checking the authorization in the session if it finds it, it uses the session instead of always hitting the database with the request( Which can slow down the site when there are many manifests saved in our database).
The pages are affected by these changes.
•	add-note.php
•	add-photo.php
•	add-undeliverable.php
•	index.php
•	package-details.php
•	package-list.php
•	scan-package.php
•	submit.php
1-18-2021


Continue working on citilogistics app.
•	Show the photo taken by the driver on the list-packages page.
•	Added tooltip and easy to access explanation to the important fields/column: Routes page, Search Package Page and Upload Routing File page
•	Removed download csv in routes page and upload-routing-file page.
•	Fixed some code in routes page.
•	Enhance the page when viewing routes.
•	Added view photo in the search-package and list-packages page.
•	Updated the column names in search-package page.
•	Fixed navbar for the drivers app.
•	Fixed displaying photo addresses.
•	Changed Add Parcel button color to green.
•	Added feature to show packages specifically by driver.
•	Change SESSIONS with GET to maximize length of login time for the drivers. Add openSSL authentication on the driver login side.
Setup PC in Internal client office. Desktop, Monitors, Keyboards and Mouse.
1-15-2021


Added feature to scan packages via cellphone and Bluetooth.
- Ability to scan unique packages ( Avoid savings parcels that are already in our database )
Created an e-mail for Internal client
Added feature to see uploaded photos on the admin page.
Added icons to the pages (Easier to navigate)
Added scan package link to the navigation bar.
Added feature to upload route and package specifically by the drivers.
Fixed sorting in the list-package page.
Added sort by delivered time stamp DESC on the Search Package page
1-14-2021


Continue working on Citilogistics app drivers side and admin side.
•	Add scanned/unscanned packages list pages.
•	Add a feature in the route list page to see how many packages have been released to the drivers.
•	Add feature to scan parcels using mobile phone, and add the parcel and driver information to the database.
1-12-2021


Continue working on the citilogistics app. 
- Fixed font sizes for custom buttons.
- Added route progress animation.
- Fixed table labels on the users page.
- Added options so that the driver can take photos with 1 click.
- Enable options to display xcrud performance.
- Removed xcrud in the admin page. It has been merged.
- Created page for mobile bluetooth scanners (Incomplete)
1-29-2021


Work on the citilogistics app
- Added a warning message when the browser doesn't support geo location.
- Added a feature to show a warning message when the driver isn't at the same location as the package address.
- Saved the addresses where the photo was taken.
Continue working on Andrew’s PC. 
-	Migrated the files(Completed)
-	Installed and tested connections through MSP N-Central(Completed)
-	Installing AV(Incomplete)
