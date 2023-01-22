# subquery-indexers

Indexers built with [SubQuery](https://subquery.network/) to support [DAO
DAO](https://daodao.zone/) frontend and API needs, on [Terp Network](https://terp.network).

## Setup

1. Install the latest stable yarn: https://yarnpkg.com/getting-started/install

2. Copy `.yarnrc.yml.example` into `.yarnrc.yml`. Do not change anything.

3. Add workspaces plugin:

```
yarn plugin import workspace-tools
```

4. Run yarn

```
yarn
```

## Containerify

See [the containerify README](./packages/containerify/README.md) file for
instructions on how to generate a Docker Compose container for an indexer.

## Relevant chain variables

### Test Network (Current Fork)

RPC: `https://rpc-terp.zenchainlabs.io/`

Start block height: `1`


### First v1 cw-core on mainnet

Code ID: `TBD`

Block Height: `TBD`

Timestamp: `TBD`
