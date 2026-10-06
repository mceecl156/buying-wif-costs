# buy dogwifhat: going from sign-up to holding WIF in your own wallet, and what the fees actually cost

Most "how to buy dogwifhat" pages stop at the click. Sign up, deposit, hit buy. That's the easy 80%, and it's also where the money leaks out: a market order that didn't need to be a market order, a withdrawal sent on the wrong chain, a welcome bonus that was never going to pay out because the task ladder requires turnover you're not going to generate.

Here's the full path, including the boring parts that decide whether buying WIF costs you 0.1% or something closer to 3%.

## What you're actually buying when you buy WIF

dogwifhat is a Solana meme coin built around a photo of a Shiba Inu in a pink knitted hat. It launched at the end of 2023 and has a fixed supply of roughly 998.9 million tokens — no team allocation, no founder vesting, no staking rewards, no governance votes. If you're holding WIF, you're holding a tradable community asset, not a claim on cash flows.

Price-wise, context matters more than any headline number. WIF peaked at $4.83 in March 2024 and, when I last checked live quotes, was trading around $0.20 — down more than 95% from that high. Daily moves of 5–12% are routine; the trend over the past year has been firmly down. Anyone quoting you a WIF price in an article without a timestamp is quoting history.

The other thing to know: WIF exists as an SPL token on Solana, and its contract address is `EKpQGSJtjMFqKZ9KQanSqYXRcF8fBopzLHYxdM65zcjm`. Meme coins spawn copycats with identical tickers, so verify that address against Solscan or the project's official site before you ever send funds to a wallet address you found somewhere.

## Centralized exchange or a Solana wallet swap?

There are two realistic routes to owning WIF, and they break differently.

**Buying on an exchange** means you create an account, pass identity verification, fund it, and trade a WIF/USDT pair. You don't need a wallet, you don't need SOL for gas, and you can fund with a card or a bank transfer in some regions. The trade-off is that the coins sit in the exchange's custody until you withdraw, and you've handed over your ID.

**Swapping in a Solana wallet** (Phantom, Solflare, and similar) means no KYC and immediate self-custody. You need SOL in the wallet to pay fees, you're exposed to whatever liquidity sits in the pool you're routed through, and slippage on a large order can easily cost more than any trading fee.

For a first purchase, the exchange route is simpler and the fee is published in advance. Gate, the platform this walkthrough uses, lists more than 5,000 cryptocurrencies and carries WIF on a spot WIF/USDT pair, plus a WIF/USDT perpetual contract and margin trading if you want leverage you probably shouldn't want on a coin that fell 95% from its peak.

## Step 1: Create the account

You need an email address or phone number and a password. Nothing exotic. One detail worth knowing: the link you sign up through determines whether you're attached to a referral code, and new-user reward eligibility is typically tied to that. If you're going to open an account anyway, use the referral rather than typing the address manually later.

👉 [Create a Gate account and check the current new-user reward pool](https://bit.ly/GateVIP)

Gate also runs a referral programme that pays 40% commission on the trading fees your invitees generate, which tells you something about how much of the exchange's revenue is fee income rather than anything else.

## Step 2: Finish identity verification

Most features — deposits above trivial amounts, spot trading, withdrawals — sit behind KYC. For Gate that means ID documents plus a face-verification step. It takes a few minutes to submit, and approval is usually quick, but it isn't instant and it isn't optional.

The reward tasks in the Rewards Hub are gated on identity verification too, so verifying early keeps the bonuses available rather than lapsing. Some regions are restricted from promotions or from parts of the service entirely, and the US, UK and China are excluded from several of the welcome offers. Check the terms attached to whatever campaign page you land on rather than assuming eligibility.

## Step 3: Fund the account

Crypto deposits on Gate are free — the platform doesn't charge to receive coins. What you pay instead is the network fee on the sending side, and that varies wildly by chain.

If you're depositing USDT, for example, an Ethereum (ERC-20) transfer needs a minimum deposit of 0.01 USDT but costs whatever Ethereum gas costs at that moment. A Solana or TRON transfer of the same amount usually costs a fraction of that. The deposit minimum and network status are published per coin and per network on Gate's fee page, and the network-status field matters more than the fee column: some networks get flagged as deposit-disabled, and sending to a disabled network is how people end up in a support queue.

Card purchases and some fiat on-ramps skip the wallet step entirely, but check the spread before you decide it's convenient. Buying crypto with a card typically prices you several percentage points worse than the spot market, which dwarfs the 0.1% trading fee you were trying to optimise.

## Step 4: Buy WIF

On Gate, buying WIF means trading the WIF/USDT spot pair. Three ways to do it, in descending order of cost:

1. **Market order.** Fills immediately against whatever is resting in the book. You pay the taker fee and you accept the price you get.
2. **Limit order.** You set the price. If it fills without crossing the spread, you're a maker — but here's the catch on Gate: maker and taker fees are *identical* (0.10% each) from VIP 0 through VIP 3. Resting an order buys you price control, not a discount, until you reach VIP 4.
3. **Convert / buy-with-card.** Fastest and worst-priced. The spread is the real cost, and no fee tier touches it.

A worked example, since the numbers are small enough that people ignore them: a $500 market buy of WIF at VIP 0 costs $0.50 in fees. With GT deduction enabled, it costs $0.45. That's not nothing, but note how small it is compared with a card purchase spread of a few percent — which is $15 on the same $500. Fix the expensive habit before optimising for basis points.

## Step 5: Get the WIF off the exchange, or don't

Withdrawing to a self-custody Solana wallet is one transaction. Pick "Solana" as the network — not Ethereum, not BEP-20 — paste the wallet address, and confirm. WIF sent over the wrong network is generally gone.

Gate's withdrawal fees are priced per coin and per network, not as a percentage, and each route has a minimum. USDT on Ethereum, as a reference point, has a minimum withdrawal of 1 USDT. Check your specific coin and network on the fee page before you send, and start with a small test transfer if the amount is large enough that losing it would sting.

The reason to withdraw at all is custody. The reason not to bother is that you'll pay a withdrawal fee and take on the risk of losing a seed phrase. If you're planning to sell in a week, leaving it on the exchange is defensible. If you're holding for years, self-custody is the point of buying a memecoin in the first place.

## What buying and selling WIF costs on Gate: every fee tier

Gate runs 17 spot tiers, VIP 0 through VIP 16. Standard rates and the lower rate you get for paying fees in GT are published separately. Your tier is set by whichever is higher: your 30-day trading volume or your 14-day average GT holding, with futures volume counted at 40% and options and USD1 contracts at 20% when the platform works out your total.

| VIP tier | 30-day spot volume required | Standard maker / taker | Rate with GT deduction | 24h withdrawal limit | Open an account |
| --- | --- | --- | --- | --- | --- |
| VIP 0 | $0 | 0.10% / 0.10% | 0.09% / 0.09% | $3,000,000 | [Sign up](https://bit.ly/GateVIP) |
| VIP 1 | $60,000 | 0.099% / 0.099% | 0.089% / 0.089% | $3,000,000 | [Sign up](https://bit.ly/GateVIP) |
| VIP 2 | $120,000 | 0.098% / 0.098% | 0.088% / 0.088% | $3,000,000 | [Sign up](https://bit.ly/GateVIP) |
| VIP 3 | $240,000 | 0.097% / 0.097% | 0.087% / 0.087% | $3,000,000 | [Sign up](https://bit.ly/GateVIP) |
| VIP 4 | $500,000 | 0.095% / 0.096% | 0.086% / 0.086% | $3,000,000 | [Sign up](https://bit.ly/GateVIP) |
| VIP 5 | $1,000,000 | 0.09% / 0.095% | 0.081% / 0.085% | $5,000,000 | [Sign up](https://bit.ly/GateVIP) |
| VIP 6 | $3,000,000 | 0.085% / 0.09% | 0.076% / 0.081% | $5,000,000 | [Sign up](https://bit.ly/GateVIP) |
| VIP 7 | $8,000,000 | 0.08% / 0.085% | 0.07% / 0.076% | $5,000,000 | [Sign up](https://bit.ly/GateVIP) |
| VIP 8 | $20,000,000 | 0.075% / 0.08% | 0.06% / 0.072% | $5,000,000 | [Sign up](https://bit.ly/GateVIP) |
| VIP 9 | $50,000,000 | 0.07% / 0.075% | 0.05% / 0.068% | $8,000,000 | [Sign up](https://bit.ly/GateVIP) |
| VIP 10 | $100,000,000 | 0.04% / 0.058% | 0.04% / 0.058% | $8,000,000 | [Sign up](https://bit.ly/GateVIP) |
| VIP 11 | $120,000,000 | 0.03% / 0.045% | 0.03% / 0.045% | $8,000,000 | [Sign up](https://bit.ly/GateVIP) |
| VIP 12 | $240,000,000 | 0.02% / 0.037% | 0.02% / 0.037% | $10,000,000 | [Sign up](https://bit.ly/GateVIP) |
| VIP 13 | $440,000,000 | 0.01% / 0.03% | 0.01% / 0.03% | $20,000,000 | [Sign up](https://bit.ly/GateVIP) |
| VIP 14 | $800,000,000 | 0.008% / 0.023% | 0.008% / 0.023% | $30,000,000 | [Sign up](https://bit.ly/GateVIP) |
| VIP 15 | $1,600,000,000 | 0% / 0.02% | 0% / 0.02% | $40,000,000 | [Sign up](https://bit.ly/GateVIP) |
| VIP 16 | $3,000,000,000 | 0% / 0.0175% | 0% / 0.0175% | $50,000,000 | [Sign up](https://bit.ly/GateVIP) |

A few things in that table are worth reading twice.

GT deduction stops helping at VIP 10. From VIP 0 to VIP 9, paying fees in GateToken knocks about a tenth off — 0.09% instead of 0.10%. At VIP 10 and above, both columns are the same number, so GT buys you nothing at the tiers where fees actually matter. It still helps a retail account, which is the only tier most WIF buyers will ever see.

Zero maker fees only arrive at VIP 15. If you like working limit orders and you're imagining a maker rebate, you need $1.6 billion of 30-day volume or a very large GT position. For everyone else, a resting limit order and a market order cost the same.

GT deduction can silently revert. Once enabled, Gate spends your GT first and falls back to the standard VIP rate the moment the balance runs dry. A session you costed out at 0.09% finishes at 0.10% if you run out mid-way. Keep a few dollars of GT parked in the account, or don't enable it and skip the mental overhead.

Futures are separate. The WIF/USDT perpetual sits in Gate's "Group B" contract category for taker pricing, and the base rate at VIP 0 is 0.020% maker against 0.050% taker. Funding payments are billed on top and are not small on a volatile meme coin.

Alpha trading costs 0.8% at every tier. Flat, no discount, eight times the VIP 0 spot rate. If you're routing a WIF trade through that venue instead of the spot book, you're paying up for it.

## The welcome bonus, minus the marketing

Gate's Rewards Hub advertises "up to 10,000+ USDT" for new accounts, and that headline is doing a lot of work. The actual structure is a starter bundle plus a laddered challenge.

The starter bundle is a set of tasks: register and log in, complete identity verification (including face verification), make a first deposit, place a first spot or futures trade, and download the app. The regional versions of the page price that bundle differently — the copies I could read showed roughly 118 to 135 USDT in value, delivered as position vouchers and coupons rather than withdrawable cash. Position vouchers typically carry a turnover condition before they unlock; recurring new-user campaigns have paired a 50 USDT position voucher with an "unlock after you trade 5,000 USDT" rule.

The larger numbers come from the advanced trading task, which pairs a net-deposit threshold with cumulative spot or futures volume and releases rewards in stages — one stage at a few tens of USDT, another worth a short VIP 5 pass plus a few hundred USDT, then 2,000, 5,000 and beyond. Those tiers require turning over multiples of your own deposit. If your plan is to buy a few hundred dollars of WIF and hold it, you'll collect the small starter rewards and nothing else, and that's fine — just don't size your trading around a bonus ladder.

👉 [See the current new-user tasks and reward terms before you deposit](https://bit.ly/GateVIP)

## The mistakes that actually cost money

**Sending WIF on the wrong network.** Solana, always. This is the single most expensive error in the list.

**Buying a fake WIF.** Check the contract address against a Solscan page or the project's own site. There is no second dogwifhat.

**Using a card because it's faster.** Several percent of spread versus 0.10% of fee. Do the comparison once and it stops being tempting.

**Treating a 95% drawdown as a discount.** WIF is down more than 95% from March 2024. That's not automatically a buying opportunity; it's a description of how meme-coin cycles unwind. Size the position so a full loss is survivable, because that outcome is on the table.

**Leaving the rewards tasks half-finished.** Most require full completion before anything is paid, and they're time-limited. Partial progress pays zero.

## Quick answers

**Do I need KYC to buy dogwifhat?** On a centralized exchange like Gate, yes for deposits and trading. Swapping in a self-custody Solana wallet doesn't require it, but you'll need SOL for fees.

**What's the cheapest way to buy WIF?** Deposit crypto, place a limit order on the WIF/USDT spot pair, and pay the 0.10% VIP 0 taker fee or the same rate as a maker — with GT deduction enabled it drops to 0.09%.

**Can I buy WIF with a credit card?** Yes, through the card on-ramp, but expect a materially worse effective price than the spot market.

**Does Gate list WIF futures?** Yes, a WIF/USDT perpetual plus margin, with VIP 0 pricing at 0.020% maker and 0.050% taker before funding payments.

**How much is dogwifhat worth right now?** It was trading near $0.20 when I checked, against a $4.83 all-time high in March 2024. Meme-coin quotes go stale in minutes, so check the live chart rather than any article.

## The short version

Open the account through the referral link so your new-user rewards attach to it, verify your identity early, deposit crypto rather than paying card spread, buy WIF on the WIF/USDT spot pair with a limit order, and pay attention to the network when you withdraw. The trading fee at VIP 0 is 0.10%, or 0.09% if you hold a little GT — small enough that it isn't the thing that decides whether this trade was a good idea. The position size is.

👉 [Start with a Gate account and check the current WIF pair and welcome tasks](https://bit.ly/GateVIP)
