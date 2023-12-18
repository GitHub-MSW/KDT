# 타입 (Type)

***
***타입종류***

```java
<기본형타입>

- 정수타입 -

byte 1byte
char 2byte
short 2byte
int 4byte
long 8byte
		  
- 실수타입 -
float 4byte
double 8byte
		  
-논리타입 -
boolean 1byte
```
***
***byte***
```java
byte var1=(byte) -129;
byte var2=-30;
byte var3=0;
byte var4=30;
byte var5=(byte) 128;
System.out.println(var1);
System.out.println(var2);
System.out.println(var3);
System.out.println(var4);
System.out.println(var5);

▶️ 127
▶️ -30
▶️ 0
▶️ 30
▶️ -128
```
- 변수 'var', '=' 대입연산자 (이퀄의 의미 아님, 우측항을 좌측항으로 대입)
- 문장의 종료 ;
- ```java byte var5=(byte) 128;```형변환 원형식으로 한바퀴 돈다고 이해 (숫자일 경우)
