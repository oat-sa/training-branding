# TAO branding training

To get this extension in your TAO installation, modify your root composer.json as follow:

## 1. Add the repository
```
"repositories": [
    ...,
    {
       "type": "vcs",
       "url": "git@github.com/oat-sa/branding-training.git"
    }
],

```

## 2. Add the extension
```
require" : {
    ...,
    "oat-sa/branding-training": "dev-step0"
],

```

## 3. Update composer
```
composer update --prefer-source
```