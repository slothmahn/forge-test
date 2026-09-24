# Fuel Forge V4 fast test

[Open the public fast test](https://slothmahn.github.io/forge-test/)

This is an accelerated alpha on Robinhood Chain **Testnet** (chain ID 46630). It uses test ETH and mock FUEL, MORE, PAMP, and cbBTC. Forge position fees route 33% to the FUEL burn pool, 20% to MORE, 5% to PAMP, and 1% to the development wallet. The burn engines use ten-second intervals and model conversions; they do not trade on a market. The app and contracts are unaudited and are not for real assets.

The current Foundry NFT mint fee is determined by the test oracle, with a 0.001–0.01 test ETH range. One percent goes to the development wallet and 99% funds mock cbBTC rewards. This deployment has new contracts, so positions and NFTs from the previous fast test remain in the older contracts.

Use a brand-new test-only wallet. Never enter a private key or seed phrase on the site. Wallet actions require your own confirmation.

To report a problem, [open a GitHub issue](https://github.com/slothmahn/forge-test/issues/new) with the action you tried, the public transaction hash, what you expected, and what happened. Do not include wallet secrets.

This repository currently contains the standalone public test page. The full contract and app source remains in the local Fuel Forge V4 project while this alpha is tested.
