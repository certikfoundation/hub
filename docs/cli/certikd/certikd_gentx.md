## certikd gentx

Generate a genesis tx carrying a self delegation

### Synopsis


It creates a genesis piece carrying a self delegation with the
following delegation and commission default parameters:

	delegation amount:           100000000uckt
	commission rate:             0.1
	commission max rate:         0.2
	commission max change rate:  0.01
	minimum self delegation:     1


```
certikd gentx [flags]
```

### Options

```
      --amount string                       Amount of coins to bond
      --commission-max-change-rate string   The maximum commission change rate percentage (per day)
      --commission-max-rate string          The maximum commission rate percentage
      --commission-rate string              The initial commission rate percentage
      --details string                      The validator's (optional) details
  -h, --help                                help for gentx
      --home-client string                  client's home directory (default "~/.certikcli")
      --identity string                     The (optional) identity signature (ex. UPort or Keybase)
      --ip string                           The node's public IP (default "192.168.0.227")
      --min-self-delegation string          The minimum self delegation required on the validator
      --name string                         name of private key with which to sign the gentx
      --node-id string                      The node's NodeID
      --output-document string              write the genesis transaction JSON document to the given file instead of the default location
      --pubkey string                       The Bech32 encoded PubKey of the validator
      --website string                      The validator's (optional) website
```

### Options inherited from parent commands

```
      --home string        directory for config and data (default "~/.certikd")
      --log_level string   Log level (default "main:info,state:info,*:error")
      --trace              print out full stack trace on errors
```

### SEE ALSO

* [certikd](certikd.md)	 - CertiK App Daemon (server)

