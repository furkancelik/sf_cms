sf CMS
=============

## sf CMS Ver. 2.0.0 
##### Change log: 
* The title has been changed to "Fully CMS" 
* More functions 
* Better optimization

### just an example, needs further development!

<img src="https://raw.github.com/sseffa/sf_cms/master/screenshoots/1.png" width="900" />

## Features

* Laravel 4.2
* Bootstrap 3
* Authentication Sentry 2.1
* Ckeditor
* Bootstrap Code Prettify
* File Manager
* Dropzone.js
* 404 for not found pages
* Custom Error Pages
* Backend
  * Manage menu (nested)
  * Manage article (category, tag)
  * Manage tag
  * Manage article category
  * Manage page
  * Manage news
  * Manage photo gallery
  * Ckeditor for post creation and editing (filemanager)
  * Form post manage
  * Site settings
  * Log view page
* Frontend
  * Article (momentjs)
  * Page
  * News
  * Photo Gallery (Lazy load image, responsive fancybox)
  * Contact Form
  * Breadcrumbs
  * Route cache

## Todo

* Multi language
* User (Cartalyst Sentry)
  * Groups,
  * Group Permissions,
  * User Permissions,
  * Login Throttling
  * User Suspension
  * User Banning
* Multi theme
* Modular Structure
* Plugin Manager

## Installation

Please check the system requirements before installing sf CMS.

1. You may install by cloning from github, or via composer.
  * Github: `git clone git@github.com:sseffa/sf_cms.git`
  * Composer: `composer create-project sseffa/sf_cms --prefer-dist`
2. From a command line open in the folder, run `composer install`.
3. Enter your database details into `app/config/database.php`.
4. Run `php artisan app:install` to setup and seed your database.
5. Default admin, email: admin@admin.com, password: admin
6. Settings `app/config/sfcms.php`. (optional)
  * Cache enable / disable
  * image folder
  * post per page
  * ...

## Credits

 * <http://www.dropzonejs.com/>
 * <http://ckeditor.com/>
 * <http://www.eyecon.ro/bootstrap-datepicker/>
 * <http://fancyapps.com/fancybox/>
 * <https://github.com/simogeo/Filemanager>
 * <https://github.com/dbushell/Nestable>
 * <http://momentjs.com/>
 * <https://github.com/tuupola/jquery_lazyload>
 * <https://github.com/mikemand/logviewer/>
...

## Screenshots

<img src="https://raw.github.com/sseffa/sf_cms/master/screenshoots/2.png" width="900" />
<img src="https://raw.github.com/sseffa/sf_cms/master/screenshoots/3.png" width="900" />
<img src="https://raw.github.com/sseffa/sf_cms/master/screenshoots/4.png" width="900" />
<img src="https://raw.github.com/sseffa/sf_cms/master/screenshoots/5.png" width="900" />
<img src="https://raw.github.com/sseffa/sf_cms/master/screenshoots/8.png" width="900" />

### Licence

[MIT license](http://opensource.org/licenses/MIT).
