# 🛒 Spring Cloud MSA E-Commerce Backend

## 📌 Project Overview

Spring Cloud 기반 MSA 구조를 학습하고,  
H2 Database를 활용하여 REST API 기반 E-Commerce 백엔드 시스템을 구현하는 프로젝트입니다.

본 프로젝트는 단순 CRUD가 아닌  
**MSA 구조 설계 + 서비스 간 통신 + API Gateway 구성**을 목표로 합니다.

---

## 🧱 Architecture (Planned)

- API Gateway (Spring Cloud Gateway)
- User Service
- Product Service
- Order Service
- (추가 예정)

---

## ⚙️ Tech Stack

- Java
- Spring Boot
- Spring Cloud
- Spring Data JPA
- H2 Database
- Gradle
- REST API

---

## 🗄️ Database

- H2 In-Memory / File Mode
- 서비스별 독립 DB 구조 지향 (MSA 개념 학습용)

---

## 🌿 Branch Strategy

- `main` : 배포 및 안정 버전
- `develop` : 통합 개발 브랜치
- `feature/*` : 기능 단위 개발

예)

- feature/user-service
- feature/order-service
- feature/product-service

---

## 🚀 Development Rules

- 모든 기능 개발은 feature 브랜치에서 시작
- 개발 완료 후 develop 브랜치로 merge
- main 브랜치는 직접 수정하지 않음
- 서비스 간 의존성 최소화 유지

---

## 🎯 Goals

- Spring Cloud 구조 이해
- MSA 서비스 분리 경험
- API Gateway 구성 이해
- 서비스 간 REST 통신 구현
- H2 기반 빠른 개발 환경 구축

---

## 📌 Status

> Project initialization phase
