# Dilaz Metaboxes
WordPress metaboxes for themes and plugins.

Feel free to use this metaboxes plugin in your __premium__ and __commercial__ projects.

## How to use
1. Download and install [Dilaz Metaboxes](https://github.com/Rodgath/Dilaz-Metaboxes-Plugin/archive/master.zip) plugin
2. Download [Dilaz Metaboxes Options](https://github.com/Rodgath/Dilaz-Metaboxes-Options) and add it into your WordPress project. 

## Example of how to use Dilaz Metaboxes in a theme
Download and install [n00b Starter Theme](https://github.com/Rodgath/n00b) to see a useful example on how to integrate this *dilaz metaboxes plugin* into your WordPress theme development project.

## Features
* __Extendability__ - Easy to update or create new functionality 
* __Easy updating__ - Your settings will not be part of core files
* __AddOns availability__ - AddOns created by other developers
* __Custom Post Types__ - It works with any custom post type
* __Plugins and Themes__ - Can be used with any WordPress theme or plugin

## Metabox Fields
* Text
* Password
* Hidden
* Paragraph
* URL
* Email 
* Number 
* Stepper
* Code
* Textarea
* WordPress Editor
* Radio Select
* Checkbox
* Multicheck/Multiple Checkboxes
* Dropdown Select
* Multiselect/Multiple Select
* Post Select
* Term/Taxonomy/Category Select
* User Select
* Timezone Select
* Image Select
* Color Picker
* Multiple Color Picker
* Date Select
* Date Select - *(From-To)*
* Month Select
* Month Select - *(From-To)*
* Time Select
* Time Select - *(From-To)*
* Date & Time Select
* Date & Time Select - *(From-To)*
* Slider Select
* Range Slider Select
* File Upload - *Image, Audio, Video, Document, Spreadsheet, Interactive, Text, Archive, Code*
* Button & Buttonset
* Switch Buttons


## File Structure
```
wp-includes/plugins/dilaz-metaboxes/  # → Root of your metaboxes
├── assets/                           # → Assets
│   ├── css/                          # → Stylesheets
│   ├── fonts/                        # → Fonts
│   ├── images/                       # → Images
│   └── js/                           # → JavaScripts
├── inc/                              # → Includes
│   ├── fields.php                    # → Metabox fields (never edit)
│   ├── functions.php                 # → Metabox functions (never edit)
│   └── metabox-class.php             # → Metabox class (never edit)
└── dilaz-metabox.php                 # → metabox access (never edit)
```



