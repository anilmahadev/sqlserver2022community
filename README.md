**A free Community SQL Server 2022 Container - contains Sample databases to get started immediately!**

Pull the image 

**docker pull anilmahadev/sqlserver2022community
**
Run the image

**docker run -e "ACCEPT_EULA=Y" -e "MSSQL_SA_PASSWORD=P@ssw0rd1234" -p 1433:1433 -d anilmahadev/sqlserver2022community:latest**

Connect to SSMS
**hostname: localhost SQL Auth: Username: sa Password: P@ssw0rd1234 --> Change and disable the SA user after creating another SYSADMIN user. Encryption: Mandatory**

Enjoy!!
