# aws-ecs-stack

## Copy Cloudformation templates to s3

```
aws s3 cp ./ s3://<bucketname>/ --recursive --exclude "*" --include "*.yaml"
```