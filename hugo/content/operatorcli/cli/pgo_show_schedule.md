---
title: "pgo_show_schedule"
---
## pgo show schedule

Show schedule information

### Synopsis

Show cron-like schedules.  For example:

	pgo show schedule mycluster
	pgo show schedule --selector=pg-cluster=mycluster
	pgo show schedule --schedule-name=mycluster-pgbackrest-full

```
pgo show schedule [flags]
```

### Options

```
  -h, --help                   help for schedule
      --no-prompt              No command line confirmation.
      --schedule-name string   The name of the schedule to show.
  -s, --selector string        The selector to use for cluster filtering.
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
