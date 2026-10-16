# Privacy bundle

**Opt-in in one require: the consent bridge and the cookie banner together.**

```sh
composer require commercekings/privacy-bundle:^0.1
bin/magento setup:upgrade
```

Install it next to any CommerceKings feature (e.g. `commercekings/module-abandoned-cart`). Without a feature it waits;
without the bundle, features run opt-out.

## What it installs

- `commercekings/module-consent-notification` – the bridge: subscriptions need a consent, withdrawing it removes them
- `commercekings/module-consent-vanilla` – the cookie banner, with the consent core and the default categories

It contains no code.

## More

[Changes](CHANGELOG.md)
