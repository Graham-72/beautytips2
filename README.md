# Beautytips

The Beautytips module provides balloon-style help tooltips for any page
element by integrating with Backdrop the BeautyTips jQuery Tooltip 
plugin by Jeff Robbins. 

It provides an API for adding custom beautytips as well as some 
built-in features. Admins can enable rollover balloon-help style 
tooltips for text fields within forms.

Most importantly, it allows developers to add their own custom 
beautytips popups to their site without having to delve into jQuery.

This is a port from the Drupal module of the same name, v7.x-2.2. 


## Status

This is an initial port of the module. Not all the features have 
been tested.

## Installation

Install this module using the official Backdrop CMS instructions at
  https://backdropcms.org/guide/modules.
  
    
## Configuration

The module settings can be found in 'Content Authoring' within
'Configuration', at admin/config/content/beautytips.
There you can select from a number of preset styles to use as a 
default for your site, or you can add a custom style.

If you enable the option 'Add beautytips.js to every page', 
then anything with the class 'beautytips' will automatically 
have a popup which displays the 'title' attribute of the element.  
If there is nothing in the title attribute, then there will be no popup.
  
With this enabled, you can also define custom elements which 
will be given a beautytip. For example, you can set it up so that 
anything on any page with the id 'example' will have a popup.  Again, 
the content of the beauty will be pulled from the element's title attribute.

## Help & Documentation

See README.txt for more information about installation and use.


## License

This project is GPL v2 software. See the LICENSE.txt file in this
directory for complete text.
    
        
## Current porting to Backdrop

Graham Oliver (github.com/Graham-72), 
assisted by Olaf Grabienski (github.com/olafgrabienski)

## Credits

### Maintainers for Drupal:

- id.sic
- kleinmp
- stephenh


### Acknowledgement

This port to Backdrop would not, of course, be possible without all
the work done by the developers and maintainers of the Drupal module.
