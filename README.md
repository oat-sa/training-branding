# TAO branding training

To get this extension in your TAO installation, modify your root composer.json as follow:

## 1. Add the repository
```
"repositories": [
    ...,
    {
       "type": "vcs",
       "url": "https://github.com/oat-sa/training-branding.git"
    }
],

```

## 2. Add the extension
```
require" : {
    ...,
    "oat-sa/training-branding": "dev-master"
],

```

## 3. Update composer
```
composer update --prefer-source
```
