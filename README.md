![vapaee-telos-dex-shadow.png](./images/vapaee-telos-dex-shadow.png)

Vapaée - worker proposal 2
--------------------------

# Financing the development of DEX Vapaee.io and the production of its review video.

## Intro

Hello, everybody. Mi name is [Viterbo](https://steemit.com/introduceyourself/@viterbo/i-am-an-entrepreneur-and-i-m-going-to-build-a-dapp-over-eos) and if you don't know me already from the Telegram Telos groups I'm responsible for the [Cards & Tokens](http://cardsandtokens.com) platform that will run on Telos, and also I'm the creator of [Vapaée.io](https://vapaee.io) Telos first DEX already deployed on mainnet (in alpha version with fake tokens to test without risks).    
Please [login with scatter](https://vapaee.io/exchange/account/) and try it.

This [Vapaée.io](https://vapaee.io) DEX was planned as a submodule of the [Cards & Tokens](http://cardsandtokens.com) platform (that covers the "Tokens" part) and bring a lot of token services to other Dapps and users (including token exchange). Although it had low priority, [something made me change my mind](https://steemit.com/telos/@viterbo/vapaee-first-telos-dex) and I decide to start on this module.

## Budget Summary

This worker proposal is for **2 cycles of 200K TLOS each**. Only 20K of the first cycle will be sold in the market, the rest will be hold as personal future investment and, hopefully, will never be sold, but used as currency.

- Cycle 1 - 200K TLOS
  - Develoment of the **Premium** version of [Vapaée.io](https://vapaee.io) (my personal revenue)
  - Plus one review video of [Cards & Tokens](http://cardsandtokens.com), [Vapaée.io](https://vapaee.io) and Telos blockchain by [Louis Thomas](https://www.youtube.com/channel/UCpceefaJ9vs4RYUTsO9Y3FA) from UK.

- Cycle 2 - 200K TLOS
  - Develoment of the **Deluxe** version of [Vapaée.io](https://vapaee.io) (also personal revenue)

## Versions

I separated the hole development of the [Vapaée.io](https://vapaee.io) DEX in three different parts: **Basic**, **Premium** and **Deluxe**. The **Basic** version is the one that is already up and running on Telos MainNet (although it's missing a couple of features). This version is my way to say **THANK YOU** and return the value that you already had gave to me with the approval of my last WP [(number #7)](https://chainspector.io/dashboard/working-proposals/7). So I will finish this **Basic** version independently if this current WP is approved or not.    
You will get a finished DEX, I think I owe you that.

For the **Premium** and **Deluxe** versions you will be able to choose if you want them separately. If you approve this WP, you will get the next version upgrade. If not, I will go back to work on the "Cards" part of the [Cards & Tokens](http://cardsandtokens.com) platform.

- **Basic** (v1.x.x)     
  This one is already deployed and ready to test. It only requires 2 more important features such as trading history chart and sqrl wallet support. The rest is already up and running on Telos mainnet. The completion of this version does not depend on the approval of this worker proposal. I will finish it because we need it.
  This verison includes:
  - Currently there is a testing period when you can use fake Tokens to try this DEX without using real ones.
  - All standar tokens on Telos network will be listed (with the exception of FLAME), and no restriction will exist to list new ones.
  - Users already can create trade-orders or match existing ones to trade tokens for TLOS, p2p with another Telos user using **vapaeetokens** contract as DEX.
  - An appropriate chart will be implemented to display graphically the trade transaction history of any token.
  - Actually only Scatter is supported. Sqrl support will be added.

- **Premium** (v2.x.x)     
  This one is a refined and more polished version than the previous one, which includes basicaly a lot of work in the presentation layer or the front-end, that in this case would be the website.
  This version includes:
  - Responsive Design: currently the trade page has a lot of components on stage at the same time, and they all do not fit when the screen is lower than full-HD. I will create a better and more responsive design for this page (and the others pages too). In fact, I will make it work as a [PWA (Progresive Web Application)](https://www.youtube.com/watch?v=fuhAmUpEEHA) to fit on cell phone screens.
  - Add more information about the token movement of the last 24h (like min price, max price, transactions count).
  - Display all prices of all tokens in your prefered currency. You will have a combo box to choose you preferred currency and all the prices will be expressed in that currency. The list will include TLOS, EOS, BTC, ETH, USD, EUR, etc.
  - Each token should have its own page with all its info (title, description, links, video, contacts, transaction history, top N holders, etc)
  - Display feedback on DEX activity on the home page (how many users, transactions per day, deposits, withdraws, earnings, etc)
----- trabajo en coordinación con thomas para hacer el video

- **Deluxe** (v3.x.x)     
  This final version is really a combination of more UI refination plus adding new token services and DEX features. This will require lots of modifications on both, the smart contract and the website. If you approve this cycle of this WP we will have a **deluxe DEX**.     
  This version includes:
  - Token Auction: users will be able to put any amount of any token to be auctioned and get paid in a specific currency and have all tokens sold in a specific time. This allows you to automatically convert any amount of token X to the best amount of token Y in a specific period of time, having the smart contract selling little amounts of X periodically in your name to the best Y offer each time.
  - Vapaee Token / Passive Income: as you can imagine there's a very little fee that both parts of the deal have to pay on each transaction and that determines the earnings of the contract. I will create a Vapaée Token that can be staked for passive income funded by this earnings.
  - Free to join: The contract **vapaeetokens** already admits any one to create and/or register any standar token on Telos but the website has no interface for that. I will create a very intuitive page to create a new token on the **vapaeetoken** smart contract, or register an existing one along with all the token info. All registered tokens will get listed in the exchange automatically.
  - Timezone: currently the the time displayed for the transactions is the blockchain datetime. I will implement a easy wey to set the user's local timezone to display the datetimes in local time. In fact, I will make the website to detect and set automatically the local timezone for the user.
  - Trade any pair: something that I came accros when I developped the first version is that you can see a sell-order (you have X and wants to sell it for Y) as an inverse of a buy-order (where you have X and wants user X as payment for Y). The smart contract already modelates the trading market this way. Now I can implement a button, that if you press it, you will invert the XXX / YYY trading pair for YYY / XXX, and all the buy-orders will convert to sell-orders and the oppositewill happend with the sell-orders.     
  At this time we may have IBC running and we may have an EOS representative token on Telos network that can be added to this DEX. Then you will be able to see the TLOS being priced in EOS and vice versa in Vapaée.io.
  - Contract Events: To be a really useful tool, all dapps owning any token being traded in this DEX should be able to 'react' when any event involving its token occurs. eg: deposits, withdraws, order, transaciton, etc. So the **vapaeetokens** smart contract should be modified to send a signal to the dapp contract owning the token involved in the event.      
  This will allow, for example, the current Telos voting system to update your "voting power" taking in account your deposits and earnings in the DEX, without you to actually having to withdraw your TLOS.
  - Skins: There will be a few different skins to choose.

## Roadmap
- incluye fechas
20 mayo entrego el Basic
10 junio entrego el Premium
08 julio entrego el Delux
