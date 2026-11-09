# Grinet/NotFoundCode

**Grinet/NotFoundCode** is a Magento 2 module that allows you to change the default 404 HTTP status code to a different one (such as 410) for SEO purposes. This adjustment helps search engines understand your site's structure better and can improve your SEO performance.

## Features

- **Custom HTTP Status Code:** Replace the default 404 status code with any code you prefer (e.g., 410) to meet your SEO requirements.
- **SEO Optimization:** Ensure that removed pages return a more appropriate status code, helping search engines correctly interpret the state of your site.
- **Easy Integration:** Seamlessly integrate into your Magento 2 installation with straightforward configuration options.

## Installation

The module can be installed via Composer or manually.

### Composer Installation

Run the following command in your Magento root directory:

```bash
composer require grinet/notfoundcode
bin/magento setup:upgrade
bin/magento cache:flush

## PHP compatibility

PHP 8.5 syntax and PHPCompatibility static checks were run on this release. Existing minimum PHP requirements are retained. Use a Magento release that supports your PHP runtime; syntax/static checks alone do not verify installation, DI compilation or storefront/admin behavior.

The Composer `mage-os` and `mageos` keywords indicate expected compatibility based on Mage-OS retaining Magento namespaces and replacing the corresponding `magento/*` packages. The existing Magento requirements are preserved. No full Mage-OS integration test was performed. See https://mage-os.org/faq/ and https://repo.mage-os.org/packages.json.
