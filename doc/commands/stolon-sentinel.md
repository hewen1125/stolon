## stolon-sentinel



### Synopsis



```
stolon-sentinel [flags]
```

### Options

```
      --cluster-name string           cluster name
  -h, --help                          help for stolon-sentinel
      --initial-cluster-spec string   a file providing the initial cluster specification, used only at cluster initialization, ignored if cluster is already initialized
      --log-color                     enable color in log output (default if attached to a terminal)
      --log-level string              debug, info (default), warn or error (default "info")
      --store-backend string          store backend type (etcdv2/etcd, etcdv3 or consul)
      --store-ca-file string          verify certificates of HTTPS-enabled store servers using this CA bundle
      --store-cert-file string        certificate file for client identification to the store
      --store-endpoints string        a comma-delimited list of store endpoints (use https scheme for tls communication) (defaults: http://127.0.0.1:2379 for etcd, http://127.0.0.1:8500 for consul)
      --store-key string              private key file for client identification to the store
      --store-prefix string           the store base prefix (default "stolon/cluster")
      --store-skip-tls-verify         skip store certificate verification (insecure!!!)
```

###### Auto generated by spf13/cobra on 15-Feb-2018
