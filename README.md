# Magento 2 custom Admin Theme

This Extension is used for custom admin theme color now available for blue theme, it will be improve to other color 

## Features:

### Frontend
- none

### Backend
- change logo at login and dashboard menu

## Introduction installation:

### Install Magento 2 Prevent Add to Cart Not Login
- Download file
- Unzip the file
- Create a folder [root]/app/code/SimoneChinaglia/Admintheme
- Copy to folder

### Enable Extension

```
php bin/magento module:enable SimoneChinaglia_Admintheme
php bin/magento setup:upgrade
php bin/magento cache:clean
php bin/magento setup:static-content:deploy
```

