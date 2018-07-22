<h1>WPSSO Inherit Parent Meta for Posts, Pages, Custom Post Types, Categories, Tags, and Custom Taxonomies</h1>

<table>
<tr><th align="right" valign="top" nowrap>Plugin Name</th><td>WPSSO Inherit Parent Meta</td></tr>
<tr><th align="right" valign="top" nowrap>Summary</th><td>WPSSO Core add-on to inherit the featured image and custom images from parents for posts, pages, custom post types, categories, tags, and custom taxon</td></tr>
<tr><th align="right" valign="top" nowrap>Stable Version</th><td>1.2.0</td></tr>
<tr><th align="right" valign="top" nowrap>Requires At Least</th><td>WordPress 4.7</td></tr>
<tr><th align="right" valign="top" nowrap>Tested Up To</th><td>WordPress 4.9.7</td></tr>
<tr><th align="right" valign="top" nowrap>Contributors</th><td>jsmoriss</td></tr>
<tr><th align="right" valign="top" nowrap>License</th><td><a href="https://www.gnu.org/licenses/gpl.txt">GPLv3</a></td></tr>
<tr><th align="right" valign="top" nowrap>Tags / Keywords</th><td>featured, custom, inherit, images, post meta, custom field</td></tr>
</table>

<h2>Description</h2>

<p style="margin:0;"><img class="readme-icon" src="https://surniaulula.github.io/wpsso-inherit-parent-meta/assets/icon-256x256.png"></p>

<p><strong>If no featured image has been selected</strong> &mdash; for a <em>post</em>, <em>page</em>, or <em>custom post type</em> &mdash; this add-on will assign the first featured image found from its parent, grand-parent, great-grand-parent, etc.</p>

<p><strong>If no custom Open Graph or Schema image has been selected</strong> &mdash; for a <em>post</em>, <em>page</em>, <em>custom post type</em>, <em>category</em>, <em>tag</em>, or <em>custom taxonomy</em> &mdash; this add-on will assign the first custom image found from its parent, grand-parent, great-grand-parent, etc.</p>

<p>Inherited featured and custom images are assigned as default values &mdash; you can always edit any child and select a different featured or custom image (which will then be inherited by its own children).</p>

<p>WordPress does not offer "featured" images for taxonomy terms (categories, tags, and custom taxonomies), so to assign an image to a term, select an image in the Document SSO (Social and Search Optimization) metabox when editing that term. This add-on will cascade those custom images to the children of that term, along with the children of those children, etc.</p>

<p>The Inherit Parent Meta (aka WPSSO IPM) add-on makes no permanent changes &mdash; simply deactivate the plugin to disable the automatically inherited images. ;-)</p>

<p>There is no add-on settings page for this plugin &mdash; simply <em>install</em> and <em>activate</em> the plugin.</p>

<h3>Coded for Performance</h3>

<p>The WPSSO IPM add-on uses the WordPress <code>wp_cache_get()</code> and <code>update_meta_cache()</code> functions for maximum performance and fully integrate with WordPress core functionality.</p>

<h3>WPSSO Core Plugin Prerequisite</h3>

<p>WPSSO Inherit Parent Meta (aka WPSSO IPM) is an add-on for the <a href="https://wordpress.org/plugins/wpsso/">WPSSO Core plugin</a> (Free or Pro version).</p>


<h2>Installation</h2>

<h3 class="top">Install and Uninstall</h3>

<ul>
<li><a href="https://wpsso.com/docs/plugins/wpsso-inherit-parent-meta/installation/install-the-plugin/">Install the WPSSO IPM Add-on</a></li>
<li><a href="https://wpsso.com/docs/plugins/wpsso-inherit-parent-meta/installation/uninstall-the-plugin/">Uninstall the WPSSO IPM Add-on</a></li>
</ul>


<h2>Frequently Asked Questions</h2>




