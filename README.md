# Nerds Theme for FOSSBilling

<img width="1000" height="500" alt="image" src="https://github.com/user-attachments/assets/2c317a38-3c15-4fda-9797-3c91b8485183" />
<img width="1000" height="500" alt="image" src="https://github.com/user-attachments/assets/d05ac550-fbb9-4dc5-a9bf-a9050f622cd5" />
<img width="1000" height="500" alt="image" src="https://github.com/user-attachments/assets/541cb0a3-4925-4ca5-983d-68a546c00012" />



## Overview

Nerds Theme is a client area theme for FOSSBilling. It's designed to enhance your user interface with a clean, modern aesthetic. This guide provides steps on how to install, upgrade, secure, and customize the Nerds theme.

## Installation

Follow these steps to install the Tide theme:

1. Clone this repository or download the latest version.
2. Extract the files and move the `Nerds` directory into the `FOSSBilling directory/themes`.
3. Change the directory owner to the user your web server runs under. For example: `chown -Rf www-data:www-data Nerds/`.
4. Set permissions to `750` using chmod: `chmod -Rf 750 tide/`.
5. Navigate to `Settings -> Themes` in the FOSSBilling admin panel and select `tide` as the default theme.

## Upgrade

To upgrade to a newer version of the Tide theme, perform the following:

1. Clone this repository or download the latest version.
2. Backup your `FOSSBilling directory/themes/Nerds/config/settings_data.json` and any custom assets located at `FOSSBilling directory/themes/tide/assets`. Pay close attention if you have customized the CSS file at `FOSSBilling directory/themes/tide/assets/css/custom.css`.
3. Extract the latest version and move the `tide` directory into `FOSSBilling directory/themes`, overwriting all files.
4. Restore your `settings_data.json` and any custom assets from the backup.
5. Change the directory owner to the web server user. For example: `chown -Rf www-data:www-data Nerds/`.
6. Set permissions to `750` using chmod: `chmod -Rf 750 Nerds/`.

## Security Measures for Prior Installations (Before 0.9.5)

For versions of Tide installed prior to 0.9.5, implement these security measures:

1. Change the directory owner to the web server user. For example: `chown -Rf www-data:www-data Nerds/`.
2. Set permissions to `750` using chmod: `chmod -Rf 750 Nerds/`.

## Theme Customization

Tide now allows you to replace default colours with custom ones, enabling you to align the theme with your branding. To make these changes, edit the `FOSSBilling directory/themes/tide/assets/css/custom.css` file as per the comments provided within it.

Please remember to regularly update your theme to receive the latest enhancements and security patches. Enjoy using Nerds theme!
