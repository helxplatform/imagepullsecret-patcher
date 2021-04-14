# imagepullsecret-patcher

A simple Kubernetes [client-go](https://github.com/kubernetes/client-go) application that creates and patches imagePullSecrets to service accounts in all Kubernetes namespaces to allow cluster-wide authenticated access to a container registry.  This can be useful when your clusters hit Docker's image download limit for anonymous/free user accounts.

For install information see the [chart readme](helm).

Original code from https://github.com/titansoft-pte-ltd/imagepullsecret-patcher.
A blog post about their work: https://medium.com/titansoft-engineering/kubernetes-cluster-wide-access-to-private-container-registry-with-imagepullsecret-patcher-b8b8fb79f7e5
