# Design-Pattern
Design-Pattern

개인 공부

11월 1주차 : Chapter3.생성 패턴

Prototype *** 

프로토타입 패턴은 인스턴스를 복제하여 사용하는 구조. 즉, 생성할 객체의 원형을 제공하는 프로토타입 인스턴스로부터 생성할 객체들의 타입이 결정.
이 패턴은 객체를 생성할 때 갖추어야 할 기본 형태가 있을 떄 사용.

처음부터 일반적인 프로토타입(원형)을 만들어놓고, 그것을 복사한 후 필요한 부분만 수정하면 new Object() 메서드로 객체를 생성하는 것보다 편리함.

![image](https://user-images.githubusercontent.com/35355780/140629037-f3671e95-8ab5-4527-83a6-3c1cadabc04e.png)

<br>
java 예시)

프로토타입 클래스

![image](https://user-images.githubusercontent.com/35355780/140629070-973ae37b-2595-4e47-b750-5108b2da339e.png)

enum

![image](https://user-images.githubusercontent.com/35355780/140629078-06945101-672d-41ba-b1b5-f3736aa7ac63.png)

복제할 구체적 프로토입 클래스

![image](https://user-images.githubusercontent.com/35355780/140629087-5384bd2f-54b2-4e91-a018-44984f19fb01.png)

클라이언트 클래스

![image](https://user-images.githubusercontent.com/35355780/140629097-b59412aa-a6ff-45a7-810c-3140e2f571be.png)

메인

![image](https://user-images.githubusercontent.com/35355780/140629104-fc1d9082-67e2-4b23-89dc-fd2c9308801a.png)

실행결과

![image](https://user-images.githubusercontent.com/35355780/140629200-f7456136-e805-4aca-b284-12c0e5cbfeb7.png)
