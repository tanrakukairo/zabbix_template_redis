# zabbix_template_redis

redis Template for Zabbix ~> 3.4.

Necessary "Dependent Item". Put userparameter_redis.conf in Include-UserParameter's Directory.

- ZABBIX 3.4用 redisのテンプレートです。
- UserParameterのワインライナーでinfoをJSON化して、依存アイテムで各値を入れてます。アイテムに設定してないのもあります。
- dbもLLDで取ってきます。
- telnetでredisたたいているので、CentOSとかは入れてください。
- FreeBSD11/CentOS7.1以上で動きます。

このテンプレートはMIT Licenseです。
