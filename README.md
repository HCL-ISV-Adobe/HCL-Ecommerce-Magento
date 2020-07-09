# HCL-Ecommerce-Magento
Creating new repository for Magento sample file code changes

Download this code and go the \xampp\htdocs\magento2\app\code and replace the InfieldDigital code with this code.

Go to the \xampp\htdocs\magento2 path and open git bash and execute the below commands for installing the code into magento.

Restarts the apache server as well from Xampp control panel.

php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy -f
php bin/magento cache:flush
php bin/magento cache:clean
