---
title: "pgo_show_benchmark"
---
## pgo show benchmark

Show benchmark information

### Synopsis

Show benchmark results for clusters. For example:

	pgo show benchmark mycluster
	pgo show benchmark --selector=pg-cluster=mycluster

```
pgo show benchmark [flags]
```

### Options

```
  -h, --help              help for benchmark
  -s, --selector string   The selector to use for cluster filtering.
```

### Options inherited from parent commands

```
      --apiserver-url string     The URL for the PostgreSQL Operator apiserver.
      --debug                    Enable debugging when true.
  -n, --namespace string         The namespace to use for pgo requests.
      --pgo-ca-cert string       The CA Certificate file path for authenticating to the PostgreSQL Operator apiserver.
      --pgo-client-cert string   The Client Certificate file path for authenticating to the PostgreSQL Operator apiserver.
      --pgo-client-key string    The Client Key file path for authenticating to the PostgreSQL Operator apiserver.
```

### SEE ALSO

* [pgo show](/operatorcli/cli/pgo_show/)	 - Show the description of a cluster

###### Auto generated by spf13/cobra on 4-Oct-2019
