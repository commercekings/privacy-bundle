# Privacy bundle

Works with Magento 2.4+ · Luma and Hyvä · PHP 8.1–8.5

**Opt-in in one line: the consent bridge and the cookie banner together.**

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

## Disclaimer

These modules help you ask for, record and respect your shoppers' choices – they don't make your store compliant on
their own. You are responsible for your store's privacy: what you collect, the wording you show, your privacy policy
and whether your setup meets the laws that apply to you (e.g. GDPR, ePrivacy, email marketing rules). Get legal advice
if you are unsure.
