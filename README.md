Drupal with SQLite on OpenShift
===================

Drupal 7 with SQLite Quickstart for Refhat's Openshift. No drush nor pear.drush.org dependency.


From the command line:
--------------

  rhc app create drupal php-5.4 --from-code=git://github.com/fwinstead/drupal-sqlite-quickstart.git


Or from the web page:
--------------

Go to:

  https://openshift.redhat.com/app/console/applications

Do | On

--- | --

Click  | **"Add Application"**

At the bottom of the page, fill in "URL to Cartridge definition" | **php-5.4**

Click | **"Next"**

Public URL | **yoursitename**

Source code | **git://github.com/fwinstead/drupal-sqlite-quickstart.git**

Click | **"Create Application"**

