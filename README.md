С�Ǻ������ļ�
=================


##˵����
��������ļ������Լ�����Windows�� weasle�������ļ���  
��Ϊ�ұ�����Linux���õ�Ҳ��Rime,��������ά��ibus-rime�Ĳֿ������������ļ�,��������windows�²����ڵ�ԭ���������½���һ��repo������С�Ǻ��������ļ�

-------------------------------
  
**�������֮���㽫����ʵ��:**

1. `<Ctrl>`��(Ĭ����`<Shift>`)�л���Ӣ��
2. ģ����
3. ` '[' �� ']' `��ҳ
4. ����״̬��Ҳ����ʹ��Ӣ�ı��(�����)�����ҿ��Է���������л���
5. �ʿ�

---------------------------------------------

**����Ҫ���Ĺ�����**

1. ��װС�Ǻ�
2. ��zip������ʽ�����ҵ����������ļ�
3. ����������`.yaml`�ļ�,������Rime�ļ�����(Ĭ��·��Ϊ:`C:\Users\username\AppData\Roaming\Rime`)
4. �ʿ�luna_pinyin.dict.yaml���ƶ����û��ļ���(�ɰ��û�������ͬ���˵�������)��
5. ���²���(Ĭ��·��Ϊ:`C:\Users\username\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\С�Ǻ�ݔ�뷨\��С�Ǻ������²���`),��������,��Ҳ�����ڿ�ʼ�˵����ҵ���һ���
6. �л���С�Ǻ����뷨,��`F4`(��`<Ctrl>+~`)�л���`����ƴ��-����`��`����ƴ��`
7. �����Ѿ�Ĭ������״̬��ʹ��Ӣ�ı����,�л���ȫ�Ƿ�ʽ�ǰ�`F4`,ѡ��`���->ȫ��`
8. ok,enjoy it!

-----------------------------------------

**������һЩ˵��,����Ȥ���Կ�һ��**

1. default.custom.yaml������ļ���������ȫ�ֵģ�  
    ������:�޸��������л���shift->Ctrl.,�ļ���ע�;���˵�������Ҽ�,�Լ���ֵͬ������

2. luna_pinyin_simp.custom.yaml
    ������:ʵ��`����ƴ��-����`��ģ����,�ļ��е�ע�;���˵����,ʵ������Щģ��,��Ҳ����ͨ���Լ��ܽ��﷨,�Զ���һЩģ��

3. alternative.yaml����luna_pinyin_simp.custom.yaml����ע�͵�˵��,ȡ��ע�͵�patch��������оͺ�
    ������: ʵ������״̬��Ҳʹ��Ӣ�ı���Լ�`'[' �� ']'`��ҳ,alternaive.yaml�е�ע��������ϸ��˵��
    
4. ����weasel.custom.yaml,������ר����С�Ǻ���һЩ�����ļ�.
    ������:���Լ���ע�Ͱ�,����д��
    
5. �ʿ�luna_pinyin.dict.yaml
�ο���ַ����https://code.google.com/p/rime-aca/downloads/detail?name=luna_pinyin.dict.yaml

a ���ݔ�뷨�����������°汾��rime_version>=0.9.9������ԓ�ļ��}�u���Ñ��ļ��A�У�Windows��%AppData%\Rime��Mac��~/Library/Rime��Linux��~/.config/ibus/rime/����
b ���ݔ�뷨�汾�^�ͣ���ԓ�ļ��}�u�������ļ��A�У�Windows�Р������bĿ�h/data����Mac�Р�/Library/Input Methods/Squirrel.app/Contents/SharedSupport/��Linux�Р� /usr/share/rime-data/���У����wͬ���ļ���
  
���²���,����:  
![weasle](http://ww4.sinaimg.cn/large/81d2b157jw1e7zjmlpjt5j208605pmx9.jpg "")

---------------------------------------------------------

����С�Ǻ���һ�����߾��Ǵʿ�,������ʿ����ð취���ǿ��Լ����ڵĻ���Ч�������,���ھͼ���dropboxͬ���û��ʿ�  

�ο���ַ:  

https://code.google.com/p/rimeime/wiki/UserGuide#%E5%90%8C%E6%AD%A5%E7%94%A8%E6%88%B6%E8%B3%87%E6%96%99  
https://gist.github.com/lotem/4483504  


�޸�installation.yaml����:

```
distribution_code_name: Weasel
distribution_name: "С�Ǻ�"
distribution_version: 0.9.26.1
install_time: "Sun Oct 13 15:44:09 2013"
installation_id: "yxjxx-win7"
rime_version: 1.0
sync_dir: 'C:\Dropbox\RimeSync'
```

Ȼ����ͼ�ν�����`�û�����ͬ��`����(Linux ��`rime_dict_manager -s`ͬ��)