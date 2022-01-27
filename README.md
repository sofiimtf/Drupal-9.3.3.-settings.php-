# Drupal-9.3.3.-settings.php-
New to Drupal here. I have a warning for Trusted Host Settings - Not enabled. Tried to edit the settings.php file, but permission is denied when trying to save. 

A couple of days ago I updated to Drupal 9.3.3. and I got this warning: 

\Trusted Host Settings
Not enabled
The trusted_host_patterns setting is not configured in settings.php. This can lead to security vulnerabilities. It is highly recommended that you configure this. See Protecting against HTTP HOST Header attacks for more information.


I followed all the steps in order to change add some code where needed in the settings.php file but when I tried to save it the permission was denied. 

Specifically: 
I am using the cPanel for the files management. The file settings.php is in this path: 
/public_html/drupal/sites/default/settings.php
At the file I press right click and "Change Permissions" and changed them from 444 (read only) to 644 (giving access to user to write). 
I enter the code in the file and click "save".
I get this message: 
The system failed to create the file “/home/username/public_html/drupal/sites/default/settings.php.lock” (as EUID: 1276, EGID: 1279 1279) because of the following error: Permission denied. 

How can I resolve this?
