优化前LoC: 210
优化后LoC: 94

优化了以下方面：
1.禁止输入多个小数点
2.输入小数点时，如果有需要，前面会自动补0
3.在没有输入任何运算符和数字之前计算器的结果框显示0
4.限制了输入算式的长度，避免过长
5.出现错误不会弹窗，而是显示在结果框中

Toolkits的使用心得：
这次使用了jQuery 来实现计算器，很方便，同时也使代码简洁了不少，代码长度大大减少，可读性也进一步增强了，但还有望提高。