# Magezon Builder for Magento 2

## Install and Upgrade

### 1. Install via Composer (Recommended)

It is recommended to install Magezon Builder module via composer for easy installion, update and maintenance.

Run the following command in Magento 2 root folder.

#### 1.1 Install

```
composer require magezon/module-builder
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy
```

#### 1.2 Upgrade

```
composer update magezon/module-builder
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy
```

Run compile if your store in Product mode:

```
php bin/magento setup:di:compile
```

### 2. Copy and Paste

Use this way if you don't want to install via composer:

- Download [the latest version here](https://github.com/magezon2018/module-builder/archive/refs/heads/main.zip) 
- Extract `main.zip` file to `app/code/Magezon/Builder`. You should create a folder path `app/code/Magezon/Builder` if it does not exist.
- Go to Magento root folder and run upgrade command line to install Magezon Builder:

```
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy
```
