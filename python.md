* list:last element's index: len(list) - 1

* 取整： 默认向下圆整，round()函数四舍五入，math.ceil()向上圆整(import math)

* range --> list

* pop返回pop掉的值

* return res==value #return bool can write like this

* `dict.get(key)`
查看字典中有无这个key，有的话返回它的value，没有返回None

* `dict.keys()`
return all key in the dict with a list

* **is** will return True if two variables **point to the same object** </br>
  **==** if the objects referred to by the **same value**

* infinit in python: `float("inf")`

* reverse python list `list.reverse()` or `list[::-1]` former doesn't return

* `for i in dict: ` equal with `for i in dict.keys():`

* `for i in list:` i is value!

* list去重\list->set：`set(list)`

* set: </br>
`
并集--> set1 | set2
交集--> set1 & set2
差集--> set1 - set2
`
`
` `range([start], [end], footstep)`, end is not included

* `enumerate()` add a counter to a iterator
```
>>>values = ["a", "b", "c"]
>>>for index, value in enumerate(values):
...    print(index, value)
...
0 a
1 b
2 c
``` 
