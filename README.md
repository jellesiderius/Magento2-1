
<p align="center">
  <img src="https://www.buckaroo.nl/media/3473/magento2_icon.png" width="200px" position="center">
</p>

# Buckaroo Magento 2 Payments Plugin

### About

Magento is an e-commerce platform owned by Adobe. There are two versions: Magento Open Source, the free, open source version written in PHP, and Magento Commerce, the paid cloud version.
More than 250,000 merchants around the world use the Magento platform.

The Buckaroo Payments Plugin ([Dutch](https://support.buckaroo.nl/categorieen/plugins/magento-2) or [English](https://support.buckaroo.eu/categories/plugins/magento-2)) for Magento 2 enables a ready-to-sell payment gateway. You can choose from popular online payment methods in The Netherlands, Belgium, France, Germany and globally.
Start accepting payments within a few minutes.

### Requirements

To use the Buckaroo plugin, please be aware of the following minimum requirements:
- A Buckaroo account ([Dutch](https://www.buckaroo.nl/start) or [English](https://www.buckaroo.eu/solutions/request-form))
- Magento version 2.4.4 or higher
- PHP 7.4 or higher

### Installation

We recommend you to install the Buckaroo Magento 2 Payments plugin with composer. It is easy to install, update and maintain.

**Run the following commands in the Magento 2 root folder:**
```
composer require buckaroo/magento2
php bin/magento module:enable Buckaroo_Magento2
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy
```

### Upgrade

**You can also update the Buckaroo plugin with composer.
To do this, please run the following commands in your Magento 2 root folder:**

```
composer update buckaroo/magento2
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy
```

### Run compile if your store in Production mode:
````
php bin/magento setup:di:compile
````

### Configuration

For the configuration of the plugin, please refer to our [Dutch](https://support.buckaroo.nl/categorieen/plugins/magento-2) or [English](https://support.buckaroo.eu/categories/plugins/magento-2) support website.
You will find all the necessary information there. But if you still have some unanswered questions, then please contact our [technical support department](mailto:support@buckaroo.nl).

### Additional plugins

The Buckaroo Magento 2 plugin can be extended with the following modules:

| Second chance module             | Google Analytics module  |
:-------------------------:|:-------------------------:
[<img src="https://www.buckaroo.nl/media/3479/magento2_secondchance_icon.png" alt="Second-chance" width="200"/>](/v1/docs/second-chance-module)|  [<img src="https://www.buckaroo.nl/media/3478/magento2_googleanalytics_icon.png" alt="Google-analytics" width="200"/>](/v1/docs/google-analytics-module)|

### Contribute

We really appreciate it when developers contribute to improve the Buckaroo plugins.
If you want to contribute as well, then please follow our [Contribution Guidelines](CONTRIBUTING.md).

### Versioning 
<p align="left">
  <img src="https://www.buckaroo.nl/media/3480/magento_versioning.png" width="500px" position="center">
</p>

- **MAJOR:** Breaking changes that require additional testing/caution.
- **MINOR:** Changes that should not have a big impact.
- **PATCHES:** Bug and hotfixes only.

### Additional information
- **Knowledge base & FAQ:** Available in [Dutch](https://support.buckaroo.nl/categorieen/plugins/magento-2) or [English](https://support.buckaroo.eu/categories/plugins/magento-2).
- **Support:** https://support.buckaroo.eu/contact
- **Contact:** [support@buckaroo.nl](mailto:support@buckaroo.nl) or [+31 (0)30 711 50 50](tel:+310307115050)

