# 감성분석 기반 심리상담 AI 챗봇
**"일상이 된 비대면…소통부재·고립"**

코로나19 사태의 장기화, 거리두기의 일상화로 재택근무와 원격수업 등이 일상으로 자리 잡았습니다.   
2022년에는 비대면 문화에 기반한 서비스가 훨씬 세련되고 정교화될 것이지만, 이런 상황이 불러올 부작용으로 대면 소통이 줄면서 사회 전체가 움츠러들고 사람들이 고립되어간다 생각해습니다. 

## 목적
코로나 사태로 사람을 못만나면서 우울감이 늘어나고있습니다. 우울감은 챗봇으로도 급감한다는 결과의 기사를 접했습니다. 그래서 사용자의 감정을 인식해 상호작용을 하는 챗봇 프로젝트를 진행했습니다

보통 챗봇 심리상담으로 얻을 수 있는 기대효과는   
- 좋은 접근성, 24시간연결
- 비대면
- 장기적으로 비용절감

이러한 이유들에도 불구하고 현재, 소비자가 챗봇에 만족하지 못한 이유를 알아보았습니다 (출처 챗봇 소비자 만족도, Spicesworks)   

 
그래서 이러한 부분을 반영하기위해 아래의 3가지를 목표로 진행했습니다.   
1. GPT-2 모델을 사용하여, 고정되지 않은 다양한 형태의 문장 생성.   
2. BERT 모델을 사용하여, **문장 맥락 파악**과 사용자 특징, 감정, 상황 등을 반영.   
3. Q,A,Q형식으로 대화 내용을 기억하여 맥락파악   



## 기간
2021.03.31 - 2021.05.19 (8 주)


## 팀 구성
본인 외 2인

## 팀 내 역할
Python을 활용한 데이터 결측치 처리, 라벨 정수화   
훈련된 BERT모델을 사용하여 스코어 출력 기능 구현   
GPT모델로 생성된 문장 중 길이제한으로 미완성 문장 제거 기능 구현   
사용자의 말투가 섞여서 생성된 경우, 케이스에 따라 문장 부분 삭제 기능 구현   
입력문장에 구두점이 없을 경우, 끝에 "." 붙여서 전달하는 기능 구현   
대화를 Q+A+Q 형식으로 저장하며 이전 대화 반영 기능 구현   


## 사용 기술
python, koGPT-2, klueBERT, streamlit


## 개발 과정 
- 앞서 진행한 3개의 프로젝트와 다르게 마지막 프로젝트는 처음 진행한 장기 프로젝트로, 하루하루 일정을 기록하고 전체를 관리하며 진행했습니다.   
<img src="https://user-images.githubusercontent.com/97740175/173689837-329990e9-6eec-4dbb-ba8d-0472862c8dbc.png" width="90%" height="90%"></img>

### 데이터 분석

### 모델

### 쳇봇시연

### 서비스확장





