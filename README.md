# Privacy bundle

Switches CommerceKings notifications to opt-in: one require that installs the consent bridge and the cookie banner.

```sh
composer require commercekings/module-abandoned-cart:^0.1 commercekings/privacy-bundle:^0.1
bin/magento setup:upgrade
```

## What it installs

- `commercekings/module-consent-notification` – the bridge: subscriptions need a consent, withdrawing it removes them
- `commercekings/module-consent-vanilla` – the cookie banner, with the consent core and the default categories

It contains no code. Without it, CommerceKings features run opt-out.

## More

[Changes](CHANGELOG.md)
