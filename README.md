### helm upgrade -f .\stepllader-values.yaml -i stapladder-test .\bankly-product\ --dry-run --debug




### helm upgrade -f .\stepllader-values.yaml --set -i stapladder-test .\bankly-product\ --dry-run --debug

### helm upgrade -f .\stepllader-values.yaml --set isCanary=false,enviroment="production" -i stapladder-test1 .\bankly-product\ --dry-run --debug