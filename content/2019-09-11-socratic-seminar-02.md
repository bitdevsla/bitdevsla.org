+++
title = "Steve Myers and Bitcoin Socratic Seminar #2"
template = "post.html"
[extra]
meetup_id = "264300269"
+++

### Agenda

6pm- Meet and Greet  
6:15pm- Speaker Presentation  
6:45pm- Socratic Seminar where we review various Bitcoin topics  
7:45pm- Clean up and leave by 8pm.  
8:00- Social at [7 Grand Lounge](https://m.yelp.com/biz/seven-grand-los-angeles).  

### Location

WeWork Fine Arts will be hosting the event at the following address.

811 W. 7th Street  
Los Angeles, CA 90017  

### Parking

FigAt7th • 945 W. 8th Street  
Validated if parking on L1, L2, L3  
1 hr for $1, 2 hrs for $2.50, 3 hrs for $4  
5 minute walking distance.  

or

Target  
943 W 8th St, Los Angeles, CA 90017  
Validated for 3 hours if you buy something at Target.  

### Guest Speaker

Steve Myers is co-founder of Bytabit AB and a senior software engineer at Disney Studios.

Steve will talk about the genesis and development of the Bytabit project, a new mobile peer to peer non-custodial bitcoin exchange.

### Socratic Seminar

Inspired by Bitdevs NY, this is an event for those interested in discussing and participating in the research and development of Bitcoin and related protocols. The Socratic Seminar events are formatted to foster debate, information sharing, and lively discussion.

Discussion topics from a variety of sources are collated by meetup members in the weeks preceding the events. We investigate pull requests in the Bitcoin Core, lnd, and other relevant repositories; we study network statistics, research papers, technical blog posts and other interesting content. To complete the meeting, members present open source projects, companies, research and other relevant materials. A feedback and Q&A section follow.

Please contact the organizers if you'd like to present at the Socratic event or have a recommended topic for discussion: ecurrencyhodler at gmail.

A post will be made prior to the event which outlines discussion topics. Archives of discussion topics and presentations can be found in the event descriptions of past meetups. The discussion portion of the event is NEVER recorded. It is recommended that you have a firm grasp of the basics of Bitcoin in order to extract the most value from our Socratic events.

#### Bitcoin News

  - [Bakkt cleared to launch Bitcoin futures](https://medium.com/bakkt-blog/cleared-to-launch-8dfc3e6f9ed0)
  - [@bitcoin switches to BTC instead of BCH](https://www.reddit.com/r/btc/comments/csfa1m/there_is_something_going_on_with_bitcoin_twitter/)
  - [Matt Corallo joins SqCrypto](https://twitter.com/TheBlueMatt/status/1163852530142654464)
  - [Plug-in Manager for C-lightning.](https://twitter.com/Snyke/status/1163875781833084929)
  - [Mastering Lightning in development!](https://twitter.com/renepickhardt/status/1166750972665679872?s=20)
  - [Simple GUI for musig wallet.](https://twitter.com/_JustinMoon_/status/1166905722325667841?s=20)
  - [Avoiding gossip Spam](https://lists.linuxfoundation.org/pipermail/lightning-dev/2019-September/002134.html)
  - [Lightning Vulnerability](https://lists.linuxfoundation.org/pipermail/lightning-dev/2019-August/002130.html)
  - [Hermit: sharded, air-gapped wallet](https://www.unchained-capital.com/blog/a-hermit-emerges/)  
    Create diff. Spending conditions with diff. Groups that combine together to spend the txn.  Makes restrictive spending a lot more flexible.

#### Network Stats

  - [BitMEXResearch](https://twitter.com/BitMEXResearch/status/1166010048046358529?s=20)  
  - [ecurrencyhodler (do a thought experiment)](https://twitter.com/ecurrencyhodler/status/1166027713380929543?s=20)  
  - [Most onchain volume on exchanges](https://medium.com/meetbitfury/report-on-international-bitcoin-flows-by-crystal-analytics-5cc3c506ac3f)  
    [crystalblockchain.com](https://crystalblockchain.com/assets/reports/International%20Bitcoin%20Flows%20Report%20for%202013-2019%20-%20by%20Crystal%20Blockchain,%20Bitfury.pdf)  
  - [Hashing Power Update: Bitcoin Hits 100 Exahashes](https://bitcoinist.com/bitcoin-hash-rate-nearing-100000000-th-s-in-historic-first/)

#### New Work/ Research
  - [Lightning Labs Node Operator Guideline](https://blog.lightning.engineering/posts/2019/08/15/routing-quide-1.html)
  - Miniscript  
    - **Problem**: Hard to write advanced scripting language and know it’s correct.  People copy paste code that works for their own purposes.  Not very efficient.  
    - **Solution**: Miniscript compiles script for users and even makes it more efficient and will make sure it’s correct and even compile it for you.  It also increases interoperability between different wallets by providing a standard and checking scripts because it makes sure everything is correct.  Previously, fear that counterparties do not (or will not) have the software to recognize and spend the coins controlled by the policy.  
    - What Miniscript enables is writing software that works with generic scripts. It lets you participate in signing any script you have keys for, while also letting you analyse what someone's script does (if they want to include you in their setup).  
    - Miniscript is able to express all possible conjunctions/disjunctions/thresholds of timelocks/hashlocks/ and (pay2)public keys.  
    - Miniscript usable today  
    - One important way Miniscript differs from regular Script is that Miniscript describes the conditions under which coins can be spent, while Script describes the actions that a Script interpreter must take.  
    - [sipa on miniscript](http://bitcoin.sipa.be/miniscript/)
    - [Miniscript: How Blockstream Engineers Are Making Bitcoin Programming Easy(er)](https://bitcoinmagazine.com/articles/miniscript-how-blockstream-engineers-are-making-bitcoin-programming-easyer)
    - [pwuille on twitter](https://twitter.com/pwuille/status/1163592166062473217)
    - [Miniscript: enabling composition and analysis of Bitcoin Script on reddis](https://www.reddit.com/r/Bitcoin/comments/cspjt8/miniscript_enabling_composition_and_analysis_of/)
    - [blockstream on twitter](https://twitter.com/Blockstream/status/1170351002589040640)
  - Distributed storage and messaging
  - [L3 (a way to provide data storage to people using LN in a decentralized way).](https://twitter.com/dr_orlovsky/status/1162417145361383424?s=21)
  - [BTC Script decoder](https://twitter.com/etscrivner/status/1167470914327470080?s=20)
  - [Eltoo, the Lightning improvement proposal that removes the possibility of stolen funds via malicious channel state publishing.](https://blog.keys.casa/crypto-101-eltoo/)
  - Previously relied on HTLC’s, el too allows you simply to update the channel itself.  Also allows you to update fees in case fee market explodes.
  - Chaincode summer resident prototype @remyers_  (currently being tested)
  - [eltoo implementation in Bitcoin functional test framework](https://lists.linuxfoundation.org/pipermail/lightning-dev/2019-September/002131.html)
  - [Reconciling the off-chain and on-chain models with eltoo](https://lists.linuxfoundation.org/pipermail/lightning-dev/2019-September/002136.html)

#### Bitcoin PR’s

  - API in RUST to fetch headers and blocks from a REST Endpoint.  REST endpoint can be URL’s people use for specific API’s.  One problem is if it’s a unique URL, can be taken down.  Could prevent it by using github as the main domain.  Adds redundancy to P2P network. 
  - [Problem: ISP can block bitcoin specific info.](https://twitter.com/Y_deGaia/status/1160587490887196673)
  - [Solution is to have dedicated url’s to serve headers/blocks.](https://github.com/bitcoin/bitcoin/pull/16762)

#### Lightning PR’s

  - [LND: improve prob. estimation for untried connections](https://github.com/lightningnetwork/lnd/pull/3462)
  - [C-lightning: Gossip Rate Limiting](https://github.com/ElementsProject/lightning/pull/3040)
  - [Avoiding gossip spam: how many updates do you need?](https://lists.linuxfoundation.org/pipermail/lightning-dev/2019-September/002134.html)
