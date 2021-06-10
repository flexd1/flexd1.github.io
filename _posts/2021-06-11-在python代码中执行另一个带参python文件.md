- 主程序代码
```
import os
sent='跳跳糖'
os.system("python code.py %s" % sent)
```

- 调用程序代码
```
import sys
sent=sys.argv[1]
print(sent)
# 其中sys.argv[1]就代表传入的参数，这种用法应该是可以传入多个参数的，没有过多研究，需要的可以自己研究一下
```
- 如果只执行不传参
```
#在code.py中import sys
#在helloworld.py中import os
#os.system("python code.py")
```