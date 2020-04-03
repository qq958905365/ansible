如果给你500台服务器，你会如何管理？

- 服务器均为Linux，操作系统有Redhat、CentOS、Ubuntu
- 服务器上运行着各类应用，如Nginx、MySQL、Redis、ElasticSearch、Python、Java等
- 简述主要思路，并尝试编写一些脚本，体现出主要内容即可
- 独立完成，提供代码的 GitHub 仓库链接即可


我选择通过ansible来管理500台服务器，这500台服务器采用zabbix来实现对其监控

一）ansible的安装步骤见“ansible安装”文件夹  
    ansible-install为ansible的安装以及配置说明  

二）ansible管理nginx见“nginx”文件夹  
    nginx_config_manage.yml为nginx配置文件的管理  
    
三）ansible管理mysql见“mysql”文件夹  
    mysql_upgrade.yml为mysql的升级脚本  
    mysql_backup.yml为mysql的备份脚本  
    
四）ansible管理redis见“redis”文件夹  
    redis_check.yml为redis集群健康性检查的脚本  
    
五）ansible管理python见“python”文件夹  
    python_install.yml为python环境变量的安装  
    
六）ansible管理java见“java”文件夹  
    java_manage.yml为java应用的操作，  

七）ansible管理zabbix见“zabbix”文件夹  
    zabbix_install.yml为安装zabbix脚本     


