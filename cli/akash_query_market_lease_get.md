## akash query market lease get

Query order

```
akash query market lease get [flags]
```

### Options

```
      --dseq uint         Deployment Sequence
      --gseq uint32       Group Sequence (default 1)
      --height int        Use a specific height to query state at (this can error if the node is pruning state)
  -h, --help              help for get
      --node string       <host>:<port> to Tendermint RPC interface for this chain (default "tcp://localhost:26657")
      --oseq uint32       Order Sequence (default 1)
  -o, --output string     Output format (text|json) (default "text")
      --owner string      Deployment Owner
      --provider string   Provider
```

### Options inherited from parent commands

```
      --chain-id string   The network chain ID
```

### SEE ALSO

* [akash query market lease](akash_query_market_lease.md)	 - Lease query commands

###### Auto generated by spf13/cobra on 28-Apr-2022
