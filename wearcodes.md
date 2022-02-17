---
layout: page
title: Wear Codes
permalink: /wearcodes/
---

[Wear Codes](https://play.google.com/store/apps/details?id=org.codechimp.qrwear) for Wear OS (Android Wear) is an easy way to bring up a handy list of QR or traditional barcodes on your watch for scanning without taking out your phone, use it for paying in Starbucks®, Dunkin' Donuts®, loyalty cards, boarding passes, sharing your contact details, web sites or just some useful text.  

## FAQ's  
# Adding a code
Using the big plus button you have three options for adding codes.

To scan a barcode, open Wear Codes, select Scan a code, then scan the barcode. It should recognise the format and show you a confirmation of the details, press Add then give the card a name, press done and the card has been added.
Tip - you can use the volume buttons on your phone to switch on and off the flash for better scanning in the dark.
If you have a screenshot of an app or another image with a barcode you can use the Import Image function. Choose your image and Wear Codes will try to decode it. If it cannot determine where the barcode is you will be given the option to crop the image, you can move the blue box around to where the image is and long hold on the edges of the box to resize it until just the barcode is selected. Press done and Wear Codes will try and decode the barcode again.
To type in your details, select Add manually, give you card a name, choose the data type and enter the code. You can also add easy sharing options for things like your email address, web site, contact details like this as well, just choose the appropriate type.  

# Adding a Starbucks® Card
Create a new manual code and give it a name such as Starbucks.
Choose a card type of Starbucks.
Enter your card number, without spaces into the Card Number field.
Save the code and next time you open the app on your watch it will be ready to pay for your coffee.  

# Adding a Dunkin' Donuts® Card
Create a new manual code and give it a name such as Dunkin' Donuts.
Choose a card type of Card.
Enter your card number, without spaces into the Card Number field.
Save the code and next time you open the app on your watch it will be ready to pay for your coffee.  

# Scanning an airline boarding pass
Boarding passes usually come in PDF417, QR or Aztec. Most airlines support all formats. Long PDF417 codes can be too large to scan reliably from a watch. If you scan a long code Wear Codes will automatically prompt you that it will be changed to a more readable format. You can always alter the type back to PDF417 if you want to as the data is the same, just the image type is different.  

# Adding a PKpass
Most PKpass files contain barcode details. To add it to wear codes do the following  

If the PKpass is in an email just click to open it. Wear Codes will read the pass and display the details for confirmation. Click done and and a new card will be added.  
Otherwise save the .pkpass file, either to your devices storage or a cloud service (Unfortunately you cannot open PKpass files directly from web sites).  
Open the file from a file browser or your cloud storage app.  
If you have multiple app's that can open PKpass files you will have to choose Wear Codes, otherwise it will open automatically, extract the details and display them for confirmation.  
Click done and a new card will be added.  

# Sharing an image or text from other apps  
You can share an image or text from any other app to Wear Codes and it will attempt to interpret what you shared and create a new card.  
If a web page is shared then a new URL type will be created.  
If an image is shared then it will try to find a barcode. If it cannot determine where the barcode is you will be given the option to crop the image, you can move the blue box around to where the image is and long hold on the edges of the box to resize it until just the barcode is selected. Press done and Wear Codes will try and decode the barcode again.  
Any other text will create a basic text QR code.  

# Have a barcode display automatically when you are near a store
If you have the automation app Tasker you can get a barcode to display automatically based on an event. The most useful being when you arrive at a location.  
Firstly decide the notification method, either as a notification or popup straight away as a full screen barcode. Choose your preferred method within Wear Codes settings screen under the Tasker category.  


There are two likely ways you can get Tasker to know when to trigger Wear Codes, either by a location or by a named WiFi access point being present. If the destination has a WiFi access point available it is preferable to use this as the trigger as it is far more battery efficient. You don't even have to connect to that Wifi, it just has to be within range.  

- Within Tasker create a new Profile and choose either Location or State.  
- If you chose location then select a location and radius.  
- If you chose state, select Net then WiFi near. Enter or choose the SSID (access point name) that is available at that location.  
- Press back and you will be now prompted for a Task.  
- Choose New Task, optionally give it a name then press the + to add a task.  
- Select Plugin, then Wear Codes.  
- Click on the pencil to edit the configuration.  
- A list of all your codes is displayed, choose the appropriate one and press the tick.  
- Press Back to complete the task.  
- You can now test the task by pressing the play button at the bottom of the screen, you should see the notification appear on Wear Codes with the appropriate code.  
- Press back again to return to the list of Tasker profiles and you're done. Any time that location/WiFi access point is close it will trigger Wear Codes.  


Tasker is a very powerful automation system and that's a very brief introduction to what it can do, please refer to the help within Tasker for more ideas on how to use it with Wear Codes and other apps.  

# Why do codes look different?
QR, Aztec and PDF417 barcode formats can contain the same data but have a different representation, you'll even see examples where logo's are embedded.  
Wear Codes uses the ZXing barcode generation library which is one of the most popular in the industry and so the barcode will still be able to be read by most scanners.  

# What are stars for?
When you star a code it will appear at the top of the watch list. If you have multiple stars they will appear in alphabetical order.  
If you are using Labels then the stars will appear at the top of the list for that label.  

# What are labels for?
If you have a lot of codes you may want to group them to help you find your code easily.  
Codes within the Default label are displayed when you first open Wear Codes on your watch with the other labels displayed at the bottom of the default list. Codes you use regularly should be in the Default list for easy access.  
Tap on a label to display the codes within that label, to return to the default list swipe left to right.
Use the Manage Labels option within the navigation drawer to add your own labels.  
To change the label a code appears under either tap on the codes icon in the list and select the label icon or from within the Edit Code screen select the change label menu option.  
Labels are displayed within the navigation drawer to allow filtering of the main list.  

# How do I transfer my codes to a new phone?
On the settings screen there are options to backup/restore.  
The backup option prompts to save a file called "WearCodes backup" onto your phone.  
Copy this file to either your SD card or cloud storage.  
From your new device copy the file back to your phone and then use the restore option to select the file from within Wear Codes.  
If you have Google Drive® installed on your phone you can choose that as the location to backup to/restore from.  

# Wear Codes is not showing on my Wear OS 2 watch?  
With Wear OS 2 the watch app is installed separately. This should be prompted automatically but   occasionally it doesn't.   
To install the watch app go to the Play Store on your watch, search for Wear Codes and install it.
Once installed it should now be synced with any codes added to your phone app.  

# Will Wear Codes work on my Samsung® Tizen watch?
No, except for the very latest Samsung watches, they run a proprietary operating system called Tizen® which is not compatible with Android Wear.  
Wear Codes will not install/work on Samsung Tizen watches.  

# Contact
If you are having trouble doing something that isn't covered by this FAQ please send an email to [android@codechimp.org](mailto:android@codechimp.org) and we’ll help you sort it out.