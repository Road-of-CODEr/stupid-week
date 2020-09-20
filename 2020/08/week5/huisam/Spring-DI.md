## Spring DI

Application에서 사용되는 오브젝트(클래스)들을 효과적으로 관리하기 위해 사용. 

일반적으로 객체를 생성하는 방식은 `팩토리` 방식이 존재하지만, 오브젝트를 사용하고자 하는 클래스에서. 

결국에는 이러한 `팩토리` 를 의존해야 된다는 단점이 존재함 :arrow_backward:   

그래서, 이를 해결하고자 **제어의 역전(Inversion Of Control)** 이라는 개념이 나오게 됨. 

**IoC 컨테이너는 어떠한 클래스에도 의존하지 않게 설계**   

* Bean Factory
* Application Context

이 2개의 오브젝트가 자체의 IoC 컨테이너를 의미하고, Bean들의 **등록/생성/조회/반환/관리** 하는 모듈로 사용되고 있음. 


