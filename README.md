# magma-artifactory-helm-promote

Please download the `.tgz` versions as per your need.

https://artifactory.magmacore.org/artifactory/helm/ \
https://artifactory.magmacore.org/artifactory/helmtest/

Clone magma repo:
```bash
git clone https://github.com/magma/magma.git
```

Go to the scripts folder:
```bash
cd magma/orc8r/tools/helm/
```

Set username and token:
```bash
export HELM_CHART_MUSEUM_TOKEN=xxxx
export HELM_CHART_MUSEUM_USERNAME=xxxx
```

Publish helm charts:
```bash
MAGMA_VERSION=1.8.0
./promote.sh orc8r-${MAGMA_VERSION}.tgz
./promote.sh cwf-orc8r-${MAGMA_VERSION}.tgz
./promote.sh fbinternal-orc8r-${MAGMA_VERSION}.tgz
./promote.sh feg-orc8r-${MAGMA_VERSION}.tgz
./promote.sh lte-orc8r-${MAGMA_VERSION}.tgz
./promote.sh domain-proxy-${MAGMA_VERSION}.tgz
```

