# Income Tax Credential Service

## Install

cd mosip-helm/charts/income-tax-credential

helm lint income-tax-credential

cd ..

helm install incometax-credential-service ./income-tax-credential -n incometax-credential --create-namespace
