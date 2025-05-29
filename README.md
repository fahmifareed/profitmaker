# Profitmaker – crypto currency trading terminal
(previously named "Kupi-terminal")

[![License](https://img.shields.io/badge/licence-GPL--2.0-blue.svg)](https://raw.githubusercontent.com/kupi-network/kupi-terminal/master/LICENSE) [![Discord](https://img.shields.io/discord/430374279343898624.svg?color=4D64BA&label=chat%20on%20discord)](https://discord.gg/2PtuMAg) ![Version](https://img.shields.io/badge/express_server-0.6.0-blue.svg) ![Version](https://img.shields.io/badge/react_client-0.6.0-blue.svg) ![Version](https://img.shields.io/badge/vue_client-0.3.0-blue.svg) [![codecov](https://codecov.io/gh/kupi-network/kupi-terminal/branch/master/graph/badge.svg)](https://codecov.io/gh/kupi-network/kupi-terminal) [![Codacy Badge](https://api.codacy.com/project/badge/Grade/a0b7b6b595fd4b3db3818fed7665b1bf)](https://www.codacy.com/app/suenot/kupi-terminal?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=kupi-network/kupi-terminal&amp;utm_campaign=Badge_Grade) [![Build Status](https://travis-ci.org/kupi-network/kupi-terminal.svg?branch=master)](https://travis-ci.org/kupi-network/kupi-terminal) [![Open in CodeSandbox](https://img.shields.io/badge/Open%20in-CodeSandbox-blue?style=flat-square&logo=codesandbox)](https://githubbox.com/suenot/kupi-terminal) [![Run on Repl.it](https://repl.it/badge/github/suenot/kupi-terminal)](https://repl.it/github/suenot/kupi-terminal) [![Mutable.ai documentation](https://img.shields.io/badge/mutable%20ai%20documentation-blue.svg)](https://wiki.mutable.ai/suenot/profitmaker)

Open source, customized, extendable trading terminal that supports 130+
crypto exchanges.

# Important announcement
I started the new full rewrite of the project. It will be more stable, more secure and more flexible. You can check it [v2.0.0-dev](https://github.com/suenot/profitmaker/tree/v2.0.0-dev) github branch. I am going to finish stable version in 2024. I will be happy to see you there. Welcome to discuss details in [discord](https://discord.com/invite/2PtuMAg).

I announced two version:
- Open source crypto terminal, and server part for custom metrcs/analytics: [https://profitmaker.cc/](https://profitmaker.cc/)
- Commercial project with crypto tokens as utility and buyback token: [https://marketmaker.cc/](https://marketmaker.cc/)

# Description for v.1.0.0


[![Demo](https://github.com/kupi-network/kupi-terminal/blob/master/demo.png?raw=true)](https://profitmaker-react-git-master-suenot.vercel.app/)

## [Demo](#demo) ·[How it works](#how-it-works) · [Features](#features) · [Technologies](#technologies) · [Warning](#warning) · [Quick start](#quick-start) · [Supported exchange markets](https://github.com/kupi-network/kupi-terminal/blob/master/MARKETS.md) · [React vs Vue](https://github.com/kupi-network/kupi-terminal/blob/master/REACT_VS_VUE.md) · [API](#api) · [Vocabulary](https://github.com/kupi-network/kupi-terminal/blob/master/VOCABULARY.md) · [Privacy policy](https://github.com/kupi-network/kupi-terminal/blob/master/PRIVACY_POLICY.md) · [Terms of use](https://github.com/kupi-network/kupi-terminal/blob/master/TERMS_OF_USE.md) · [Changelog](https://github.com/kupi-network/kupi-terminal/blob/master/CHANGELOG.md) · [Roadmap](https://github.com/kupi-network/kupi-terminal/blob/master/ROADMAP.md) · [Support us](#support-us) · [Team](#team) · [Contact us](#contact-us)

## Demo

React version: [https://react.profitmaker.app/](https://react.profitmaker.app/)

Vue version: [https://vue.profitmaker.app/](https://vue.profitmaker.app/)

## Project repositories:

- [React version](https://github.com/suenot/profitmaker-react)

- [Vue version](https://github.com/suenot/profitmaker-vue)

- [Express server](https://github.com/suenot/profitmaker-express)

- [Kupi-network API](https://github.com/suenot/kupi-terminal-api) (deprecated)


## How it works

![Demo](https://github.com/kupi-network/kupi-terminal/blob/master/structure.png?raw=true)


## Features

-   Open source
-   Your api keys stay on your machine, no need to send them anywhere
-   Customized with dashboards and widgets
-   Extendable with users modules
-   Free realtime API (Timeseries will be in immediate future)
-   Framework for creating trading bots

## Technologies

-   [React](https://github.com/facebook/react),
-   [react-grid-layout](https://github.com/STRML/react-grid-layout),
-   [material-ui](https://github.com/mui-org/material-ui)
-   [Vue](https://github.com/vuejs/vue),
-   [vue-grid-layout](https://github.com/jbaysolutions/vue-grid-layout),
-   [element](https://github.com/ElemeFE/element),
-   [movue](https://github.com/nighca/movue),
-   [v-charts](https://github.com/ElemeFE/v-charts)
-   [Mobx](https://github.com/mobxjs/mobx)
-   [Express](https://github.com/expressjs/express)
-   [Mongo](https://github.com/mongodb/mongo)
-   [CCXT](https://github.com/ccxt/ccxt)
-   [Flaticon](https://www.flaticon.com/)
-   [Echarts](https://github.com/apache/incubator-echarts)

## WARNING

THE SOFTWARE UNDER HEAVY DEVELOPMENT. PROVIDED "AS IS", WITHOUT WARRANTY
OF ANY KIND.

## Quick start

### [TL;DR](https://github.com/kupi-network/kupi-terminal/blob/master/INSTALL_TL_DR.md)

### [Install with docker](https://github.com/kupi-network/kupi-terminal/blob/master/INSTALL_WITH_DOCKER.md)

### [Install manually](https://github.com/kupi-network/kupi-terminal/blob/master/INSTALL_MANUALLY.md)

If you had any problems with installing we can help in [voice/text
Discord chat](https://discord.gg/2PtuMAg)

## API

### Server api

Server: [https://kupi.network/api](https://kupi.network/api) (secure) or
[http://kupi.network/api](http://kupi.network/api) (faster)

Swagger: [try api
online](https://app.swaggerhub.com/apis-docs/soloviofff/kupi.network/1.0.0)

```bash
/stocks
/binance/pairs
/binance/orders/ETH_BTC
/binance/trades/ETH_BTC
/binance/candles/ETH_BTC/1m # timeframes: ['1m', '3m', '5m', '15m', '30m', '1H', '2H', '4H', '6H', '12H', 'D', 'W', 'M']
/coinmarketcap
```

#### terminal server api:

```http://localhost:8051/```

```bash
/balance
/openOrders/:stock/:pair
/myTrades/:stock/:pair
/cancelOrder
/createOrder
```

## Team

-   Eugen Soloviov [github](https://github.com/suenot) [telegram](https://t.me/suenot) [facebook](https://www.facebook.com/soloviov.evgeniy) - maintainer
-   Sergey Soloviov [github](https://github.com/soloviofff) - contributor
-   Igor Korotin [github](https://github.com/markolofsen) - contributor

## Contact Us

For business inquiries contact with [Eugen Soloviov](https://t.me/suenot)

## Sponsored Promotion

Want this place? Contact with [Eugen Soloviov](https://t.me/suenot)

![Placehodler](https://user-images.githubusercontent.com/1707/48204972-43569e00-e37c-11e8-9cf3-b86e3dc19ee9.png)

## Licensing
Profitmaker is licensed under the MIT License with Commons Clause. This means you can:

✅ Allowed:
- Use Profitmaker for any purpose (personal, commercial, academic)
- Modify the code
- Distribute copies
- Create and sell products built using Profitmaker

❌ Not Allowed:
- Sell Profitmaker itself
- Offer Profitmaker as a hosted service
- Create competing products based on Profitmaker

See the [LICENSE](./LICENSE) file for the complete license text. For commercial licensing or questions about permitted use, you can always contact Eugen Soloviov via [Telegram](https://t.me/suenot) or by [email](mailto:suenot@gmail.com).

