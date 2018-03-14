1.正则表达式
定义：是一个特殊的字符序列，用于检查字符串是否与某种模式匹配。
re模块使python具有全部正则表达式功能。
compile函数根据一个字符串与可选标志参数生成一个正则表达式。

1.1 re.match函数
从字符串的起始位置开始匹配，如果起始位置匹配不成功则返回none。
re.match(pattern, string, flag=0)
pattern   正则表达式
string    字符串
flag      标志位

group(num)或groups()匹配对象生成匹配表达式。
