# WimbleChain
## Basic MimbleWimble implementation for Bitcoin.

![](https://wimblechain.github.io/logo-mw.png)

## Benefits

- Massively lower blockchain size (1,000x smaller)
 - One minute block times
- Lightning network compatible
- Compatible with existing Bitcoin software
- Private transactions

## How it works

WimbleChain uses an original MimbleWimble implementation to create blinded transactions, verified by summing the kernel offsets of each transaction. This is done by introducing Pederson commitments to the BTC blockchain through use of a sidechain. The sidechain functions on 60s block times, and commitments irreversibly to the BTC chain every time a new BTC block is mined. This vastly lowers hashpower requirements needed to implement MimbleWimble as an altcoin, and instead allows the Bitcoin chain to include simpler, smaller transfers of Wimble. Wimble are Wrapped MW blinded values that represent actualy Bitcoin, and are therefore interchangeable with Bitcoin in a private, highly scalable environment.


# Interested in WimbleChain? Join us on Gitter:

[![Gitter](https://badges.gitter.im/WimbleChain/community.svg)](https://gitter.im/WimbleChain/community?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

[Visit official website](https://wimblechain.github.io/)
[Sign up for our newsletter](https://trawk.typeform.com/to/CE5p72)
[Join Gitter Community](https://gitter.im/WimbleChain/communityhttps://gitter.im/WimbleChain/community)
