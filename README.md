# mysqlBackUp
mysql备份脚本

git clone https://github.com/luckman666/mysqlBackUp.git

chmod +x /XXXXXX/mysqlBackup.sh

crontab -e

00 03 * * * /XXXXXX/mysqlBackup.sh

恢复

mysql -u username -p databse < backup.sql
