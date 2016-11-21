# CakePHP3 Adminlte 2 Skeleton

[![Build Status](https://img.shields.io/travis/cakephp/app/master.svg?style=flat-square)](https://travis-ci.org/cakephp/app)
[![License](https://img.shields.io/packagist/l/cakephp/app.svg?style=flat-square)](https://packagist.org/packages/cakephp/app)

A skeleton for creating applications with Cakephp3 and Adminlte 2 theme

The framework source code can be found here: [cakephp/cakephp](https://github.com/cakephp/cakephp).

## Installation

-> Download [Composer](http://getcomposer.org/doc/00-intro.md) or update `composer self-update`.

Clone project with below command 

   Run below command to clone this project.
 >git clone https://github.com/ashishonmobile/cakephp3_adminlte_2.git <folder_name>

Download libraries from below command.
 >php composer.phar update

 >php composer.phar instal (this will create missing app.php file, logs and tmp folders)

Create a database in mysql, You can give any name to it.

than run below command to create the table in database.

 >php bin/cake.php migrations migrate

now its time to bake controller, model and template

 >php bin/cake.php bake model all
 >php bin/cake.php bake controller all
 >php bin/cake.php bake template all

This will create all the required php files and ctp files in project.

Now you can access the user page from below  url

http://localhost/cakephp3_adminlte_2/users


## Configuration

Read and edit `config/app.php` and setup the 'Datasources' and any other
configuration relevant for your application.
