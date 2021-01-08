# aws-circleci
## Command to run:

export AWS_ACCESS_KEY_ID=$AWS_ACCESS_KEY_ID
export AWS_SECRET_ACCESS_KEY=$AWS_SECRET_ACCESS_KEY
export AWS_DEFAULT_REGION=$AWS_DEFAULT_REGION

aws cloudformation create-stack --stack-name myfirsttest --region $AWS_DEFAULT_REGION --template-body file://stack.yml
