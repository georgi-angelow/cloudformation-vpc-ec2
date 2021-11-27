aws cloudformation create-stack --stack-name development --template-body file://cf.yaml --profile example

aws cloudformation delete-stack --stack-name development --profile example
