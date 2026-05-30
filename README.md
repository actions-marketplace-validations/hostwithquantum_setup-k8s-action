# setup-k8s-action

A composite action to setup k8s tools and write the kubeconfig to `~/.kube/config` so `kubectl` works with no extra setup.

Options:

- environment
- config-staging
- config-production

> [!IMPORTANT]
> **v0.6.1**: Location is now the default: `~/.kube/config`.

Uses:

- [`yokawasa/action-setup-kube-tools`](https://github.com/yokawasa/action-setup-kube-tools)
