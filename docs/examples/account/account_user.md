# Fetching Users

Below you will find a list of examples for common scenarios. 

To learn about all available params, please check our [API Reference](https://www.vendus.pt/ws/account/users.doc).

## Simple Call

```php
<?php

$vendus = new Vendus\Api('YOUR_API_KEY');
$userId = 18169199;
$user   = $vendus->account->users->get($userId);

?>
```