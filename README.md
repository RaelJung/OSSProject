![logo](https://user-images.githubusercontent.com/64372881/84566555-0e5aca80-adad-11ea-92ee-0bf457cc8ff1.png)
# OSS Final Project
This repo is for OSS class 03 section final project.
Made by 21900658 Rael Jung. 
# Project Information
- This project runs a website that introduce information about the characters of the Nintendo game Animal Crossing.
- It also allows other people to post or edit posts freely if they log in.
# Introducing video
link : https://www.youtube.com/watch?v=ROuToU4yPhE   
# Practicality of the Project 
- Since Animal Crossing is a popular game these days, people will visit this website a lot because they will need information about this game. 
- It is good for many people to use steadily because it can communicate through posting and commenting functions. 
# How to start project? 
1. Before start, we should set the raspberry pi.
- Log in to your raspberry pi.
- Use sudo su - command.
- Create an account to use as the blog's domain. 
2. Install file.
- Install Nginx HTTP Server:
+ sudo su -
+ apt update
+ apt install nginx
+ service nginx restart
- Install PHP 7.3 and Related Modules
+ apt install software-properties-common
+ apt update
+ apt install php7.3-fpm php7.3-common php7.3-mbstring php7.3-xmlrpc php7.3-sqlite3 php7.3-soap php7.3-gd php7.3-xml php7.3-cli php7.3-curl php7.3-zip
3. Configure Nginx Batflat Site
- cd /etc/nginx/sites-available
- vi myblog.com *I have upload this file on git*
- cd /etc/nginx/sites-available/myblog.com myblog.com
- nginx -t
- service nginx restart
4. Download Batflat
**You shold log in personal account raspberry pi which you made in first step!**
- cd ~/html
- wget https://github.com/sruupl/batflat/archive/master.zip
- unzip master.zip
- mv batflat-master blog
- cd blog
- mk dir ./tmp
- mk dir ./admin/tmp
- chmod -R 777 ./uploads ./inc/data ./adim/tmp ./tmp
5. Go into your local account
- Go into local host file
- Enter the domain of myblog.com
6. Want to change blog content 
- Go to myblog.com/admin and log in. 
- First id and pw : admin
- Add some post and communicate with other people!
# Source of this Project
Using batflat
Website : https://batflat.org/
# Need help?
Just send me an email. (21900658@handong.edu)
**THANK YOU!**
