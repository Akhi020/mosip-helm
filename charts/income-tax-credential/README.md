# Income Tax Credential Service

## Install
cd mosip-helm/charts/income-tax-credential
helm lint income-tax-credential
cd ..
helm install income-tax-credential ./income-tax-credential -n income-tax --create-namespace
