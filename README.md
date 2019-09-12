# 오브젝트

## 소프트웨어 모듈의 목적
- 실행 중에 제대로 동작하는 것
- 변경을 위해 존재하는 것
- 코드를 읽는 사람과 의사소통하는 것

## 절차지향
- 절차지향: 프로세스와 데이터를 별도의 모듈에 위치시키는 방식

## 객체지향1
- 데이터와 프로스세가 동일한 모듈 내부에 위차하도록 하는 방식
- 절차지향과 근본적인 차이는 책임의 이동이다.
- 객체는 자신을 스스로 책임을 진다.

## 객체지향2
- 설계를 어렵게 만드는 것은 의존성이다.
- 의존성을 제거함으로 객체 사이의 결합도를 낮춘다.
- 최소한의 의존성만 남긴다.
- 다른 객체가 몰라도 되는 사항은 캡슐화하여 감춘다.
- 캡슐화하는 것은 객체의 자율성, 응집도를 높게해준다.

## 객체지향 프로그래밍하는 동안 알아야 할 사항
### 1. 어떤 클래스가 필요한지를 고민하기 전에 어떤 객체들이 필요한지 고민하라.
    - 클래스는 공통적인 상태와 행동을 고유하는 객체들을 추상화한 것이다.
    - 클래스의 윤곽을 잡기 위해서는 어떤 객체들이 어떤 상태와 행동을 가지는지를 먼저 결정해야한다.
    - 객체를 중심에 두는 접근 방법은 설계를 단순하고 깔끔하게 만든다.
### 2. 객체를 돌립적인 존재가 아니라 기능을 구현하기 위해 협력하는 공동체의 일원으로 봐야 한다.
    - 객체를 협력하는 공동체의 일원으로 바로보는 것이 설계를 유연하고 확장 가능하게 만든다.
    - 객체들의 모양과 윤관이 잡히면 공통된 특성과 상태를 가진 객체들을 타입으로 분류하고 이 타입을 기반으로 클래스로 구현한다.

## 도메인
- 문제를 해결하기 위해 사용자가 프로그램을 사용하는 분야를 도메인이라고 한다.

## 클래스의 내부와 외부를 구분해야하는 이유
- 경계의 명확성이 객체의 자율성을 보장한다.
- 프로그래머에게 구현의 자유를 제공한다.

## 자율적인 객체
- 객체는 상태와 행동을 함꼐 가지는 복합적인 존재이다.
- 객체가 스스로 판단하고 행동하는 자율적인 존재이다.
- 데이터와 기능을 객체 내부로 묶는 것을 캡슐화라고 부른다.

## 다형성
- 객체지향 프로그램의 컴파일 시간 의존성과 실행 시간 의존성이 다를 수 있다는 사실을 기반으로 한다.
- 서로 다른 메소드를 실행할 수 있게 한다.
