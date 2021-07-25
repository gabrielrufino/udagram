# Udagram - Cloud Formation

**Create command**

```bash
aws cloudformation create-stack \
  --stack-name udagram \
  --template-body file://infra.yml \
  --parameters file://params.json \
  --capabilities "CAPABILITY_IAM" "CAPABILITY_NAMED_IAM" \
  --region=us-west-2
```

**Update command**

```bash
aws cloudformation update-stack \
  --stack-name udagram \
  --template-body file://infra.yml \
  --parameters file://params.json \
  --capabilities "CAPABILITY_IAM" "CAPABILITY_NAMED_IAM" \
  --region=us-west-2
```
