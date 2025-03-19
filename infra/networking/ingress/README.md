# ingress

We are going to use an nginx ingress to our cluster.

Here it is the installation [guide](https://kubernetes.github.io/ingress-nginx/deploy/#quick-start).

Command to update the release:

```bash
$ helm upgrade --install ingress-nginx ingress-nginx \
      --repo https://kubernetes.github.io/ingress-nginx \
      --namespace ingress-nginx --create-namespace \
      -f values.yaml
```
