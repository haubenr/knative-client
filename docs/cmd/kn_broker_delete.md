## kn broker delete

Delete a broker

```
kn broker delete NAME
```

### Examples

```

  # Delete a broker 'mybroker' in the current namespace
  kn broker create mybroker

  # Delete a broker 'mybroker' in the 'myproject' namespace
  kn broker create mybroker --namespace myproject
```

### Options

```
  -h, --help               help for delete
  -n, --namespace string   Specify the namespace to operate in.
      --no-wait            Do not wait for 'broker delete' operation to be completed. (default true)
      --wait               Wait for 'broker delete' operation to be completed.
      --wait-timeout int   Seconds to wait before giving up on waiting for broker to be deleted. (default 600)
      --wait-window int    Seconds to wait for broker to be deleted after a false ready condition is returned (default 2)
```

### Options inherited from parent commands

```
      --cluster string      name of the kubeconfig cluster to use
      --config string       kn configuration file (default: ~/.config/kn/config.yaml)
      --context string      name of the kubeconfig context to use
      --kubeconfig string   kubectl configuration file (default: ~/.kube/config)
      --log-http            log http traffic
```

### SEE ALSO

* [kn broker](kn_broker.md)	 - Manage message brokers

