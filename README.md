# VQMod Extensions for OpenCart 4.1.x.x

This directory contains VQMod extensions for OpenCart 4.1.x.x.

## Available Extensions

### auto-product-model.xml
**Auto Model No For New Product v2.0**

Automatically generates a random model number for new products in the admin panel.

- **Target**: `admin/controller/catalog/product.php`
- **Functionality**: Replaces empty model field with a random 13-digit number (1000000000000-9999999999999)
- **VQMod Version**: 2.6.6

### hide-product-model.xml
**Hide Model No For Product v1.0**

Hides the product model number from the product display page.

- **Target**: `catalog/view/template/product/product.twig`
- **Functionality**: Comments out the model display line in product templates
- **VQMod Version**: 2.6.6

## Installation

1. Copy the desired XML files to your OpenCart VQMod installation XML directory
2. Ensure VQMod is properly installed and configured
3. Clear VQMod cache if necessary

## Compatibility

- OpenCart: 4.1.x.x
- VQMod: 2.6.6+ with the opencart scripts from their new repository

## Author

[Gudasoft](https://www.gudasoft.com)
