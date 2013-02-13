Opauth-Vimeo
=============
Vimeo strategy for [Opauth][1], based on Opauth-OAuth.

Getting started
----------------
1. Install Opauth-Vimeo:
   ```bash
   cd path_to_opauth/Strategy
   git clone git://github.com/LubosRemplik/opauth-vimeo.git Vimeo
   ```

2. Create Vimeo application at https://developer.vimeo.com/apps/new
	
3. Configure Opauth-Vimeo strategy with at least `Consumer key` and `Consumer secret`.

4. Direct user to `http://path_to_opauth/vimeo` to authenticate


Strategy configuration
----------------------

Required parameters:

```php
<?php
'Vimeo' => array(
	'key' => 'YOUR CONSUMER KEY',
	'secret' => 'YOUR CONSUMER SECRET'
)
```

Dependencies
------------
tmhOAuth requires hash_hmac and cURL.  
hash_hmac is available on PHP 5 >= 5.1.2.

Reference
---------
 - [Vimeo](https://developer.vimeo.com/apis/advanced)
