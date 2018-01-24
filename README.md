# -
对于控制的初识与相关实现

# 基础任务:

- arra.cpp:输入一个数组，分别对其进行:排序、求平均数、求中位数、求众数。 
- con_mul.cpp:输入两个数 m，n，对其求最大公约数和最小公倍数。
- goldbach.cpp:验证哥德巴赫猜想（任意一个大于等于 6 的偶数都可以分解为两个素数之和）。
- in_put.cpp:输入 5 位同学的一组信息，包括学号、姓名、微积分成绩、线代成绩、概率论成绩，求得每位同学的平均分和总分，然后按照总分从高到低排序（结构体实现）

# 拓展任务:

- fun.cpp:编写一个函数，求一个数的偶数因子并排序。

  ```
  void fun （int x， int * pp， int *n）
  ```

  ​	它的功能是：求出 x 的偶数因子，并按从小到大的顺序放在 pp 所指的数组中，这些因子的个数通过形参 n 返回（假设 pp 指向足够大的空间）。

  ​	例如，若 x 的值为 24，则输出 pp 指向的数组为{2，4，6，8，12，24}，输出 n 指向 6。 

- del_substr.cpp:编写一个函数，删除一个字符串的一部分。

  ```
  int del_substr (char *str  ,  char const *substr)
  ```

  ​	函数首先判断 substr 是否出现在 str 中，如果未出现，函数返回0；如果出现，函数应该把 str 中位于该子串后面的所有字符复制到该子串的位置，从而删除该子串，然后函数返回 1；如果 substr 多次出现在 str 中，函数只删除第一次出现的子串。 

  ​	例如：如果 str 指向 ABCDEFG，substr 指向 FGH、CDF、XABC，函数返回 0；如果 substr 指向 CDE，函数就把 str 修改为指向 ABFG。 