# FHEM Container Helm Chart

## Using Helm Chart
* clone or download repository
* helm install <NAME> </path/to/repoDir> -n <NAMESPACE> --create-namespace

for yout own values create a value file with your changes an install with
* helm install <NAME> </path/to/repoDir> -f <MY_OWN_VALUEFILE>-n <NAMESPACE> --create-namespace
