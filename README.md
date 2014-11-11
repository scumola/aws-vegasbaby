
Launch a cloudformation stack

aws cloudformation create-stack \
    --stack-name net-inf-test$RANDOM \
    --template-body file:///Users/kgutwin/aws/aws-vegasbaby/net-inf-v2.json \
    --disable-rollback --parameters ParameterKey=KeyName,ParameterValue=vegasbaby 
