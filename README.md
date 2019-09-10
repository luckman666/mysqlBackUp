# mysqlBackUp
mysql备份脚本

使用方式：

chmod 600 /opt/mysqlBackup.sh

chmod +x /opt/mysqlBackup.sh

crontab -e

00 03 * * * /root/mysqlBackup.sh

恢复

mysql -u username -p databse < backup.sql
