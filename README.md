# collector-aws

This repo contains the CloudFormation Stacks for creation of

* network
* database
* compute resources

# Troubleshooting
## Check DB connection from inside EC2 (Amazon Linux 2023)

```bash
sudo dnf update -y
sudo dnf install mariadb105-server
mysql -u MY_USER -p`MY_PASSWORD` -h MY_HOST -P 3306
```

