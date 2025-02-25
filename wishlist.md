## Criticals / Must Have

1. [PIBD - (faster and more robust syncing strategy)](https://github.com/stakervali/grin-wishlist/issues/6)
  *-In beta, being tested on mainnet*
2. [multi-sig*](https://github.com/stakervali/grin-wishlist/issues/2)
  *-Not happening any time soon if I understand correctly, since there is no solution yet to generate threshold range proofs:*
3. Wallet backend improvements
  *- Grin-wallet had many bug fixes and stability improvements*
4. libsecp fork update 
   *-not updated, last commit to libsecp was 5 years ago*
5. safe cancel*
   *WIP, not merged https://github.com/mimblewimble/grin-rfcs/pull/71, part of Grin GUI?*

## Important

1. Tor support for nodes*
2. [light node*](https://github.com/stakervali/grin-wishlist/issues/7)
3. [testnet exchange/ making it easier for exchange integrations](https://github.com/stakervali/grin-wishlist/issues/4)
 *-Implemented - [Link]([url](https://github.com/stakervali/grin-wishlist/issues/4))*
4. payjoins*
  *-Not really payjoin, but [Coin Swap, mwixnet]([url](https://forum.grin.mw/t/request-for-funding-scilio-coinswap-implementation/9149)) is nearly implemented, see aggregator*
5. [binaries for older systems, older GLIBC or build on low RAM machine < 300MB]()
7. [invoice payment proofs*](https://github.com/stakervali/grin-wishlist/issues/10)
    *-Implemented in the under contract flow branch [grin GUI wallet]([url](https://github.com/mimblewimble/grin-wallet/pull/681)), part of unified/[biderection payment proofs]([url](https://phyro.github.io/grinvestigation/bidirectional_paymentproofs.html))*
8. hardware wallets*
  *-Leger HW support for Grin is implemented. [Tutorial]([url](https://www.youtube.com/playlist?list=PLb1nuT3sFYbD_sydCVCngbvATsm9RwWyF), [Download the code here]([url](https://github.com/NicolasFlamel1/ledger-live/releases)))* 

## Fix if time / Nice to Have

1. wallet view key*
2. [one-time use slatepack addresses for wallet*](https://github.com/stakervali/grin-wishlist/issues/11)
  *-Generate new slatepack address is implemented in Grin++, not yet in grin-wallet*
3. flyclient*
   *-Nothing implemented, would require header history or inclusion proof according to discussions on KeyBase*
4. [atomic swaps*](https://github.com/stakervali/grin-wishlist/issues/1)
  *-Gene made a first implementation of "non-ideal" atomic swap, grin reaper offered to continue implementation, nothing fixed yet.*
  https://forum.grin.mw/t/questions-about-the-state-of-the-atomic-swap-pr-and-introduction/10332
  https://github.com/mimblewimble/grin-rfcs/pull/83
5. aggregators
  *-mwixnet/CoinSwap, third stage under review with two open issues out of 9 issues*
https://forum.grin.mw/t/request-for-funding-scilio-coinswap-implementation/9149**
https://github.com/mimblewimble/mwixnet/issues/11
6. block archive node support*
   *-Implemented, fast sync method could still be added in the future*
7. [improve compatibility with OSX](https://github.com/stakervali/grin-wishlist/issues/3)
  *-No specific changes as far as I know, or are these part of the many changes to grin-wallet*
8. anchors*
9. bulletproofs+*
  *-[Not deemed safe/well tested enough yet in 2020](keybase://chat/grincoin#dev/5873), 
  *-Had a [positive review]([url](https://tari.substack.com/p/taris-bulletproofs-audit-is-done)) in Tari, (see [full report]([url](https://github.com/tari-project/bulletproofs-plus/blob/main/docs/quarkslab-audit/report.pdf)https://github.com/tari-project/bulletproofs-plus/blob/main/docs/quarkslab-audit/report.pdf)). 
10. NRD activation*
11. [Display slatepacks as QR codes in CLI
  *-Implemented*
