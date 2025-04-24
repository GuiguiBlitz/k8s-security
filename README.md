# k8s-security
Dev sec con kubernetes security workshop


## Env setup

Install kind

```bash
# For AMD64 / x86_64
[ $(uname -m) = x86_64 ] && curl -Lo ./kind https://kind.sigs.k8s.io/dl/v0.27.0/kind-linux-amd64
chmod +x ./kind
sudo mv ./kind /usr/local/bin/kind
```

Init cluster 

`kind create cluster -n devseccon`

