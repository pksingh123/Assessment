# Assessment DHL Location Finder

## Overview
Provide a brief overview of the project. This could include the purpose of the site, its key features, and any other relevant information.

## Requirements
- PHP >= 8.2 (Check the specific version required for your project)
- Composer
- MySQL
- Git

## Local Development Setup

### 1. Clone the repository
```bash
git clone https://github.com/pksingh123/Assessment.git
cd Assessment

composer install

&& import databse in your local from Databse directory && make required changes in "settings.php"
clear the cache
drush cr

### Run the command for admin onetime login
drush uli admin

### phpunit Test
mkdir -p web/sites/simpletest/browser_output && chmod -R 777 web/sites/simpletest
cp web/core/phpunit.xml.dist web/core/phpunit.xml
Make the reuired changes in phpunit.xml in the following places. 
Set the value of SIMPLETEST_BASE_URL with site URL
Set the value of SIMPLETEST_DB with database details
Set the value of BROWSERTEST_OUTPUT_DIRECTORY with full path of the directory
  Run the pwd command and get the fullpath of the directory
Set the value of BROWSERTEST_OUTPUT_BASE_URL switch site URL for output




