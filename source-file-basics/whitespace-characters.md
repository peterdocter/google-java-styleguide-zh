#### 2.3.1 空白字符

除了行结束符序列，ASCII水平空格字符(0x20，即空格)是源文件中唯一允许出现的空白字符，这意味着：

1.  所有其它字符串中的空白字符都要进行转义。
2.  制表符不用于缩进。
