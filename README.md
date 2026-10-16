<a href="https://commercekings.net"><img align="right" src="https://img.shields.io/badge/Built%20by-CommerceKings-F26322?labelColor=1F1F1F" alt="Built by CommerceKings – expert Magento engineering"></a>

# Privacy bundle

<sub>Expert Magento engineering. New store, maintenance, custom development, high-performance hosting or more sales? [Talk to us](https://commercekings.net).</sub>

Works with Magento 2.4+ · Luma and Hyvä · PHP 8.1–8.5

[![License](https://badgen.net/github/license/commercekings/privacy-bundle)](LICENSE) [![Release](https://badgen.net/github/release/commercekings/privacy-bundle)](https://github.com/commercekings/privacy-bundle/releases)

**Opt-in in one line: the consent bridge and the cookie banner together.**

## Installation

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
