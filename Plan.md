# 드로잉 앱

**💡 후반부는 진행하면서 업데이트하기**

## 월요일 : 계획을 계획한다. 미션을 위한 지식적 기반 확립

---

- [x]  MVC패턴 학습
    - [x]  유튜브 영상
    - [x]  Model ?
    - [x]  View ?
    - [x]  Controller ?
    - [x]  정리
  
- [x]  Factory 패턴 학습
    - [x]  정리
    
- ReadMe와 분리하여 정리할 것
- 설명이 가능해야 한다.
- “기록”과 “보관” 의 중요성

## 화요일 : 구현 필요한 지식과 디자인

---

- [x]  Observer 패턴
    - [x]  유튜브 영상
   
- [x]  요구사항에 대하여
    - [x]  속성 변경시 화면 업데이트
    - [ ]  “Plane 모델 객체에서는 변화에 대해 NotificationCenter에 post한다”

- [x]  MVC패턴 설계
    - [x]  Logic
    - [x]  관심사 / 역할 분리
    - [x]  클래스 다이어그램

- [x]  시동걸고 일단 밟자.

- 디자인시 모든 것들에 대한 “Why?” 를 항상 생각할 것


## 수요일 : 엉망이라도 일단 만들어

---

- [x]  하지만 최대한 엉망이 아니도록 노력
- [x]  설계가 잘못됐을 때의 대처
    - 즉흥적인 것들에 대한 깔끔한 처리 염두하면서 코드작성하기
    
- [x]  모델
    - [x]  모델 클래스 파일은 Core Graphics나 UIKit에 독립적인 타입
    - [x]  생성자에 정보를 만들어 넘겨주는 팩토리
 
- [ ]  iOS 메인 런루프 동작
    - [ ]  정리

- [x]  + 프로토콜(Protocol) 역할과 표현 방식

- [x]  + 시스템 로그 함수

## 목요일 : 구현에 집중해보자

---

- [x]  이어서 구현하기
    - [x]  피드백 반영

- [x]  속성 변경 동작
    - [x]  설계
    - [x]  구현

- [x]  Observer 패턴
    - [x]  이게 뭔데
    - [x]  NotificationCenter 동작 방식
    - [x]  정리

## 금요일 : 여기까지 다 끝냈냐?

---

- [x]  아니.
    - [x]  피드백 반영
    - [x]  최대한 끝내봐.
- [ ]  사진 추가하기

------------------
## 4 / 10 ~ 4 / 14 

## 월요일 : PR을 보내지 않으면 집에 갈 수 없다.

---

- [x]  TestCode 작성 마무리
- [x]  PR 메세지 작성

## 화요일 : 아…

---

- [x] 개인사정으로 인한 결석

## 수요일 : 옵저버 정복하기

---

- [ ]  피드백 반영
    - [ ] Plane 내부에 있는 Model객체를 모아놓은 배열의 변화는 Plane내부에서 처리 할 것. 잡일은 Plane이 해라.   
- [ ]  Observer Pattern
    - [ ]  Notification Center 구조로 구현
    - 설계 하고 구현하기
    - [ ]  Model과 View의 동기화과정에 이용하기
    - 내 코드의 Synchronizer를 변형해야 할듯
- [ ]  사진 추가하기
    - [ ]  사진데이터를 관리하는 모델 구현
    - [ ]  사진데이터를 관리하는 뷰 구현
    - [ ]  기존의 RandomSquare와 독립된 객체로 구현한다
        - [ ]  Square 프로토콜을 채택하여 구현.
        - [ ]  느슨한 연결에 대해서 감을 잡았으니 진짜 다 끊어보자.
- [ ]  밤코해라. 어제의 공백을 채워야지 ? 

## 목요일 :  추가 조건 구현

---

- [ ]  UIGestureRecognizer
    - [ ]  Gesture 종류
- [ ]  Delegate
    - [ ]  정확히 뭔지 모른다. 이제 좀 알자.
- [ ]  Square 프로토콜을 채택한 모델로 만들어진 View들은 이동이 가능해야한다.
- [ ]  임시View 표시 ?
    - [ ]  GestureRecognizer 이용하면 될 것 같은데 ?
    - [ ]  선택한 View 를 캡처
    - [ ]  alpha값을 받아와서 반토막 내서 임시뷰로 사용
- [ ]  밤코해라.

## 금요일 : PR 보냈길 바란다.

---

- [ ]  아직이겠지. 드래그 이벤트 마무리
    - [ ]  PR
- [ ]  피드백 반영
    

