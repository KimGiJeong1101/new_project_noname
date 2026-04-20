# 🚀 Enterprise Web Modernization Project

이 프로젝트는 기존의 오래된 기술 스택이 가진 한계를 극복하고, 더 빠르고 안정적인 최신 개발 방식(Modern Full-stack)을 연구하는 프로젝트입니다.

---

## 1. 프로젝트 개요 (Project Overview)
- **배경**: 오래된 기술(JSP, MyBatis, XPlatform)로 인해 화면 수정이나 기능 추가가 어려웠던 점을 최신 기술로 해결하고자 합니다.
- **목표**: 최신 자바(Spring Boot 3)와 화면 개발 도구(React)를 사용하여, 실제 기업에서 바로 쓸 수 있는 깔끔한 시스템 본보기를 만듭니다.
- **핵심 가치**:
  - **데이터 안정성**: TypeScript를 사용해 코드를 짤 때 데이터 타입을 미리 정해두고 실수를 방지합니다.
  - **효율적인 설계**: SQL을 일일이 작성하는 대신, 자바 객체 중심으로 데이터를 관리해 개발 속도를 높입니다.
  - **화면 부품화**: 자주 쓰는 화면 요소를 부품(Component)처럼 만들어 필요할 때마다 재사용합니다.

---

## 2. 사용 기술 (Tech Stack)

### 🖥️ Backend (서버)
- **Framework**: Spring Boot 3.x
- **Language**: Java 17
- **Database**: Oracle DB
- **Data Tool**: Spring Data JPA & Querydsl
- **Convention**: 데이터베이스 테이블 매핑 시 모든 **COLUMN NAME은 UPPERCASE(대문자)**를 사용합니다.

### 🎨 Frontend (사용자 화면)
- **Library**: React (Vite 기반)
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **Convention**: 함수형 컴포넌트 작성 시 화살표 함수(`const App = () => {}`) 스타일을 사용합니다.

---

## 3. 개발 로드맵 (Roadmap)

### Phase 1: 서버 고도화 (Spring Boot & Oracle)
- 복잡한 SQL문을 직접 관리하는 방식에서 자바 코드로 데이터를 다루는 방식(JPA)으로 전환하여 생산성을 높입니다.
- 데이터베이스 관련 명칭은 대문자 사용 규칙을 엄격하게 준수합니다.
- 복잡한 검색 기능을 만들 때, 오타가 나지 않도록 안전한 도구(Querydsl)를 도입합니다.

### Phase 2: 화면 현대화 (React & TS)
- 화면이 빠르게 로딩되고 개발하기 편리한 최신 환경(Vite)을 구축합니다.
- 서버와 주고받는 데이터가 어떤 모양인지 미리 정의하여 데이터 관련 에러를 사전에 차단합니다.
- 화면 디자인과 비즈니스 로직을 분리하여 관리하기 쉬운 구조를 만듭니다.

---

## 4. 개발 원칙 (Development Principles)
1. **Naming**: 데이터베이스와 관련된 모든 명칭은 **UPPERCASE(대문자)** 사용을 원칙으로 합니다.
2. **Syntax**: 최신 버전의 자바(Java 17)와 자바스크립트(ES6+) 문법을 적극 사용하여 읽기 좋은 코드를 작성합니다.
3. **Architecture**: 사용자 화면(Frontend)과 서버 데이터 처리(Backend)의 역할을 명확히 구분한 RESTful API 구조를 지향합니다.

---

## 5. 폴더 구조 (Directory Structure)
- 상세 주제 선정 및 프로젝트 초기화 후 업데이트 예정입니다.
