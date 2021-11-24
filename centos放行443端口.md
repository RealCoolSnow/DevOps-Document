# 向防火墙添加端口
firewall-cmd --permanent --zone=public --add-port=443/tcp
# reload
systemctl reload firewalld
# 查看状态
firewall-cmd --list-all