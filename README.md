# VQMod Extensions for OpenCart 4.1.x.x

This directory contains VQMod extensions for OpenCart 4.1.x.x.

## Available Extensions


### Auto Model No For New Product

location: vqmod/auto-product-model.xml

Automatically generates a random model number for new products in the admin panel.

- **Target**: `admin/controller/catalog/product.php`
- **Functionality**: Replaces empty model field with a random 13-digit number (1000000000000-9999999999999)

### Hide Model No For Product

location vqmod/hide-product-model.xml

Hides the product model number from the product display page.

- **Target**: `catalog/view/template/product/product.twig`
- **Functionality**: Comments out the model display line in product templates


## Compatibility

- OpenCart: 4.1.x.x
- VQMod: 2.6.6+ with the opencart scripts from their new repository

## Author

[Gudasoft](https://www.gudasoft.com)
