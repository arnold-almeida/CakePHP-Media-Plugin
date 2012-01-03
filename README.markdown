##Installation
1. Clone into /path/to/app/Plugin 
``git clone https://aeolu@github.com/aeolu/CakePHP-Media-Plugin.git Media``
2. Add as a submodule
``git submodule add https://aeolu@github.com/aeolu/CakePHP-Media-Plugin.git Plugin/Media``
3. Load the plugin.
{{{
    //Within you bootstrap.php
    CakePlugin::load('Media');
}}}
4. Initialize Media files.
``cake Media.Media init``
<pre>
``---------------------------------------------------------------``
``Media Shell``
``---------------------------------------------------------------``
``Do you want to create missing media directories now?  ``
``[n] > y``
``/app/webroot/media/                               [OK  ]``
``/app/webroot/media/static/                        [OK  ]``
``/app/webroot/media/static/aud                     [OK  ]``
``/app/webroot/media/static/doc                     [OK  ]``
``/app/webroot/media/static/gen                     [OK  ]``
``/app/webroot/media/static/img                     [OK  ]``
``/app/webroot/media/static/vid                     [OK  ]``
``/app/webroot/media/transfer/                      [OK  ]``
``/app/webroot/media/transfer/aud                   [OK  ]``
``/app/webroot/media/transfer/doc                   [OK  ]``
``/app/webroot/media/transfer/gen                   [OK  ]``
``/app/webroot/media/transfer/img                   [OK  ]``
``/app/webroot/media/transfer/vid                   [OK  ]``
``/app/webroot/media/filter/                        [OK  ]``
````
``Your transfer directory is missing a htaccess file to block requests.``
``Do you want to create it now?  ``
``[n] > n``
</pre>
