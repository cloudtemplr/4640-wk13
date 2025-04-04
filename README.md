# 4640-w13-lab-start-w25

See D2L for lab instructions

- When is the state file created?

The terraform state file which is terraform.tfstate is created when we run the terraform command `terraform apply for the first time.

- When is the lock file present?

The lock file is created while running terraform apply before entering yes on the operation. 

- Is the lock file always in the bucket after it is created?

No. The lock file is temporary. It will disappear after entering yes from the terraform apply operation and be saved in the DB we configured if we did. 

![lock-file](<스크린샷 2025-04-04 094354.png>)
![state-file](<스크린샷 2025-04-04 094419.png>)