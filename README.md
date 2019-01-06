# Linux Server
This is a repository for my new deployed server.

## Info
1. IP address is [142.93.22.164](http://142.93.22.164.xip.io/).
2. SSH port is ```2200```.
3. To open the application please go to; [Catalog App](http://142.93.22.164.xip.io/).

## Summary
1. I used DigitalOcean hosting service to make my server instance with ```ubuntu``` installed.
2. I updated the libraries using ```sudo apt-get update``` & ```sudo apt-get upgrade```.
3. I created a new user "grader" with sudo permissions.
4. I created an authorization key, and enforced using the key instead of password.
5. I configured and enabled the ufw by only enabling the required ports:
- ```2200``` for SSH instead of ```22```.
- ```80``` for www.
- ```123``` for NTP.
6. I installed ```apache2```.
7. I installed ```flask``` and all the required libraries to run the ```Flask``` application using ```pip``` command.
8. I installed ```.git```, and cloned my (CatalogApp repository)[https://github.com/walidpiano/CatalogApp/].
9. I changed the permissions of ```.git``` file to be accessible to ```root``` user only.
10. I installed ```postgresql``` and created ```catalog``` database.
11. I created and configured new user to ```postgresql``` with full access permission.
12. I modified my ```__ini__.py``` file to connect to ```postgresql``` database instead of ```sqllite``` one.
13. I added the new ip to ```Google OAuth```.

## 3rd Party Resources
- Apache.
- Flask.
- .git
- postgresql
- Google OAuth.
