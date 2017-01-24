# magento2_helloworld

## Installation
Add the VCS in your composer.json
        "repositories": [
        {
            "type": "vcs",
            "url": "https://github.com/guigur/magento2_helloworld"
        }],

Then execute:   
1. composer require Guigur/Helloworld
2. composer update         
3. php -f bin/magento module:enable Guigur_Helloworld
4. php -f bin/magento setup:upgrade

## Usage
go to http://urlofmystore/helloworld
