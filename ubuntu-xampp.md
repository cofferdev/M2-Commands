**/opt/lampp/bin/php -dmemory_limit=5G bin/magento deploy:mode:show**

**/opt/lampp/bin/php -dmemory_limit=5G bin/magento deploy:mode:set developer**

**/opt/lampp/bin/php -dmemory_limit=5G bin/magento deploy:mode:set production**

**/opt/lampp/bin/php -dmemory_limit=5G bin/magento module:enable Namespace_Module**

**/opt/lampp/bin/php -dmemory_limit=5G bin/magento module:disable Namespace_Module**

**/opt/lampp/bin/php -dmemory_limit=5G bin/magento module:uninstall Namespace_Module**

**/opt/lampp/bin/php -dmemory_limit=5G bin/magento setup:upgrade**

**/opt/lampp/bin/php -dmemory_limit=5G bin/magento setup:di:compile**

**/opt/lampp/bin/php -dmemory_limit=5G bin/magento setup:static-content:deploy -f**

**/opt/lampp/bin/php -dmemory_limit=5G bin/magento indexer:reindex**

**/opt/lampp/bin/php -dmemory_limit=5G bin/magento indexer:info**

**/opt/lampp/bin/php -dmemory_limit=5G bin/magento indexer:status**

**/opt/lampp/bin/php -dmemory_limit=5G bin/magento maintenance:enable**

**/opt/lampp/bin/php -dmemory_limit=5G bin/magento maintenance:enable --ip=127.0.0.1 --ip=127.0.0.2**

**/opt/lampp/bin/php -dmemory_limit=5G bin/magento maintenance:enable --ip=none**

**/opt/lampp/bin/php -dmemory_limit=5G bin/magento maintenance:disable**

**/opt/lampp/bin/php -dmemory_limit=5G bin/magento maintenance:status**

**/opt/lampp/bin/php -dmemory_limit=5G bin/magento maintenance:allow-ips --ip=127.0.0.1 --ip=127.0.0.2**

**/opt/lampp/bin/php -dmemory_limit=5G bin/magento cache:clean**

**/opt/lampp/bin/php -dmemory_limit=5G bin/magento cache:flush**

**/opt/lampp/bin/php -dmemory_limit=5G bin/magento cache:status**

**/opt/lampp/bin/php -dmemory_limit=5G bin/magento cache:enable [cache_type]**

**/opt/lampp/bin/php -dmemory_limit=5G bin/magento cache:disable [cache_type]**

* config
* layout
* block_html
* collections
* reflection
* db_ddl
* compiled_config
* eav
* customer_notification
* config_integration
* config_integration_api
* google_product
* full_page
* config_webservice
* translate
* vertex