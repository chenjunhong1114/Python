#Python
### 我们人类思维是习惯于“四舍五入”法，你有什么办法使得 int() 按照“四舍五入”的方式取整吗？
- 5.4 “四舍五入”结果为：5，int(5.4+0.5) == 5   
- 5.6 “四舍五入”结果为：6，int(5.6+0.5) == 6
### Python3中，一个语句可以分成多行书写吗？
可以，一行过长的语句可以使用反斜杠或者括号分解成几行，不妨试试  
- 3 > 4 and \  
  1 < 2  
- ( 3 > 4 and   
  1 < 2 )  
### 有什么方法可以打印let's go
- 'let\'s go'
- "let's go"
### 当用户输入错误类型（不是整型）
- while not temp.isdigit():
###补充： 
***s为字符串 ***
- s.isalnum() 所有字符都是数字或者字母，为真返回 Ture，否则返回 False。   
- s.isalpha() 所有字符都是字母，为真返回 Ture，否则返回 False。   
- s.isdigit() 所有字符都是数字，为真返回 Ture，否则返回 False。   
- s.islower() 所有字符都是小写，为真返回 Ture，否则返回 False。   
- s.isupper() 所有字符都是大写，为真返回 Ture，否则返回 False。   
- s.istitle() 所有单词都是首字母大写，为真返回 Ture，否则返回 False。   
- s.isspace() 所有字符都是空白字符，为真返回 Ture，否则返回 False。  