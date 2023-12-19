# Binary

***

```java
String str = Integer.toBinaryString(25);

System.out.println("25의 2진수 " + str);

▶️
25의 2진수 11001

```
- 십진수를 이진수로 변환하는 메소드 사용
- 스트링으로 리턴되는 메소드이므로 변수 타입을 스트링으로 바꿔준다(*java api참조)

```java
int num = 250;
String str2 = Integer.toBinaryString(num);
System.out.println(num + "의 2진수 " + str2);

▶️
250의 2진수 11111010

```
- `int num = 250;`변수의 사용 이유

