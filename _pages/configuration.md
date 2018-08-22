---
layout: page
permalink: /configuration/
---

# Configuration

Settings that affect the site as a whole can be found in the `_config.yml` file located in the root of your project. If you do not have one of these files, you can create a blank file or copy the [default _config.yml](https://github.com/SevenZeroThree/zero/blob/master/_config.yml) file from the theme.

The theme's default _config.yml file contains comments for each of the configuration options with the intent that it provides some context for what each of them do. More detailed explanations for all of the configuration options can be found below.

## Title
This is the name of your site. It will appear in several areas of the theme:

- Most importantly, it will appear in the `<title>` HTML tag
- The top left of every page in the header area
- The bottom left of every page in the footer area

*Example Usage*:  `title: "My Site"`

## Author
The author of the website. This will likely be your name, but can be any name you wish. This will appear in the default footer.

*Example Usage*:    `author: "Christopher Tobin"`

## Analytics
Analytics will be disabled unless you provide a Google Analytics Tracking Id *AND/OR* a Google Tag Manager Container Id.

Don't know what values to put here? Check with [Google Analytics](https://www.google.com/analytics) to get a Google Analytics Tracking Id. It will start with `UA`. If using Google Tag Manager, you can retrieve your Container Id from the [Tag Manager](https://tagmanager.google.com) portal. It will start with `GTM`.

*Example Usage*:
```
analytics:
    google_analytics_tracking_id: "UA-XXXXXX-X"
    google_tag_manager_container_id: "GTM-XXXXX"
```