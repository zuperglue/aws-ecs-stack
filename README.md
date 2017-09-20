# aws-ecs-stack

### Copy Cloudformation templates to s3

```
aws s3 cp ./ s3://<bucketname>/ --recursive --exclude "*" --include "*.yaml"
```

### Make ecs executable and copy to /usr/local/bin

```
chmod +x ecs
cp ecs /usr/local/bin
```