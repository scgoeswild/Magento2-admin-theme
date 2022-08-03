# Magento 2 custom Admin Theme

This Extension is used for custom admin theme color now available for blue theme, it will be improve to other color 

## Features:

### Frontend
- none

### Backend
- change logo at login and dashboard menu

## Introduction installation:

### Option 1: Manual installation
- Download file
- Unzip the file
- Create a folder [root]/app/code/SimoneChinaglia/Admintheme
- Copy to folder

### Option 2: Composer installation (suggest)
- composer require simonechinaglia/admintheme

### Enable Extension

```
php bin/magento module:enable SimoneChinaglia_Admintheme
php bin/magento setup:upgrade
php bin/magento cache:clean
php bin/magento setup:static-content:deploy
```

