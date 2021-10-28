# Stake Your OHM (3, 3)

Sometimes, the Olympus website might not be accessible due to [hosting issues](https://twitter.com/FleekHQ/status/1416505712222609411). Fear not, you can still interact with the Olympus contracts to perform certain actions such as staking. In this guide, we will show you how to stake OHM tokens via [Etherscan](https://etherscan.io).

If you have never staked OHM before, there are two steps involved:

1. Approve the staking contract to spend your OHM tokens.

If you have staked OHM before, there is only one step to perform: Stake your OHM tokens.

### &#x20;<a href="how-to-approve-ohm-spending-via-etherscan" id="how-to-approve-ohm-spending-via-etherscan"></a>

1. Check and ensure your selected network is "Ethereum Mainnet" in your wallet. Then press **Connect to Web3** to connect your wallet if you haven't done so.
2. Once it is connected, select the third option _approve_.
3. On the _spender (address)_ field, we would fill in the [staking contract address](.gitbook/assets/staking). Enter this value: **0xC8C436271f9A6F10a5B80c8b8eD7D0E8f37a612d**
4. On the _amount (uint256)_ field, fill in the amount of OHM you would like the staking contract to spend on your behalf, and multiply it by 1e9. Alternatively, you can use [this calculator](https://docs.google.com/spreadsheets/d/1vm48OCBnVh8uah0-3Xa7HqFwmfxgcrMIWPrOllSFIvA/edit?usp=sharing) to perform the conversion for you. If you don't want to repeat this step whenever you want to stake, you can choose a very large value. Let's say you want to allow the contract to spend up to 1e9 OHM on your behalf, you would enter: **1000000000000000000**
5. Sign the transaction on Metamask and wait for it to complete.

### &#x20;<a href="how-to-stake-ohm-via-etherscan" id="how-to-stake-ohm-via-etherscan"></a>

1. Check and ensure your selected network is "Ethereum Mainnet" in your wallet. Then press **Connect to Web3** to connect your wallet if you haven't done so.
2. Once it is connected, select the _stake_ option.
3. On the _\_amount (uint256)_ field, fill in the amount you wish to stake, and multiply it by 1e9. Alternatively, you can use [this calculator](https://docs.google.com/spreadsheets/d/1vm48OCBnVh8uah0-3Xa7HqFwmfxgcrMIWPrOllSFIvA/edit?usp=sharing) to perform the conversion for you. For example, if you want to stake 1 OHM, fill in the value: **1000000000**
4. Sign the transaction on Metamask and wait for it to complete.
