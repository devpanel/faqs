## **SERVER**
### Q: I have an existing server, can I use it?
### Q: I don't have a server, can I buy on DevPanel?
> No, you'll have to ***purchase the server directly*** from your chosen VPS / cloud provider. We currently support VPS-instances from:
>
> + **Amazon Web Service (AWS)**
> + **DigitalOcean**

- - -
### Q: Which server OS *(operating system)* is supported?
> _DevPanel supports the ff. major Linux distros:_
* `Ubuntu` | `Debian` | `CentOS`

- - -
### Q: What do I need to link a server to my dashboard?
To link your Linux server / VPS to your DevPanel dashboard, make sure:

+ it's any of the **supported linux distros** (Ubuntu, Debian, CentOS)
+ you have **root access**
	+ *(a privileged user account - allowed to run & install packages)* | `USERNAME` & `PASSWORD` is required.
+ there's **enough space & memory**
	+ *(at least **>4GB** disk-space; **>1GB** memory)* | Or, double-check how much server-resource your app/site will need to run.

- - -
### Q: Will my server packages be modified?
> YES. A setup script will automatically be deployed in order to install additional packages and modify configuration files *(apache, mysql, nginx, etc)* into the server.

If it's a brand new server, go ahead -- no worries!

If the server has specific packages or customization, be aware that binaries and configuration files might be replaced.

The installation script **WILL NOT** delete existing data -- however we recommend using a clean server.

> **FOR DEVELOPERS**: check serverlink github repo -- to know more about the packages.

- - -
### Q: Is **docker** supported?
> **Not yet**, but is currently undergoing development.

* * *

## **APPS**
### Q: Which apps can we deploy?
### Q: Can we deploy app from a git repo *(github, bitbucket, gitlab)*?
### Q: Is it possible to re-deploy into an existing app?
### Q: Where are apps located in the server?
### Q: `DRUPAL`: is **drush** installed?
### Q: `WORDPRESS`: is there **wp-cli**?
### Q: `PHP`: is **composer**  installed?
### Q: `PHP`: can I **switch PHP versions**?
### Q: `PHP`: can I **use different versions of PHP** at the same time?
### Q: `nodejs`: is **npm** installed?

## **BACKUPS**
### Q: How to create manual backups?
### Q: What is actually backed-up from my app?
### Q: Automated backups available?
### Q: Can we download app-backups anytime?

## **TEAMS**
