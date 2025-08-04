# Flexi CRM Webform plugin

A dynamic webform editor plugin that uses the Flexi Public API to save patient credentials and CRM log records

## Requirements
|                 | Minimum | Preferred |
|-----------------|---------|-----------|
| Flexi MU plugin | 1.0.0   | 1.0.0     |
| PHP             | 7.2     | >8        |
| MySQL           | 5.6     | 8.0       |
| Wordpress       | 6.0.0   | 6.4.3     |

> **IMPORTANT:** You need to enable [Pretty Permalinks](https://wordpress.org/documentation/article/customize-permalinks/#pretty-permalinks) in Wordpress to send form data to Public API.

## Installation
- Install the **[Flexi MU plugin](https://bitbucket.org/illionitgroup/flexi-wp-mu-plugins/src/main/)** into your Wordpress website
- Copy the `flexi-wp-plugin-crm-public-api` directory into `/wp-content/plugins`
- Enable the plugin in `WP Admin -> Plugins` by clicking on the `Enable` button beneath the `Flexi CRM PublicAPI plugin` plugin
- **Initial setup:**
    - Fill your **Public API** credentials on the `WP Admin -> Flexi Webform` page
    - Hit the `Save` button
- **Creating forms:**
    - On the left side menu, a new `Forms` page will appear.
    - There you can create forms like any ordinary *Page* or *Post*.
    - After you created the form, you need to paste it's **shortcode** into your *Page*, *Post*, or *Sidebar*.
