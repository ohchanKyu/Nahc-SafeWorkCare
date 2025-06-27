<h1 align="center">$\bf{\large{\color{#6580DD} Nahc \ SafeWorkCare }}$</h1>
<h3 align="center">
 산업재해 예방을 위한 통합 정보 제공 플랫폼
</h3>
<p align="center">
 2025년 고용 노동 공공데이터 활용 공모전 작품 <br>
</p>

<blockquote>
  <p dir="auto">
     <strong> 2025년 고용 노동 공공데이터 활용 공모전 작품 </strong> <br>
     <strong> 개발 기간 : 2025.03.10 ~ 2025.05.15 </strong>
  </p>
</blockquote>

<br>

### 프로젝트 소개
Safe WorkCare는 산업재해 예방을 위한 통합 정보 제공 플랫폼입니다. <br>
산업재해 통계 시각화, 실제 사고 사례 분석, 사업장 맞춤형 위험 진단, <br>
예방조치 체크리스트 작성, 그리고 고용노동부 공식 자료 기반 AI 상담 기능까지 제공하여, <br>
사업장 규모나 업종에 관계없이 누구나 쉽게 안전관리를 체계화할 수 있도록 지원합니다. <br>

<br> 

### 개발 환경
#### Frontend
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
#### Backend
![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white)
![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
#### Backend-LLM
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![Langchain](https://img.shields.io/badge/langchain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
#### Cloud 
- **Oracle** <br>
- **CloudType** <br>

<br>

### 데이터 활용
#### 한국산업안전보건공단
- 규모별 재해자수 <br>
- 규모별 재해율 <br>
- 규모별 사망자수 <br>
- 산업중분류별 재해자수 <br>
- 성별 재해자수 <br>
- 성별 사망자수 <br>
- 연령별 재해자수 <br>
- 연령별 사망자수 <br>
- 산업재해 고위험요인(SIF) 목록 <br>
#### 고용노동부
- 한권으로 통하는 고용노동정책 <br>

<br>

### 서비스 기능
- <p>$\bf{\large{\color{#6580DD} 산업재해 \ 통계 \ 시각화 \ 대시보드 }}$</p>

   #### 기능
     * 산업재해 통계를 업종, 성별, 연령, 기업 규모별로 연도별 시계열 시각화
     * 사용자가 선택한 조건에 따라 데이터 필터링 및 그래프 제공
   #### 핵심 기술
     * 공공데이터 기반 시계열 분석 및 시각화
     * 고용노동부 및 산재공단 통계 API 연동
     * JavaScript 기반 차트 라이브러리(Chart.js) 활용
   #### 사용자 UI
     * 산업재해 통계자료 UI ( 규모별 사망자 수 )
       <p align="left">
         <img src="https://github.com/user-attachments/assets/80850811-8fa5-47c0-bfd0-7289d2f4fe18"/>
       </p>

- <p>$\bf{\large{\color{#6580DD} 산업재해 \ 사례 \ 분석 \ 기능 }}$</p>

   #### 기능
     * 실제 산업재해 사례 데이터 검색 및 사고 유형 필터링
     * 사고 발생 원인과 예방조치 함께 제공
   #### 핵심 기술
     * 산업재해 사례 DB 구축 및 관리
     * 검색 엔진 및 텍스트 필터링 기능
     * 사례 데이터 태깅 및 분류 알고리즘
   #### 사용자 UI
     * 산업재해 사례 분석 UI ( 초기 화면 )
       <p align="left">
         <img src="https://github.com/user-attachments/assets/cbaf7cd8-607c-4a7a-b197-aa66c7719b6c"/>
       </p>
     * 키워드 검색 및 필터링 검색 UI
       <p align="left">
         <img src="https://github.com/user-attachments/assets/2ff0787c-f017-4cad-b303-e45ddef837e7"/>
       </p>

- <p>$\bf{\large{\color{#6580DD} 맞춤형 \ 위험요인 \ 진단 \ 서비스 }}$</p>

   #### 기능
     * 사용자 입력(업종, 작업환경 등)에 따라 유사 조건의 고위험 요소 분석
     * 사전 예방 중심의 위험 인사이트 제공
   #### 핵심 기술
     * TF-IDF 기반 위험요소 자동 추출
     * 코사인 유사도 기반 유사사례 검색
     * 단어 전처리 및 불용어 제거
     * 위험 상황에 대한 LLM 기반 요약 및 클러스터링, 위험도 설명 문장 자동 생성
   #### 사용자 UI
     * 맞춤형 위험요인 진단 UI ( 초기 화면 및 결과 화면 )
       <p align="left">
         <img src="https://github.com/user-attachments/assets/37ae0d83-6b4e-4fab-85b5-db2abc13003a"/>
       </p>

- <p>$\bf{\large{\color{#6580DD} 예방조치 \ 체크리스트 \ 자동 \ 생성 }}$</p>

   #### 기능
     * 진단 결과에 따라 작업별 안전조치 및 보호구 항목 리스트 생성
     * 현장에서 활용 가능한 체크리스트 제공
   #### 핵심 기술
     * LLM 기반 체크리스트 항목 자동 구성
     * PDF 자동 변환 및 다운로드 기능
     * 사고 유형별 예방항목 매핑 시스템
   #### 사용자 UI
     * 예방조치 체크리스트 작성 UI ( 초기 화면 및 결과화면 )
       <p align="left">
         <img src="https://github.com/user-attachments/assets/ef6fd413-55ec-4c79-85f4-5f1c0c7d175f"/>
       </p>
     * 예방조치 체크리스트 다운로드 UI 및 PDF 자동 생성 파일
       <p align="left">
         <img src="https://github.com/user-attachments/assets/677b0a97-42a0-4d73-be8e-997dd57c745e"/>
       </p>

- <p>$\bf{\large{\color{#6580DD} AI \ 기반 \ 정책 \ 상담 \ 기능 }}$</p>

   #### 기능
     * 사용자 질문에 고용노동 정책 문서를 기반으로 실시간 답변 제공
     * 정책 내용의 조항과 함께 정확한 출처 제공
   #### 핵심 기술
     * RAG 기술 기반 질의응답 시스템
     * 정책 문서 임베딩 및 인덱싱
     * 대화 히스토리 저장 및 컨텍스트 유지
   #### 사용자 UI
     * 채팅방 리스트 및 새로운 AI 채팅 생성 UI ( 초기화면 )
       <p align="left">
         <img src="https://github.com/user-attachments/assets/4885a75c-3d08-4a35-8422-69101286f0c3"/>
       </p>
     * AI 채팅 UI
       <p align="left">
         <img src="https://github.com/user-attachments/assets/7ba4e5b5-1df2-4d62-8704-01c3e5034317"/>
       </p>

<br>

### 배포 URL
- https://www.nahc-career.o-r.kr/
- 현재 오라클 및 클라우드 타입 운영 종료


