# Privacy bundle<a href="https://commercekings.net"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/commercekings/privacy-bundle/main/.github/commercekings-dark.svg"><img align="right" width="152" src="https://raw.githubusercontent.com/commercekings/privacy-bundle/main/.github/commercekings-light.svg" alt="Built by CommerceKings. Ready to sell more? Talk to us"></picture></a>

Works with Magento 2.4.4+ · Luma and Hyvä · PHP 8.1–8.5

[![License](https://badgen.net/github/license/commercekings/privacy-bundle)](LICENSE) [![Release](https://badgen.net/github/release/commercekings/privacy-bundle)](https://github.com/commercekings/privacy-bundle/releases)

**Opt-in in one line: the consent bridge and the cookie banner together.**

## Installation

```sh
composer require commercekings/privacy-bundle:^0.1
bin/magento setup:upgrade
```

Install it next to any CommerceKings feature (e.g. `commercekings/module-abandoned-cart`). Without a feature it waits;
without the bundle, features run opt-out.

Then select the banner in **Stores > Configuration > CommerceKings > Consent > Source**: *Cookie banner
(vanilla-cookieconsent)*. Until you do, no banner is shown and no visitor has consent, so features send nothing.
Enable each feature in its own section (e.g. **CommerceKings > Abandoned Cart > Enabled**).

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
