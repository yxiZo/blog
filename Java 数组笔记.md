---
share: "true"
---

对于数组 ,常见的数据结构

在内存中 表示位连续不断的一块内存

对于链表

在内存中  表示位不连续的一块

java 中 数组存放的是 同一类型的数据, 引用类型


引用类型是指 数组变量 存储的只是数据地址(指针)


```java
// double 类型的数组
double[] hens = { 3, 5, ,1, 2.4, 2, 50 };

// 通过 for 循环 可以遍历数组
for(int i = 0; i < 3; i++){  
	System.out.println(hens[i]);  
}
System.out.println(hens.length);
```


对比 javascript 

```javascript
// javascript 弱类型 可以存在不同类型 ,但一般不会这样使用
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

1.  动态初始化
```java
int b = 1;
int a[] = new int[5];
double scores = new double[5];
```

2. 先声明在分配
```java
double[] scores;  
scores = new double[5];
```
3. 静态初始化
```java
int[] a = {1,2,3,4,5};
a[1] = 3;
System.out.println(Arrays.toString(a));
```


> Tips:
> 注意数组的数据类型
> 其实就是自动类型转换的知识点
> 高精度可以兼容低精度, 低精度则不能向上,否则会出现精度丢失

## 数组赋值机制

值传递 和 引用传递


![00000-1196744786.png](https://pic.yxizo.com/test/2023/11/00000-1196744786.png)




## 数组算法

冒泡排序

```java
public class BubbleSort{
	public static void main(String[] args) {
		// 对一个数组进行冒泡排序
	}
}

```

归并排序
```java
```

快速排序
```java

```


## 额外补充
### Java Scanner

Java 的 Utils 包 用来监控输入
