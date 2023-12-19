# CompareOperatorExp

***

```java
int num1 = 10;
int num2 = 11;
System.out.println("바로출력:" + (num1 == num2));
boolean b1 = num1 == num2;
boolean b2 = num1 >= num2;
boolean b3 = num1 != num2;

System.out.println(b1);
System.out.println(b2);
System.out.println(b3);

char c1 = 'A';
char c2 = 'B';
boolean b4 = c1 > c2;
System.out.println(b4);

▶️
바로출력:false
false
false
true
false

```
- `boolean b2 = num1 >= num2;`or
- `boolean b3 = num1 != num2;`다르다 순서가 바뀌면안됨
