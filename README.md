# Zabbix-Monitor zabbix 监控服务


说明：

1、zabbix_mysql                                 监控mysql(版本：5.5.42)的各个数值

   zabbix_mysql/zbx_export_templates.xml        模板文件

   zabbix_mysql/conf/zabbix_agentd.conf         添加监控脚本参数

   zabbix_mysql/script/getmysqlinfo.sh          监控脚本，里面的参数根据需要修改


2、zabbix_redis                                 监控redis(版本：2.8.24) 自动发现，自动创建items

   zabbix_redis/zbx_export_templates.xml        模板文件

   zabbix_redis/conf/zabbix_agentd.conf         添加监控脚本参数
    
   zabbix_redis/script/redisdbports.sh          自动发现脚本

   zabbix_redis/script/redismonitor.sh          监控脚本，里面的参数根据需要修改

