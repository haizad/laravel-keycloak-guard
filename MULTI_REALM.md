## Keycloak Multi Realm

1. Copy config/realm.php to your Laravel config folder.

```php
<?php

return [
  'realm1' => env('KEYCLOAK_REALM1_PUBLIC_KEY', null),

  'realm2' => env('KEYCLOAK_REALM2_PUBLIC_KEY', null),

  'realm3' => env('KEYCLOAK_REALM3_PUBLIC_KEY', null),

  'realm4' => env('KEYCLOAK_REALM4_PUBLIC_KEY', null),

  'realm5' => env('KEYCLOAK_REALM5_PUBLIC_KEY', null)
];

```

2. Pass realmName paramater in your header.