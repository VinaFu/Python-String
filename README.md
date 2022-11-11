# Python-String

耗时的都是type转变！！！

sum（）一般用在list里面，
sum（）的结果一般是integer

list  里面一般是integer
      有引号的话是string

      1. 从string转到 list：
         p = ‘123456’ - string
         new = [int(x) for x in p]
          # new = [1，2，3，4，5，6]

      2. 从integer 转 list：
         一般有一步先到string
         num = 123
         res = [int(x) for x in str(num)] --    int list
            # 先把转成string再转成integer，再放进list里面
            # new = [1,2,3]
            
         L = [str(x) for x in str(x)]     --    str list
         // ['1', '2', '3']
            
      3. 从integer到 string
      4. 从list到int
          
          s = [str(i) for i in list]
     
          # Join list items using join()
          res = int("".join(s))
            
      5. 从list到string


