# tf_poems
基于字级别的写诗模型，[简单的藏头诗]，填词诗   
基于tf编写的一个写诗模型. 数据来自于唐诗.   
在这个模型中进行了改动：  
https://github.com/Irvinglove/tensorflow_poems   

需要:  
   tensorflow-gpu  
   numpy  
   python2.7  
运行样列:    
如果没有GPU,你需要安装cpu版本tensorflow-cpu 将/gpu:0 改成 /cpu:0   
如果有GPU,可以直接运行train.py文件.   

效果样例:   

[INFO] 作诗一首   
  
----------1 . 藏头诗----------   
----------2 . 填词写诗----------    
    
选择类型:1   
输入关键字,多个关键字以','分割龚,细,军   
   
龚痛秦关好，将兵道寂均。  
细盆兼气劲，水压积花时。  
军舌休遗约，衣铺万国催。  
会稽师休出，抱疾闭荒祠。  
[INFO] 作诗一首  
    
----------1 . 藏头诗----------   
----------2 . 填词写诗----------   
   
选择类型:2   
输入关键字,多个关键字以','分割我,爱,中,华   
   
旦暮我前爱无私，笙歌鸾阁冷霄澜。   
泛中高会南华岳，回处寒灯照驻生。   
约雨长留三寸后，伏猿争肯学翻翻。   
幽夔花下王孙恋，怨竹开门凤辇来。  
近种新诗潜舞定，何堪歌吹欲冥搜。  
   
