#回车和换行的替换
'
  $str = str_replace("\r"," ",$str);
  $str = str_replace("\n"," ",$str);
  $str = str_replace("\r\n"," ",$str);
  这里必须用双引号，单引号不起作用
'
