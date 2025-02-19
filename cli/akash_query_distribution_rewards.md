## akash query distribution rewards

Query all distribution delegator rewards or rewards from a particular validator

### Synopsis

Query all rewards earned by a delegator, optionally restrict to rewards from a single validator.

Example:
$ akash query distribution rewards akash1gghjut3ccd8ay0zduzj64hwre2fxs9ld75ru9p
$ akash query distribution rewards akash1gghjut3ccd8ay0zduzj64hwre2fxs9ld75ru9p akashvaloper1gghjut3ccd8ay0zduzj64hwre2fxs9ldmqhffj

```
akash query distribution rewards [delegator-addr] [validator-addr] [flags]
```

### Options

```
      --height int      Use a specific height to query state at (this can error if the node is pruning state)
  -h, --help            help for rewards
      --node string     <host>:<port> to Tendermint RPC interface for this chain (default "tcp://localhost:26657")
  -o, --output string   Output format (text|json) (default "text")
```

### Options inherited from parent commands

```
      --chain-id string   The network chain ID
```

### SEE ALSO

* [akash query distribution](akash_query_distribution.md)	 - Querying commands for the distribution module

###### Auto generated by spf13/cobra on 28-Apr-2022
