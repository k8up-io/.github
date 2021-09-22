# K8up Backup Operator

K8up is a Kubernetes backup operator based on [Restic](https://restic.readthedocs.io) that will handle PVC and application backups on a Kubernetes or OpenShift cluster.

Just create a `schedule` and a `credentials` object in the namespace you’d like to backup.
It’s that easy. K8up takes care of the rest. It also provides a Prometheus endpoint for monitoring.

## Documentation

The documentation is written in AsciiDoc and published with Antora to [k8up.io](https://k8up.io/).
It's source is available in the `docs/` directory.

## Getting Started

We have a [Getting Started](https://github.com/k8up-io/getting-started) guide to quickly learn how k8up will help you.

## Contributing

We welcome contributions in all of our repositories.
The k8up-operator is written in Go, licensed under the terms of the BSD 3-clause license and its main repository is [github.com/k8up-io/k8up](https://github.com/k8up-io/k8up).
