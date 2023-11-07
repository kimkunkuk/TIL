## Object 클래스

* 모든 자바 클래스가 상속하는 최상위 클래스.
* 11개의 메소드를 정의하고있다. 자바의 모든 클래스가 가지는 기능

| Object Class Methods |
|---------------------|

### String toString()
* 객체가 가지고 있는 정보를 문자열타입 으로 바꿔주는 메소드

### equals, hashcode 메소드
* 자바의 모든 클래스는 비교가능
* equals 는 객체를 비교해주는 메소드

```java
 int x = 0; 
 int y = 1; 
  x == y // x,y의 값을 비교

String str1 = new String("java");
String str2 = new String("java");

str1.equals(str2) // 객체를 비교
```

### clone 메소드
* 인스턴스 객체의 복제, 해당 인스턴스 객체를 복사화여 그 찹조값을 반환한다.
* 클래스의 복제를 가능하게 하기위해 Cloneable 인터페이스 재정의필요