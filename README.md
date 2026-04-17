# Enterprise Web Modernization Project

실무 레거시 기술 스택의 한계를 보완하고, 생산성과 안정성이 높은 모던 풀스택 아키텍처를 연구하는 프로젝트입니다.

## 1. Project Overview
- **배경**: JSP, MyBatis, XPlatform 기반 환경의 유지보수 제약을 최신 기술로 해결하고자 함
- **목표**: Spring Boot 3와 React(TS)를 활용한 기업용 시스템 리뉴얼 프로토타입 구축
- **핵심 가치**: 
  - TypeScript를 통한 타입 안정성 확보
  - JPA 기반의 객체 지향적 데이터 설계
  - 컴포넌트 기반의 UI 재사용성 극대화

---

## 2. Tech Stack

### Backend
- **Framework**: Spring Boot 3.x
- **Language**: Java 17
- **Database**: Oracle DB
- **ORM**: Spring Data JPA & Querydsl
- **Convention**: Entity 매핑 시 모든 Column Name은 UPPERCASE 사용

### Frontend
- **Library**: React (Vite 기반)
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **Convention**: 함수형 컴포넌트 작성 시 Arrow Function 스타일 준수

---

## 3. Development Roadmap

### Phase 1: Backend Advancement (Spring Boot & Oracle)
- MyBatis의 SQL 매핑 구조를 JPA로 전환하여 생산성 향상
- @Column 어노테이션을 활용한 대문자 기반 DB 명명 규칙 엄격 준수
- Querydsl을 도입하여 타입 안정성이 보장된 동적 쿼리 구현

### Phase 2: Frontend Modernization (React & TS)
- Vite를 활용한 최적화된 개발 및 빌드 환경 구축
- API 응답값 및 데이터 모델에 대한 엄격한 Type Definition 적용
- 단위 컴포넌트화를 통한 화면 설계 및 비즈니스 로직 분리

---

## 4. Development Principles
1. **Naming**: 데이터베이스 관련 모든 명칭은 UPPERCASE를 원칙으로 함
2. **Syntax**: Java 17 및 ES6+ 최신 문법을 적극 도입하여 가독성 유지
3. **Architecture**: 프론트엔드와 백엔드의 역할을 명확히 분리한 RESTful API 지향

---

## 5. Directory Structure (TBD)
- 상세 주제 선정 및 프로젝트 초기화 후 업데이트 예정
