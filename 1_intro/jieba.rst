======
jieba
======

:duref:`ref <“结巴”中文分词：做最好的 Python 中文分词组件>`

**“Jieba”** (Chinese for “to stutter”) Chinese text segmentation: built to be the best Python Chinese word segmentation module.
完整文档见 README.md
`GitHub: https://github.com/fxsjy/jieba`_

-----
特点
-----
**支持三种分词模式：**

    1. 精确模式，试图将句子最精确地切开，适合文本分析；
    2. 全模式，把句子中所有的可以成词的词语都扫描出来, 速度非常快，但是不能解决歧义；
    3. 搜索引擎模式，在精确模式的基础上，对长词再次切分，提高召回率，适合用于搜索引擎分词。

**支持繁体分词**

**支持自定义词典**

**MIT 授权协议**

在线演示：
.. _a link: http://jiebademo.ap01.aws.af.cm/