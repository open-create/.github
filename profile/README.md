<div align="center">
  <br />
   <img width="781" height="267" alt="publiT" src="https://github.com/user-attachments/assets/1e658059-ec2b-428d-8434-baeb8dead0f8" />
  <br />
  <h1>publiT</h1>
  <div>
    <img src="https://img.shields.io/github/v/release/Team-SWAcademy/SWAcademy-Server?color=%23068fc6" alt="GitHub release (latest by date)" />
  </div>
  <br />
</div>

## Index

1. [**서비스 소개**](#1)
1. [**기술 스택**](#2)
1. [**주요 기능**](#3)
1. [**프로젝트 구성도**](#4)
1. [**개발 팀 소개**](#5)
1. [**개발 기간 및 일정**](#6)
1. [**실행 방법**](#7)

<br />

<div id="1"></div>

## 📍 서비스 소개

**📝 퍼블릿 (publiT)** 은 공정한 수익구조를 추구하는 AI 기반 글 창작 플랫폼입니다.
<br>
퍼블릿은 다음과 같은 기능을 제공하여 작가분들에게 보다 나은 창작 경험을 제공합니다.
1. AI 기반 스마트 품질 검사: 항목별 점수를 제공하여 글의 보완점을 알려줍니다.
2. publiT 글쓰기 코파일럿: 사용자의 작성 패턴을 분석하여 선호하는 문체, 내용으로 앞으로 작성할 내용을 AI가 작성해줍니다.


이를 통해 독자는 검증된 양질의 콘텐츠를 즐길 수 있고, 신뢰할 수 있는 정보를 얻을 수 있게 됩니다.

[**🔗 프론트엔드 저장소 바로가기 Click !**](https://github.com/open-create/publiT-client) 👈

[**🔗 백엔드(메인 서버) 저장소 바로가기 Click !**](https://github.com/open-create/publiT-server) 👈

[**🔗 AI 모델 서버 저장소 바로가기 Click !**](https://github.com/open-create/publiT-model) 👈

[**🔗 서버 API 문서 바로가기 Click !**](https://hazel-anorak-25a.notion.site/publiT-API-2465f59b177780f28c09da72701bc874?pvs=74) 👈

<br>
<div id="2"></div>

## 🔨 사용 기술
### **Frontend**

| <img height="50" alt="image" src="https://github.com/user-attachments/assets/6128e398-bca3-4240-9789-ccd4ca94c64b" /> | <img height="50" alt="image" src="https://github.com/user-attachments/assets/bfb55eb7-16ec-4de8-8de2-fe955c01c002" />| <img height="50" alt="image" src="https://github.com/user-attachments/assets/de3dd007-19c0-460a-afec-f0e6deb10f69" /> | <img width="50" height="50" alt="image" src="https://github.com/user-attachments/assets/5c99611f-84b9-464f-965e-c56c24e0ff73"> |
| :------: | :---: | :---: | :---: |
|  Typescript | NextJS | Jotai | Tanstack-query |
- 스타일링: Chakra UI / Emotion / Lucide Icon
- 에디터: Tiptap

---
### **Backend**
| <img height="50" alt="image" src="https://github.com/user-attachments/assets/6128e398-bca3-4240-9789-ccd4ca94c64b" /> | <img height="50" alt="image" src="https://github.com/user-attachments/assets/4f4b6dd3-fea6-4b5f-b514-ce13b0c6b5aa" />| <img height="50" alt="image" src="https://github.com/user-attachments/assets/17bca473-4b53-435f-b465-6f14819dc71a" /> | <img height="50" alt="image" src="https://github.com/user-attachments/assets/f664cead-5058-431c-88c6-6c97631cfb22" /> |
| :------: | :---: | :---: | :---: |
|  Typescript | NestJS | Mysql | TypeORM |

---
### **DevOps**
| <img  height="50" alt="image" src="https://github.com/user-attachments/assets/c960ba14-5ad2-4561-9280-2b7e4e7ed871" /> | <img height="50" alt="image" src="https://github.com/user-attachments/assets/1e45bc26-1590-4e71-8351-29e03f0ce964" /> | <img height="50" alt="image" src="https://github.com/user-attachments/assets/95ec0e35-b779-49d6-98d5-202d9dceebc8" /> |
| :------: | :---: | :---: | 
|  Cloud Run | Cloud Build | Docker |


<br>
<div id="3"></div>

## ⭐️ 주요 기능
| 기능 | 내용 |
|---|---|
|소셜 로그인	|Google, Kakao, Naver 등 주요 소셜 계정을 이용해 간편하게 회원가입 및 로그인 가능|
|스마트 리뷰|	사용자가 작성한 글이나 콘텐츠를 분석하여 **항목별 점수(예: 문법, 가독성, 창의성 등)**와 개인화된 코멘트를 제공|
|글 작성/편집|	기본 텍스트 에디터 제공 (작성, 수정, 삭제 가능)|
|글 저장/불러오기	|임시 저장 및 불러오기 기능 지원|
|글 공개/비공개| 설정	개인 보관용 / 공개 여부 설정 가능|
|태그 및 카테고리	|글에 태그/카테고리 추가하여 탐색 및 관리 용이|
|좋아요/댓글	|다른 사용자의 글에 좋아요, 댓글 기능 제공|
|검색 기능|	제목, 태그, 카테고리 기반 글 검색 가능|
|마이페이지	|내가 작성한 글, 받은 리뷰, 통계 확인 가능|
|구독| 원하는 작가를 구독하고 글이 등록될 때마다 알림|

<br>




<div id="4"></div>

## 📝 프로젝트 구성도
### Architecture
<img width="656" height="815" alt="image" src="https://github.com/user-attachments/assets/16ac0479-6acf-42ec-a100-f990c8f9d071" />

### Entity-Relationship Diagram
<img width="1200" height="809" alt="image" src="https://github.com/user-attachments/assets/6d4546b1-868b-40c8-85b5-f6c6e0ff9321" />


<br>








<div id="3"></div>
