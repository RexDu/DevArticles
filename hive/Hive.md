# Hive�����̳�

һ����������
���ػ�������

```bash
source /etc/profile
```

����`Hive`����

```bash
nohup hive --auxpath /opt/elasticsearch-hadoop-5.6.0/dist/elasticsearch-hadoop-5.6.0.jar --service metastore &
```

����ͣ����

```bash
ps -ef|grep hive|grep -v grep |awk '{print $2}'|xargs -n 1 -i kill -9 {}
```

