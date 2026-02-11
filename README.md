# 📚 One Bite Books – App Router

이 프로젝트는 개인 창작물이 아닌,  
인프런 강의 「**한입 크기 Next.js**」의 App Router 파트를 학습하며 따라 만든 실습 프로젝트입니다.

본 레포지토리는 **App Router 기반 프런트엔드 전용 레포지토리**로,  
Next.js의 최신 라우팅 방식인 **App Router 구조를 그대로 구현**하고  
분리된 백엔드 API 서버와 연동하여 동작합니다.

강의 내용을 단순히 따라치는 데서 그치지 않고,  
**Page Router와 App Router의 구조적 차이와 실제 배포 환경에서의 설정을 직접 경험하고 정리하는 것**을 목표로 합니다.

---

## 📖 Reference

- 강의명: 한입 크기 Next.js
- 강의 링크  
  https://inf.run/AfmqK

---

## ✨ Features

- 전체 도서 목록 조회
- 추천 도서 목록 분리 표시
- 도서 클릭 시 **상세 정보 모달 UI 표시**
- 모달 기반 도서 상세 정보 확인
- 도서 **리뷰 작성 및 조회 기능**
- Next.js App Router 기반 페이지 구성
- Server / Client Component 구조 활용
- REST API를 통한 서버 데이터 연동

---

## 🗂️ Repository Structure

```
one-bite-books-app-router
├─ app/ App Router 기반 페이지 구조
├─ components/ 공통 컴포넌트
├─ public/
├─ package.json
└─ README.md
```

---

## 🚀 Live Demo (Production)

Frontend

- https://one-bite-books-app-six.vercel.app/

---

## 🛠 Tech Stack

Frontend

- Next.js (App Router)
- React
- TypeScript
- CSS Modules

Backend

- NestJS
- TypeScript
- Prisma
- REST API  
  (강의에서 제공된 서버 코드 기반)

Database

- Supabase (PostgreSQL)

Dev / Infra

- Git & GitHub
- Vercel

---

## 🔧 Local Development

Frontend 실행

```
npm install
npm run dev
```

API 서버는 별도의 백엔드 레포지토리에서 실행하거나,  
배포된 Production API 서버를 사용합니다.

---

## 🔗 Backend Repository

백엔드 서버는 별도의 레포지토리로 분리되어 관리됩니다.

https://github.com/y-jh107/one-bite-books-server

---

## 📌 Purpose of This Repository

- Next.js App Router 구조 학습
- Page Router와 App Router의 차이점 비교 이해
- Server / Client Component 사용 기준 정리
- 백엔드 서버 분리 및 API 연동 경험
- Vercel 기반 App Router 프런트엔드 배포 경험

---

## 📎 Notes

- 본 프로젝트의 기본 구조는 인프런 강의 「**한입 크기 Next.js**」의 내용을 기반으로 합니다.
- 도서 상세 모달 UI 및 리뷰 기능은 **강의 예제를 확장하여 추가 구현한 기능**입니다.
- 이 레포지토리는 데이터베이스 설계보다는  
  **App Router 환경에서의 컴포넌트 구조, 렌더링 흐름, 사용자 인터랙션 처리**를 이해하는 것을 목표로 합니다.
- 백엔드 서버 및 데이터베이스 스키마는 강의에서 제공된 코드를 기반으로 하며, 본 레포지토리에는 포함되어 있지 않습니다.
- 외부 공유 시에는 **Production 도메인만 사용**합니다.
- Preview URL은 내부 테스트 및 개발 확인 용도로만 사용합니다.

---

## 🙌 Author

학습 및 App Router 기반 프런트엔드 배포 정리  
https://github.com/y-jh107
