# Pattern-Exploiting Training (PET)
基于苏神代码的修改，苏神之前的代码prompt只能放在句子前面，因为[mask]的位置是一个固定的值。
现在修改后可以基于[CLS]和[SEP]这两个token来定位[mask]的位置，所以满足各种prompt的需求。

### 环境
bert4keras>=0.10.8, tensorflow = 1.15.0, keras = 2.3.1；

### 解读
苏神的博客：https://kexue.fm/archives/7764


