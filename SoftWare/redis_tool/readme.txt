Windowsƽ̨Redis��װ

���ص�ַ: http://code.google.com/p/servicestack/wiki/RedisWindowsDownload

Redis�ļ��������¼����ļ�

redis-server.exe ���������

redis-check-dump.exe ���������ݿ���

redis-check-aof.exe ��������־���

redis-benchmark.exe �����ܲ��ԣ�����ģ��ͬʱ��N���ͻ��˷���M�� SETs/GETs ��ѯ (������ Apache ��ab ����).

ָ��redis�������ļ�����û��ָ������ʹ��Ĭ������
��ѹĿ¼�ŵ�E:\redis-2.0.2

E:\redis-2.0.2>redis-server.exe redis.conf

redis-cli.exe�������пͻ��ˣ�������

E:\redis-2.0.2>redis-cli.exe -h 127.0.0.1 -p 6379

����һ��Key����ȡ���ص�ֵ:

redis> set mykey somevalue

OK
.....
��ʼʹ��redis�ɡ�