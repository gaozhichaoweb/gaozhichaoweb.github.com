# 替换\r\n
用户输入数据里有换行，传到Js里获取会提示出错
```markdown
$str = str_replace("\r"," ",$str);
$str = str_replace("\n"," ",$str);
$str = str_replace("\r\n"," ",$str);
```
这里必须使用双引号，单引号不起作用
