# localhost-wordpress/Other-CMS-landing-page-using-xampp
localhost wordpress landing page using xampp



 



Do you want to create a local WordPress / Other CMS site on your computer using XAMPP? Installing WordPress on your computer helps you try out test themes / plugins, and learn web development. In this article, we will show you how to create a local WordPress site Using XAMPP.



Why Create a Local Site?

Creating local sites is a common practice among developers and site owners. It allows you to test various features without creating an actual website on the internet.

Local websites are only visible to you on your computer. You can try different WordPress themes and plugins, test their features, and learn the WordPress basics.

If you already have a website, then you can create a local copy of website on your computer to try out new plugin updates before implementing them on your live website.

Important: Local website will only be visible to you on your computer. If you want to build a live site, then you will need a domain name and hosting. 

Having said that, let’s check out how to install CMS/WordPress(in our case) locally on Windows, Mac, or Linux using XAMPP.



What is XAMPP?

In order to create a local website, you will need to set up a web server software (Apache), PHP, and MySQL on your computer.

PHP is a programming language and MYSQL is a database management software. Both of them are required to run any CMS/WordPress.

Installing each of these software separately is quite difficult for beginners. This is where XAMPP comes in.

XAMPP makes it easy for you to build WordPress websites locally. It is available for Windows, Mac, and Linux based computers.

Let’s get started.

Installing XAMPP on Your Computer

First, visit the website and click on the download button for your operating system.
1. Download and install XAMPP at default location. 
https://www.apachefriends.org/download.html

￼

Depending on your operating system, the application interface may differ from the screenshots here. 

After downloading XAMPP, you will need to click and run the installer.

￼

XAMPP will ask you where you want to install the software and which packages you’d like to install. The default settings will work for most users. Keep clicking on ‘Next’ to finish the setup wizard.

After finishing the wizard, check the ‘start the control panel now’ option and then click on the finish button.

￼

This will launch the XAMPP control panel. Go ahead and click on the start button next to Apache and MySQL.

￼

XAMPP will now start Apache and MySQL. You may see a Windows Firewall notification, it is important that you click on ‘Allow Access’ button for both applications to run on your computer.
(make sure you haven't created a saprate database on your machine using MYSQL to avoid issues).

￼

Once both applications are started their names will be highlighted in Green.

You have successfully installed XAMPP on your computer.

Now you are ready to create a local website and install WordPress using XAMPP.

Creating a Local WordPress Site with XAMPP

Download wordpress. 
https://wordpress.org/latest.zip


You will need to download WordPress/any other CMS. Visit the WordPress.orgwebsite and click on the ‘Download WordPress’ button.

￼

After downloading WordPress, you need to extract the zip file, and you will see a wordpress folder. You need to cut & paste the contents of this folder to your website folder.

￼

Next, head over to your XAMPP installation folder.

On Windows it would be C:/Program Files/XAMPP/htdocs or C:\Xampp\htdocs folder.

On Mac, it will be /Applications/XAMPP/htdocs folder.


4. Choose a website name. eg : "testpage".


Create a folder with the same name you choose for your website inside htdocs folder.
Paste the contents of the wordpress folder you have cut/copied earlier in the folder you have created as your website's name.
This will be your directorie.

￼


Next, you need to open your favorite web browser and visit localhost/website_name. You will see a page like this:

￼

This page will tell you that WordPress needs a database name, database username, password, and host information.

Let’s create a database for your WordPress site.

You’ll need to open a new browser tab and visit localhost/phpmyadmin/. This will launch phpMyAdmin app that comes pre-installed with XAMPP. It allows you to easily manage your database using a simpler interface.

You would need to click on Databases, provide a name (name that same as your website's name) for your new database, and then click on the create button to continue.

￼

Now that you have created a database, you can use it for your WordPress site.

Switch back to /localhost/website_name browser tab and click on the ‘Let’s Go’ button.

On the next screen, you will be asked to provide your WordPress database information.

Enter the database name you created earlier. Your username is ‘root’ and you should leave the password field blank. For the database host field, you need to use localhost.

See the screenshot below:



Once you are done, click on the ‘Submit’ button to continue.

If you are on Windows or Linux, WordPress will now store these settings in your WordPress configuration file called "wp-config.php" file.

However, if you are on Mac, then it will show you the contents of the file and will ask you to create it.

You will need to create this file in your website’s root folder.

After creating the file, paste the text you copied earlier inside it. Next, you need to save the file and return back to WordPress installer to continue.

In the next step, WordPress will ask you to provide information about your website. First, enter the title you want to use for this site.

After that you need to enter a username, password, and an email address for your admin account.



Once you have filled all the information, click on the ‘Install WordPress’ button to continue.

WordPress will now run the installation and prompt you to login once it’s done.

You can login to your website by going to /localhostwe page and use the username / password that you entered during installation to login.



Things to Try After Creating a Local WordPress Site

Now that you have created your local WordPress site using XAMPP, you can work on it like you would do on a live WordPress site.

Head over to Appearance to customize your site’s appearance or install a new theme. 

The next thing you would want to try is WordPress Plugins. Plugins are like apps for your WordPress site and allow you to add cool features like contact form, photos gallery, e-commerce stores, etc.



 
