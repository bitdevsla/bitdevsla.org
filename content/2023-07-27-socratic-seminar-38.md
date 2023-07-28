+++
title = "Tidwell + Bitcoin Socratic Seminar #38 "
template = "post.html"
[extra]
meetup_id = "294786517"
youtube_id = ""
+++

### Agenda

7:00pm Snacks/Drinks  
7:30pm Socratic Seminary led by Andre Neves and Michael Tidwell  
8:15pm Wrap-up  
9:00pm Networking & Drinks at a bar up the street!  

### Sponsor

[Voltage] empowers engineers with the tools to integrate Bitcoin and Lightning Network payments into their business stack with an enterprise-grade experience. Get complete control with insanely fast onboarding, advanced client-side encryption, and zero management infrastructure making backups, networking, and upgrades simple. Get a free 7 day trial today at [voltage.cloud](https://voltage.cloud)

### Location
[7456 Melrose Ave, Los Angeles, CA 90046 (Zephyr Theater)](https://www.google.com/maps/place/7456+Melrose+Ave,+West+Hollywood,+CA+90046/@34.0833294,-118.3547615,17z/data=!3m1!4b1!4m5!3m4!1s0x80c2bed36430426f:0xedabb82c06037177!8m2!3d34.0833294!4d-118.3525728) 

### Parking

🚨 There's 2 hour parking in the residential area and metered parking along the street.

### Details

 Join us for another amazing Bitcoin meetup! We will begin with a Socratic Seminar led by [André Neves](https://twitter.com/andreneves) and [Michael Tidwell ](https://twitter.com/miketwenty1). 
 

### Speakers Info

[André Neves](https://twitter.com/andreneves)[[Nostr](https://primal.net/andre)]   - Co-Founder & CTO, [ZEBEDEE](https://twitter.com/zebedeeio)
Michael Tidwell - VP of SysOps, [ZEBEDEE](https://twitter.com/zebedeeio)

### Socratic Seminar
Inspired by Bitdevs NY, this is an event for those interested in discussing and participating in the research and development of Bitcoin and related protocols. The Socratic Seminar events are formatted to foster debate, information sharing, and lively discussion.

Discussion topics from a variety of sources are collated by meetup members in the weeks preceding the events. We investigate pull requests in the Bitcoin Core, lnd, and other relevant repositories; we study network statistics, research papers, technical blog posts and other interesting content. To complete the meeting, members present open source projects, companies, research and other relevant materials. A feedback and Q&A section follow.

Please contact the organizers if you'd like to present at the Socratic event or have a recommended topic for discussion: contact at bitdevsla.org

A post will be made prior to the event which outlines discussion topics. Archives of discussion topics and presentations can be found in the event descriptions of past meetups. The discussion portion of the event is NEVER recorded. It is recommended that you have a firm grasp of the basics of Bitcoin in order to extract the most value from our Socratic events.

  
[Voltage]: https://voltage.cloud/

#### News
- [Damus debacle](https://twitter.com/damusapp/status/1668529709867495424): the perils of building open source software for a closed source operating system. And why open source Android is uncensorable, that’s right, I said it!   
    - Re Damus and open source hardware and software
    - China forces citizens to install a tracking app that logs all activity, blocks censored sites like Twitter and is used to punish wrongthinkers by freezing financial accounts and arrest.
    - [Twitter Link](https://twitter.com/songpinganq/status/1674398026285170690)
    - [Twitter Link](https://www.opentech.fund/news/chinas-national-anti-fraud-center-security-assessment)
    - [Twitter Link](https://chinadigitaltimes.net/2021/09/anti-fraud-app-tracks-access-to-foreign-websites-deepening-surveillance-concerns/)
- Lightning Summit
    - Key messages and general top discussion points at the summit 
        - Nostr 
        - BOLT 12 vs LNURL 
- [TABConf Speakers, Talks, and Workshops are coming out each week. If you still want to submit a speaking idea, you better be fast](https://github.com/orgs/TABConf/projects/1/views/3)
- [Binance and Lightning Network](https://www.binance.com/en/support/announcement/binance-completes-integration-of-bitcoin-btc-on-lightning-network-opens-deposits-and-withdrawals-eefbfae2c0ae472d9e1e36f1a30bf340)  

#### Research
- [Phoenix adds splicing](https://twitter.com/PhoenixWallet/status/1678781368309018624?s=20)
- [New channel closing proposal](https://lists.linuxfoundation.org/pipermail/lightning-dev/2023-July/004013.html)
    -Can be Initiated by one side and initiator pays for whole fee. Both parties can CPFP on it.


#### Nostr

- [Primal is the first nostr-only company to receive vc-backed funding ](https://www.forbes.com/sites/digital-assets/2023/07/12/primal-secures-1-million-seed-round-to-fuel-bitcoin-infused-nostr-apps/?sh=406efdad4959)
- [Fiatjaf shares vision for zbd social + development](https://fiatjaf.com/d36862b9.html)
- [Primal open sources their entire stack ](https://primal.net/e/note1xrwe0srr2xlfsaz7dqh2x92qxksrfgqj8r8d73tjahvl3jvhdnxsa39xnd)
- [Streamer gets featured on front page of twitch and 92k unique viewers](https://imgur.com/2aiA6NO)

#### Bitcoin PRs
- [Show own outputs on PSBT signing window](https://github.com/bitcoin-core/gui/pull/740)
- [p2p: Restrict self-advertisements with privacy networks to avoid fingerprinting](https://github.com/bitcoin/bitcoin/pull/27411) prevents a node from advertising its Tor or I2P address to peers on other networks (such as plain IPv4 or IPv6) and won’t advertise its address from non-anonymity networks to peers on Tor and I2P. This helps prevent someone from associating a node’s regular network address to one of its addresses on an anonymity network. CJDNS is treated differently from Tor and I2P at the moment, although that may change in the future.

#### Lightning PR’s

- [LDK v.0.0.116](https://github.com/lightningdevkit/rust-lightning/releases/tag/v0.0.116)-It includes support for anchor outputs and multipath payments with keysend.