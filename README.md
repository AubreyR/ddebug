# DDEBUG #

Drupal Core Hack Debugging Script

### What is this repository for? ###

* This script allows Drupal developers to see all hooks as they are triggered by Drupal core, all template files as they are parsed, and all render functions as they are parsed.  All output is currently displayed directly on the Drupal website itself, which allows the developer to see the components rendered within the display itself instead of having to dig through code.
* Version - 0.9beta

* **NEVER EVER DEPLOY THIS IN A DRUPAL PRODUCTION ENVIRONMENT**

### How do I get set up? ###

1. Pull repository the location you would like to install to, copy the binary to `/usr/local/bin`
2. Chmod the file so that it's executable (if it's not already)
3. Run from inside a `../kbox/appname/code` folder

### Dependencies ###
* grep (GNU grep) 2.25 or higher
* sed (GNU sed) 4.2.2 or higher
* kalabox 0.13.0-beta.2 or higher
* kalabox Drush 8.0.5 or higher
* Drush 8.1.2 or higher
* git 2.7.4 or higher

### Contribution guidelines ###

* Regression Testing Still to be Developed (Test plan to be based from CEW testing in BASH by Peter Walsh)
* All code review to be performed by members of the VIU Web Team

### Who do I talk to? ###

* Author: Aubrey Robertson - Co-op Student Technician - aubrey.viu@gmail.com
* Supervisor: Michael Carpenter - Web Manager - michael.carpenter@viu.ca
* Team Lead: Darryl Woods - Programmer Analyst - darryl.woods@viu.ca