结论、单例的情况下，允许循环注入。

prototype 不允许循环注入。

有单例有prototype 如果第一个是单例则允许，否则不行。

问题：会产生内存泄漏的问题。