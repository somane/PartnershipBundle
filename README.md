PartnershipBundle
=================

Symfony2 Partnership Bundle

Installation
============

To install this bundle please follow the next steps:

First add the dependency in your `composer.json` file:

```json
"require": {
    ...
    "maliteam/partnership-bundle": "dev-master"
},
```

Then install the bundle with the command:

```sh
php composer update
```

Enable the bundle in your application kernel:

```php
<?php
// app/AppKernel.php

public function registerBundles()
{
    $bundles = array(
        // ...        
        new MALITEAM\Bundle\PartnershipBundle\MALITEAMPartnershipBundle(),
    );
}
```

Now the Bundle is installed.
