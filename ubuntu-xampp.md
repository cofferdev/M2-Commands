**/opt/lampp/bin/php -dmemory_limit=5G bin/magento deploy:mode:show**

**php -dmemory_limit=5G bin/magento deploy:mode:set developer**

**php -dmemory_limit=5G bin/magento deploy:mode:set production**

**php -dmemory_limit=5G bin/magento module:enable Namespace_Module**

**php -dmemory_limit=5G bin/magento module:disable Namespace_Module**

**php -dmemory_limit=5G bin/magento module:uninstall Namespace_Module**

**php -dmemory_limit=5G bin/magento setup:upgrade**

**php -dmemory_limit=5G bin/magento setup:di:compile**

**php -dmemory_limit=5G bin/magento setup:static-content:deploy -f**

**php -dmemory_limit=5G bin/magento indexer:reindex**

**php -dmemory_limit=5G bin/magento indexer:info**

**php -dmemory_limit=5G bin/magento indexer:status**

**php -dmemory_limit=5G bin/magento maintenance:enable**

**php -dmemory_limit=5G bin/magento maintenance:enable --ip=127.0.0.1 --ip=127.0.0.2**

**php -dmemory_limit=5G bin/magento maintenance:enable --ip=none**

**php -dmemory_limit=5G bin/magento maintenance:disable**

**php -dmemory_limit=5G bin/magento maintenance:status**

**php -dmemory_limit=5G bin/magento maintenance:allow-ips --ip=127.0.0.1 --ip=127.0.0.2**

**php -dmemory_limit=5G bin/magento cache:clean**

**php -dmemory_limit=5G bin/magento cache:flush**

**php -dmemory_limit=5G bin/magento cache:status**

**php -dmemory_limit=5G bin/magento cache:enable [cache_type]**

**php -dmemory_limit=5G bin/magento cache:disable [cache_type]**

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