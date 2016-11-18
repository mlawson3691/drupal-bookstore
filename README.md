# Books Galore

#### A Drupal 7 bookstore app, November 18th, 2016

#### By Mark Lawson

## Description

This application is an exercise in Drupal 7 using basic core and contrib modules. The application is a website for a fictional book store, where they post their most recent book reviews. Users can sign up to view discounts and comment on reviews. This application uses Views for displaying content, Features for bundling content, and CSS-Injector for added styling. The installed theme is 'Creative' from Devsaran.

## Setup/Installation Instructions

* Clone the repository
* Start a server using MAMP (on Mac)
* Open the MAMP Preferences:
  * Set the document root to the project's root directory
  * Set the Apache Port to 8888 and the MySQL Port to 8889
* Set up the database:
  * In the browser, navigate to phpMyAdmin (localhost:8888/phpMyAdmin)
  * Select the "Import" tab along the top
  * Choose the .sql.zip file from the project located in sites/db-backup
  * Make sure character set is "utf-8"
  * Click "Go"
  * Select the "Privileges" tab along the top
  * Click "Add User" and enter the following credentials:
    * Username: bookstore
    * Host: Local
    * Password: bookstore
  * Click "go"
* Navigate your browser to localhost:8888
* NOTE: Before committing again, be sure to export database and replace copy in sites/db-backup

## Known Bugs

There are no known bugs at this time.

## Support and Contact Details

Please report any bugs or issues to mlawson3691@gmail.com.

## Languages/Technologies Used

* Drupal 7.52
* MAMP
* MySQL
* Contrib Modules:
  * Chaos Tools
  * Views
  * Features
  * CSS-Injector
  * Strongarm
  * Diff

### License

*This application is licensed under the MIT license.*

Copyright (c) 2016 Mark Lawson
