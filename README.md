Rime之“地球双拼”方案
----------------------------------
有朙月拼音的双拼方案，可不能缺地球拼音的双拼方案:

带声调的双拼方案---地球拼音＋朙月双拼+声调

td_pinyin.schema.yaml       
“带调自然码双拼”     默认声调;/,\符号为1234声

td_pinyin_abc.schema.yaml   
“带调智能ABC双拼”    默认声调;/,\符号为1234声

td_pinyin_flypy.schema.yaml   
“带调小鹤双拼”    默认声调;/,\符号为1234声

td_pinyin_mspy.schema.yaml  
“带调MSPY双拼”       默认声调-/,\符号为1234声(;=ing)

td_pinyin_pyjj.schema.yaml  
“带调拼音加加双拼”   默认声调;/,\符号为1234声

注：关于声调的定义方案： 

1、数字1234567890（用12345作五声，定义67890候选，用78906作五声，定义12345候选] 

2、符号;,./[']\-=（MSPY双拼方案使用了;键）

3、字母aeovui（要点:O导零声母，zh(z)\ch(c)\sh(s)模糊音,新华双拼还用wyx作声调]

4、`(grave),Tab,CapsLock,Shift_L,Shift_R作五声 

5、数字、符号、字母、功能键综合随机选用 







