=== WPSSO Inherit Parent Metadata ===
Plugin Name: WPSSO Inherit Parent Metadata
Plugin Slug: wpsso-inherit-parent-meta
Text Domain: wpsso-inherit-parent-meta
Domain Path: /languages
License: GPLv3
License URI: https://www.gnu.org/licenses/gpl.txt
Assets URI: https://surniaulula.github.io/wpsso-inherit-parent-meta/assets/
Tags: featured, custom, inherit, images, post meta, custom field
Contributors: jsmoriss
Requires PHP: 7.0
Requires At Least: 4.7
Tested Up To: 5.8
Stable Tag: 3.7.0

Inherit featured and custom images from parents for posts, pages, custom post types, categories, tags, and custom taxonomies.

== Description ==

<p><img class="readme-icon" src="https://surniaulula.github.io/wpsso-inherit-parent-meta/assets/icon-256x256.png"> Inherit featured and custom images from parents for posts, pages, custom post types, categories, tags, and custom taxonomies.</p>

= Featured Image =

**If no featured image has been selected** - for a *post*, *page*, or *custom post type* - this add-on will assign the first featured image found from its parent, grand-parent, great-grand-parent, etc.

WordPress does not offer featured images for taxonomy terms (categories, tags, and custom taxonomies) - to assign a custom image to a term, select an image in the Document SSO metabox when editing a term. The WPSSO IPM add-on will cascade the custom image(s) to the children of that term, along with the children of those children, etc.

= Custom Images =

**If no custom image has been selected in the Document SSO metabox** - for a *post*, *page*, *custom post type*, *category*, *tag*, or *custom taxonomy* - this add-on will assign the first custom image found (if any) from its parent, grand-parent, great-grand-parent, etc.

Inherited images are assigned as default values - you can always edit any child to select a different featured or custom image (which will then be inherited by its own children).

The Inherit Parent Metadata (WPSSO IPM) add-on makes no permanent changes - deactivate the plugin to disable the inherited image feature. ;-)

There is no add-on settings page for this plugin - simply *install* and *activate* the plugin.

<h3>WPSSO Core Required</h3>

WPSSO Inherit Parent Metadata (WPSSO IPM) is an add-on for the [WPSSO Core plugin](https://wordpress.org/plugins/wpsso/).

== Installation ==

<h3 class="top">Install and Uninstall</h3>

* [Install the WPSSO Inherit Parent Metadata add-on](https://wpsso.com/docs/plugins/wpsso-inherit-parent-meta/installation/install-the-plugin/).
* [Uninstall the WPSSO Inherit Parent Metadata add-on](https://wpsso.com/docs/plugins/wpsso-inherit-parent-meta/installation/uninstall-the-plugin/).

== Frequently Asked Questions ==

== Screenshots ==

== Changelog ==

<h3 class="top">Version Numbering</h3>

Version components: `{major}.{minor}.{bugfix}[-{stage}.{level}]`

* {major} = Major structural code changes / re-writes or incompatible API changes.
* {minor} = New functionality was added or improved in a backwards-compatible manner.
* {bugfix} = Backwards-compatible bug fixes or small improvements.
* {stage}.{level} = Pre-production release: dev < a (alpha) < b (beta) < rc (release candidate).

<h3>Standard Version Repositories</h3>

* [GitHub](https://surniaulula.github.io/wpsso-inherit-parent-meta/)
* [WordPress.org](https://plugins.trac.wordpress.org/browser/wpsso-inherit-parent-meta/)

<h3>Changelog / Release Notes</h3>

**Version 3.7.0 (2021/06/08)**

* **New Features**
	* None.
* **Improvements**
	* None.
* **Bugfixes**
	* None.
* **Developer Notes**
	* Renamed '\*_img_id_pre' option keys to '\*_img_id_lib' for WPSSO 8.30.0.
* **Requires At Least**
	* PHP v7.0.
	* WordPress v4.7.
	* WPSSO Core v8.34.0.

**Version 3.6.0 (2021/03/08)**

* **New Features**
	* None.
* **Improvements**
	* Added backwards compatibility with the classic editor.
* **Bugfixes**
	* None.
* **Developer Notes**
	* None.
* **Requires At Least**
	* PHP v7.0.
	* WordPress v4.7.
	* WPSSO Core v8.25.2.

**Version 3.5.1 (2021/02/25)**

* **New Features**
	* None.
* **Improvements**
	* Updated the banners and icons of WPSSO Core and its add-ons.
* **Bugfixes**
	* None.
* **Developer Notes**
	* None.
* **Requires At Least**
	* PHP v7.0.
	* WordPress v4.7.
	* WPSSO Core v8.23.0.

**Version 3.5.0 (2020/12/02)**

* **New Features**
	* None.
* **Improvements**
	* None.
* **Bugfixes**
	* None.
* **Developer Notes**
	* Included the `$addon` argument for library class constructors.
* **Requires At Least**
	* PHP v7.0.
	* WordPress v4.7.
	* WPSSO Core v8.16.0.

== Upgrade Notice ==

= 3.7.0 =

(2021/06/08) Renamed option keys for WPSSO 8.30.0.

= 3.6.0 =

(2021/03/08) Added backwards compatibility with the classic editor.

= 3.5.1 =

(2021/02/25) Updated the banners and icons of WPSSO Core and its add-ons.

= 3.5.0 =

(2020/12/02) Included the `$addon` argument for library class constructors.

