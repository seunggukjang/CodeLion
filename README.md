# README.MD
## CodeLion Making Web

### AssignMent1(22.03.15~22.03.19)
#### 1. 서버란?
> * 서버(호스트)는 클라이언트(게스트)에게 적절한 서비스를 제공하는 단말기나 프로그램입니다. 인터넷에선 TCP같은 프로토콜로 클라이언트가 서버에게 연결 요청을 보낸 뒤 응답과 반응을 통해 서비스를 제공하며, 요청-반응 같은 관계를 서버-클라이언트 관계라 함.

#### 2. nodeJS express, Django, Spring 에 대해서
> * nodeJS express : Node.js 웹(서버) 프레임워크(응용 프로그램 표준 구조를 구현하는 클래스와 라이브러리 모임)
>   * 스크립트 : 인터프리터로 번역되는 언어
>   * JavaScript : ['웹페이지에 생동감을 불어넣기 위해' 만들어진 프로그래밍 언어](https://ko.javascript.info/intro "구글 : 자바스크립트란 검색 결과")
>   * Node.js : 런타임에서 JavaScript가 작동되게 만드는 프로그램. 자바스크립트 런타입이라고 함.
> * Django : 파이썬 기반 웹 프레임워크
>   * MVT : 
>     - Model : SQL같은 DB인터페이스
>     - View : User Interface파트. 예시로 클라이언트가 URL로 접속 시, View가 model에서 적절한 html찾아 클라이언트에게 보여주고, template에게 Options의 인자를 제공
>     - Template : Jason같은 런타임용 스크립트. Template파일 내부에 클라이언트가 실행 가능한 기능이 표기되어 있어 프론트엔드 작업자에게 제공. 마치 DLL로 plug-in하는 느낌
>   * express와의 차이점 : 프레임워크 작동 방식에서 Django가 MVT방식때문인지 프론트 엔드와 독립성이 강함.
> * Spring : Java 기반 웹 프레임워크
>   * 특징 : 메모리 관리. OOP를 더 준수하게 만들도록 도와주는 역할. 독립성 증가, 은닉 증가.

#### 3. SQL vs noSQL 차이점
> |   언어    |        SQL        |        noSQL        |
> | :---: | :---: | :---: |
> |   정규화  |         O         |           X         |
> |   스키마  |        정적       |   동적(ex. Jason)   |
> | 쿼리 처리 | 표준 SQL 쿼리 구문 | 구조화되지 않은 쿼리 |
> |저장소 구조|      비계층적      |       계층적        |


#### 4. restAPI 란?
> * REST : Representational State Transfer [자원을 이름으로 구분하여 해당 자원의 상태를 주고 받는 모든 것](https://hanamon.kr/rest-api/#:~:text=REST%EC%9D%98%20%EC%A0%95%EC%9D%98,%EB%B0%9B%EB%8A%94%20%EB%AA%A8%EB%93%A0%20%EA%B2%83%EC%9D%84%20%EC%9D%98%EB%AF%B8%ED%95%9C%EB%8B%A4.). URI를 이용해 CRUD작업 
>   - 자원 : 문서, 그림, 데이터 등
>   - 표현 : 자원을 표현하기 위한 이름
>   - 상태 : 데이터가 요청될 때의 자원의 상태
>   - 전달 : 상태 전달
> * URI : Uniform Resource Identifier 통합 자원 식별자, 네트워크 상에서 특정 자원을 나타내는 유일한 주소
>   - URL : Uniform Resource Locator 통합 자원 위치 지정자, 네트워크 상에서 자원이 어디에 있는지 알려주기 위한 규약
>   - URN : Uniform Resource Name : 통합 자원 명칭, 자원의 이름을 지칭
> * CRUD : Create, Read, Update, Delete로 사용자 인터페이스 아키텍처. 웹 서비스에 많이 사용하는 아키텍처 형태
> * HTTP : Hyper Text Transfer Protocol로 restAPI 사용
> * restAPI : rest기반으로 api구현
> * SOAP : Simple Object Access Protocol로 [다른 언어로 다른 플랫폼에서 빌드된 application이 통신할 수 있도록 설계된 최초의 표준 프로토콜](https://www.redhat.com/ko/topics/integration/whats-the-difference-between-soap-rest)

### Question?
> * JavaScript는 스크립트 언어로 인터프리터로 번역되는 언어이다. 그러면 JavaScript 엔진 동작이 컴파일인가? 인터프리터인가?<https://hanamon.kr/javascript-%EB%9F%B0%ED%83%80%EC%9E%84-%EC%9E%91%EB%8F%99-%EB%B0%A9%EC%8B%9D-%EB%B9%84%EB%8F%99%EA%B8%B0%EC%99%80-%EC%9D%B4%EB%B2%A4%ED%8A%B8-%EB%A3%A8%ED%94%84/#:~:text=%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8%20%EB%9F%B0%ED%83%80%EC%9E%84%EC%9D%B4%EB%9E%80%20%EC%9E%90%EB%B0%94,%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8%20%EB%9F%B0%ED%83%80%EC%9E%84%EC%9D%B4%EB%9D%BC%EA%B3%A0%20%ED%95%9C%EB%8B%A4.>
> * Node.js에서 Node는 loop라고 하는데 Node는 Node.js 프로그램 그 자체를 의미하는 것과 비슷한가?<https://hanamon.kr/nodejs-%EA%B0%9C%EB%85%90-%EC%9D%B4%ED%95%B4%ED%95%98%EA%B8%B0/>
> * MVT 해석한게 아닌 것 같은데?

</br></br>
### Assignment Check List
- [x] 서버란?
- [x] nodeJS express, Django, Spring 에 대해서
- [x] SQL vs noSQL 차이점
- [x] restAPI 란?
