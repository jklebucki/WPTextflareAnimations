# TextFlare Animations

TextFlare Animations is a WordPress plugin that allows you to create and manage animated text groups with configurable options. This plugin provides a user-friendly interface to configure animations and generate shortcodes to display them on your WordPress site.

## Features

* Create and manage text animations
* Configurable animation types, durations, and delays
* Customizable style options including text color, font size, font family, background color, and text alignment
* Generate shortcodes to easily embed animations in posts and pages
* Supports multiple animation types: Zoom, Fade, and Cube

## Installation


1. Download the plugin files and upload them to the `/wp-content/plugins/textflare-animations` directory, or install the plugin through the WordPress plugins screen directly.
2. Activate the plugin through the 'Plugins' screen in WordPress.
3. Navigate to the 'TextFlare' menu in the WordPress admin to configure your animations.

## Usage


1. Go to the 'TextFlare' menu in the WordPress admin.
2. Create a new configuration by selecting an animation type, setting the duration and delay, and customizing the style options.
3. Add text items to the text list.
4. Save the configuration.
5. Copy the generated shortcode and paste it into any post or page where you want the animation to appear.

## Shortcodes

Use the following shortcode to display an animation:

\[textflare id="CONFIG_ID"\]

Replace `CONFIG_ID` with the ID of the configuration you want to display.

## Development

### File Structure

* `textflare-animations/admin-template.html`: HTML template for the admin interface.
* `textflare-animations/admin.css`: CSS styles for the admin interface.
* `textflare-animations/admin.js`: JavaScript for the admin interface, using Vue.js.
* `textflare-animations/textflare-animations.php`: Main plugin file, handles WordPress hooks and AJAX endpoints.

### Scripts and Styles

* Vue.js is used for the admin interface.
* Styles are included in `admin.css` and enqueued in the WordPress admin.
* Frontend styles are also enqueued to ensure animations are displayed correctly.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request on GitHub.

## License

This project is licensed under the MIT License.


