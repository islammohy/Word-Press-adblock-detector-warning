# AdBlock Detector WordPress Plugin

![WordPress Version](https://img.shields.io/wordpress/plugin/v/adblock-detector)
![License](https://img.shields.io/github/license/yourusername/adblock-detector)
![Last Commit](https://img.shields.io/github/last-commit/yourusername/adblock-detector)

## Description

The AdBlock Detector is a simple WordPress plugin that detects AdBlock usage on a website and shows a message to the users, requesting them to disable AdBlock to support the website. The plugin uses JavaScript to check for the presence of AdBlock in the user's browser and displays a customizable message if it is detected.

## Installation

1. Download the plugin as a ZIP file from the GitHub repository or the WordPress plugin website.
2. In your WordPress admin dashboard, go to "Plugins" → "Add New" → "Upload Plugin".
3. Choose the downloaded ZIP file and click "Install Now".
4. After installation, click "Activate" to enable the AdBlock Detector plugin.

## Usage

The plugin will automatically detect AdBlock usage when users visit your website. If AdBlock is detected, a floating message will be displayed at the top of the page, requesting users to disable AdBlock to support your website. The message can be customized by editing the `adblock-detector.php` file and the `style.css` file in the plugin directory.

## Customization

### Changing the Message

You can change the message displayed to users by modifying the `adblock_detector_show_message()` function in the `adblock-detector.php` file. Look for the following line of code:

```php
echo '<div id="adBlockMessage"><p>Please disable AdBlock to support our website.</p></div>';
