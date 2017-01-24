# magento2_helloworld

## Installation
Add the VCS in your composer.json
        "repositories": [
        {
            "type": "vcs",
            "url": "https://github.com/guigur/magento2_helloworld"
        }],

Then execute:   
              > composer require Guigur/Helloworld
              > composer update
         
              > php -f bin/magento module:enable Guigur_Helloworld
(optional)    > php -f bin/magento setup:upgrade

## Usage
go to http://urlofmystore/helloworld
