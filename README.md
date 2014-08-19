wb283-sp2-patch
===============

Since 2014-08-17 **WebsiteBaker 2.8.3 SP2** is available and can be retrieved from the [official WebsiteBaker download page](http://www.websitebaker.org/de/download/neueste-version.php).

This service pack fixes some smaller issues and change the database access from the deprecated `mysql_` to the `mysqli_` interface.

The service pack does not initialize the CAPTCHA table at installation, so you will run into a problem because you can not access the backend.

PHP 5.4, 5.5 or 5.6 and current MySQL are a bit stronger than older versions and no longer accept uninitialized values, unfortunately WebsiteBaker 2.8.3 SP2 does not fix these issues.

This Patch fixes all problems I know. 

* Download [WebsiteBaker 2.8.3 SP2](http://www.websitebaker.org/de/download/neueste-version.php)
* unzip the archive
* Download [wb283-sp2-patch](https://github.com/phpManufaktur/wb283-sp2-patch/releases)
* unzip the archive
* copy the content of the patch into the `\wb` installation directory
* copy the content of the `\wb` installation directory to your webserver
* execute the installation

