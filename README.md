Steps:
1. Swap ETH for WETH
2. Deposit/supply some WETH into the Aave Lending Protocol.
3. Borrow some asset using the ETH collateral
    1. Short sell the borrowed asset via DEX.
4. Repay everything back

Testing method:
1. Integration test: `sepolia`
2. Unit test: `mainnet-fork` (since we do NOT deploy our own contract and oracle usage is NOT required, just fork Aave's contracts from the Ethereum mainnet)
