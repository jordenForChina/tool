

# ��� #

1. ʲô�� cookie?
2. cookie ��ȡ������
3. ��װ�� cookie

# �γ����� #

## ʲô�� cookie? ##

cookie����������ҳ����Ϣ

���磺 �Զ���¼����ס�û������洢��Ϸ���� �ȵ�

### ���� ###


URL: ͳһ��Դ·����  Э�飺�������˿ں�/ ·����ɵ�

http://www.baidu.com:80/xinwen
https://www.baidu.com
ftp://
smtp://


ֻҪ Э�顢�������˿� һ�£���ô cookie ���Թ���

http://www.baidu.com:80/xinwen
http://www.baidu.com:80/blog
��ͬһ��cookie

����ָ��ͬһ̨����
http://sina.weibo.com
http://t.sina.com
��� cookie ��һ��

file:///D:/%E8%AF%BE%E5%A0%82%E8%B5%84%E6%96%99/day13/demo1-cookie%E4%BB%8B%E7%BB%8D.html
��Ϊ chrome �����������洢���ص�cookie�� ѧϰ�� Firefox �����






1. ͬһ����վ������ҳ�湲��һ��cookie
2. ��������С����
3. ����ʱ��


## cookie ʹ�� ##

### ���� cookie ###

```
document.cookie = "username=zhangsan"; 
// expires= ����ʧЧʱ��
document.cookie = "password=123;expires=" + new Date(); 
```

### ��ȡ cookie ###

document.cookie


## ��װ���� ##

 * ���һ��cookie
 * ��ȡһ��cookie
 * ɾ��cookie
 

### �����û������� ###

### ����ͼƬλ�� ###

### ���빺�ﳵ ###


## �Ự���ټ��� ##

session��cookie���ǻỰ���ټ�����
����������¼����ͻ��˸�������֮��ͨ��ʱ��Ҫ�õ���һЩ���ݡ�

session�������ڷ������ڴ���, cookie����ڿͻ��˱���Ӳ����
                           sessionId �Ǵ��ڿͻ��˱��ص�

�ͻ���ÿ�η��ʷ���������Я���÷��������͵����ص�cookie�ļ�
��ʹ��session����ͻ�����Ϣʱ��cookie�ļ�������Ҫ��������ͻ�����Ϣ��ֻ��Ҫ�򵥼�¼һ��sesssion��ID��


---------

����������ȫ��ֹcookie���ܵĻ����������վ�Ļ��������޷�����ʹ��


## С���� ##

��������ı������⣬ʹ�����·������ܽ��������������

ʹ��encodeURIComponent('xxxxx')���� �洢�� cookie ��
ʹ��decodeURIComponent(document.cookie)����



# ��ҵ #

1. ��ק��Ч������
2. �û�����ı���
3. ���ﳵ

