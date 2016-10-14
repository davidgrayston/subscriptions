# subscriptions

To install the site run the following command:
```
composer install
```
It will download the required files from the composer.json file
```
If using Acquia dev desktp, create a new site from subscriptions/web which will create/configure the database
```

Install the site and import config
```
cd web/sites/default/
```
```
drush si config_installer --site-name="Subscriptions" --account-pass=demo --yes
```

Import config
```
drush cim sync --yes
```
