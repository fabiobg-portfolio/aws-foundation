# aws-foundation

## Account and Users

- Root user - owner ID using email address - avoid doing daily tasks
- [IAM users](https://us-east-1.console.aws.amazon.com/iam/home?region=us-east-1#/home) - specific users with specific access permissions
  - Permissions - individual or by Group

## Computing

- EC2 - Elastic Cloud Computing
  - VMs according to your need - choose OS (Linux, Windows, etc...), CPU and Memory
    - e.g. Amazon Linux 2023, Ubuntu
  - AMI - choose a template image, save your image for backup, restore your image in different regions.
    - e.g. t3.micro (x86) or t4g.micro (ARM)
- EBS - Elastic Block Storage
  - Store your data - attach to EC2 VM as a Disk
    - e.g. 8G, 10G
  - Save snapshots in a different place (S3) for backup - define the frequency
- S3 - Simple Storage Service
  - Define the usage frequency - Frequent: Standard or Stardard IA; Infrequent: One Zone or Glacier.
 
 ## Design

 - Small Architecture sample: [Controle de Cadastro - Design.drawio](/Controle%20de%20Cadastro%20-%20Design.drawio)
