![wordpress](https://img.shields.io/badge/wordpress-v6.2-0678BE.svg?style=flat-square)
![php](https://img.shields.io/badge/PHP-v7.3-828cb7.svg?style=flat-square)
![Node](https://img.shields.io/badge/node-v18-644D31.svg?style=flat-square)
![composer](https://img.shields.io/badge/composer-v2-126E75.svg?style=flat-square)
<br>

## ABOUT
A simple Wordpress Proof Of Concept (POC) to test install Wordpress with Composer and create a new theme.
Trough this POC, we will:
- Install via composer with a custom path (core Wordpress, Theme, Plugins)
- Create a new custom Theme
- Create a custom plugin
- Make unit tests using PHP UNIT (TBC)
- Use Github workflows and automate:
  - Building custom frontend code (JS, CSS)
  - Building custom backend code (PHP)
  - Deploy on SFTP

## HOW TO INSTALL THE PROJECT

### BACKEND

1- Clone the website project from your directory:

```git
git clone git@github.com:Rapkalin/wordpress-repository.git
```

2- Move to the project directory:
- cd wordpress-repository
- composer install 

3- Create a .env file with the following variables:
```
DATABASE_NAME='your-database-name'
DATABASE_USER='your-database-username'
DATABASE_PASSWORD='your-database-password'
DATABASE_HOST='your-host'
```

### FRONTEND
- N/A


## MEANING OF SOME DIRECTORIES AND FILES 

### WEBSITE/APP
- W3 Super Cache: this plugin install a few files and directories:
  - cache
  - w3tc-config
  - advanced-cache.php
- Languages: directory that handle the translation of your website. It is created by Wordpress when you configure the default language of your Wordpress website.