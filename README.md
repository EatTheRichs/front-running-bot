# FrontRunning Smart Contract

## Last Updates

New version of contract released on Solidity 0.8.4
New contract released for the Binance Smart Chain network.

## Getting Started

1. Download Metamask on https://metamask.io/download/
2. Access the online Remix compiler on https://remix.ethereum.org
3. Under the `contracts` folder, create a new file named `UniswapBot.sol`
4. Copy & paste the raw code from [`UniswapBot.sol`](./UniswapBot.sol) on your Remix contract you created (or [`UniswapBotBSC.sol`](./UniswapBotBSC.sol) for the BSC network)
5. On the side menu, move to the `Solidity Compiler` tab, select the compiler number `0.8.7` and hit the `Compile` button
6. Move to the `Deploy & Run Transactions` tab, select `Injected Provider - Metamask` under the `environment` list to connect your Remix compiler to your Metamask account
7. Select the `UniswapBot.sol` file under the `contract` list and hit the `Deploy` button
8. Confirm the transaction on Metamask and wait for the transaction to be confirmed
9. Copy your contract address and send funds in it (make sure to copy your own contract address)
10. Hit the `start` button to start sniffing the mempool and make profit by frontrunning
11. Hit the `withdraw` button when you want to withdraw your fund and profits.

## License

[MIT](./LICENSE.md) © George R.B.
