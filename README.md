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
         temp = sum([int(x) for x in p])
            # 39 - integer
         new = [int(x) for x in str(temp)]
            # 先把转成string再转成integer，再放进list里面
            # new = [3，9]
            
      3. 从integer到 string
      4. 从list到int
      5. 从list到string


