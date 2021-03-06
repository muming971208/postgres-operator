---
title: "pgo show"
---
## pgo show

Show the description of a cluster

### Synopsis

Show allows you to show the details of a policy, backup, pvc, or cluster. For example:

	pgo show backup mycluster
	pgo show backup mycluster --backup-type=pgbackrest
	pgo show cluster mycluster
	pgo show config
	pgo show pgouser someuser
	pgo show policy policy1
	pgo show pvc mycluster
	pgo show namespace
	pgo show workflow 25927091-b343-4017-be4b-71575f0b3eb5
	pgo show user --selector=name=mycluster

```
pgo show [flags]
```

### Options

```
  -h, --help   help for show
```

### Options inherited from parent commands

```
      --apiserver-url string     The URL for the PostgreSQL Operator apiserver that will process the request from the pgo client.
      --debug                    Enable additional output for debugging.
      --disable-tls              Disable TLS authentication to the Postgres Operator.
      --exclude-os-trust         Exclude CA certs from OS default trust store
  -n, --namespace string         The namespace to use for pgo requests.
      --pgo-ca-cert string       The CA Certificate file path for authenticating to the PostgreSQL Operator apiserver.
      --pgo-client-cert string   The Client Certificate file path for authenticating to the PostgreSQL Operator apiserver.
      --pgo-client-key string    The Client Key file path for authenticating to the PostgreSQL Operator apiserver.
```

### SEE ALSO

* [pgo](/pgo-client/reference/pgo/)	 - The pgo command line interface.
* [pgo show backup](/pgo-client/reference/pgo_show_backup/)	 - Show backup information
* [pgo show cluster](/pgo-client/reference/pgo_show_cluster/)	 - Show cluster information
* [pgo show config](/pgo-client/reference/pgo_show_config/)	 - Show configuration information
* [pgo show namespace](/pgo-client/reference/pgo_show_namespace/)	 - Show namespace information
* [pgo show pgadmin](/pgo-client/reference/pgo_show_pgadmin/)	 - Show pgadmin deployment information
* [pgo show pgbouncer](/pgo-client/reference/pgo_show_pgbouncer/)	 - Show pgbouncer deployment information
* [pgo show pgorole](/pgo-client/reference/pgo_show_pgorole/)	 - Show pgorole information
* [pgo show pgouser](/pgo-client/reference/pgo_show_pgouser/)	 - Show pgouser information
* [pgo show policy](/pgo-client/reference/pgo_show_policy/)	 - Show policy information
* [pgo show pvc](/pgo-client/reference/pgo_show_pvc/)	 - Show PVC information for a cluster
* [pgo show schedule](/pgo-client/reference/pgo_show_schedule/)	 - Show schedule information
* [pgo show user](/pgo-client/reference/pgo_show_user/)	 - Show user information
* [pgo show workflow](/pgo-client/reference/pgo_show_workflow/)	 - Show workflow information

###### Auto generated by spf13/cobra on 2-Jul-2020
