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
- `char c='A';`char 타입은 작은따옴표'' char는 한글자만 가능
- `System.out.println("c:"+c);`문자열 연결
- `System.out.println(c+c2);`연산 우선순위가 문자열보다 숫자가 더우선순위에 있기때문 아스키코드

```java
char c1='A'+1;
		
System.out.println("c1:"+c1);
System.out.println("c1:"+(int)c1);
		
int c2=70;
System.out.println("c2:"+c2);
System.out.println("문자로 표현 : "+(char)c2);

▶️ c1:B
▶️ c1:66
▶️ c2:70
▶️ 문자로 표현 : F
```
- 아스키 코드

***
***Int***
```java
int var1=10;
int var2=017;
int var3=0b101; 
int var4=0xa;
int var5=0xb;
int var6=0xc;
int var7=0xd;
int var8=0xe;
int var9=0xf;
		
int var10=2100000000;
		
System.out.println("var1:"+var1);
System.out.println("var2:"+var2);
System.out.println("var3:"+var3);
System.out.println("var4 16진수a:"+var4);
System.out.println("var5:"+var5);
System.out.println("var6:"+var6);
System.out.println("var7:"+var7);
System.out.println("var8:"+var8);
System.out.println("var9:"+var9);
System.out.println("var10:"+var10);

▶️ var1:10
▶️ var2:15
▶️ var3:5
▶️ var4 16진수a:10
▶️ var5:11
▶️ var6:12
▶️ var7:13
▶️ var8:14
▶️ var9:15
▶️ var10:2100000000
```
- `int var1=10;`default 10진수
- `int var2=017;`0 8진수
- `int var3=0b101;`0b bit 2진수
- `int var4=0xa;`0x 16진수

***
***Long***
```java
long var1=10;
long var2=10L;

System.out.println("var1 : "+var1);
System.out.println("var2 : "+var2);

▶️ var1 : 10
▶️ var2 : 10
```
-`long var2=10L;`L생략 가능
