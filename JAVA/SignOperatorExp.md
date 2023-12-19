# SignOperatorExp

***

```java
int x = -100;
int result1 = +x;// +1*-100
int result2 = -x;// -1*-100

System.out.println("result1 : " + result1);
System.out.println("result2 : " + result2);

short s = 100;
int result3 = -s;
System.out.println("result3 : " + result3);

▶️
result1 : -100
result2 : 100
result3 : -100
```
- 부호연산
- `int result1 = +x;`+1*-100
- `int result2 = -x;`-1*-100

```java
int x1 = 10;
x1 = ++x1;
x1 = x1++;

System.out.println("x1:" + x1);
System.out.println("x1-1:" + (++x1));
System.out.println("x1-2:" + (x1++));
System.out.println("x1:" + x1);

▶️
x1:11
x1-1:12
x1-2:12
x1:13
```
- 증감연산 ++ (1씩증가) --
- `x1 = ++x1;`전위연산
- `x1 = x1++;`후위연산
- `x1++;`후위연산
- `System.out.println("x1-1:" + (++x1));`x1=x1+1
- 출력전에 증감
- `System.out.println("x1-2:" + (x1++));`x1=x1+1 후위연산은 출력후에 계산
- 출력후 증감

