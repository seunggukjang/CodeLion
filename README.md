# README.MD
## CodeLion Making Web
### AssignMent
#### 1. 서버란?
> * 서버(호스트)는 클라이언트(게스트)에게 적절한 서비스를 제공하는 단말기나 프로그램입니다. 인터넷에선 TCP같은 프로토콜로 클라이언트가 서버에게 연결 요청을 보낸 뒤 응답과 반응을 통해 서비스를 제공하며, 요청-반응 같은 관계를 서버-클라이언트 관계라고도 합니다.

#### 2. nodeJS express, Django, Spring 에 대해서
> * nodeJS express : Node.js 웹(서버) 프레임워크(응용 프로그램 표준 구조를 구현하는 클래스와 라이브러리 모임)
>   * 스크립트란, 인터프리터로 번역되는 언어
>   * JavaScript란, ['웹페이지에 생동감을 불어넣기 위해' 만들어진 프로그래밍 언어](https://ko.javascript.info/intro "구글 : 자바스크립트란 검색 결과")
>   * Node.js란, 런타임에서 JavaScript가 작동되게 만드는 프로그램. 자바스크립트 런타입이라고 한다.


> * Django : 파이썬 기반 웹 프레임워크
>   > * MVT란 : Model(SQL같은 DB인터페이스), View(User Interface파트. 예시로 클라이언트가 URL로 접속 시 view가 , View가 model에서 적절한 html찾아 클라이언트에게 보여주고, template에게 Options의 인자를 제공함), Template(Jason같은 런타임용 스크립트처럼 보인다. Template파일 내부에 클라이언트가 실행 가능한 기능이 표기되어 있어 프론트엔드 작업자에게 제공하는 듯 하다. 마치 DLL로 plug-in하는 느낌이다.)
>   > * express와의 차이점 : 프레임워크 작동 방식에서 Django가 MVT방식때문인지 프론트 엔드와 독립성이 강해 보인다.

> * Spring : Java 기반 웹 프레임워크
>   > * 특징 : 메모리 관리. OOP를 더 준수하게 만들도록 도와주는 역할. 독립성 증가, 은닉 증가.

#### 3. SQL vs noSQL 차이점
> | :---: | :---: | :---: |
> |   언어    |        SQL        |        noSQL        |
> |   정규화  |         O         |           X         |
> |   스키마  |        정적       |   동적(ex. Jason)   |
> | 쿼리 처리 | 표준 SQL 쿼리 구문 | 구조화되지 않은 쿼리 |
> |저장소 구조|      비계층적      |       계층적        |


### Question?
> * JavaScript는 스크립트 언어로 인터프리터로 번역되는 언어이다. 그러면 JavaScript 엔진 동작이 컴파일인가? 인터프리터인가?<https://hanamon.kr/javascript-%EB%9F%B0%ED%83%80%EC%9E%84-%EC%9E%91%EB%8F%99-%EB%B0%A9%EC%8B%9D-%EB%B9%84%EB%8F%99%EA%B8%B0%EC%99%80-%EC%9D%B4%EB%B2%A4%ED%8A%B8-%EB%A3%A8%ED%94%84/#:~:text=%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8%20%EB%9F%B0%ED%83%80%EC%9E%84%EC%9D%B4%EB%9E%80%20%EC%9E%90%EB%B0%94,%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8%20%EB%9F%B0%ED%83%80%EC%9E%84%EC%9D%B4%EB%9D%BC%EA%B3%A0%20%ED%95%9C%EB%8B%A4.>
> * Node.js에서 Node는 loop라고 하는데 Node는 Node.js 프로그램 그 자체를 의미하는 것과 비슷한가?<https://hanamon.kr/nodejs-%EA%B0%9C%EB%85%90-%EC%9D%B4%ED%95%B4%ED%95%98%EA%B8%B0/>
> * MVT 해석한게 아닌 것 같은데?
> 
</br></br>
### Assignment Check List
- [x] 서버란?
- [ ] nodeJS express, Django, Spring 에 대해서
- [ ] SQL vs noSQL 차이점
- [ ] restAPI 란?
