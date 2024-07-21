Are you starting off with data migration to the AWS cloud ?

If yes, this step by step tutorial will get you started in minutes, saving a lot of time in researching.

The process includes:
- VPC setup
- RDS setup
- EC2 setup
- Backing-up your MYSQL database
- Exporting the backup file to the EC2 server.
- Importing the data into your database.

Happy Learning Data Gurus!!!!

1.	ssh -i location_of_pem_file ec2-user@ec2-instance-public-dns-name
2.	sudo dnf update -y
3.	sudo dnf install mariadb105
4.	scp -r -i pem file db_name ec2-DSN-Value: new-DB-backup-file-name 
5.	source backup.sql;

