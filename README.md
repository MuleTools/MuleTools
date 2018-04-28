![alt text](http://78.media.tumblr.com/9bd864d40a068728c446797cd67b92b3/tumblr_inline_oydq7f74eO1tu47rq_500.png "Mule Tools")

# Mule Tools: 

## Alternative means of bitcoin transaction broadcast

## Table Of Contents

I. [Introduction](#i-introduction)  
II. [Tools](#ii-tools)  
III. [Projects](#iii-projects)  
IV. [Articles](#iv-articles)  
V. [Submissions](#v-submissions)  
VI. [Other](#vi-other)  

## I. Introduction

### Inspiration

Inspired by [Blockstream](https://blockstream.com)'s [Blockstream Satellite](https://blockstream.com/2017/08/15/announcing-blockstream-satellite.html), and continuing in the vein of ideas set down by [Nick Szabo](http://unenumerated.blogspot.fr/) pertaining to [physical broadcasts](http://nakamotoinstitute.org/advances-in-distributed-security/), Mule Tools will be a clearing house for code that enables alternative broadcast methods for bitcoin transactions with a view towards routing around censorship, network outages, hijacking by hostile external and internal actors.

### Overview

The bitcoin blockchain is the longest running, most secure, and most valuable cryptocurrency blockchain. As such, it is under continual attack, from actors outside and even from within its own ecosystem (ie. 2x, bcash). The purpose of the projects and tools stored in these repositories is to make the bitcoin network more resilient and capable of re-routing around censorship and hostile actors.

We are interested in assisting with the development of any alternative paths for bitcoin *pushTx* including but not exclusively limited to:

- SMS relay
- satellite hook-up
- fax or any form of hard copy to character recognition
- save to external support (USB)
- Portable Document Format (PDF)
- telex
- HF audio
- Morse code
- meshNets
- NFC
- BLE
- chat apps (especially encrypted)

Projects can use one or more methods for enabling an alternative route to *pushTx*.

All submitted projects will be considered for support by and possible inclusion in [Samourai Wallet](https://samouraiwallet.com) which now includes basic hooks for exporting signed raw bitcoin transactions hex code.  
 
## II. Tools

### Vocal message with latest block hash (1-518-BLK-TIME):
[+1(518)255-8463](tel:0015182558463)

### Obtain signed raw hex transaction from a Trezor:
[instructions](http://archive.is/iWTdV) 

### Obtain signed raw hex transaction from Samourai Wallet:
Copy and paste signed raw hex transaction or scan/share QR code as of Samourai v0.96. [announcement:](https://twitter.com/SamouraiWallet/status/922074806467661826)


## III. Projects

### SMSPushTx: [fork](https://github.com/muletools/smspushtx)

### Pony Direct (use any Android device as SMS relay): [repo](https://github.com/MuleTools/PonyDirect)

### Send bitcoin via APRS: [fork](https://github.com/muletools/bitcoin_aprs)

### Message in a Bottle (includes incentive to broadcast): [concept](http://archive.is/D8jWX)

## IV. Articles

Physical broadcasts are discussed in [Advances in Distributed Security](http://nakamotoinstitute.org/advances-in-distributed-security/) by Nick Szabo.

[Hijacking Bitcoin: Routing Attacks on Cryptocurrencies](https://btc-hijack.ethz.ch).

[Carrier Pigeon Faster Than Broadband Internet](https://m.phys.org/news/2009-09-carrier-pigeon-faster-broadband-internet.html) OpenDime delivered via carrier pigeon? ;)

## V. Submissions

### Contributing

All contributions proposed must target the bitcoin blockchain. Therefore, convert any alt-coin related code to bitcoin. BCASH and Segwit2X are alt-coins.

All pull requests should be directed to 'develop' branch of each project - do not submit pull requests to 'master'.

Join us! Pull requests, code, documentation are all welcome.

## VI. Other

### Donations

#### Bitcoin address

[![address](http://api.qrserver.com/v1/create-qr-code/?color=000000&bgcolor=FFFFFF&data=3CVpeDSsauNRWiWeXWRrgc5eFUpujtN7Wo&qzone=1&margin=0&size=200x200&ecc=L)](http://srv1.yogh.io/#addr:id:3CVpeDSsauNRWiWeXWRrgc5eFUpujtN7Wo)

#### Payment code (BIP47)

[![BIP47 payment code](http://api.qrserver.com/v1/create-qr-code/?color=000000&bgcolor=FFFFFF&data=PM8TJVzLGqWR3dtxZYaTWn3xJUop3QP3itR4eYzX7XvV5uAfctEEuHhKNo3zCcqfAbneMhyfKkCthGv5werVbwLruhZyYNTxqbCrZkNNd2pPJA2e2iAh&qzone=1&margin=0&size=200x200&ecc=L)](https://paynym.is/+samouraiwallet)

### Dev contact

[PGP](http://pgp.mit.edu/pks/lookup?op=get&search=0x72B5BACDFEDF39D7)
