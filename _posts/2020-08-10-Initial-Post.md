--- 
title: 第一篇博客
date: 2020-08-10
categories: [杂文]
tags: 
math: true
---

# 写作测试

## 音乐测试

失败了。

## 公式测试 

$$\frac{\int_0^{+\infty}\frac{\tau^{-4N-1}}{e^{\frac{1}{\tau}}-1}\mathrm d \tau}{(\int_0^{+\infty}\frac{\tau^{-2N-1}}{e^{\frac{1}{\tau}}-1}\mathrm d \tau)^2}$$

$$\int_0^{+\infty}\frac{\tau^{-4N-1}}{e^{\frac{1}{\tau}}-1}\mathrm d \tau=\int_0^{+\infty}\frac{x^{4N+1}}{e^{x}-1}\frac{1}{x^2}\mathrm {d} x=\int_0^{+\infty}\frac{x^{4N-1}}{e^{x}-1}\mathrm {d} x$$

## 代码片段测试

```cpp
while (t--) {
    scanf("%lld%lld", &b, &x);
    if (b % x == 1)
        puts("T");
    else
        puts("F");
}
```

```python
def memorize(func):
    mem = {}
    def inner(x, y):
      if ((x, y) not in mem):
        mem[(x, y)] = func(x, y)
      return mem[(x, y)]
    return inner

@memorize
def f(x, y):
  t = 1
  if x + 1 < R and a[x + 1][y] > a[x][y]:
    t = max(t, f(x + 1, y) + 1)
  if (y + 1 < C and a[x][y + 1] > a[x][y]):
    t = max(t, f(x, y + 1) + 1)
  if (x > 0 and a[x - 1][y] > a[x][y]):
    t = max(t, f(x - 1, y) + 1)
  if (y > 0 and a[x][y - 1] > a[x][y]):
    t = max(t, f(x, y - 1) + 1)
  return t
```

## 文件测试

单击[这里](/assets/img/tom.gif)获得神秘gif一张

点击[这里](/assets/img/jhy.jpg) 获得金爷头像一张 

**今年的份更完啦~**
