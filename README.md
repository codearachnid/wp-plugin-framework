WordPress Plugin Framework
===================

Author: Timothy Wood @[codearachnid](http://codearachnid.com)

This plugin is a skeleton framework for starting your plugin development process. It uses a Singlton combined with lazy loading of required classes.

### Code Notes

The plugin will initialized at the `plugins_loaded` hook. 

Text Domain: `wp-plugin-framework`

Read more on the [case for singletons](http://eamann.com/tech/the-case-for-singletons/) and why I chose to set this project up in this fashion.