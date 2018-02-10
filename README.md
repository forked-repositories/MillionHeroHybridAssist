# MillionHeroHybridAssist V3
百万英雄、冲顶大会 辅助作答器 使用三引擎混合搜索 准确率超高 慎用、侵删！
2018/02/08 已更新
====
## 十分感谢`smileboywtu`原作者提供的源代码思路 
### 原Repo链接：<link>https://github.com/smileboywtu/MillionHeroAssistant</link><br>

本Repo根据其源代码进行了修改和汉化 支持三引擎搜索模式 准确率大幅上升<br>

使用时，请按照原作者`smileboywtu`的Repo说明进行配置，在此不再赘述。<br>
本Repo只是提升了相关性能，汉化加强并集成了ADB，大体框架仍然保持不变！<br>

<b>代码仅供技术交流使用，切勿用于任何其它用途！用于任何盈利用途后果自负！</b><br>
如有对西瓜视频、冲顶大会等相关利益方的侵权，请联系我立即删除。在此致以诚挚感谢！<br><br>

### 使用前须知 <br>
* 您在使用时，需要更换config.py中的baiduOCR等秘钥参数（现在的是没法使用的，需要您自行到百度开发者中心去申请OCR的秘钥并替换<link>https://cloud.baidu.com/</link>，具体操作办法百度一下都有）。否则无法使用！<br>
* 您必须在电脑中安装 Python3.5 或以上版本的环境<br>
* 同时为了您能够使用正常，请在使用前以管理员模式运行runfirst.bat批处理以初始化运行环境<br><br>

### ====  已更新 2018/02/08  ====<br>
* 1、加强的否认模式搜索<br>
* 2、新增知乎搜索模式<br>
* 3、新增对iOS设备的支持！期待已久！<br><br>

### ====  已更新 2018/02/02  ====<br>
* 1、将所有中文数字转换成阿拉伯数字<br>
* 2、对于题目中携带“未”“没有”"无"的，新增否定题目模式搜索<br>
* 3、双引擎搜索转并发线程<br>
* 4、对于答案中含题目中关键字的，给予足够提示<br>
* 5、搜索的时候，关键字去除前面的题目序号<br>
* 6、对于两个答案权重接近时，同样给出不可靠提示<br><br>

### ===  Upcoming Features ===<br>
* 1、修改现在的检索算法，让模糊题更快地找寻到正确答案<br>
* 2、尝试使用自适应算法给出更正确的解答
