## Step to run

1. Reset Every thing in moralis database

   - Remove all activeItem and ItemList and all event table in moralis database.

1. Sync all needed with Moralis

```shell
yarn run moralis:sync
yarn run moralis:cloud
```

3. Start local hardhat node and

```sh
hh node
yarn dev

```

4. Reset sync local node on moralis
5. NFT command stuff

```sh
hh run scripts/mint-and-list.ts --network localhost
```

6. When sell or list in ui need to mine block local for moralis will trigger confirm block.

```sh
hh run scripts/mine.ts --network locahost
```
