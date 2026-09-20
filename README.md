<div align="right">
  <a href="./README_EN.md">English Version</a>
</div>

# 안녕하세요! 통계 분석가 / 데이터 사이언티스트 Hanwo-ol 입니다.

> 현재 전북대학교 의생명연구원 신경과 Vestibular Lab에서 전정기능장애 및 신경계 질환 환자 데이터를 기반으로 통계 분석 및 데이터 모델링을 연구하고 있습니다.

<br>

## EXPERIENCE
홀 매니저와 영업을 하며 인과분석이라는 연구를 접했고
복학과 석사과정을 거치며 연구자의 길을 시작했습니다.(물론 인과분석은 아직 시작도 못했습니다.)

### 전북대학교병원 의생명연구원 신경과 Vestibular Lab
- Researcher (2026.06 - 현재)
- 보행분석을 통한 전정기능장애 예측 및 진단 보조 딥러닝 모델 연구
- 환자 안구 운동 영상 및 신호 데이터를 활용한 전정기능장애 진단 보조 모델링 연구
- 전정기능장애 관련 바이오마커 발굴 및 딥러닝 모델 연구
- FHIR 기반 MG 모델링 연구

## EDUCATION

### 전북대학교 대학원 통계학과 
- 석사 졸업 (2024.09 - 2026.08)
### 전북대학교 통계학과 / 금융경제정보학 
- 학사 졸업 (2017.03 - 2024.02)

<br>

## PUBLICATION
아직은 미약하고 볼품 없습니다. 연구 자체가 너무 행복하고 즐거운 과정이기 때문에 한 줄 씩 늘려 나갈겁니다.

### 1저자
- Kim, Hanwool, et al. "Spatiotemporal Attention With Conditional Feature Modulation for Satellite-Based Solar Irradiance Prediction." IEEE Geoscience and Remote Sensing Letters 23 (2025): 1-5.

### 석사 졸업 논문
- Conditional Diffusion with CRPS Loss Post Spatially Adaptive Refinement: Appliction to Spatio-Temporal Image Prediction.(2026.8.)
  - 지도 교수님: 전북대학교 통계학과 김광수 교수님

### 학회 발표
- **한국통계학회 포스터 발표 (1저자)** - *문서의 멀티모달 특징과 매니폴드 학습을 이용한 분류 성능 향상 연구* (2025.06)
- **한국인공지능학회 포스터 발표 (3저자)** - *Human vs LLM Text Classification Using a Multi-Feature Approach* (2025.08)
- **한국인공지능학회 포스터 발표 (2저자)** - *Interpretation of Medical Imaging in Survival Prediction with DNN and UMAP* (2024.11)

<br>

## Research Projects (주요 연구 과제)

### 위성 영상 기반 일사량 예측 모델링[2024.09 - Current]
#### 주요 역할
- 공간적-시간적 어텐션(Spatiotemporal Attention) 기법을 적용한 일사량 예측 파이프라인 구축
- FiLM을 통해 주변 정보를 모델에 injection 하는 등 조건부 정보 주입 방법론 연구

#### 성과
- 연구 결과를 바탕으로 IEEE GRSL 1저자 논문 게재 (2026.01)
- CRPS 손실 기반 조건부 확산과 사후 공간 적응형 보정 모델 - 석사 졸업 논문 인준 (2026.01 - 2026.08)
- 디퓨전 기반 태양광 예측 및 사후 공간 적응형 보정 모델 paper work (2026.01 - ing)

### 풍력 발전 예측(Wind Prediction) 모델링 연구[2025.11 - Current]
#### 주요 역할
- 풍력 발전량 예측을 위한 데이터 분석 및 모델링 연구 수행

#### 성과
- On progress

### 의료 데이터 ML/DL 모델의 Reproducibility/Generalization 검증 연구[2025.12 - Current]
#### 주요 역할
- 당뇨 및 Glucose 예측 연구 파트 책임
- Breast Cancer 예측 및 COVID-19 ML 모델의 Reproducibility(재현성) 검증 연구 수행

#### 성과
- On progress -- NPJ Digital Medicine submission 준비

### 가상 현실 공간 탐색(vMWM) 기반 경도인지장애(MCI) 행동 지표 분석 연구[2026.06 - Current]
#### 주요 역할
- vMWM 가상 궤적 데이터 및 다변량 행동 지표(지연시간, 부유 행동, 근접도 오차, 종점 전략) 전처리 파이프라인 구축 및 통계 분석 총괄
- 일반화추정방정식(GEE), 다항 로지스틱 회귀, 사후 생존분석(Cox, AFT) 및 부트스트랩 검증 등 통계 모형 구축
- 논문 Methods 및 Results 통계 파트 작성, 재현성 검증 및 데이터 무결성 감사 수행

#### 성과
- On Progress -- Alzheimer’s Research & Therapy submission 준비 중

### 경도인지장애 환자의 어지럼 장애에 대한 표준화 은행엽 추출물 임상시험[2026.06 - Current]

#### 주요 역할
- 임상 통계 및 민감도 분석(Formal Analysis): ANCOVA 주분석, 결측치 보정을 위한 MICE(다중대체법, $m=20$) 분석, Tipping-point 분석 및 18점 Responder(반응군) 분석 수행
- 임상 데이터 큐레이션 및 파이프라인 구축(Data Curation & Software): 71명 무작위 배정 임상 코호트 데이터 전처리·정제 및 재현 가능한 Python/R 분석 파이프라인 개발
- 결과 시각화 및 원고 작성 지원(Visualization & Writing): CONSORT 흐름도, Tipping-point 히트맵, DHI 점수 변화 그래프 등 핵심 Figure/Table 제작 및 통계·결과 섹션 검토/수정

#### 성과
- On Progress -- Phytomedicine 투고 및 심사 중 (Manuscript No. PHYMED-D-26-09173) (Standardized Ginkgo biloba Extract for Dizziness-Related Disability in Mild Cognitive Impairment: A Randomized Placebo-Controlled Trial)


### 무역 시계열 데이터 기반 이상 탐지(Anomaly Detection) 모형 연구 [2024.12 - 2025.09]
- 의뢰 기관: 한국기계산업진흥회 -> 전북대학교 산학협력단 통계학과
#### 주요 역할
- 기존 알고리즘의 적절성 검토 및 다변량 이상 탐지 최신 문헌(40건) 비교 분석
- 데이터 처리 파이프라인 검수 및 기존 모델 잠재 버그 개선
- CICADA 알고리즘 기반 이상 탐지 모델 설계 및 제안 (최종 채택)
- 최종 소스코드, 사용 가이드라인, 데이터 수집 방안 문서화 및 전달


<br>

## Teaching & Mentoring (교육 및 멘토링)

- **전북대학교 교내 튜터링** (2025.07 - 2025.08)
  - 학부생 대상 딥러닝 문헌 조사 및 모델링 아이디어 세미나 개최
- **전북대학교 응용통계연구소 하계 특강 조교 (전주 솔내고)** (2025.07)
  - Python을 활용한 데이터 처리, 전처리 및 관리 방안 실습 교육 진행
  - 수강생 질의응답 및 자습용 코드 공유 페이지 운영
- **전북대학교 응용통계연구소 2025 하계 WORKSHOP 조교** (2025.07)
  - R을 이용한 통계 자료 분석 강의 조교
  - 과정별 질의응답 내용을 복습할 수 있는 저장소 페이지 운영
- **농촌진흥청 GWAS 분석 조교** (2025.04)
  - R을 활용한 식물 유전자 탐색 및 GAPIT 데이터 처리 방안 가이드라인 제공
- **전북대학교 응용통계연구소 2025 동계 WORKSHOP 조교** (2025.01)
  - R을 이용한 통계자료분석 시각화 과정 강의 조교
  - 대학원생 및 연구원 대상 1:1 질의응답 및 시각화 토론 진행

<br>

## Tech Stack (기술 스택)

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" /> 
  <img src="https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white" alt="R" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" />
</p>

<br>

## Interested in...



<br>

## Contact

- **Email**: [11015khw@gmail.com](mailto:11015khw@gmail.com) / [1015khw@naver.com](mailto:1015khw@naver.com)
- **Google Scholar**: [Scholar Profile](https://scholar.google.com/citations?user=Fo2SdQIAAAAJ&hl=ko)

<br>

<details>
<summary><b>기타 이력 및 활동 (클릭하여 펼치기)</b></summary>
<div markdown="1">

- **자격증**: 데이터분석준전문가(ADsP, 2023.09), TOEIC (955점, 2024.03), 회계관리 2급 (2019.01)
- **엘비휴넷(주) 전주센터 마케팅전략팀** (2022.02 - 2023.03): OutBound 마케팅 및 DB 관리, 주간 실적 집계 분석
- **수출입은행/전북 자원봉사 (희망씨앗 봉사단 9기)** (2021.06 - 2021.12): 네이처 리패브릭 팀 대외 협력 및 참여자 DB 분석 (최종 1등 수상)

</div>
</details>
