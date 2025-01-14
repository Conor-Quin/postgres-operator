---
title: "pgo_delete_label"
---
## pgo delete label

Delete a label from clusters

### Synopsis

Delete a label from clusters. For example:

    pgo delete label mycluster --label=env=research
    pgo delete label all --label=env=research
    pgo delete label --selector=group=southwest --label=env=research

```
pgo delete label [flags]
```

### Options

```
  -h, --help              help for label
      --label string      The label to delete for any selected or specified clusters.
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

* [pgo delete](/operatorcli/cli/pgo_delete/)	 - Delete an Operator resource

###### Auto generated by spf13/cobra on 4-Oct-2019
