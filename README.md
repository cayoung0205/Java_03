## Java 100_변수

- static 개념, 역활

`문제 code`

```java
public class Java100_variable_HelloWorld4{
	public static void main(String[] agrs){
		System.out.println("Hello World~");
	}
}
```

`해설`

```
- static으로 선언된 함수(메서드)나 변수는 자바 버추얼 머신에서 인스턴스 객체의 생성 없이 호출을 할 수 있다.
- 쉽게말해서, 객체 생성없이 해당 힘수(메서드)를 호출해서 사용할 수 있다.
```

```
- 자바프로그램을 실행하면 static으로 지정된 메서드를 찾아서 먼저 메모리에 할당시킨다.
- static으로 지정된 메서드가 여러개인 경우에는 객체를 생성하는 것과 상관없이 모두 메모리에 할당시킨다.
- 그런 후에, 'main'으로 이름이 만들어진 메서드가 있는지를 찾아서 그 메서드를 가장 먼저 시작점의 메서드로써 호출을 하게 되는 것이다. 
```

`static이 아닌 경우`

```
class : 공장 
class --> 객체 생성 --> 생성된 객체 class 내의 기능을 호출하여 사용
```

