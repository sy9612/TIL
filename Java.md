#### 객체지향 (vs 절차지향)

절차지향이 기능 중심이라면 객체지향은 데이터가 중심

절차지향이 함수로부터 데이터를 받아와 기능을 구현하는 방식이라면 

객체지향은 객체에 데이터와 기능이 존재하고 객체들이 서로 유기적으로 동작하는 주체가 됨

코드의 재사용성이 높고 유지보수에 용이하다는 장점을 가지고 있음

**기본형 vs 참조형**

기본형: stack 메모리 영역에 실제 값을 저장하는 데이터 타입, call by value 사용, byte, int, long,,,

참조형: 메모리상에 객체가 있는 위치를 저장하는 것, call by reference, String, class, interface,,,

**가비지 컬레션이란?**

시스템에서 사용하지 않는 동적 할당된 메모리 블록을 찾아 다시 사용 가능한 자원으로 회수하는 것

**StringBuffer vs StringBuilder**

둘다 String과 다르게 한번만 만들고 메모리의 값을 변경

StringBuilder는 싱글 스레드에서 StringBuffer 는 멀티 스레드에서 안전

**interface vs abstract**

추상클래스: 추상 메소드를 하나 이상 가진 클래스, 자식 클래스에게 강제성 부여 가능, 기능 확장 가능, 객체 생성이 불가능, 클래스를 상속 받아 오버라이딩하여 사용해야 함

인터페이스: 모든 메서드가 구현부가 없는 추상메소드로 이루어진 클래스

**쓰레드?**

프로세스내에서 실제로 작업을 수행하는 주체, 모든 프로세스에는 1개 이상의 스레드가 존재

**JDBC?**

자바에서 DB의 종류에 상관없이 데이터베이스에 더욱 쉽게 접근할 수 있도록 하는 API

**동기 vs 비동기**

동기식 방법은 A를 수행하는 중에 B를 수행하지 못함, 요청을 보낸 후 응답을 받아야 다음 동작이 이루어짐, 설계 간단 직관적 but 시스템 효율 저하

비동기는 복잡하지만 자원을 효율적으로 사용가능

**== vs ===**

일치 여부만 확인, === 타입도 같이 확인

**스프링 프레임워크란?**

자바 플랫폼을 위한 오픈 소스 애플리케이션 프레임워크, 하드웨어적인 구성이 필요없는 경량 프레임워크

**Spring boot**

스프링 프레임워크를 사용하는 프로젝트를 간편하게 셋업할 수 있는 서브 프로젝트 

**쿠키와 세션**

쿠키는 서버가 사용자의 웹 브라우저에 저장하는 데이터로 브라우저마다 저장되는 쿠키가 다름

세션은 일정 시간동안 같은 브라우저로부터 들어오는 일련의 요구사항을 하나의 상태로 보고 상태를 유지시킴, 브라우저 종료시 소멸

**servlet vs jsp**

서블릿을 java에 html이 삽입, jsp는 html에 java가 삽입

**maven**

프로젝트 관리 도구, 프로젝트의 모든 단계에 사용하는 개발 도구, 프로젝트에 필요한 라이브러리를 자동으로 관리해주는 빌드 도구, 필요한 라이브러리 jar파일을 자동으로 다운 받을 수 있음

**http vs https**

http는 웹 서버 통신을 위한 프로토콜, 80번 포트를 사용

https는 443번포트 사용, 암호화된 통신을 제공하는 http로 느리지만 보안유지를 위해 사용

**get vs post**

get은 클라이언트에서 서버로 데이터를 전달할 때 주소 뒤에 key와 value가 결합된 쿼리 스트링 형태로 전달, 전송 데이터의 한계가 있고 post보다 전송 속도가 빠름

post는 일정 크기 이상의 데이터를 보낼 때 사용, 쿼리 스트링 데이터뿐만 아니라 객체들의 값을 전송가능

둘다 보안에 취약하고 post는 개발자도구 이용시 내용확인가능

**CORS?**

도메인이 다른 2개의 사이트가 데이터를 주고 받을 때 발생하는 문제로 서버내에서 요청이 허락된 도메인에만 데이터를 주기 위해서, 요청을 허락하기 위해서는 response의 헤더에 추가해줘야함

**서블릿?**

클라이언트의 요청을 처리하고 그 결과를 반환하는 규칙을 지킨 자바 웹 프로그래밍 기술

**REST API?**

http통신에서 자원에 대한 CRUD요청을 리소스와 메소드로 표현하여 특정한 형태로 전달하는 방식

**의존성 주입 DI란?**

**MVC 패턴이란?**
