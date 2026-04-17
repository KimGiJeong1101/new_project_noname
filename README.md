# 🚀 Legacy to Modern: Enterprise Web Renewal Project

실무에서 접하는 레거시 기술 스택의 한계를 극복하고, **더 높은 생산성과 안정성을 갖춘 모던 풀스택 아키텍처**를 연구하는 개인 학습 및 실습 저장소입니다.

## 📌 Project Overview
- **Background**: JSP, MyBatis, XPlatform 기반의 환경에서 겪는 유지보수의 어려움을 현대적 기술로 해결하고자 함
- **Goal**: Spring Boot 3와 React(TS)를 활용하여 기업용 시스템의 현대적 리뉴얼 프로토타입 구축
- **Core Values**: 
  - **Type Safety**: TypeScript와 Querydsl을 통한 컴파일 단계 에러 방지
  - **Efficiency**: JPA를 활용한 객체 지향적 데이터 설계 및 개발 속도 향상
  - **Modern UI**: 컴포넌트 기반의 재사용 가능한 프론트엔드 구조 설계

---

## 🛠 Tech Stack

### 🔹 Backend
- **Framework**: Spring Boot 3.x
- **Language**: Java 17
- **Database**: Oracle DB
- **ORM**: Spring Data JPA & Querydsl
- **Convention**: 레거시 DB 호환을 위해 모든 Entity의 Column Name은 **UPPERCASE** 매핑

### 🔹 Frontend
- **Library**: React (Build by Vite)
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **Convention**: 모든 함수형 컴포넌트는 **Arrow Function (`const App = () => {}`)** 스타일 준수

---

## 🏗 Roadmap & Key Steps

### Step 1. Backend Advancement (Spring Boot 3 + Oracle)
- [ ] **JPA Integration**: 반복적인 SQL 매핑(MyBatis) 대신 JPA를 도입하여 비즈니스 로직에 집중
- [ ] **Strict Naming Strategy**: `@Column(name = "USER_ID")` 처럼 대문자 컬럼명을 명시적으로 매핑
- [ ] **Querydsl**: 복잡한 사내 통계나 조회 쿼리를 자바 코드로 안전하게 구현하는 연습

### Step 2. Frontend Modernization (React + TS + Vite)
- [ ] **Vite Setup**: Webpack 대비 압도적으로 빠른 개발 환경 구축
- [ ] **Strict Typing**: API 통신 데이터(DTO)에 인터페이스를 적용하여 프론트-백엔드 간 데이터 무결성 확보
- [ ] **Component Architecture**: XPlatform의 제약에서 벗어나 자유롭고 체계적인 UI 컴포넌트화

---

## 📝 Learning Rules
1. **DB First**: 테이블 설계 및 컬럼 정의 시 항상 **대문자**를 우선 사용한다.
2. **Modern Syntax**: Java 17 및 ES6+ 최신 문법을 적극 활용하여 코드의 가독성을 높인다.
3. **Clean Code**: "미래의 나" 혹은 "동료 개발자"가 읽기 쉬운 코드를 지향한다.

---

## 📂 Project Directory (TBD)
*주제 선정 및 프로젝트 초기화 후 업데이트 예정*
