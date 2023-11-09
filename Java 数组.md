---
share: "true"
---

对于数组 ,常见的数据结构

在内存中 表示位连续不断的一块内存

对于链表

在内存中  表示位不连续的一块

java 中 数组存放的是 同一类型的数据, 引用类型

```java
// double 类型的数组
double[] hens = { 3, 5, ,1, 2.4, 2, 50 }

// 通过 for 循环 可以遍历数组
for(int i = 0; i < 3; i++){  
	System.out.println(hens[i]);  
}
System.out.println(hens.length)
```


对比 javascript 

```javascript
// javascript 弱类型  可以存在不同类型
const a = [ 1, 2, 2, 3, "34"]

// 通过下标可以访问元素值
a[0] // 1

// 数组实例上有多种方法和属性, 方便处理
a.length // 数组长度
a.forEach(() => {})
a.reduce(() => {})
a.filter(() => {})
```


## 初始化

1. 