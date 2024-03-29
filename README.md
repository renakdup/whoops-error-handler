# Whoops WordPress Error handler
Whoops PHP error handler for WordPress.   
It catches Fatal errors and Exceptions and shows in beautiful format.
We can see a stack trace and parts of invocable code and we can go through the stack trace to see the called parts in the code.  
In the debug information we can find GET, POST, Files, Cookie, Session, Server/Request Data, Environment Variables.

![Whoops Error Handler for WordPress](./doc/img/default-original.png)

## How to install WordPress error handler
1. Create `mu-plugins` directory.
    ```bash
    mkdir wp-content/mu-plugins
    ```

2. Download release and unzip `Whoops WP error handler` in `mu-plugins/mu-plugins`.
   ```bash
   //TODO:: in progress
   ```

3. Create the file `mu-plugins/mu-plugins/whoops-error-handler.php` and include general file of plugin
```php
require_once __DIR__ . '/whoops-error-handler/whoops-error-handler.php';
```



## Available themes
To use one of the themes add a const `RD_WHOOPS_THEME` to the `wp-config.php`

**Smooth material dark**
```php
const RD_WHOOPS_THEME = 'material-dark-smooth';
```
![material-dark-smooth.png](./doc/img/material-dark-smooth.png)

**Material dark**
```php
const RD_WHOOPS_THEME = 'material-dark';
```
![material-dark-smooth.png](./doc/img/material-dark.png)

**Gray**
```php
const RD_WHOOPS_THEME = 'gray';
```
![material-dark-smooth.png](./doc/img/gray.png)

**Original optimized**
```php
const RD_WHOOPS_THEME = 'original-optimized';
```

![material-dark-smooth.png](./doc/img/original-optimized.png)

**Original Default**
```php
const RD_WHOOPS_THEME = 'default-original';
```

![material-dark-smooth.png](./doc/img/default-original.png)