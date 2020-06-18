# Admin Bar ID Menu
Contributors: eceleste  
Tags: admin, bar, admin-bar, id  
Requires at least: 3.1  
Tested up to: 5.4.2  
Stable tag: 1.1.1  
Requires PHP: 5.6
License: GPLv2 or later
License URI: <https://www.gnu.org/licenses/gpl-2.0.html>  

Makes the ID number of the current page or post visible in the Admin Bar.

## Description

There are times that you need to know the ID number of a page or post in WordPress and it can be more painful than it should be to find that number. This plugin does one simple thing: it displays the ID number of the page, post, category, or tag you are looking at in the WordPress Admin Bar. It appends this ID to the edit menu already on the Admin Bar. Needless to say, that means that this plugin is only useful for WordPress version 3.1 or above, since the Admin Bar was first introduced with 3.1.

## Installation

1. Upload the `admin-bar-id-menu` folder to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress

## Frequently Asked Questions

### Why would anyone need this?

If you are asking this question, you don't need this at all. The only time to bother with this plugin is after you've been frustrated a few times trying to track down an id.

### Why don't I see numbers on "view" items?

The inclusion of id numbers on the "view" items in the Dashboard only works in WP 3.3 and up. If you are not seeing those numbers, then you may need to upgrade your WordPress installation.

## Screenshots

![Admin bar snapshot](screenshot-1.png)
1. Notice the number next to the edit link in the Admin Bar, that is the page's ID number.

## Upgrade Notice

### 1.1.1

Tested with more recent versions of WordPress, but no functional difference from earlier versions.

## Developer Information

### Git vs. SVN

I am maintaining this plugin at [GitHub](https://github.com/efc/admin-bar-id-menu), but WordPress requires [SVN](https://plugins.svn.wordpress.org/admin-bar-id-menu) for plugins. I am using the [wp-deploy](https://github.com/efc/wp-deploy) scripts to deploy the SVN version, which includes tranforming this readme into a format acceptable to WordPress.

### Version Bumps

Please update the following files whenever you need to bump the version. Note, a version bump is essential to having changes in the stylesheet recognized by browsers in the wild.

* [admin-bar-id-menu.php](admin-bar-id-menu.php) (change the Version in the header, which is the usual WordPress thing to do)
* [changelog.md](changelog.md) (describe the changes in this version)
* [readme.txt](readme.txt) (update the Stable tag in the header, replace Changelog with most recent version info)
* in this file replace the Upgrade Notice

