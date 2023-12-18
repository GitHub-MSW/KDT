# Type

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
- `byte var5=(byte) 128;`형변환 원형식으로 한바퀴 돈다고 이해 (숫자일 경우)

***
***Char***
```java
char c='A';
char c2='B';
System.out.println("c:"+c);
System.out.println(c+c2);

▶️ c:A
▶️ 131
```
- char 타입은 작은따옴표'' char는 한글자만 가능
- 문자열 연결
- 연산 우선순위가 문자열보다 숫자가 더우선순위에 있기때문 아스키코드
