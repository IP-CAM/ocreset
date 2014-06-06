ocreset
=======

Open Cart Administrator Password Reset tool.
--------------------------------------------
This is a little app that hopefully will be useful when people get stuck. It's inspired by wpreset file you can find amoung my repositories. Its orignally made by opencart forum user JAY6390. his version can be found here. http://forum.opencart.com/viewtopic.php?f=23&t=15626

I have just made a few tweaks to allow resetting OC passwords in latest versions of open cart. How open cart handles passwords has changed since JAY6390 has written this tool. they have introduced SALT and changed the hashing technique.

Instructions for use
--------------------

1. Either download the ocreset.php file and save it in your store's directory (The same one as the .htaccess/.htaccess.txt file)
2. Run the file through your browser by visiting your site's store address followed by ocreset.php, so for a localhost in a directory called shop it would be http://localhost/shop/ocreset.php  for your domain in the root directory just use  http://www.yoursite.com/ocreset.php
3. You should now see a screen with a dropdown that has a list of your site administrators
4. Select your administrator name you want to reset, type your password in the password field and click "Change Password"
5. If all went well a message should appear at the top of the screen with

    User `admin` updated successfully!

    where admin is the name of the user you've just reset

6. Once you've reset your password MAKE SURE YOU DELETE THE OCRESET.PHP FILE from your server, to avoid anyone gaining unauthorised access to your store

MAKE SURE YOU DELETE THE OCRESET.PHP FILE
-----------------------------------------
