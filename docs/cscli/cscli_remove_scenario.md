## cscli remove scenario

Remove/disable scenario

### Synopsis

<config> must be a valid scenario.

```
cscli remove scenario [config] [flags]
```

### Options

```
  -h, --help   help for scenario
```

### Options inherited from parent commands

```
      --all             Delete all the files in selected scope
  -c, --config string   path to crowdsec config file (default "/etc/crowdsec/config/default.yaml")
      --debug           Set logging to debug.
      --error           Set logging to error.
      --info            Set logging to info.
  -o, --output string   Output format : human, json, raw. (default "human")
      --purge           Delete source file in ~/.cscli/hub/ too
      --warning         Set logging to warning.
```

### SEE ALSO

* [cscli remove](cscli_remove.md)	 - Remove/disable configuration(s)


