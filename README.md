# magma-artifactory-helm-promote

Clone magma repo:
```bash
git clone https://github.com/magma/magma.git
```

Go to the scripts folder:
```bash
cd magma/orc8r/tools/helm/
```


Publish helm charts:
```bash
./promote.sh cwf-orc8r-0.2.2.tgz
./promote.sh fbinternal-orc8r-0.2.2.tgz
./promote.sh feg-orc8r-0.2.5.tgz
./promote.sh lte-orc8r-0.2.6.tgz
./promote.sh orc8r-1.5.27.tgz
./promote.sh domain-proxy-0.1.0.tgz
```

