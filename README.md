Awesome lnurl [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) <img src="https://cdn.jsdelivr.net/gh/btcontract/lnwallet@v0.3-129/app/src/main/res/drawable-xxhdpi/icon_bolt_shape.png" width="200" align="right" alt="./jq">
========================================================================

A curated list of awesome things related to the **lnurl** super-protocol for interaction between [Lightning](https://github.com/lightningnetwork/lightning-rfc) wallets and third-party services.

* [Awesome **lnurl**](#awesome-lnurl)
  * [Documentation](#documentation)
  * [Services](#services)
  * [Wallets](#wallets)
  * [Libraries](#libraries)
  * [Tools](#tools)
  * [Contribute](#contribute)
  * [License](#license)

----


Documentation
------------------------------------------------------------------------

_Readings about **lnurl**_.

* [The spec](https://github.com/btcontract/lnurl-rfc/blob/master/spec.md) &ndash; The confusing, but honest, **lnurl** spec, by [Anton Kumaigorodski](https://twitter.com/akumaigorodski), the enigmatic one-man coding machine.
* [An introduction to lnurl](https://telegra.ph/lnurl-a-protocol-for-seamless-interaction-between-services-and-Lightning-wallets-08-19) &ndash; An article introducing the various types of **lnurl**'s, by [fiatjaf](https://twitter.com/fiatjaf).
* [lnurl-withdraw flow](https://gist.githubusercontent.com/fiatjaf/468d8ec581bc498664cafeef755c02ff/raw/c234d267b87772d71f9654dded53397e381a2db5/lnurl-withdraw-flow.txt) &ndash; One of those incomprehensible program action-data flows detailing how lnurl-withdraw takes place.


Services
------------------------------------------------------------------------

_Apps and services supporting **lnurl** in the wild_.

### lnurl-channel

* [LNBIG](https://lnbig.com/) &ndash; Get free inbound channels on your mobile wallet from this mysterious entity.
* [Bitrefill's Thor](https://www.bitrefill.com/thor) &ndash; Buy a reliable incoming channel from this super liquid node, or get a turbo channel from which you can spend immediately.

### lnurl-login

* [Lightning Charger](https://charger.alhur.es/) &ndash; Identify yourself before creating a transaction then identify again when redeeming.

### lnurl-withdraw

* [Kriptode](https://kriptode.com/) &ndash; Use **lnurl** to grab your earnings from trading sats for likes, answering polls or making bets.
* [Lightning Gifts](https://lightning.gifts/) &ndash; Gifts are redeemable with **lnurl**; you can even print your gifts and
* [Paywall](https://paywall.link) &ndash; The Lightning Paywall Generator allows you to withdraw your earnings with **lnurl**.
* [@lntxbot](https://t.me/lntxbot) &ndash; You can extract your balance from the Telegram bot to another wallet with **lnurl**, or even share withdraw codes so you can physically pay friends.
* [Lightning Charger](https://charger.alhur.es/) &ndash; Send your on-chain bitcoins to your mobile wallet as an incoming transaction.

### lnurl-pay

* _~_


Wallets
------------------------------------------------------------------------

_Some wallets that support **lnurl**_.

* [Bitcoin Lightning Wallet](https://lightning-wallet.com/) &ndash; BLW supports _lnurl-channel_, _lnurl-login_ and _lnurl-withdraw_.
* [BlueWallet](https://bluewallet.io/) &ndash; supports _lnurl-withdraw_.
* [@lntxbot](https://t.me/lntxbot) &ndash; The Telegram-based wallet supports _lnurl-withdraw_.

Libraries
------------------------------------------------------------------------

_Integrate **lnurl** in projects and services_.

* [go-lnurl](https://github.com/fiatjaf/go-lnurl) &ndash; lnurl-withdraw helper structs, encode/decode, verify lnurl-login signatures .
* [php-lnurl](https://github.com/tkijewski/php-lnurl) &ndash; Easy PHP encoding and decoding of bech32 lnurls.


Tools
------------------------------------------------------------------------

_Stuff for using and playing with **lnurl**_.

* []() &ndash;

Contribute
------------------------------------------------------------------------

Please contribute! Open an issue or a PR and we’ll discuss it or merge it. If
you’re opening a PR, please ensure all formatting is ok (if you’re in a hurry
just open an issue).


License
------------------------------------------------------------------------

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
