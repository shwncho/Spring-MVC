# Spring-MVC
---

- Command + shift + T → 테스트코드 편하게 작성하는 단축키(IntelliJ
- Test code 작성시 알면 좋을 패턴
    
    ```java
    //given (뭔가가 주어졌을 때)
    
    //when (이것을 실행했을 때)
    
    //then(그 때 나오는 결과)
    ```
    
- 스프링 빈과 의존관계
    1. 컴포넌트 스캔과 자동 의존관계 설정
    2. 자바 코드로 직접 스프링 빈 등록하기.
    
    >💡 참고 →실무에서는 주로 정형화된 컨트롤러, 서비스, 리포지토리 같은 코드는 컴포넌트 스캔을 사용한다. 그리고 정형화 되지 않거나, 상황에 따라 구현 클래스를 변경해야 하면 설정을 통해 스프링 빈으로 등록한다
    
   
    
- DB에서(이건 내가 하다가 찾은거)

	(')홑따옴표 : 문자열을 감싸주는 기호

	(")쌍따옴표 : 테이블명, 컬럼명 등을 감싸주는 기호

- Spring
    - 
    
    개방-폐쇄 원칙(OCP, Open-Closed Principle)
    확장에는 열려있고, 수정, 변경에는 닫혀있다.
    스프링의 DI (Dependencies Injection)을 사용하면 기존 코드를 전혀 손대지 않고, 설정만으로 구현
    클래스를 변경할 수 있다.
    
- Command + N → 생성자, Getter and Setter 등 만들기 편한 단축키
(IntelliJ)
- Option + Enter → implements 하려는 인터페이스의 구현체를 한 번에 생성(IntelliJ)
