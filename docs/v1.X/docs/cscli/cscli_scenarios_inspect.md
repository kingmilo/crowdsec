## cscli scenarios inspect

Inspect given scenario

### Synopsis

Inspect given scenario

```
cscli scenarios inspect [config] [flags]
```

### Examples

```
cscli scenarios inspect crowdsec/xxx
```

### Options

```
  -h, --help         help for inspect
  -u, --url string   Prometheus url (default "http://127.0.0.1:6060/metrics")
```

### Options inherited from parent commands

```
  -b, --branch string   Use given branch from hub
  -c, --config string   path to crowdsec config file (default "/etc/crowdsec/config.yaml")
      --debug           Set logging to debug.
      --error           Set logging to error.
      --info            Set logging to info.
  -o, --output string   Output format : human, json, raw.
      --trace           Set logging to trace.
      --warning         Set logging to warning.
```

### SEE ALSO

* [cscli scenarios](cscli_scenarios.md)	 - Install/Remove/Upgrade/Inspect scenario(s) from hub

