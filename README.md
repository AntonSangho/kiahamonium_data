# 경제적 자유를 향한 데이터의 힘 
## 🏫 기아-하모니움 x 공학도서관 데이터 분석 직무탐구

안녕하세요! 경제 데이터 분석의 세계로 떠나는 여정에 오신 것을 환영합니다! 🎉
이코노미스트지의 빅맥지수를 활용해 재미있는 데이터 분석을 시작해봅시다.

## 🎯 수행목표
- 데이터 분석이란 무엇인지, 그리고 데이터 분석의 목적과 중요성을 설명할 수 있어요!
- 다양한 데이터 분석 도구(CODAP, Google Colab, ChatGPT)를 활용하여 데이터를 분석할 수 있어요!
- 빅맥지수의 개념과 경제적 의미를 이해하고 데이터로 해석할 수 있어요!
- 팀 프로젝트를 통해 실제 경제 데이터를 분석하고 인사이트를 도출할 수 있어요!

## ⏰ 일정표

| 시간 | 구분 | 내용 |
|------|------|------|
| 14:00 - 14:07 | **데이터 분석 개념** | • 데이터 분석의 정의와 중요성 <br> • 실생활 속 데이터 분석 사례 <br> • 빅맥지수 데이터의 의미와 활용 |
| 14:07 - 14:14 | **데이터 유형** | • 정형/비정형 데이터 구분 <br> • 범주형/수치형 데이터 이해 <br> • 시계열 데이터 개념 <br> • 빅맥지수 데이터의 유형 분석 |
| 14:14 - 14:22 | **데이터 분석 프로세스** | • 데이터 수집 → 전처리 → 분석 → 시각화 → 해석 <br> • 각 단계별 핵심 개념 <br> • 빅맥지수 분석 프로세스 예시 |
| 14:22 - 14:30 | **데이터 분석 도구** | • CODAP, Google Colab, ChatGPT 소개 <br> • 각 도구의 특징과 장단점 <br> • 실습 준비 안내 |
| 14:30 - 14:45 | **CODAP 실습** | • CODAP 인터페이스 익히기 <br> • 빅맥지수 데이터 불러오기 <br> • 기본 그래프 생성 및 데이터 패턴 관찰 |
| 14:45 - 15:00 | **Google Colab 실습** | • Colab 환경 설정 및 한글 폰트 설치 <br> • 빅맥지수 데이터 시각화 코드 실행 <br> • 국가별/연도별 데이터 필터링 방법 |
| 15:00 - 15:15 | **ChatGPT 실습** | • 효과적인 프롬프트 작성법 <br> • 데이터 분석 질문 예시 <br> • ChatGPT 응답 해석 및 활용 |
| 15:15 - 15:25 | **프로젝트 안내** | • 미니프로젝트 주제 소개 <br> • 팀 구성 및 역할 분담 <br> • 프로젝트 계획 수립 방법 |
| 15:25 - 16:00 | **팀별 프로젝트 수행** | • 데이터 분석 및 시각화 <br> • 인사이트 도출 <br> • 발표 자료 준비 |
| 16:00 - 16:15 | **발표 준비** | • 최종 발표 자료 점검 <br> • 발표 순서 정하기 <br> • 발표 시간 안내 (팀당 5분) |
| 16:15 - 16:45 | **팀별 발표** | • 분석 과정 및 결과 공유 <br> • 발견한 경제적 인사이트 설명 <br> • 질의응답 |
| 16:45 - 17:00 | **종합 토론 및 마무리** | • 전체 프로젝트 리뷰 <br> • 데이터 분석의 한계점 논의 <br> • 추가 학습 자료 안내 |

## github 짧은 주소
- <a href="https://bit.ly/bigmac-index-class" target="_blank">https://bit.ly/bigmac-index-class</a>

## [사전 설문지](https://forms.gle/exampleFormLink)
<img src="./img/qr-pre-survey.png" width="200" height="200">

수업을 진행하기 전에 여러분의 데이터를 알아보기 위한 설문입니다.

## 📝 공유문서
우리가 함께 사용할 공간이에요!
- <a href="https://docs.google.com/spreadsheets/d/bigmac-index-collaboration" target="_blank"> ping 시트 ↗️</a>

## 📊 빅맥지수 데이터셋 컬럼 설명

### 기본 정보 컬럼
- **date**: 데이터 수집 날짜
- **iso_a3**: 3글자 국가 코드 (예: KOR, USA)
- **currency_code**: 3글자 통화 코드 (예: KRW, USD)
- **name**: 국가 이름

### 가격 및 환율 컬럼
- **local_price**: 현지 통화로 표시한 빅맥 가격
- **dollar_ex**: 1달러당 현지 통화 환율
- **dollar_price**: 달러로 환산한 빅맥 가격

### 원시(Raw) 빅맥지수 컬럼
- **USD_raw**: 미국 달러 대비 원시 빅맥지수
- **EUR_raw**: 유로화 대비 원시 빅맥지수
- **GBP_raw**, **JPY_raw**, **CNY_raw**: 각각 영국 파운드, 일본 엔, 중국 위안화 대비 빅맥지수

### GDP 조정 컬럼
- **GDP_bigmac**: 1인당 GDP (달러 기준)
- **adj_price**: GDP를 고려하여 조정된 빅맥 가격

### 조정(Adjusted) 빅맥지수 컬럼
- **USD_adjusted**, **EUR_adjusted**, **GBP_adjusted**, **JPY_adjusted**, **CNY_adjusted**: GDP를 고려하여 조정된 빅맥지수

## 📚 수업 자료실 
데이터와 관련 자료를 찾아볼 수 있는 사이트예요!
- 🍔 <a href="https://github.com/TheEconomist/big-mac-data" target="_blank">빅맥지수 GitHub 저장소 ↗️</a>
- 📊 <a href="https://www.economist.com/big-mac-index" target="_blank">이코노미스트 빅맥지수 공식 페이지 ↗️</a>
- 🌍 <a href="https://www.gapminder.org/" target="_blank">갭마인더 ↗️</a>
- 📈 <a href="https://data.worldbank.org/" target="_blank">세계은행 데이터 ↗️</a>
- 🌐 <a href="https://www.imf.org/en/Data" target="_blank">IMF 데이터 ↗️</a>

## 💻 실습 자료실 
단계별로 따라하면서 배워볼 수 있어요!
1. 🔰 <a href="https://codap.concord.org/" target="_blank">CODAP 환경 접속하기 ↗️</a>
2. 📊 <a href="https://colab.research.google.com/drive/bigmac-index-tutorial" target="_blank">빅맥지수 Colab 튜토리얼 ↗️</a>
3. 🤖 <a href="https://colab.research.google.com/drive/chatgpt-bigmac-analysis" target="_blank">ChatGPT를 활용한 빅맥지수 분석 ↗️</a>
4. 🌐 <a href="https://colab.research.google.com/drive/korean-font-setup" target="_blank">Colab 한글 폰트 설정하기 ↗️</a>
5. 🌍 <a href="https://drive.google.com/file/d/bigmac-visualization-examples" target="_blank">빅맥지수 시각화 예시 ↗️</a>

## 🚀 미니프로젝트 주제 예시
재미있는 프로젝트 주제들을 참고해보세요!

1. **"빅맥 세계 여행 계획"**: 100만원으로 가장 많은 빅맥을 먹을 수 있는 글로벌 여행 경로 계획하기
2. **"통화 가치 분석가"**: 시간에 따른 특정 국가들의 통화 가치 변화 추적 및 경제 이벤트와 연결하기
3. **"경제 발전과 빅맥"**: GDP와 빅맥 가격의 관계 분석 및 예외 국가 사례 연구
4. **"빅맥 예측가"**: 과거 데이터 트렌드를 바탕으로 내년 빅맥 가격 예측하기
5. **"우리나라 빅맥지수"**: 한국의 빅맥지수 변화와 경제 상황 연관성 분석하기

## 🤔 궁금한 점이 있다면?
질문은 언제든 환영합니다! 공유 시트에 자유롭게 작성해주세요!

## [피드백 설문지](https://forms.gle/feedbackFormLink)
<img src="./img/qr-feedback.png" width="200" height="200">

더 나은 수업을 위해 여러분의 솔직한 의견을 듣고자 합니다.
본 설문은 익명으로 진행되며, 앞으로의 수업 개선을 위한 자료로만 활용됩니다.

---
*맛있고 즐거운 데이터 분석 여정이 되길 바랍니다! 🍔✨*