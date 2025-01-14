---
title: "pgo_create_user"
---
## pgo create user

Create a PostgreSQL user

### Synopsis

Create a postgres user. For example:

    pgo create user --username=someuser --all --managed
    pgo create user --username=someuser  mycluster --managed
    pgo create user --username=someuser -selector=name=mycluster --managed
    pgo create user --username=user1 --selector=name=mycluster

```
pgo create user [flags]
```

### Options

```
  -h, --help                  help for user
      --managed               Creates a user with secrets that can be managed by the Operator.
      --password string       The password to use for creating a new user which overrides a generated password.
      --password-length int   If no password is supplied, this is the length of the auto generated password (default 22)
  -s, --selector string       The selector to use for cluster filtering.
      --username string       The username to use for creating a new user
      --valid-days int        Sets passwords for new users to X days. (default 30)
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

* [pgo create](/operatorcli/cli/pgo_create/)	 - Create a Postgres Operator resource

###### Auto generated by spf13/cobra on 4-Oct-2019
