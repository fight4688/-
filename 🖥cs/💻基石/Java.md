# MESS
接口是限制，抽象类是模板
# 泛型（在使用时明确类型）
泛型的原始实现是object
==使用？实质是使用object接受，所以无法接受基本类型==
1. 泛型类 public class Car<.T>
2. 泛型方法public <.T>T fix(T t)
Arrays.sort(arr,(o1,o2)->o2-01);用于实现泛型比较器从而实现反向排序，但只能使用包装类


# 集合
数组和集合都能用来存储对象，但集合长度可变
![](../../asset🧰/Pasted%20image%2020240229133642.png)
线性表可通过数组（顺序表）和链表实现，各有优缺

Deque：双端队列，有ArrayDeque和LInkedList两种方式
一般通过ArrayDeque实现栈（push pop）
队列可以通过ArrayDeque和LInkedList实现(offer poll)

