# Lab7_8_repo
repo for lab 7 and 8 for software securty
Project - Wordpress vs. Kali

 These are the exploits i did

1. XSS in Update-page,  add script to the php of our plugin,  able to exploit an XSS vulnerability within the update page of the plgugin tab.

Steps:

go to plugins page,open  editor,Add a script to the php,Update your file,Navigate to "Updates" tab under Dashboard
 Version: 4.2
Fixed Version: 4.7.1




2 - cross site scripting  vulnerability in Page's Edit-page

a) So add a script to the title of a page, we can exploit an XSS vulnerability. This script does not show up on the published blog page, but still triggers the alert.

Steps:

Navigate to All Pages,Select a page to edit,Add some script to the end of page title,Update the page,Check the published website to see the script activate
 Version used : 4.2
Fixed Version: 4.7.1



3 - cross site script vulnerability in Post's Edit-page, by adding a script to the end of a post title, we are able to trigger that script as soon as we load the main page of the application.

Steps:

Navigate to the Post tab,Select a post to edit,Add some script to the end of the post title,Update the post,Navigate to the main page

 Version used : 4.2
Fixed Version: 4.2.5

