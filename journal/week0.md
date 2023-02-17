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

###  I created a lucid chart for a logical diagram 
 !.[Billing alarm image].(assets/logical%20diagram.png)
 Here is the [link for the logical diagram](https://lucid.app/lucidchart/07998726-1ecc-4eba-bbde-b847efbdfa4d/edit?viewport_loc=-1831%2C320%2C3347%2C1448%2C0_0&invitationId=inv_6793fffa-ed59-4092-9c91-63c57fc69b3b)
 

       ##**Home work challenges**
       I created a billing alarm using the was console
       !.[Billing alarm image].(assets/Billing%20alarm.png)
       I used Use EventBridge to hookup Health Dashboard to SNS and send notification when there is a EC2 health issue so I  created an health check by the console
       !.[Checking Health check ].(assets/health%20check.png)
      
       
       
       
       
       
      
      
      
     
