Awesome lnurl [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) <img src="https://i.imgur.com/wNtVhj3.png" width="200" align="right" alt="./jq">
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

* [The spec](https://github.com/btcontract/lnurl-rfc) &ndash; The confusing, but honest, **lnurl** spec, by [Anton Kumaigorodski](https://twitter.com/akumaigorodski), the enigmatic one-man coding machine.
* [lnurl-pay for everything](https://xn--57h.bigsun.xyz/lnurl-pay-for-everything.html) &ndash; an article about how **lnurl-pay** can bring China's QR frenzy to the rest of the world in a non-centralised manner.
* [lnurl-withdraw flow](https://⚡️.bigsun.xyz/lnurl-withdraw-flow.txt) &ndash; One of those incomprehensible program action-data flows detailing how **lnurl-withdraw** takes place.
* [lnurl-pay flow](https://⚡️.bigsun.xyz/lnurl-pay-flow.txt) &ndash; Same as above, but for **lnurl-pay**.


Services
------------------------------------------------------------------------

_Apps and services supporting **lnurl** in the wild_.

### lnurl-pay

* [lntorub](https://vds.sw4me.com/rulnurl/)	&ndash; Build reusable URLs that allow you to recharge Russian, phones, send money to Russian cards and recharge Skype globally.
* [lnurlpayserver](https://github.com/fiatjaf/lnurlpayserver) &ndash; An easy to host server that talks to your lnd, Spark or @lntxbot nodes and allows you to generate and serve **lnurls** and manage items in a physical shop.
* [tip.bigsun.xyz](https://tip.bigsun.xyz) &ndash; Static donation **lnurls** that send money directly to your node, noncustodially. Ideal for street musicians.
* [@lntxbot](https://t.me/lntxbot) &ndash; `https://lntxbot.bigsun.xyz/@telegramusername` allows you to send money to anyone using a fixed **lnurl**. It can be printed and shared at will. It's basically an old-style address.

### lnurl-auth

* [Etleneum](https://etleneum.com/) &ndash; The only supported login method is **lnurl**.
* [Wheel of Fortune](https://fortune.lngames.net) &ndash; Login with lnurl Instead of manually saving your key.

### lnurl-withdraw

* A big collection of services allow you to withdraw your balances with **lnurl**: [Etleneum](https://etleneum.com/), [Paywall](https://paywall.link), [Microbet](https://microbet.fun/), [Kriptode](https://kriptode.com/), [lngames.net](https://lngames.net/), [LightningScratchAnd.win](https://lightningscratchand.win/), [Lightning Gifts](https://lightning.gifts/), [LN Markets 𝞪](https://lnmarkets.com/).
* [Bitcoin Bounce](https://thndr.games/) &ndash; Play for free and win satoshi prizes. **lnurl** is the only way to redeem.
* [GraafOne](https://www.graaf.one/) &ndash; Allows you to buy Bitcoin in Canada and withdraw directly to your **lnurl**-powered wallet.
* [LNPay.co](https://lnpay.co) &ndash; Provides static **lnurl** rechargeable faucets you can print, email or easily embed!
* [@arcbtc's TheFossa](https://twitter.com/BTCSocialist/status/1176206194333147136) &ndash; A DIY ATM machine that eats coins and spits out sats.
* [Sinclair Faucet](https://lnurl.com/faucet/) &ndash; A faucet generator that creates printable **lnurl** codes withdrawable multiple times.
* [LightningCashback](https://twitter.com/21isenough/status/1193631492603293698) &ndash; A POS system that prints **lnurl** QR codes containing your change in receipts (fiat onramp?).
* [@21isenough's LightningATM](https://twitter.com/21isenough/status/1194963700110770176) &ndash; A DIY ATM machine that eats coins and spits out sats.
* [@lntxbot](https://t.me/lntxbot) &ndash; You can extract your balance from the Telegram bot to another wallet with **lnurl**, or even share withdraw codes so you can physically pay friends.

### lnurl-channel

* [LNBIG](https://lnbig.com/) &ndash; Get free inbound channels on your mobile wallet from this mysterious entity.
* [Bitrefill's Thor](https://www.bitrefill.com/thor) &ndash; Buy a reliable incoming channel from this super liquid node, or get a turbo channel from which you can spend immediately.


Wallets
------------------------------------------------------------------------

_Some wallets that support **lnurl**_.

* [Bitcoin Lightning Wallet](https://lightning-wallet.com/) &ndash; BLW supports _lnurl-pay_, _lnurl-withdraw_, _lnurl-auth_ and  _lnurl-channel_.
* [@lntxbot](https://t.me/lntxbot) &ndash; supports _lnurl-pay_, _lnurl-withdraw_ and _lnurl-auth_.
* [Zeus](https://github.com/ZeusLN/zeus) &ndash; supports _lnurl-pay_ and _lnurl-withdraw_.
* [Shockwallet](https://shockwallet.app/#features) &ndash; supports _lnurl-pay_, _lnurl-withdraw_ and _lnurl-channel_.
* [Breez](https://breez.technology/) &ndash; supports _lnurl-channel_ and _lnurl-withdraw_.
* [BlueWallet](https://bluewallet.io/) &ndash; supports _lnurl-withdraw_.
* [Zap](https://www.zaphq.io/) &ndash; supports _lnurl-withdraw_.
* [Wallet of Satoshi](https://www.walletofsatoshi.com/) &ndash; supports _lnurl-withdraw_ and _lnurl-channel_.
* [c-lightning](https://github.com/ElementsProject/lightning/) with the [`lnurl` plugin](https://github.com/fiatjaf/lightningd-gjson-rpc/tree/master/cmd/lnurl) &ndash; RPC methods that perform the _lnurl-channel_, _lnurl-auth_ and _lnurl-withdraw_.

Libraries
------------------------------------------------------------------------

_Integrate **lnurl** in projects and services_.

* [go-lnurl](https://github.com/fiatjaf/go-lnurl) &ndash; **lnurl** helper structs, encode/decode, verify signatures, misc helpers.
* [lnurl-node](https://github.com/chill117/lnurl-node) &ndash; CLI tool and **lnurl** server in Node.js.
* [passport-lnurl-auth](https://github.com/chill117/passport-lnurl-auth) &ndash; Passport strategy that uses lnurl-auth
* [js-lnurl](https://github.com/fiatjaf/js-lnurl) &ndash; Tools for adding **lnurl** support in a JavaScript wallet.
* [php-lnurl](https://github.com/tkijewski/php-lnurl) &ndash; Easy PHP encoding and decoding of bech32 **lnurl**s.
* [python-lnurl](https://github.com/python-ln/lnurl) &ndash; Tools for dealing with **lnurl** in Python.
* [lnurl-rust](https://github.com/edouardparis/rust-lnurl) &ndash; Rust helpers for **lnurl**.


Tools
------------------------------------------------------------------------

_Stuff for using and playing with **lnurl**_.

* [lnurl codec](https://lnurl.bigsun.xyz/codec) &ndash; Easily encode and decode **lnurls**.
* [SeedAuth](https://seedauth.etleneum.com/) &ndash; A service that allows you to login to **lnurl-auth** services using just a username and password.
* [lnurl playground](https://lnurl.bigsun.xyz/) &ndash; A simple tool that allows you to try and see how your wallet interacts with an **lnurl** server.

Contribute
------------------------------------------------------------------------

Please contribute! Open an issue or a PR and we’ll discuss it or merge it. If
you’re opening a PR, please ensure all formatting is ok (if you’re in a hurry
just open an issue).


License
------------------------------------------------------------------------

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
