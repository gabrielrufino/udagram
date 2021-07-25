# Udagram - Cloud Formation

```bash
aws cloudformation create-stack \
  --stack-name udagram \
  --template-body file://infra.yml \
  --parameters file://params.json \
  --capabilities "CAPABILITY_IAM" "CAPABILITY_NAMED_IAM" \
  --region=us-west-2
```

```bash
aws cloudformation update-stack \
  --stack-name udagram \
  --template-body file://infra.yml \
  --parameters file://params.json \
  --capabilities "CAPABILITY_IAM" "CAPABILITY_NAMED_IAM" \
  --region=us-west-2
```
