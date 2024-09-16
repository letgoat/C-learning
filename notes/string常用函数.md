字符处理函数：
isalpha();
isdigit();
isspace();
islower();
isprint();
isupper();
isxdigit();
tolower();
toupper();

s.substr(pos,n);

s.insert(pos,args);
s.erase(pos,len);
s.assign(args);
s.append(args);
s.replace(range,args);
上述中的args可以是下列形式之一；append和assign可以使用所有形式
str不能与s相同，迭代器b和e不能指向s
str: 字符串str
str,pos,len  str中从pos开始最多len个字
cp,len

string搜索操作
s.find(args)
s.rfind(args)
s.find_first_of(args)
s.find_last_of(args)
s.find_first_not_of(args)
s.find_first_not_of(args)

