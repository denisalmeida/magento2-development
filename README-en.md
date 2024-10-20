# Magento 2 Customization Project

## Overview

This repository aims to showcase my skills in developing and customizing themes, modules and components.

## Installation

To set up this project locally, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone git@github.com:denisalmeida/magento2-development.git
   cd magento2-customization
   ```

2. **Install Dependencies:**
   ```bash
   composer install
   ```

3. **Magento Setup:**
   - Configure your Magento instance as per the Magento installation guidelines.
   - Apply necessary database configurations and run setup commands.

4. **Deploy Static Content:**
   ```bash
   bin/magento setup:static-content:deploy
   ```

5. **Enable Custom Modules:**
   ```bash
   bin/magento module:enable Vendor_Module
   ```

6. **Upgrade Database Schema:**
   ```bash
   bin/magento setup:upgrade
   ```

7. **Clear Cache:**
   ```bash
   bin/magento cache:flush
   ```

8. **Open your Magento store in a web browser and verify the setup.**

## Folder Structure

The project follows a standard Magento 2 folder structure:

- `app/code`: Custom modules and extensions.
- `app/design`: Custom theme files.


# Authors

*   [Denis Almeida](https://denisalmeida.com)


## License

This project is licensed under the [Open Software License (OSL) v. 3.0](LICENSE).

Feel free to reach out with any questions or feedback!