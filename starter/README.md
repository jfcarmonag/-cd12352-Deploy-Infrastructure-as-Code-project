# CD12352 - Infrastructure as Code Project Solution
# Juan

## Spin up instructions
For creating the network run:
``./create.sh network network.yml network-parameters.json``
For creating the app, run:
``./create.sh udagram udagram.yml udagram-parameters.json``

## Tear down instructions
Run 
``aws cloudformation delete-stack --stack-name network``
``aws cloudformation delete-stack --stack-name udagram``


## Other considerations
The s3 bucket with the app is in the udagram parameters. It can be changed with
your own bucket.

