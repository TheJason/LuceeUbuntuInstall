#Introduction

`aptitude update`

`aptitude -y upgrade`

`aptitude -y install apache2`

`wget http://cdn.lucee.org/downloader.cfm/id/155/file/lucee-5.0.0.252-pl0-linux-x64-installer.run -O lucee.run`

NOTE: You can get the [latest Linux Installers Here](http://lucee.org/downloads.html).

This command will download the file and the ""-O"" flag will have "wget" to name it as "lucee.run" for our convenience.

Let's set the file permission to 744, allowing Owner to "Read, Write and Execute" and the rest just to "Read".

`chmod 744 lucee.run`

The permissions and users can be changed later according to your needs. Please see the documentation for the instructions.

Run the Lucee installer to begin the set up:

`sudo ./lucee.run`
Follow the step-by-step install process.  Once 

For the control panels:
http://vpsipaddr:8888/lucee/admin/server.cfm
http://vpsipaddr:8888/lucee/admin/web.cfm

These instructions were "tweaked" from the Digital Ocean Tutorial by: O.S. Tezer titled: [How to Set Up Railo CFML Engine with Tomcat and Apache on a Debian 7 or Ubuntu 13 VPS](https://www.digitalocean.com/community/tutorials/how-to-set-up-railo-cfml-engine-with-tomcat-and-apache-on-a-debian-7-or-ubuntu-13-vps)
