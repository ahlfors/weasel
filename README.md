С�Ǻ������ļ�
=================


##˵����
��������ļ������Լ�����Windows��weasle�������ļ���  
��Ϊ�ұ�����Linux���õ�Ҳ��Rime,����������Mint16֮����ָ�������,����ibusҲû��fcitx����,���ڸ���fcitx-sunpingyin��fcitx-sougoupinyin��(fcitx��Mint16�²�����������,��֪����ʲôԭ��).�����Ҿ�ϲ�ķ�����ibus-rime��Ҫ�޸������ļ�����ʵ�ֵĴ󲿷ֹ���,fcitx������ͼ�ν���������.

-------------------------------
  
**�������֮���㽫����ʵ��:**

1. `<Ctrl>`���л���Ӣ��(Ĭ����`<Shift>`)
2. ģ����
3. `[` �� `]`��ҳ;`,`��`.`;`Tab`��`shift+Tab`Ҳ����������ҳ
4. ����״̬��Ҳ����ʹ��Ӣ�ı��(�����)�����ҿ��Է���������л���
5. �ʿ�

---------------------------------------------

**����Ҫ���Ĺ�����**

1. ��װ[С�Ǻ�](https://code.google.com/p/rimeime/wiki/Downloads)
2. ��zip������ʽ����[�ҵ����������ļ�](https://github.com/yxjxx/weasel)
3. ����������`.yaml`�ļ�,������Rime�ļ�����(Ĭ��·��Ϊ:`C:\Users\<your_username>\AppData\Roaming\Rime` **Notice:replace <your_username> with your real username**)
5. ���²���(Ĭ��·��Ϊ:`C:\Users\username\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\С�Ǻ�ݔ�뷨\��С�Ǻ������²���`),��������,��Ҳ�����ڿ�ʼ�˵����ҵ���һ���
6. �л���С�Ǻ����뷨,��`F4`(��`<Ctrl>+~`)�л���`����ƴ��-����`
7. �����Ѿ�Ĭ������״̬��ʹ��Ӣ�ı����,�л���ȫ�Ƿ�ʽ�ǰ�`F4`,ѡ��`���->ȫ��`
8. �Զ����ݶ���
9. ok,enjoy it!

-----------------------------------------

**������һЩ˵��,����Ȥ���Կ�һ��**

1. default.custom.yaml������ļ���������ȫ�ֵģ�  ������:�޸��������л���shift->Ctrl.,�ļ���ע�;���˵�������Ҽ�,�Լ���ֵͬ������

2. luna_pinyin_simp.custom.yaml  ������:ʵ��`����ƴ��-����`��ģ����,�ļ��е�ע�;���˵����,ʵ������Щģ��,��Ҳ����ͨ���Լ��ܽ��﷨,�Զ���һЩģ��

3. alternative.yaml����luna_pinyin_simp.custom.yaml����ע�͵�˵��,ȡ��ע�͵�patch��������оͺ�������: ʵ������״̬��Ҳʹ��Ӣ�ı���Լ�`'[' �� ']'`��ҳ,alternaive.yaml�е�ע��������ϸ��˵��
    
4. ����weasel.custom.yaml,������ר����С�Ǻ���һЩ�����ļ�.
    
5. �ʿ�luna_pinyin.dict.yaml
�ο���ַ����https://code.google.com/p/rime-aca/downloads/detail?name=luna_pinyin.dict.yaml ��ԓ�ļ��}�u���Ñ��ļ��A�У�Windows��%AppData%\Rime��Mac��~/Library/Rime��Linux��~/.config/ibus/rime/����
���²���,����:  
![weasle](http://ww4.sinaimg.cn/large/81d2b157jw1e7zjmlpjt5j208605pmx9.jpg "")

6. �Զ����ݶ���.![�Զ���](http://ww1.sinaimg.cn/large/81d2b157jw1eegnzlfgmqj20e7068aan.jpg "")
7. �Զ��巭ҳ��.![��ҳ](http://ww1.sinaimg.cn/large/81d2b157jw1eego55or8uj20le094mzb.jpg "")
8. ����С�Ǻ���һ�����߾��Ǵʿ�,������ʿ����ð취���ǿ��Լ����ڵĻ���Ч�������,���ھͼ���dropboxͬ���û��ʿ�  
�ο���ַ:  
https://code.google.com/p/rimeime/wiki/UserGuide#%E5%90%8C%E6%AD%A5%E7%94%A8%E6%88%B6%E8%B3%87%E6%96%99  
https://gist.github.com/lotem/4483504  
�޸�installation.yaml����:

```
distribution_code_name: Weasel
distribution_name: "С�Ǻ�"
distribution_version: 0.9.26.1
install_time: "Sun Oct 13 15:44:09 2013"
installation_id: "yxjxx-win7" #��Ҫ�������� ͬ��Ŀ¼������,Ĭ����һ��id
rime_version: 1.0
sync_dir: 'C:\Dropbox\RimeSync'#��Ҫ�������� ͬ��Ŀ¼
```
Ȼ����ͼ�ν�����`�û�����ͬ��`����(Linux ��`rime_dict_manager -s`ͬ��)    

9.Linux �����²��������`$rm ~/.config/ibus/rime/default.yaml; ibus-daemon �Cdrx`  
�������:`current session already has an ibus-daemon.`
�Ҽ��������ϵ�Rimeͼ��restart����