Control Room for AutoHotkey
============

This symfony project has the following design goals.
* Authenticate users
    * bot runners
    * bot developers
    * Control Room administrators
* Group permissions
* Securely store application credentials
* Audit log of activity
* Start and Stop automation jobs on authenticated bot runners

##Primary Components
* Installer (written in AHK)
    * WAMP
        * PHP 7
        * Apache
        * MySQL
    * Setup Symfony
    * Setup project space
    * Build DB
    * Capture Domain assignment
    * Add God Mode user
    * Install SSL
    * Desktop shortcut
* Application
    * View from browser
    * User Management
    * Client Management
    * Audit Log
    * Automation Management




