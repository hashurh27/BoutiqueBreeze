

### 2. Requirements:

* **Bagisto**: v1.3.3.


### 3. Installation:
* Install the PWA extension
```
composer require bagisto/pwa:dev-master
```

* Run these commands below to complete the setup

```
php artisan config:cache
```

```
php artisan migrate
```

```
php artisan route:cache
```

```
php artisan vendor:publish

-> Press 0 and then press enter to publish all assets and configurations.
```

> That's it, now go to https://yourdomain/pwa
#   B o u t i q u e B r e e z e  
 