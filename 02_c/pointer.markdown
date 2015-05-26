#pointer

####指向函数的指针

1. 每个函数都有地址。
2. 函数名表示指向函数的指针。

**声明：**

```cpp
	void (*pf)(int);
```
**作为参数：**

```cpp
	double intefrate(double (*f)(double), double a, double b){}
	double intefrate(double f(double), double a, double b){}
	double result = integrate(f, a, b);
```
**函数中调用：**

```cpp
	y = (*f)(x);
	y = f(x);
```




