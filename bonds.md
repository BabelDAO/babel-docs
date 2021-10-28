# Bonds

### &#x20;<a href="dai-bond" id="dai-bond"></a>

All bond contracts are more or less the same, with the one exception of the assets or LP tokens they manage. The bond contracts handle all deposits and redemptions. Here parameters for monetary policy are configured. Such parameters are for instance the [BCV](<.gitbook/assets/glossary (1)>) and the max individual payout. Below are listed DAI bond contracts by version, where the latest version represents the currently active contract.

*

### &#x20;<a href="eth-bond" id="eth-bond"></a>

Since ETH is not an ERC-20 token itself, our ETH bonds utilize [wETH](https://weth.io). All things being equal to our other bond types, the only exception for ETH bonds is that we do not mint OHM against wETH taken in to begin with. Below are listed ETH bond contracts by version, where the latest version represents the currently active contract.

*

### &#x20;<a href="frax-bond" id="frax-bond"></a>

*

### &#x20;<a href="lusd-bond" id="lusd-bond"></a>

All bond contracts are more or less the same, with the one exception of the assets or LP tokens they manage. The bond contracts handle all deposits and redemptions. Here parameters for monetary policy are configured. Such parameters are for instance the [BCV](<.gitbook/assets/glossary (1)>) and the max individual payout. Below are listed LUSD bond contracts by version, where the latest version represents the currently active contract.

*

### &#x20;<a href="ohm-dai-lp-bond" id="ohm-dai-lp-bond"></a>

*

### &#x20;<a href="ohm-frax-lp-bond" id="ohm-frax-lp-bond"></a>

*

### &#x20;<a href="ohm-lusd-lp-bond" id="ohm-lusd-lp-bond"></a>

All bond contracts are more or less the same, with the one exception of the assets or LP tokens they manage. The bond contracts handle all deposits and redemptions. Here parameters for monetary policy are configured. Such parameters are for instance the [BCV](<.gitbook/assets/glossary (1)>) and the max individual payout. Below are listed OHM / LUSD LP bond contracts by version, where the latest version represents the currently active contract.

*

### &#x20;<a href="redeem-helper" id="redeem-helper"></a>

The redeem helper contract is configured with all active bond contract addresses. When calling `redeemAll` all claimable bond rewards are redeemed for the given recipient. Below are listed redeem helper contracts by version, where the latest version represents the currently active contract.

*
