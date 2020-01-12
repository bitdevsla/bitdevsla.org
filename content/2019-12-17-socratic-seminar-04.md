+++
title = "Bitcoin Socratic Seminar #4"
template = "post.html"
[extra]
meetup_id = "266674940"
+++

### Agenda

7:00 Socratic Seminar where we review various Bitcoin topics  
7:45pm- Clean up and leave by 8pm.  
8:00- Social at [7 grand lounge](https://m.yelp.com/biz/seven-grand-los-angeles).

### Sponsors

[River Financial](https://www.river.com) - The best place to buy, sell, and use Bitcoin for the long-term investor.

### Location

WeWork Fine Arts will be hosting the event at the following address:  
811 W. 7th Street (12th floor)  
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

### Socratic Seminar

Inspired by Bitdevs NY, this is an event for those interested in discussing and participating in the research and development of Bitcoin and related protocols. The Socratic Seminar events are formatted to foster debate, information sharing, and lively discussion.

Discussion topics from a variety of sources are collated by meetup members in the weeks preceding the events. We investigate pull requests in the Bitcoin Core, lnd, and other relevant repositories; we study network statistics, research papers, technical blog posts and other interesting content. To complete the meeting, members present open source projects, companies, research and other relevant materials. A feedback and Q&A section follow.

Please contact the organizers if you'd like to present at the Socratic event or have a recommended topic for discussion: ecurrencyhodler at gmail.

A post will be made prior to the event which outlines discussion topics. Archives of discussion topics and presentations can be found in the event descriptions of past meetups. The discussion portion of the event is NEVER recorded. It is recommended that you have a firm grasp of the basics of Bitcoin in order to extract the most value from our Socratic events.

#### News

  - [Ransom Attack on Coldcard](https://medium.com/shiftcrypto/a-ransom-attack-on-coldcards-change-and-keypath-verification-f3c71461624a)
  - [Troublesome Change Outputs](https://blog.coinkite.com/troublesome-change/)
  - [Bitcoin Mining in North America](https://bitcoinmagazine.com/articles/bitcoin-mining-in-north-america-a-new-gold-rush-in-the-new-world)
  - [Bitcoin Core 0.19.0.1 Release](https://bitcoincore.org/en/releases/0.19.0.1/)
  - the new bip157 getblockfilters. it's a first step to better btc/ln light clients.. with some interesting pros/cons
  - bip37/bip111 bloom filters is official off by default.. we discussed it last meeting.. but I didn't know there is also a dos issue associated with why it was turned off
for the P2P changes, this is new and interesting: By default, Bitcoin Core will now make two additional outbound connections that are exclusively used for block-relay. it's to prevent partitioning attacks.. but doesn't say how. I think since they won't be blocked by spam tx or other messages
  - [Nayuta releases full node and spv mobile bitcoin wallet.](https://medium.com/nayuta-en/running-a-lnd-along-side-bitcoind-on-android-779dcf4e16bb)
  - [C-lightning release](https://twitter.com/Snyke/status/1206715011105722368?s=20)

#### Stats

  - [Fee Estimation Dashboard](https://txstats.com/dashboard/db/fee-estimation?orgId=1)
  - [LN Big Sun Explorer](https://ln.bigsun.xyz/)

#### New Work & Research

  - [Bitcoin’s Initial Block Download](https://blog.bitmex.com/bitcoins-initial-block-download/)
  - [Analysis of Bech32 swap/insert/delete detection and next steps](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2019-December/017521.html)
  - [BOLT 13 Watchtower Protocol](https://lists.linuxfoundation.org/pipermail/lightning-dev/2019-November/002350.html)
  - [Composable MuSig](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2019-November/017493.html)
  - [How to profit from payment channels](https://arxiv.org/pdf/1911.08803.pdf)
  - [Payment Points with Schnorr](https://suredbits.com/payment-points-part-1/)
  - [Rust Bitcoin Projects](https://github.com/rust-bitcoin)
    - Early project, active contributors include: Polstra, Roose, Corallo, Blumer, etc.. 
    - Goals? “written entirely in Rust to illustrate the benefits of strong type safety, including ownership and lifetime, for financial and/or cryptographic software.”

#### Bitcoin PRs

  - [fix uninitialized variable nMinerConfirmationWindow](https://github.com/bitcoin/bitcoin/pull/17449)
  - [Remove unused COINBASE_FLAGS](https://github.com/bitcoin/bitcoin/pull/17449)
  - [Expose height of wallet transaction](https://github.com/bitcoin/bitcoin/pull/17437/files)
  - [BIP-322 generic signed message format](https://github.com/bitcoin/bitcoin/pull/16440)
  - [Assume UTXO Work](https://github.com/bitcoin/bitcoin/pull/16945)
  - [Deduplicate sign/verify code](https://github.com/bitcoin/bitcoin/pull/17577/files)
  - [Signed-digit multi-comb for ecmult_gen](https://github.com/bitcoin-core/secp256k1/pull/693)

#### Lightning PRs ⚡

  - [c-lightning: generate a static tor onion address unique to the node id](https://github.com/ElementsProject/lightning/pull/3155)
  - [c-lightning: Add a sendcustommsg RPC call and a custommsg plugin hook for experimental protocol extensions](https://github.com/ElementsProject/lightning/pull/3315)
  - [c-lightning: experimental MPP send and receive support](https://github.com/ElementsProject/lightning/pull/3309)
  - [lnd: experimental key send mode](https://github.com/lightningnetwork/lnd/pull/3795)
  - [lnd: invoices - expose custom tlv records from the payload](https://github.com/lightningnetwork/lnd/pull/3742)
  - [lnd: add optional close address](https://github.com/lightningnetwork/lnd/pull/3702)
  - [LN Spec: Bolt 1: Specify that extensions to existing messages must use TLV](https://github.com/lightningnetwork/lightning-rfc/pull/714)

