# Finished & tested Cloudformation Templates
# Be careful to change the key name to a proper one at the Webserver template line 9

aws --region eu-central-1 cloudformation create-stack --template-body file://template.yaml --stack-name stackname --capabilities CAPABILITY_IAM
