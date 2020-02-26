+++
title = "Will Reeves and Bitcoin Socratic Seminar #7"
template = "post.html"
[extra]
meetup_id = "268296785"
+++

### Agenda

7:00 Networking  
7:15 Will Reeves  
7:45 Socratic Seminar  
8:45 Clean Up  

### Sponsors

[River Financial](https://www.river.com) - The best place to buy, sell, and use Bitcoin for the long-term investor.  

[Square Crypto](https://twitter.com/sqcrypto) - Supporting open-source Bitcoin development.

[Indie Desk](https://www.indiedesk.com/) - The first coworking space in LA. They offer $275 / per month 24/7 access, 
month to month, no contract. ([on Twitter](https://twitter.com/indiedesk))

### Location

[Indie Desk  
333 S Grand Ave #3310  
Los Angeles, CA  ](https://www.google.com/maps/search/?api=1&query=34.052933%2C-118.251880)

#### Parking  

Parking can be difficult in DTLA. If you park in the parking structure at 330 S Hope Street, Indie Desk will give you a $10 parking voucher after 5pm.

### Guest Speaker

Will Reeves is the CEO of Fold. His previous work experience includes serving as a Venture Lead and Product Manager at 
Beyond, a product design studio that worked with Google Store, Google Cloud, and Marketo.

### Guest Links

[Will Reeves on Twitter](https://twitter.com/wlrvs)  
[Fold App on Twitter](https://twitter.com/fold_app)

### Socratic Seminar

#### News

- [Onboarding to Bitcoin Core](https://medium.com/@amitiu/onboarding-to-bitcoin-core-7c1a83b20365)
- [Lightning Labs raises series A ($10MM)](https://docs.google.com/document/d/1kQy8No_w8Kdtmnw52TR5PY_LiUZ_ZVEWCf2vuxazCnk/edit)
- [Open Node Apple Pay integration](https://www.opennode.com/blog/opennode-apple-pay-debit-cards-and-more/)
- [Bitcoin Retirement Series Part 1: Bitcoin Investing In Retirement Plans (US Version)](https://medium.com/@hhua/bitcoin-retirement-series-part-1-bitcoin-investing-in-retirement-plans-us-version-2d65c5fffe31)
- [Lightning Loop Beta](https://blog.lightning.engineering/announcement/2020/02/05/loop-beta.html)

#### Research

- [Congestion Attacks in Payment Channel Networks](https://medium.com/@ayelem02/congestion-attacks-in-payment-channel-networks-b7ac37208389
)
  - Lightning nodes pay themselves. They select the longest route to tie up as much liquidity as possible by not accepting the payment. They were able to tie up the liquidity in the network with less than 0.5 BTC.
    - You can also attack a single hub’s by tying up their liquidity (much smaller attack) and routing back to yourself through the same hub. 
  - Lnd recently changed cltv delta default from 144 to 40. Max cltv is 2016 (2 weeks). Can add more hops with 40 delta as a LN payment can go up to the max cltv. 
  - Mitigation: 
    - Higher routing fees to increase cost of attack.
    - Enforcing fast HTLC resolution. If a node doesn’t forward secret fast, penalize them by closing the channel. 
- [Upgradeable Channel Commitments](https://twitter.com/ecurrencyhodler/status/1232379435849961472
)

#### Statistics

- [SegWit Usage](https://segwit.space/)

#### Bitcoin PRs <font color="#FF9900">₿</font>

- Adding Rust Lightning to Bitcoin Core
  - <https://github.com/bitcoin/bitcoin/pull/18179>
    - Concern about the added work to maintain Core.
    - Increased vulnerabilities to Core.
    - Advantage is long-term viability on mobile (android and iPhone). 
      - Android and iPhone forks processes but the phone itself manages each process. So bitcoind and c-lightning is run separately. If Bitcoind starts taking up a ton of memory, the phone will kill it.
- [GUI: PSBT save and load](https://github.com/bitcoin/bitcoin/pull/17509)

#### Lightning PRs ⚡

- [c-lightning: Bitcoin backend generalization](https://github.com/ElementsProject/lightning/pull/3488)
- [lnd: Adds `fundall` flag to `openchannel`](https://github.com/lightningnetwork/lnd/pull/4029)
- [lnd: Intercept forward htlc [WIP] #4018](https://github.com/lightningnetwork/lnd/pull/4018)

