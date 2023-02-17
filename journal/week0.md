# Week 0 — Billing and Architecture
## required homework/tasks
## install aws cli , I did it but I had some issuess in aws security as I put some information like the secret access key and region
I am providing the instruction I used for my configuration
I did follow these instructions

```
tasks:
  - name: aws-cli
    env:
      AWS_CLI_AUTO_PROMPT: on-partial
    init: |
      cd /workspace
      curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
      unzip awscliv2.zip
      sudo ./aws/install
      cd $THEIA_WORKSPACE_ROOT
      ```
      ![CLI CONFIG](https://user-images.githubusercontent.com/124487792/219653554-115ac51b-41a1-4f6c-a23f-b2147d418eab.png)
     
