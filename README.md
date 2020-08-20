# custom-resource-cf

What is a custom resource?

CloudFormation has lots of defined resources that you can use to provision AWS resources. However, if you want to provision an AWS resource that CloudFormation doesn't support yet, or if you want to include some complicated logic during your CloudFormation stack creation / update / deletion, you can use a custom resource to do that easily. Custom resources are basically just Lambda functions that get called by CloudFormation. While not complicated, they do require a bit of configuration to get going. This repository is design to kickstart building custom resources, having the scaffolding for Python, Node.js, and Java functions (Ruby coming soon!) and examples in both YML and JSON.