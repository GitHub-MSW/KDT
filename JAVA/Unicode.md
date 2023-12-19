# Unicode

***

```java
char char1 = '가';
char uni1 = '\uac00';
System.out.println(char1);
System.out.println(uni1);

▶️
가
가

```
- `char char1='가';`두글자 불가, 한글자
```java
char uni_n1 = '\uac00';
char uni_n2 = '\ub098';
char uni_n3 = '\ub2e4';
System.out.println("Name : " + uni_n1 + uni_n2 + uni_n3);
System.out.println(uni_n1 + uni_n2 + uni_n3);

▶️
Name : 가나다
135036

```
- 이름 유니코드로 출력
