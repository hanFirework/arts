# ARTS-week002

> 每周至少做一个leetcode算法题、阅读并点评至少一篇英文技术文章、学习至少一个技术技巧、分型一篇有观点和思考的技术文章。简称ARTS打卡计划。

## Algorithm

#### [234.回文链表](https://leetcode-cn.com/problems/palindrome-linked-list)



## Review

读英文一直是弱项，从今天起，从 左耳听风 里的链接英文文章开始

#### [Teach Yourself Programming in Ten Years](http://norvig.com/21-days.html)
- 速成24小时是不可能的，需要10年/10000小时
- 成为程序员
  - interested -fun enough，才能坚持10年/10000小时
  - program -learning by doing
  - talk with other programmers, read other programs
  - 花几年时间在大学或更高学位，让自己接触到需要学历要求的更有挑战性的工作；有更深入的理解；
  - work on projects with other programmers 如果做到其中最好的，就主导一个项目；如果是最差的，就反思之中遇到的问题；
  - work on projects after other programmers 理解前人的代码，并fix it；思考前人是为什么这么设计
  - 学习half dozen的编程语言，emphasizes class abstractions (like Java or C++)；emphasizes functional abstraction (like Lisp or ML or Haskell)；supports syntactic abstraction (like Lisp)；supports declarative specifications (like Prolog or C++ templates), and one that emphasizes parallelism (like Clojure or Go). 理解各种语言的设计思想、编程范式
  - computer 知道程序运行耗时、内存(缓存)、读取硬盘、硬盘寻址
  - standardization 代码格式标准化，易读 like language、feel
  
从书本中获取知识
不是24 hours or 21 days

## Tip

#### jackson 实体转json 为NULL或者为空不参加序列化

实体上

@JsonInclude(Include.NON_NULL) 

//将该标记放在属性上，如果该属性为NULL则不参与序列化 
//如果放在类上边,那对这个类的全部属性起作用 
//Include.Include.ALWAYS 默认 
//Include.NON_DEFAULT 属性为默认值不序列化 
//Include.NON_EMPTY 属性为 空（“”） 或者为 NULL 都不序列化 
//Include.NON_NULL 属性为NULL 不序列化

2.代码上
ObjectMapper mapper = new ObjectMapper();
mapper.setSerializationInclusion(Include.NON_NULL);

//通过该方法对mapper对象进行设置，所有序列化的对象都将按改规则进行系列化 //Include.Include.ALWAYS 默认 
//Include.NON_DEFAULT 属性为默认值不序列化 
//Include.NON_EMPTY 属性为 空（“”） 或者为 NULL 都不序列化 
//Include.NON_NULL 属性为NULL 不序列化

**注意：只对VO起作用，Map List不起作用**

Position beyond number of declared ordinal parameters. Remember that ordinal parameters are 1-based! Position: 1

```
Query query = getSession().createSQLQuery(countSql);
query.setParameter(i, values[i]) i从0开始
5.0.12.Final

round((st_distance (s.gpsLocal,point(?0,?1))/0.0111),1) as distance

改为

round((st_distance (s.gpsLocal,point(?,?))/0.0111),1) as distance
```





## Share

[浅析多租户在 Java 平台和某些 PaaS 上的实现](<https://www.ibm.com/developerworks/cn/java/j-lo-mutiltenancy/index.html>)

[数据层的多租户浅谈]([https://www.ibm.com/developerworks/cn/java/j-lo-dataMultitenant/#N101F6%20%E6%95%B0%E6%8D%AE%E5%B1%82%E7%9A%84%E5%A4%9A%E7%A7%9F%E6%88%B7%E6%B5%85%E8%B0%88])

