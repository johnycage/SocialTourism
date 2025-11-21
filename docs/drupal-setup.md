# Drupal Setup

## Prerequisite

* PHP 8.3, Composer installed.
* Database, user and password, host address (`localhost` or AWS-link etc.)

## Instructions

1. Download or clone this repository
   (I assume that you're pulling it in your home folder `/home/username/`)
   `git clone https://github.com/johnycage/socialtourism.git`
2. Install Drupal
   Enter into Drupal folder
   `cd Drupal`
   As per the composer.json instructions
   `composer install`
   **Optional** Activate drush
   `composer require drush/drush`
3. Point the web root to `/home/yourname/SocialTourism/Drupal/web/`
4. Make sure that Database server is running and username, database is added. 
5. Setup Drupal using browser installer walkthrough
   **OR** use `drush site:install`
