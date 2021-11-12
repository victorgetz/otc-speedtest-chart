## Usage
How to install:

```shell
    export CHART_NAME=otc-speedtest
    export CHART_REPO_NAME=otc-speedtest-chart
    helm repo add $CHART_REPO_NAME https://iits-consulting.github.io/$CHART_REPO_NAME/
    helm search repo $CHART_NAME
    helm install $CHART_NAME $CHART_REPO_NAME/$CHART_NAME
```
# Description

Nginx which serves simple 1 MB Files