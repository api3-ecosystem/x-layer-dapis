## API3 dAPIs on X Layer

This repository contains the proxy contract addresses for the API3 dAPIs available on X Layer Mainnet and Testnet. The dAPIs are deployed on-chain and the proxy contracts are used to read the latest data feed values.

### API3ServerV1 Address
`0x709944a48caf83535e43471680fda4905fb3920a`
### Proxy Factory
`0x9EB9798Dc1b602067DFe5A57c3bfc914B965acFD`

## X Layer Mainnet

### Proxy Contract Addresses

| Assets | Deviation threshold | Proxy contracts | Sponsor wallets |
|--------|---------------------|-----------------|-----------------|
| ETH/USD | 1% | 0x93F7efd59A74A3Ccc7168C0De481461e5Bd9518c | 0xC680BcDA3b122837A0D49ba23f607b412Cd90906 |
| BTC/USD | 1% | 0x08506208E776ecbdF4cE9DB69C08Aa90A06825C0 | 0x82D117e7AdEd3fC8A9266252899B21C843dDC4B2 |
| AAPL/USD | 1% | 0x9C4bE884D10eCbde09a53A992Bf3a01D7c8fCA26 | 0x91E8A2033f1ce7f0138f88e01EFEAA14776387FD |
| AAVE/USD | 1% | 0x84d9dF066b43C60A5f0906c930914dc98B654493 | 0x17EeAbF49bE81B763F88877E508584cf0A5a5eD6 |
| AMZN/USD | 1% | 0x89A95AcF28f7b9f1F06A3DD4A064560568b30E92 | 0xd74eDF7043472830d93145Bd0087059c6AB317F3 |
| API3/USD | 1% | 0x1d53D38bf5e79D3cd5707539932B22B09a4E450b | 0xBA1817Ceb62A8dcC9d42a166b9F7CAB204656c72 |
| ARB/USD | 1% | 0xcf98F303A091c5A22F78c32aB207cfEA2774dfa4 | 0x751114392B3Da45f24755aCd51a6E794E5Af029a |
| DAI/USD | 1% | 0x2C5A3774cb2A47054679eB86a897440c564AC867 | 0xF8CbF618Bc8ff4BF78bEb744ba33380C362227Db |
| DOGE/USD | 1% | 0xC3E0695aC7168b8631b1B66779AB8a5C751a3146 | 0x8B67b0728380fF6931cc7D4aa8ab2844A6f0B82F |
| DOT/USD | 1% | 0x1f41022571aB856b362932411E5cfAD82A13A415 | 0x1503370573eB9bD04fc376a14fA3Be51E9046425 |
| FIL/USD | 1% | 0xE0bC254Ecb354Fe5e6aB6F94C14b9F008Ddd7371 | 0x666deEF0501EcC1D1611Acc8B36C0b67B0d9451F |
| LTC/USD | 1% | 0x06D26311CFd6EF7A5820c53ea2184ecE9a51a0Aa | 0xDf5ebd7B04806829a286e6332004C796951a3fda |
| OKB/USD | 1% | 0xE9Db25a1315A3F92Bc815B4D15b78d7759c2139D | 0xc291031327953E61400004B5F209bEc996F69BcF |
| SUSHI/USD | 1% | 0xe1a246f50856A84C85e9284AE25D810ddF189862 | 0xc0A66985c2106a2e03AAbEF1E57a93Da0d10E951 |
| USDC/USD | 1% | 0xAEE355E75272Fd737690Af830A20193c93e6f159 | 0x2b265b6D826E8d538C3721a1B364073CB3f75234 |
| USDT/USD | 1% | 0x7b25be75b8bBf3CE6F9B7a6F82bB84d2976cb7aB | 0x8Fc8f8548C2ff2D7A8a92a30ACaB3cA6a6b9F868 |
| UNI/USD | 1% | 0x2d76D9E6707632675a7b6f2C3731e7a2449f6C6c | 0x2DC913BBFB55451dbd10aF61a0064DA687E3397e |

## X Layer Testnet

### Proxy Contract Addresses

| Assets | Deviation threshold | Proxy contracts | Sponsor wallets |
|--------|---------------------|-----------------|-----------------|

Make sure to use the correct proxy contract address for the data feed you want to read. Also, fund the sponsor wallets with the required amount of gas so it keeps the data feeds updated.

## Usage

The proxy contracts are used to read the latest data feed values. The proxy contracts are deployed on-chain and the addresses are available in this repository for now. The proxy contracts are used to read the latest data feed values.

[Check out this guide on how to read a data feed on X Layer](https://docs.api3.org/guides/dapis/read-a-dapi/)
