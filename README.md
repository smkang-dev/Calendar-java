# Calendar-Java

Java Swing을 활용하여 구현한 데스크톱 일정 관리 애플리케이션입니다.

사용자는 날짜별 일정을 조회하고, 제목·시간·설명을 입력하여 일정을 추가하거나 삭제할 수 있습니다.

---

## 주요 기능

* 날짜별 일정 조회
* 일정 추가
* 일정 삭제
* 일정 목록 관리
* Java Swing 기반 GUI 조작

---

## 핵심 구현 내용

### 일정 데이터 객체화

일정의 제목, 설명, 시작 시간, 종료 시간 등의 정보를 `ScheduleEvent` 객체로 관리하도록 설계했습니다.

### 일정 관리 로직 분리

일정 추가, 날짜별 조회, 삭제 기능을 GUI 코드와 분리하여 `ScheduleManager`와 `HumanScheduleManager`에서 처리하도록 구현했습니다.

이를 통해 화면 구성과 일정 관리 로직의 역할을 구분했습니다.

### 이벤트 기반 GUI 구현

Java Swing의 버튼, 입력창, 목록 컴포넌트와 이벤트 리스너를 활용하여 사용자의 입력에 따라 일정이 추가되거나 삭제되도록 구현했습니다.

---

## 기술 스택

* Java
* Java Swing
* IntelliJ IDEA
* Git / GitHub

---

## 프로젝트 구조

```text
CalendarGUI.java
ScheduleManager.java
HumanScheduleManager.java
ScheduleEvent.java
```

* `CalendarGUI.java`
  메인 화면 구성 및 사용자 이벤트 처리

* `ScheduleManager.java`
  일정 관리 기능을 정의하는 인터페이스

* `HumanScheduleManager.java`
  일정 추가, 조회, 삭제 등 실제 일정 관리 로직 구현

* `ScheduleEvent.java`
  일정 정보를 저장하는 데이터 모델


---

## 프로젝트에서 배운 점

* Java Swing을 활용한 데스크톱 GUI 개발 방법을 익혔습니다.
* 객체지향 설계를 통해 일정 데이터를 객체로 관리하는 방법을 학습했습니다.
* 인터페이스와 구현 클래스를 분리하는 구조를 경험했습니다.
* GUI와 일정 관리 로직을 분리하는 방법을 학습했습니다.
* 이벤트 기반 프로그래밍의 동작 방식을 이해했습니다.
