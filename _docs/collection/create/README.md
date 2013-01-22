## 컬랙션 생성
앱 개발을 위해서는 필수적인 요소가 바로 컬랙션이다. 컬랙션 생성 방법은 두 가지가 있다. SDK 를 이용하는 방법과 애플리케이션 대쉬보드의 데이터브라우저를 이용하는 방법이다.

이 문서에서는 데이터브라우저를 활용하는 방법으로 가이드할 예정이다.

1. [http://baas.io](http://baas.io) 으로 접속하여 로그인
2. 로그인이 완료되면 애플리케이션 대쉬보드로 이동

애플리케이션 대쉬보드에는 앱을 관리하기 위한 다양한 기능을 제공한다. 이 중에서 콜랙션을 생성하기 위해서는 좌측 메뉴중 **데이터브라우저**로 이동한다

3. 데이터브라우저로 이동
4. "Add Collection" 버튼을 이용해 "mycollection" 이름의 컬렉션 생성

> 유의사항
> 콜랙션 명을 "mycollection" 이라고 입력하여 생성하면 baas.io 는 자동으로 콜랙션 명칭을 복수형으로 변경한다. 
> 데이터브라우저 콜랙션 리스트를 보면 "mycollections" 로 생성됨을 확인할 수 있다.
> 또 하나의 예를 들어 "person" 으로 생성하면 "people" 로 생성된다.
> 이것은 baas.io 내부적으로 사전 정보에 따라 변경되는 것으로 모든 것이 '-s', '-es' 형태의 복수형이 아닐 수도 있다.

컬랙션 생성이 완료되었다면 콜랙션에 엔티티를 가져오고 넣어보자.