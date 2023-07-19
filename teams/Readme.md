# Teams

Each subdirectory represents a teams k8s workload.

## Single Tenant

For teams running their own k8s cluster, the cluster configuration files _must_
be put in a `clusters` subdirectory.

## Multi Tenant

If we run a multi-tenant setup we do _not_ need a `clusters` subdirectory for each team.
Everyting is deployed to a single cluster.
