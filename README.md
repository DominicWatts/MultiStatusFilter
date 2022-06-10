# Magento 2 Admin Order Multi Status Filter

![phpcs](https://github.com/DominicWatts/MultiStatusFilter/actions/workflows/phpcs.yml/badge.svg)

![PHPCompatibility](https://github.com/DominicWatts/MultiStatusFilter/workflows/PHPCompatibility/badge.svg)

![PHPStan](https://github.com/DominicWatts/MultiStatusFilter/actions/workflows/phpstan.yml/badge.svg)

![php-cs-fixer](https://github.com/DominicWatts/MultiStatusFilter/workflows/php-cs-fixer/badge.svg)

Filter Magento 2 admin order grid by multiple order statuses using multiselect

## Install instructions

    composer require dominicwatts/multistatusfilter

    php bin/magento setup:upgrade

    php bin/magento setup:di:compile

## Usage instructions

Admin grid

![Screenshot](https://gcdnb.pbrd.co/images/wCwXiZxDn9sl.png?o=1)

May need to clear any existing order grid filter
