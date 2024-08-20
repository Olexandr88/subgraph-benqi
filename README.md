# Benqi-subgraph

### Commands:

generate types:

- `npx graph codegen --output-dir src/types/`
  build code:
- `npx graph build`
  deploy:
- `npx graph deploy --debug --access-token <TOKEN> yhayun/Benqi --node https://api.thegraph.com/deploy/ --ipfs https://api.thegraph.com/ipfs/`

### Guides

- Deploying subgraphs to Moonriver [https://docs.moonbeam.network/builders/integrations/indexers/thegraph/]
- Reference (Compound V2) [https://github.com/compound-finance/compound-v2-subgraph]
- Partial Benqi graph (Compound V2):
  - [https://github.com/ChaosLabsInc/benqi-subgraph-partial]
  - [https://github.com/token-terminal/tt-subgraphs/tree/main/benqi/v1-avalanche]

## WIP

There are some commented out sections from the original compund-v2 graph, they're all marked with `TODO @yhayun` comment.
Missing items (not exahsutive):

- market.underlyingPriceUSD
- market.accrualBlockNumber
- market.supplyRate
