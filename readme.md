Traefik Ingress redirection sandbox.

The run.sh script allow to start a k3s stack thanks the [k3d tool](https://github.com/rancher/k3d).

It will generate a certificate for `whoami` domain with [mkcert](https://github.com/FiloSottile/mkcert) in the /certs directory.

```shell script
# Start the kubernetes cluster and apply the conf from /conf directory
./run.sh start
# Stop a delete the kubernetes cluster
./run.sh stop
```