# DenyLogicalOperatorExp

***

```java
boolean play1 = false;
boolean play2 = false;
System.out.println(play1);
System.out.println(!play2);
play2 = !play2;// 역함수 not
System.out.println(play2);
System.out.println(play2);

boolean play3 = true;
boolean play4 = false;
boolean play5 = false;

boolean result1 = play3 || play4 || play5;
System.out.println("result1:" + result1);
boolean result2 = play3 && play4 && play5;
System.out.println("result2:" + result2);

▶️
false
true
true
true
result1:true
result2:false

```
- `System.out.println(!play2);`!는 반대의 의미
- `play2 = !play2;`역함수 not
- `boolean result1 = play3 || play4 || play5;`or 요소하나라도 true면 true
- `boolean result2 = play3 && play4 && play5;`and 요소모두가 true일때만 true

