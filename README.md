# tsse-1.3.9

INSTALLATION INSTRUCTIONS:
------------------------------------------------------------------------
1. Unzip the archive and transfer the files to a directory on your web server.

2. Change the permission files and folders on the CONF [folder+Files] - TORRENTS [folder] - BITBUCKET [folder] - CACHE [folder] - ALL can be written to by the web server.

3. Create a database (set charset: utf8_general_ci This will stop login problems)

4. Run the installer from http://yourtrackerurl/install/index.php file in your web browser and follow the on screen instructions.

5. Open include/functions.php change line 17 and 27 (see this lines for more info)

6a. Change default value of timezone from your tracker table: phpmyadmin>yourtrackertable>users>tzoffset>change default value. (default: 0 (GMT) Casablanca, Dublin, Edinburgh, London, Lisbon, Monrovia))

6b. Edit include/globalfunctions.php change following lines: 17 and 25 (Default: 0 (GMT) Casablanca, Dublin, Edinburgh, London, Lisbon, Monrovia)

NOTE: If you have sent mail problem, click on site settings and change SMTP servers or disable/enable it or use test mail function or check your host settings...

DO NOT FORGET TO RE-SETUP ALL SITE SETTINGS by USING SITE SETTINGS PANEL AFTER FIRST INSTALL!
