# Tel Protocol Setup (Click2Dial)

***<u>Windows Tel Protocol Setup for Click2Dial</u>***

1. Create a new folder location 'C:\CCG\TelProDialer'
2. Download in de-compress TelProDialer.zip into the above location
   1. Your administrator will provide a link to TelProDialer.zip
   2. Your folder should now look like the below

![re-provision](https://github.com/codebase-technology/Telemedia-Documentation/raw/master/Tel%20Protocol%20Setup/images/contents.jpg)

3. Make the above location full control for everyone

![re-provision](https://github.com/codebase-technology/Telemedia-Documentation/raw/master/Tel%20Protocol%20Setup/images/permissions.jpg)

4. Double click on the 'Setup.reg' file to add the required registry entries

<img src="https://github.com/codebase-technology/Telemedia-Documentation/raw/master/Tel%20Protocol%20Setup/images/reg.jpg" style="zoom:50%;" />

5. Open the 'Setting.ini' file and complete the following entries:
   6. phone_ip - *The local IP Address of the phone (Bind IP to Mac or use statics)*
   2. pbx_ip - *The public IP Address of the PBX*
   3. ext - *The username of the extension*
   4. phone_user - *An encrypted string of the phone's admin portal username*
   5. phone_password - *An encrypted string of the phone's admin portal password*
   6. licence_key - *An encrypted licence key*

   All encrypted strings are available from your administrator.

6. Save and close the file.

7. Open 'Default Apps'

8. Click on 'Choose default apps by protocol'

9. Scroll down to the 'TEL *(URL:Tel)*' protocol

10. Click on the corresponding app button to choose 'TelProDialer' from the list

![re-provision](https://github.com/codebase-technology/Telemedia-Documentation/raw/master/Tel%20Protocol%20Setup/images/protocol.jpg)

11. Close 'Default Apps'
12. Create