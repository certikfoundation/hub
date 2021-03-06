## certikcli keys delete

Delete the given key

### Synopsis

Delete a key from the store.

Note that removing offline or ledger keys will remove
only the public key references stored locally, i.e.
private keys stored in a ledger device cannot be deleted with the CLI.


```
certikcli keys delete <name> [flags]
```

### Options

```
  -f, --force   Remove the key unconditionally without asking for the passphrase
  -h, --help    help for delete
  -y, --yes     Skip confirmation prompt when deleting offline or ledger key references
```

### Options inherited from parent commands

```
      --chain-id string   Chain ID of tendermint node
  -e, --encoding string   Binary encoding (hex|b64|btc) (default "hex")
      --home string       directory for config and data (default "~/.certikcli")
  -o, --output string     Output format (text|json) (default "text")
      --trace             print out full stack trace on errors
```

### SEE ALSO

* [certikcli keys](certikcli_keys.md)	 - Add or view local private keys

