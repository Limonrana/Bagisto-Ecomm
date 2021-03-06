<p align="center">
<a href="#"><img src="https://bagisto.com/wp-content/themes/bagisto/images/logo.png" alt="Total Downloads"></a>
</p>

## Topics

1. [Introduction](#introduction)
2. [Requirements](#requirements)
3. [Installation & Configuration](#installation-and-configuration)
4. [License](#license)

### Introduction

Bagisto is a hand tailored E-Commerce framework built on some of the hottest opensource technologies
such as [Laravel](https://laravel.com) (a [PHP](https://secure.php.net/) framework) and [Vue.js](https://vuejs.org)
a progressive Javascript framework.

**Bagisto can help you to cut down your time, cost, and workforce for building online stores or migrating from physical stores
to the ever demanding online world. Your business -- whether small or huge -- can benefit. And it's very simple to set it up.**

# Visit our live [Demo](https://bagisto.limonrana.com)

It packs in lots of features that will allow your E-Commerce business to scale in no time:

-   Multiple Channels, Locale, Currencies.
-   Built-in Access Control Layer.
-   Beautiful and Responsive Storefront.
-   Descriptive and Simple Admin Panel.
-   Admin Dashboard.
-   Custom Attributes.
-   Built on Modular Approach.
-   Support for Multiple Store Themes.
-   Multistore Inventory System.
-   Orders Management System.
-   Customer Cart, Wishlist, Product Reviews.
-   Simple, Configurable, Group, Bundle, Downloadable and Virtual Products.
-   Price rules (Discount) inbuilt.
-   Theme (Velocity).
-   CMS Pages.

**For Developers**:
Take advantage of two of the hottest frameworks used in this project -- Laravel and Vue.js -- both of which have been used in Bagisto.

### Requirements

-   **OS**: Ubuntu 16.04 LTS or higher / Windows 7 or Higher (WampServer / XAMPP).
-   **SERVER**: Apache 2 or NGINX.
-   **RAM**: 3 GB or higher.
-   **PHP**: 7.2.0 or higher.
-   **Processor**: Clock Cycle 1 Ghz or higher.
-   **For MySQL users**: 5.7.23 or higher.
-   **For MariaDB users**: 10.2.7 or Higher.
-   **Node**: 8.11.3 LTS or higher.
-   **Composer**: 1.6.5 or higher.

### Installation and Configuration

**1. You can install Bagisto by using the GUI installer.**

##### b. Extract the contents of zip and execute the project in your browser:

```
http(s)://localhost/bagisto/public
```

or

```
http(s)://example.com/public
```

**2. Or you can install Bagisto from your console.**

##### Execute these commands below, in order

```
1. composer create-project bagisto/bagisto-standard
```

```
2. php artisan bagisto:install
```

**To execute Bagisto**:

##### On server:

Warning: Before going into production mode we recommend you uninstall developer dependencies.
In order to do that, run the command below:

> composer install --no-dev

```
Open the specified entry point in your hosts file in your browser or make an entry in hosts file if not done.
```

##### On local:

```
php artisan serve
```

**How to log in as admin:**

> _http(s)://example.com/admin/login_

```
email:admin@example.com
password:admin123
```

**How to log in as customer:**

_You can directly register as customer and then login._

> _http(s)://example.com/customer/register_

### License

Bagisto is a truly opensource E-Commerce framework which will always be free under the [MIT License](#).
