360CPS API(PHP)
==============

���
-------------
���������ǻ���360CPS�����ĵ�ʵ�ֵ�һ���򵥿�ܣ�������Ա����ͨ���޸ĸÿ�ܵ� api_config.php��plugin/CPS360_plugin_api.php �ļ���ʵ����Ҫ��CPS�ӿڹ��ܡ�

�ӿڵ�ַ
-------------
	1��������ת�ӿڣ�http://example.com/360cps/api_redirect.php
	2��������ѯ�ӿ�: http://example.com/360cps/api_order.php
	3�����˲�ѯ�ӿ�: http://example.com/360cps/api_check.php

�ر�˵�����û��¶���ʱ����ͨ������$CPS360_plugin_api->order_save()��������¼CPS�Ķ���


�ļ�˵��
-------------
	1��core/CPS360_api.class.php		�ӿں�����
	2��core/CPS360_models.class.php	����ģ��
	3��core/CPS360_plugin.class.php	���ģ��
	4��plugin/CPS360_plugin_api.php	���ģ�壨���޸ģ�
	5��api_config.php					�ӿ�������Ϣ�����޸ģ�
	6��api_redirect.php				������ת�ӿ�
	7��api_order.php					������ѯ�ӿ�
	8��api_check.php					���˲�ѯ�ӿ�

�����ĵ�
-------------
http://open.union.360.cn/apidoc