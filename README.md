# Integration for Elementor forms - Sendinblue

A lightweight but feature packed Sendinblue integration for Elementor forms.
With this integration you can send your form data and contacts to Sendinblue as easily as the standard integrations. 
Keeping performance in mind this integration doesn't add any additional scripts on page load. 
Feel free to post any feature requests and possible issues.

## Installation

### Minimum Requirements

* WordPress 5.0 or greater
* PHP version 5.4 or greater
* MySQL version 5.0 or greater
* [Elementor Pro](https://elementor.com) 3 or greater

### We recommend your host supports:

* PHP version 7.4 or greater
* MySQL version 5.6 or greater
* WordPress Memory limit of 64 MB or greater (128 MB or higher is preferred)


## Installation

1. Install using the WordPress built-in Plugin installer, or Extract the zip file and drop the contents in the `wp-content/plugins/` directory of your WordPress installation.
2. Activate the plugin through the 'Plugins' menu in WordPress.
3. Go to Pages > Add New
4. Press the 'Edit with Elementor' button.
5. Drag and drop the form widget of Elementor Pro from the left panel onto the content area, and find the Sendinblue action in the "Actions after submit" dropdown.
6. Fill your Sendinblue data and Key and you are all set. All users will be added after they submit the form.


## Frequently Asked Questions

**Why is Elementor Pro required?**

Because this integration works with the Form Widget, which is a Elementor Pro unique feature not available in the free plugin.

**Can I still use other integrations if I install this integration?**

Yes, all the other form widget integrations will be available.

## Changelog

### 1.5.1 - 12-08-2022
* Add default value "email" to the email field ID.
* Tested Elementor up to 3.7.0
* Tested Elementor PRO up to 3.7.3

### 1.5.0 - 15-07-2022
* Added a new action after submit to unsubscribe users.
* Skip existing emails - This will skip double optin notification mail if they are already in Sendinblue.
* Tested Elementor up to 3.6.7
* Tested Elementor PRO up to 3.7.2
* Tested WordPress up to 6.0.1

### 1.4.4 - 24-05-2022
* Added default double optin URL when empty the home URL will be used.
* Tested Elementor PRO up to 3.7.1

### 1.4.3 - 08-05-2022
* Tested Elementor up to 3.6.5
* Tested Elementor PRO up to 3.6.5
* Tested WordPress up to 6.0.0

### 1.4.2 - 05-04-2022
* Tested Elementor up to 3.6.2
* Tested Elementor PRO up to 3.6.4

### 1.4.1 - 13-03-2022
* Fix bug on settings page with callback
* Fix bug on settings page showing double output
* Tested WordPress up to 5.9.2
* Tested Elementor up to 3.5.6
* Tested Elementor PRO up to 3.6.3

### 1.4.0 - 27-02-2022
* Elementor form fields shortcodes are now compatible
* Added debugging when WP Debug is on
* Added basic settings page where you can enter a global sendinblue API key
* Possibility to use global or custom API key
* Tested Elementor up to 3.5.5
* Tested Elementor PRO up to 3.6.2

### 1.3.3 - 24-01-2022
* Tested Elementor up to 3.5.4
* Tested Wordpress up to 5.9

### 1.3.2 - 21-01-2022
* Fix possible fatal error on plugin activation
* Tested Elementor up to 3.5.3

### 1.3.1 - 25-12-2021
* Tested PHP up to 8.0
* Add link to the support page
* Add link to the Pro version
* Tested Elementor up to 3.5.2
* Tested Elementor PRO up to 3.5.2
* Update recommended PHP version to 7.4

### 1.3.0 - 19-11-2021
* Added Firstname attribute mapping
* Added Lastname attribute mapping
* Tested Elementor up to 3.4.8

### 1.2.0 - 13-11-2021
* Added GDPR checkbox functionality
* Added dynamic tags to the double optin field
* Added dynamic tags to the email field
* Added dynamic tags to the name field
* Added dynamic tags to the lastname field
* Tested Elementor PRO up to 3.5.1
* Tested Elementor up to 3.4.7
* Tested WordPress up to 5.8.2

### 1.1.0 - 05-10-2021
* Added dynamic tags to the API key field
* Added dynamic tags to the redirect url field
* Added dynamic tags to the list ID field

### 1.0.0 - 25-09-2021
* Initial Release