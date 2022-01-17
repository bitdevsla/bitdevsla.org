+++
title = "Multisig Wallets, Casa, and Bitcoin Socratic Seminar #25"
template = "post.html"
[extra]
meetup_id = "282351102"
youtube_id = ""
+++

### Agenda  

3:00pm Pizza and beers  
3:45pm Speaker  
4:15pm Socratic Seminar  
5:15pm Wrap-up  
5:30pm Food/Drinks at a local bar  

### Sponsor  

[River Financial](https://river.com/) - The best place to buy, sell, and use Bitcoin for the 
long-term investor. Use this link for 2 months of 0 fees: <https://river.com/signup?a=PRLBLIOI>.

[Casa](https://app.keys.casa/subscribe/gold) - The safest way to store your bitcoin. Get $21 off a gold plan using the promo code: bitdevsla  
### Location  

[7456 Melrose Ave, Los Angeles, CA 90046 (Zephyr Theater)](https://www.google.com/maps/place/7456+Melrose+Ave,+West+Hollywood,+CA+90046/@34.0833294,-118.3547615,17z/data=!3m1!4b1!4m5!3m4!1s0x80c2bed36430426f:0xedabb82c06037177!8m2!3d34.0833294!4d-118.3525728)

### Parking

There's 2 hour parking in the residential area and metered parking along the street. You can also buy a drink and park at the CVS across the street.  

### Details  

Join us for our first Bitcoin meetup of 2022 and start your New Years off with a bang! We're going to have free pizza and beer right when the doors open so make sure to get there early in order to network with other local Bitcoiners.  

This month we have the pleasure of hosting Andrew Yang, Client Services Manager at Casa, who will be breaking down how to use multisig wallets. Casa is a multisig provider that offers the most secure Bitcoin wallet you can use while being non-custodial at the same time.  

The talk will then be followed by a Socratic Seminar and then we will get drinks at a local restaurant after.  

### Guest Speakers


[Andrew Yang](https://twitter.com/ecurrencyhodler) - Client Services Manager at [Casa](https://keys.casa)  



### Socratic Seminar


#### News

- [Jack Dorsey to Launch Bitcoin Legal Defense Fund](https://bitcoinmagazine.com/business/jack-dorsey-to-launch-bitcoin-legal-defense-fund)  
- [Chainalysis Launches Support for Lightning Network](https://blog.chainalysis.com/reports/lightning-network-support/)  
  - [Current State of Lightning Network Privacy](https://abytesjourney.com/lightning-privacy/)
  - [Using Lightning description hashes](https://twitter.com/niftynei/status/1479154453777465344)


#### Research  
- [Efficient Reusable Taproot Addresses](https://gist.github.com/Kixunil/0ddb3a9cdec33342b97431e438252c0a)
- [DSN Bitcoin Network Monitoring](https://www.dsn.kastel.kit.edu/bitcoin)
#### Bitcoin PRs <font color="#FF9900">₿</font>  
- "p2p: Add DISABLETX message for negotiating block-relay-only connections" (core [#20726](https://github.com/bitcoin/bitcoin/pull/20726))
- "p2p: Erlay support signaling" (core [#23443](https://github.com/bitcoin/bitcoin/pull/23443))  
  - What is Erlay?  
    - Erlay is a proposal to improve the bandwidth efficiency of relaying unconfirmed transactions between Bitcoin full nodes.  
    - Erlay is a two-part proposal that first limits the number of peers to which a node will directly advertise transactions (default: 8) and, second, uses set reconciliation based on libminisketch with the remainder of its peers to avoid sending the txid of any transactions that the receiving peer has already seen.  
    - This proposal focuses on part 2. A node receives a sketch. They create their own sketch. They compare the two sketches and see a difference. Then they request the txns from the difference to relay. That way it doesn’t have to re-request or broadcast redundant txns.  
  - Example of a soft-fork without requiring consensus agreement.  
    - 2 levels to soft-forks  
      - Block validation
      - Txn relay
	
#### Lightning PRs ⚡ 


