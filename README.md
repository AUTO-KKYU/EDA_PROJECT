# 🤖 로봇공학 산업의 취업 시장 동향 및 핵심 기업 분석
# Employment Trends and Key Company Analysis in the Robotics Engineering Industry 

![스크린샷 2024-01-25 210230](https://github.com/donggyu0411/EDA_PROJECT/assets/118419026/08f9c508-0b4e-4c0c-8f7f-0695b3228e0c)


---
## 01. 🏁 프로젝트 소개
- 산업 동향 이해: 로봇공학 산업의 최신 취업 시장 동향을 파악하여, 이 분야에서 어떤 기술이 중요한지 파악
- 핵심 기업 분석: 주요 로봇공학 기업들의 사업 영역, 재무 상태, 채용 동향 등을 분석하여 취업준비생들 궁금해 하는 로봇 분야의 시장경쟁력, 연봉 등을 분석
- 데이터 구축을 통한 CS지식 함양: 크롤링과 DB구을 통해 수집된 데이터와 EDA를 통한 분석을 통해, Code 작성과 데이터 시각화의 insight함양

### 수행 계획 및 예상 결과물
* 1월 17일
    * 주제 선정 및 1차 데이터 크롤링 : 기업이름, url

* 1월 18일
    * url기반 2차  크롤링 

* 1월 19일
    * url 기반 2~3차 크롤링 

* 1월 20일
    * Pandas를 활용한 데이터 전처리 및 MySQL 기반 DB 구축 

* 1월 21일
    * 웹크롤링 DB 보완 및 시각화 시작

* 1월 22일
    * Folium과 seaborn을 통한 데이터 시각화 및 발표 내용 논의
 
* 1월 23일
    * 코드 및 데이터 총 정리, 발표자료 수정 및 시각화 보완

* 1월 24일
    * 최종 발표준비
---
## 02. 🫂 프로젝트 멤버
- 팀명: R.DA(알다)
- 팀장: 유윤하
- 팀원: 김동규 송용탁 양혜경

---
## 03. 📝 프로젝트 기술

![스크린샷 2024-01-24 204430](https://github.com/donggyu0411/EDA_PROJECT/assets/118419026/0cbd3db9-b267-423e-b3fa-d224b893819f)
### <사용한 모듈 및 서버>
- Ubuntu 22.04
- python 3. 10. 12
- matplotlib 3.8.2
- folium 0.15.1
- seaborn-0.13.1
- plotly-5.18
- selenium – 4.16
- beautifulsoup – 4.12.2
- pandas – 2.1.4 
- mysql_connector_python-8.2.0
- Amazon RDS
- chrome
- pytesseract-0.3.10
  
### #필수 기능(주요 구현 기능)
-	MySQL 기반 DB 구축 및 AWS 연동을 통한 관리
-	selenium과 beautifulsoup를 활용한 웹크롤링
-	pandas 모듈을 통한 데이터 전처리
-	matplotlib, seaborn, plotly,folium등을 활용한 데이터 시각


---
## 04. ✍️프로젝트 목적
- 주제 선정을 위한 마인드 맵 작성
 ![Team-mind_map](https://github.com/donggyu0411/EDA_PROJECT/assets/118419026/b7b8d4e5-54f5-4ffc-aff2-eb7b64e0cc1a)
- AI를 응용하려는/하고있는 채용 시장 파악
- 각 직무별 요구하는 핵심 능력 파악
- 기업 분위기 및 기업 가치
- 기업별 요구 기술 스택
---
## 05. ☑️가설 설정
- 로봇 산업군에 대한 의문점 제시
![image](https://github.com/donggyu0411/EDA_PROJECT/assets/118419026/4d614e19-7de6-4c1e-9998-e911f8b08c6e)

- 가설 검증을 위한 Flow Chart

  
![Screenshot from 2024-01-23 15-55-53](https://github.com/donggyu0411/EDA_PROJECT/assets/118419026/4a4ba693-d314-4225-b67b-364b83ffde60)

---
## 06. 🔎 데이터 수집
- 채용 사이트 선정
- 채용 사이트 EDA 과정
### 06.1 채용 사이트 선정
![스크린샷 2024-01-24 213559](https://github.com/donggyu0411/EDA_PROJECT/assets/118419026/9a54bc7d-1290-460d-a89c-62d3a897999d)
### 06.2 채용 사이트 EDA 과정 
![스크린샷 2024-01-24 213822](https://github.com/donggyu0411/EDA_PROJECT/assets/118419026/290c93fd-94fb-44e0-add3-53c5eed243a5)
#### Step 1. 1차 크롤링을 통한 기업 기초 자료 조사 +  상세 정보 크롤링을 위한 URL 수집
#### Step 2. 수집된 URL 기반 2차 크롤링 진행
#### Step 3. '기업이름', '고용형태', '연봉', '기업주소', '키워드', '담당업무','필요역량' csv 생성 및 AWS 업로드
#### Step 4. 구축된 DB 위도 경도 정보 추가, 필요역량 불용어 처리 등 DB 후처리
- 빈출정도 파악
  
![스크린샷 2024-01-24 215442](https://github.com/donggyu0411/EDA_PROJECT/assets/118419026/42a8f07d-070b-44c0-b64d-ab298d54f024)




---
## 07. 🎴데이터 분석 및 시각화
-  직무(키워드) 별 시각화 분석
-  반복어 검출 데이터 기반 시각화 분석
-  Folium을 활용한 지역별 직무 분포 파악

### 07.1 직무(키워드) 별 시각화 분석
#### - 키워드 컬럼 내 자율주행/드론/딥러닝/로봇 제어 분포
![스크린샷 2024-01-24 214908](https://github.com/donggyu0411/EDA_PROJECT/assets/118419026/9e9333e7-36ff-474c-83fb-d656526a91f3)
#### - 각 키워드 컬럼값 내 필요역량 비중
![스크린샷 2024-01-24 215112](https://github.com/donggyu0411/EDA_PROJECT/assets/118419026/53bc7a92-a192-4734-b6ca-c4587f95b19b)
![스크린샷 2024-01-24 215341](https://github.com/donggyu0411/EDA_PROJECT/assets/118419026/21cb1d82-d9bb-4c33-bed6-562bf362614a)

### 07.2 반복어 검출 데이터를 활용한 시각화
#### - 직무 별 필요 역량 파악을 위한 시각화(Word Cloud)
![스크린샷 2024-01-24 215857](https://github.com/donggyu0411/EDA_PROJECT/assets/118419026/b7ef5fda-73db-427a-b59b-8111285f6c13)

### 07.3 Folium을 활용한 지역별 직무 분포 파악
#### - Google Map API와 Folium을 연동한 지역별 직무 분포도
![ezgif com-video-to-gif-converter](https://github.com/donggyu0411/EDA_PROJECT/assets/118419026/5bc9eb29-617e-4bc7-97e7-c33865072046)
![bandicam2024-01-2422-43-08-222-ezgif com-video-to-gif-converter](https://github.com/donggyu0411/EDA_PROJECT/assets/118419026/6991e47e-5ee7-4d36-ade3-576eb313e484)
![bandicam2024-01-2422-45-06-167-ezgif com-video-to-gif-converter](https://github.com/donggyu0411/EDA_PROJECT/assets/118419026/06d4e91a-7c3d-4ebb-a4be-f54f78f6de3d)
![image](https://github.com/donggyu0411/EDA_PROJECT/assets/118419026/1903c0d1-9072-458f-a676-a68ac9b2ca96)
---
## 08. 🗂️DB 구축 및 전망 분석
- AWS RDS와 MySQL을 이용한 채용사이트 DB 구축
- 기업 성장 지표 DB 구축
- Query와 시각화를 통한 DB 분석
- 기업 추천
### 08.1 AWS RDS와 MySQL을 이용한 채용사이트 DB 구축
![스크린샷 2024-01-24 230922](https://github.com/donggyu0411/EDA_PROJECT/assets/118419026/006f6037-58e8-42d2-97f5-4025a274951d)
![스크린샷 2024-01-24 225905](https://github.com/donggyu0411/EDA_PROJECT/assets/118419026/74f32b6b-560c-48ba-a328-ae7566ba910f)
![스크린샷 2024-01-24 230004](https://github.com/donggyu0411/EDA_PROJECT/assets/118419026/afbdb3a6-2485-4df3-84ab-b080d9c0e1f9)
![스크린샷 2024-01-24 230037](https://github.com/donggyu0411/EDA_PROJECT/assets/118419026/3426375e-fa01-41d6-b1b6-dbbaaefed833)

### 08.2 기업 성장 지표 DB 구축
![스크린샷 2024-01-24 230253](https://github.com/donggyu0411/EDA_PROJECT/assets/118419026/a202b010-d896-4f25-a9e6-d7da0200f5d1)
![스크린샷 2024-01-24 230343](https://github.com/donggyu0411/EDA_PROJECT/assets/118419026/95b89f6a-41ed-4248-9315-765c2f3ef71b)
![스크린샷 2024-01-24 230831](https://github.com/donggyu0411/EDA_PROJECT/assets/118419026/dbe5151a-5ab4-4a7e-9511-8911523a74df)


### 08.3 Query와 시각화를 통한 DB 분석
![스크린샷 2024-01-24 230450](https://github.com/donggyu0411/EDA_PROJECT/assets/118419026/8b70e971-039d-4bdb-92fd-0db818af2b81)
![스크린샷 2024-01-24 230707](https://github.com/donggyu0411/EDA_PROJECT/assets/118419026/ff69d8c5-e5fc-4117-bb53-bd31158859fb)

### 08.4 기업 추천
![스크린샷 2024-01-24 231415](https://github.com/donggyu0411/EDA_PROJECT/assets/118419026/53b53a8f-17e8-4c37-ab6b-3f80e369ae04)
![스크린샷 2024-01-24 231638](https://github.com/donggyu0411/EDA_PROJECT/assets/118419026/579955be-c34d-4c00-b9bb-2d852ab97e8c)
![스크린샷 2024-01-24 231701](https://github.com/donggyu0411/EDA_PROJECT/assets/118419026/dacc2a8c-05b7-4bce-b87f-787f4ac008dd)
![스크린샷 2024-01-24 231737](https://github.com/donggyu0411/EDA_PROJECT/assets/118419026/ac2d9bcd-ce62-4a0a-a16d-02a1b9a30e5f)
![스크린샷 2024-01-25 202107](https://github.com/donggyu0411/EDA_PROJECT/assets/118419026/5f9c5674-6c7b-4120-ba5f-66b73dd30f0a)


---
## 08. 📌가설 검증 및 기업 분석
- Fact Check : 채용 시장? 신입 뽑아주나요?
- 가설 검증
- 기업 분석 : 이슈, 채용 정보

### 08.1 Fact Check : 채용 시장? 신입 뽑아주나요?
![스크린샷 2024-01-25 210500](https://github.com/donggyu0411/EDA_PROJECT/assets/118419026/dac199a1-f3d8-4708-9cb5-c8a455cba24e)
![image](https://github.com/donggyu0411/EDA_PROJECT/assets/118419026/b0d35473-5e59-44c2-8582-aa649f439052)
![스크린샷 2024-01-25 210839](https://github.com/donggyu0411/EDA_PROJECT/assets/118419026/980257c6-da2d-40f5-995d-557da622120b)

### 08.2 가설 검증
![스크린샷 2024-01-25 211023](https://github.com/donggyu0411/EDA_PROJECT/assets/118419026/f834eef5-a649-4879-b5d4-582dc9fe1f9b)
![스크린샷 2024-01-25 211123](https://github.com/donggyu0411/EDA_PROJECT/assets/118419026/b8de354d-ef78-4737-87a7-8d3055ac9f5f)
![스크린샷 2024-01-25 211211](https://github.com/donggyu0411/EDA_PROJECT/assets/118419026/09153df9-bd24-45d9-b4e3-4fbfd90c30ef)
![스크린샷 2024-01-25 211257](https://github.com/donggyu0411/EDA_PROJECT/assets/118419026/2dd528c3-b6eb-4f09-97b6-40fe4a914249)
![스크린샷 2024-01-25 211314](https://github.com/donggyu0411/EDA_PROJECT/assets/118419026/13661249-c619-4a9c-9cb9-b2939962d48d)
![스크린샷 2024-01-25 211352](https://github.com/donggyu0411/EDA_PROJECT/assets/118419026/be6d4c73-f913-4523-b84c-2f0b37558e17)
![스크린샷 2024-01-25 211438](https://github.com/donggyu0411/EDA_PROJECT/assets/118419026/c1d4f3ee-b321-4644-a568-345af755ad8e)

### 08.3 기업 분석 : 이슈, 채용 정보
![스크린샷 2024-01-25 211721](https://github.com/donggyu0411/EDA_PROJECT/assets/118419026/8b02c170-c062-4f37-a855-3db09a358ee2)
![스크린샷 2024-01-25 211928](https://github.com/donggyu0411/EDA_PROJECT/assets/118419026/8a8178f6-5399-448d-a128-6a3505f3a08d)
![스크린샷 2024-01-25 212024](https://github.com/donggyu0411/EDA_PROJECT/assets/118419026/b924f556-0276-4d0e-919f-227d8f93086c)

---
## 09. 💡 실전 문제 해결 사례
- 사람인 크롤링의 문제점 : img 파일 형태의 비정형적인 웹사이트
- 점핏 크롤링의 문제점 : 무한 스크롤 웹페이지
- 원티드 크롤링의 문제점 : 로그인 팝업

### 09.1 사람인 크롤링 문제점
![스크린샷 2024-01-25 212217](https://github.com/donggyu0411/EDA_PROJECT/assets/118419026/0e30aed7-1474-47ec-a1b4-2afbe0249fcf)
![스크린샷 2024-01-25 212255](https://github.com/donggyu0411/EDA_PROJECT/assets/118419026/e587370a-f4c1-4abb-aaaf-a4b4db18311b)
![스크린샷 2024-01-25 212555](https://github.com/donggyu0411/EDA_PROJECT/assets/118419026/7597e06e-3264-4f79-894a-42382cb218e0)

### 09.2 점핏 크롤링 문제점
![스크린샷 2024-01-25 212700](https://github.com/donggyu0411/EDA_PROJECT/assets/118419026/fa87e1f5-ca20-4125-8eed-d3a4b03af113)

### 09.3 원티드 크롤링 문제점
![스크린샷 2024-01-25 212739](https://github.com/donggyu0411/EDA_PROJECT/assets/118419026/1d10ffc3-3a85-4860-9844-2aaeea651b38)

## Additional Details 
### The visualization materials related to the EDA project are stored in the form of output in an ipynb file.
