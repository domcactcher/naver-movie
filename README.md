# Redux를 사용한 Global state 관리

Redux란?

> 모든 컴포넌트에 대해 데이터와 이벤트 상태를 공유하기 위해서 만들어진 일종의 프레임워크
(Vue는 Vuex)

전역 변수라고 생각하면 편해요(전역 객체로 똑같이 구현 가능)


## 구현사항

### 구현 1

구글 로그인(firebase api 사용가능) + 상태변화에 따른 ui 변화 간단히 구현
    
### 구현 2 

네이버 영화 api를 사용해서 영화를 검색하면 해당 영화의 목록(영화이름, 감독, 개봉일, 평점, 썸네일 이미지)을 가져오시면 됩니다.
    
    
### 조건

- 화면 레이아웃은 header, footer, navigation bar로 이루어저야 합니다.

- 비로그인 상태에선 영화를 검색할 수 없어야 합니다.

- 네이버 영화 목록을 가져올 때 유튜브처럼 lazy loading을 구현하셔야 됩니다.

### 기한

**구현 1** - 2019.08.03 모임까지

**구현 2** - 2019.08.10 모임까지
