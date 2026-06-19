<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Pretendard&weight=600&size=28&duration=3000&pause=800&color=4A90E2&center=true&vCenter=true&width=600&lines=%EA%B5%AC%EC%A1%B0%EB%A5%BC+%EB%A8%BC%EC%A0%80+%EC%84%A4%EA%B3%84%ED%95%98%EB%8A%94+%EA%B0%9C%EB%B0%9C%EC%9E%90;%EB%81%9D%EA%B9%8C%EC%A7%80+%EC%B1%85%EC%9E%84%EC%A7%80%EB%A9%B0+%EC%99%84%EC%84%B1%ED%95%98%EB%8A%94+%EA%B0%9C%EB%B0%9C%EC%9E%90;Backend%2C+Frontend%2C+Infra%EB%A5%BC+%EB%AA%A8%EB%91%90+%EB%8B%A4%EB%A3%A8%EB%8A%94+%ED%92%80%EC%8A%A4%ED%83%9D" alt="Typing SVG" />

<br>

# 👋 안녕하세요, 김은동입니다

</div>

<br>

<div align="center">

[![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white)](#)
[![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)](#)
[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](#)
[![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)](#)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](#)

[![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)](#)
[![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)](#)
[![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socketdotio&logoColor=white)](#)
[![Gemini](https://img.shields.io/badge/Gemini_API-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)](#)
[![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)](#)

</div>

<br>

## 💡 About Me

- 🏕️ 4인 팀 프로젝트(**모닥모닥**)에서 **풀스택 + 어드민 시스템 + 인프라**를 담당, 75개 테이블 규모의 데이터 모델 설계와 운영 전반을 책임졌습니다.
- 👗 개인 프로젝트(**FITLOG**)에서 기획부터 인증·실시간 채팅·AI 연동까지 **프론트엔드와 백엔드를 모두 단독 구현**했습니다.
- 🧩 화면 단위 기능 구현에 머물지 않고, DB 모델링·서버 인프라·운영 도구까지 시스템 전체를 보는 개발을 지향합니다.
- 🔄 막히면 원인을 구조적으로 분리해 해결하는 디버깅 방식을 선호합니다. (Oracle Cloud 마이그레이션, Socket 상태 동기화 이슈 등 트러블슈팅 경험 다수)

<br>

## 🛠 Tech Stack

<table>
<tr>
<td valign="top" width="50%">

**Frontend**
- React, Vue.js 3
- JavaScript (ES6+), JSP/JSTL
- MUI v6, Zustand
- HTML5 / CSS3

</td>
<td valign="top" width="50%">

**Backend**
- Spring Boot 3.x, MyBatis
- Node.js, Express
- Socket.io (실시간 통신)
- JWT, Passport.js, OAuth2

</td>
</tr>
<tr>
<td valign="top">

**Database**
- MySQL (AWS RDS)
- Oracle Database (Oracle Cloud ATP)

</td>
<td valign="top">

**External API / Tools**
- Google Gemini API
- Kakao Map, Toss Payments
- Git / GitHub

</td>
</tr>
</table>

<br>

## 📌 Projects

### 🏕️ [모닥모닥 (ModakModak)](https://github.com/sochaeyeon/modak)
> 캠핑장 조회 · 장비 렌탈/구매 · 커뮤니티 통합 캠핑 플랫폼 | 팀 프로젝트 (4인) | 2026.04 ~ 2026.04

`Spring Boot` `MyBatis` `JSP` `Vue.js 3` `MySQL`

**담당: 풀스택 / 어드민 시스템 / 인프라**

- 메인 페이지, 캠핑장 지도·목록·상세 조회(시설 정보 포함) 구현
- 비회원 주문 조회·상세, 회원/비회원 대여 연장·반납·교환 처리 로직 설계
- 게시판(목록·상세·작성), 1:1 실시간 채팅방 및 채팅 목록 통합 관리, AI 챗봇 연동
- **Admin 시스템 전체** — 대시보드·매출 통계·회원·상품·캠핑장·쿠폰·리뷰·문의·등급·알림·주문취소 통합 관리 구현
- 알림 목록/상세, 설치·QR·분리수거 가이드 페이지 구현
- 초기 29개 → 최종 75개 테이블로 확장된 데이터 모델 설계 참여

<br>

### 👗 [FITLOG](https://github.com/rladmsehd135/fashion-sns)
> 코디 공유 · AI 스타일 추천 · 실시간 커뮤니티 패션 SNS | 개인 프로젝트 | 2026.05 ~ 2026.06

`React` `Node.js/Express` `Oracle DB` `Socket.io` `Gemini API`

**기획부터 배포까지 프론트엔드/백엔드 단독 구현**

- JWT Access/Refresh Token 이중 구조 인증, 카카오·구글 소셜 로그인 연동
- OOTD 게시물 업로드(다중 이미지), 인스타그램 스타일 상세 모달, 이미지 캐러셀 구현
- Socket.io 기반 1:1·그룹 실시간 채팅 — 읽음 처리, 타이핑 인디케이터, 안 읽은 메시지 카운트 동기화
- Google Gemini API를 활용한 개인 스타일 분석 기반 AI 코디 추천 기능 구현
- 24시간 스토리, 인기 랭킹, 스타일 배틀, 다크/라이트 모드(Zustand persist) 구현
- Oracle Cloud ATP 마이그레이션 트러블슈팅 (스키마 충돌, identity 컬럼, tablespace 이슈 해결)

<br>

## 📈 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=rladmsehd135&show_icons=true&theme=default&hide_border=true&count_private=true" width="49%" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=rladmsehd135&layout=compact&hide_border=true&theme=default" width="35%" />

<br>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=rladmsehd135&theme=default&hide_border=true" width="60%" />

</div>

<br>

## 📮 Contact

- **Email** : [eundong011204@naver.com](mailto:eundong011204@naver.com)
- **Phone** : 010-8010-9397
- **GitHub** : [github.com/rladmsehd135](https://github.com/rladmsehd135)

<br>

<div align="center">

**문제를 구조화하고, 끝까지 책임지는 개발을 합니다.**

</div>
