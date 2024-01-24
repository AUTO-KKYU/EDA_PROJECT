# 🤖 로봇공학 산업의 취업 시장 동향 및 핵심 기업 분석
# Employment Trends and Key Company Analysis in the Robotics Engineering Industry 

![스크린샷 2024-01-24 203120](https://github.com/donggyu0411/EDA_PROJECT/assets/118419026/b1bc0562-3167-40a8-b7de-44d7f5d16921)

---
## 01. 🏁 프로젝트 소개
- 산업 동향 이해: 로봇공학 산업의 최신 취업 시장 동향을 파악하여, 이 분야에서 어떤 기술이 중요한지 파악
- 핵심 기업 분석: 주요 로봇공학 기업들의 사업 영역, 재무 상태, 채용 동향 등을 분석하여 취업준비생들 궁금해 하는 로봇 분야의 시장경쟁력, 연봉 등을 분석
- 데이터 구축을 통한 CS지식 함양: 크롤링과 DB구을 통해 수집된 데이터와 EDA를 통한 분석을 통해, Code 작성과 데이터 시각화의 insight함양
---
## 02. 🫂 프로젝트 멤버
- 팀명: R.DA(알다)
- 팀장: 유윤하
- 팀원: 김동규 송용탁 양혜진

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

![image](https://github.com/donggyu0411/EDA_PROJECT/assets/118419026/1903c0d1-9072-458f-a676-a68ac9b2ca96)

<br>

#### KoNLPy를 이용한 직무 키워드 추출 및 NLP(Natural Language Processing, 자연어처리)
- 4가지 컬럼 분석: 채용포지션, 담당업무, 지원자격, 우대사항
- 쉽고 간결한 한국어 정보처리 파이썬 패키지
- Okt Class 여러 형태소 분석기를 호출하여 사용
- nouns(): 텍스트에서 명사만 반환하는 함수
- pos(): 텍스트를 형태소 단위로 나눈 후, 각 품사까지 태깅하여 반환하는 함수.

![Screenshot from 2023-10-05 09-35-26](https://github.com/addinedu-amr-4th/eda-repo-5/assets/55674360/2377d9f2-7ecd-43bd-84c6-997d524ebc69)

<br>  
<br>  

#### KoNLPY를 채택한 이유  
- Tesseract 라이브러리를 사용하여 OCR(광학 문자 판독, 이미지에서 텍스트 추출) 구현 시도  
- opencv로 이미지 전처리 하여도 인식률 저하  
  - 필터(Grayscale, Threshold, GaussianBlur, Canny Edge 검출) 사용  
  - ROI 설정하여 cropped된 이미지 사용  
- KaKao Brain에서 개발한  PORORO 자연어처리 라이브러리 시도  

![Screenshot from 2023-10-05 09-35-49](https://github.com/addinedu-amr-4th/eda-repo-5/assets/55674360/54ab90ab-2832-4c87-9407-550bb8bf6300)


<br>
<br>

![Screenshot from 2023-10-04 17-08-29](https://github.com/addinedu-amr-4th/eda-repo-5/assets/141194237/3d9cda86-1648-4695-9ddb-d8438d6c5261)

<br>
<br>

![Screenshot from 2023-10-04 17-08-47](https://github.com/addinedu-amr-4th/eda-repo-5/assets/141194237/1d4be375-a94f-470a-b6ef-9944f0d02b2e)

<br>
<br>

![Screenshot from 2023-10-04 17-09-08](https://github.com/addinedu-amr-4th/eda-repo-5/assets/141194237/1e88d3c2-4836-4fc3-b68f-b85a6321a0e8)

<br>
<br>

![Screenshot from 2023-10-04 17-09-51](https://github.com/addinedu-amr-4th/eda-repo-5/assets/141194237/419e17a7-e083-4e61-8567-1de65203fc73)

<br>
<br>

![Screenshot from 2023-10-04 17-10-08](https://github.com/addinedu-amr-4th/eda-repo-5/assets/141194237/5416b33b-f045-4d57-a64a-be8c7e7c4bc3)

<br>
<br>

![Screenshot from 2023-10-04 17-10-37](https://github.com/addinedu-amr-4th/eda-repo-5/assets/141194237/18937b17-7463-4b7b-9575-e091c8aa8ca6)

<br>
<br>

![Screenshot from 2023-10-04 17-10-58](https://github.com/addinedu-amr-4th/eda-repo-5/assets/141194237/fdfe3230-5d14-46b3-8e99-153e2bc778ef)

<br>
<br>

![Screenshot from 2023-10-04 17-11-28](https://github.com/addinedu-amr-4th/eda-repo-5/assets/141194237/21a6473a-e578-40bd-95fc-40d1552bf39e)

<br>
<br>

![Screenshot from 2023-10-04 17-11-45](https://github.com/addinedu-amr-4th/eda-repo-5/assets/141194237/39511d82-0052-4650-a0db-ced3b12f4e34)

<br>
<br>

### 05-6. 위치 시각화

![Screenshot from 2023-10-04 17-35-09](https://github.com/addinedu-amr-4th/eda-repo-5/assets/146154079/a132baf9-4597-4ab8-9c3e-756011eafe38)

![Screenshot from 2023-10-04 17-35-12](https://github.com/addinedu-amr-4th/eda-repo-5/assets/146154079/bc33984e-0a72-4021-83dd-6bdf70b080b1)

![Screenshot from 2023-10-04 17-39-32](https://github.com/addinedu-amr-4th/eda-repo-5/assets/146154079/1a171c58-9006-42d3-8b1c-d69f659ae6d0)

![Screenshot from 2023-10-04 17-39-38](https://github.com/addinedu-amr-4th/eda-repo-5/assets/146154079/d957a114-8734-44bf-bb12-60bb86461925)

![Screenshot from 2023-10-04 17-40-24](https://github.com/addinedu-amr-4th/eda-repo-5/assets/146154079/cbb4ae4b-9560-4696-aab7-1ac261df8176)

![Screenshot from 2023-10-04 17-45-00](https://github.com/addinedu-amr-4th/eda-repo-5/assets/146154079/98f64e85-326e-4c89-a03a-0ad0f380718c)

![Screenshot from 2023-10-04 17-45-19](https://github.com/addinedu-amr-4th/eda-repo-5/assets/146154079/27fa663c-aa77-41d1-aeed-9500059de827)

![Screenshot from 2023-10-04 17-45-22](https://github.com/addinedu-amr-4th/eda-repo-5/assets/146154079/9ee72936-ef5a-4031-a701-b335df267a8e)

![Screenshot from 2023-10-04 17-45-29](https://github.com/addinedu-amr-4th/eda-repo-5/assets/146154079/31f9e605-c2c3-4546-b9ee-ecfe32651221)

![Screenshot from 2023-10-04 17-45-35](https://github.com/addinedu-amr-4th/eda-repo-5/assets/146154079/d165ce66-b1e9-4ef7-a4f7-27597227c903)

![Screenshot from 2023-10-04 17-45-38](https://github.com/addinedu-amr-4th/eda-repo-5/assets/146154079/15f621d4-a279-4ce1-8b64-3e899083e858)

![Screenshot from 2023-10-04 17-45-41](https://github.com/addinedu-amr-4th/eda-repo-5/assets/146154079/b8be70e2-e147-48f5-9cfd-354829d4213c)

![Screenshot from 2023-10-04 17-45-43](https://github.com/addinedu-amr-4th/eda-repo-5/assets/146154079/83ed9050-11d7-4813-9389-7028f789b6f0)

![Screenshot from 2023-10-04 17-47-00](https://github.com/addinedu-amr-4th/eda-repo-5/assets/146154079/2b4658b5-9592-4247-b159-780ea1d4bb27)

![Screenshot from 2023-10-04 17-47-27](https://github.com/addinedu-amr-4th/eda-repo-5/assets/146154079/1cfc3bb0-2339-4693-915b-1c826c8811c8)

![Screenshot from 2023-10-04 17-47-50](https://github.com/addinedu-amr-4th/eda-repo-5/assets/146154079/983410cf-d6e9-4eba-a6a2-7544354cae2a)

![image](https://github.com/addinedu-amr-4th/eda-repo-5/assets/146154079/b6af5932-7f9f-4294-9e25-b31a4761eca2)

![Screenshot from 2023-10-12 18-58-22](https://github.com/addinedu-amr-4th/eda-repo-5/assets/146154079/19e7d049-5e82-49b6-9316-6278b997f768)

![Screenshot from 2023-10-12 18-59-39](https://github.com/addinedu-amr-4th/eda-repo-5/assets/146154079/57ba0bd1-c4f6-40d9-9213-60180e5533da)

![Screenshot from 2023-10-12 19-00-37](https://github.com/addinedu-amr-4th/eda-repo-5/assets/146154079/b2622d68-195f-4b7a-b852-c3c5fe48d3b7)

![Screenshot from 2023-10-12 19-01-27](https://github.com/addinedu-amr-4th/eda-repo-5/assets/146154079/bb7e5c50-33bf-4bba-ae03-cdbdf6511a88)

![Screenshot from 2023-10-12 19-02-00](https://github.com/addinedu-amr-4th/eda-repo-5/assets/146154079/70f48741-b912-4784-a66f-96d17730fd67)

![Screenshot from 2023-10-12 19-03-35](https://github.com/addinedu-amr-4th/eda-repo-5/assets/146154079/45ec0c08-7471-4e5a-b1f2-2fa5c6ace85b)

![Screenshot from 2023-10-12 19-04-10](https://github.com/addinedu-amr-4th/eda-repo-5/assets/146154079/ed6ae383-7e87-4e7c-9306-0fd4ea17cc64)

![Screenshot from 2023-10-12 19-05-04](https://github.com/addinedu-amr-4th/eda-repo-5/assets/146154079/ee5007c0-4d89-4c95-95f4-d6c5775239f3)

![Screenshot from 2023-10-12 19-06-43](https://github.com/addinedu-amr-4th/eda-repo-5/assets/146154079/e869beca-9ef5-45b4-82de-5e568da34338)

![Screenshot from 2023-10-12 19-07-15](https://github.com/addinedu-amr-4th/eda-repo-5/assets/146154079/5219aea8-5223-440f-a82d-5953a0d75fa3)

![Screenshot from 2023-10-12 19-14-46](https://github.com/addinedu-amr-4th/eda-repo-5/assets/146154079/2984f7dd-f7b0-422b-bd47-ae82b5ed22f4)

![Screenshot from 2023-10-12 19-13-09](https://github.com/addinedu-amr-4th/eda-repo-5/assets/146154079/f4699854-1bb8-4311-8ec4-c40f0c46c26c)

![Screenshot from 2023-10-12 19-09-48](https://github.com/addinedu-amr-4th/eda-repo-5/assets/146154079/8e21ca0c-209a-4e8d-82d6-e3ccd53933db)

![Screenshot from 2023-10-12 19-11-30](https://github.com/addinedu-amr-4th/eda-repo-5/assets/146154079/e88e04e6-90ef-4861-87cb-71a186b8b9eb)

![Screenshot from 2023-10-12 19-23-08](https://github.com/addinedu-amr-4th/eda-repo-5/assets/146154079/2241be81-2578-4023-bd10-726705c515ec)

![Screenshot from 2023-10-12 19-24-04](https://github.com/addinedu-amr-4th/eda-repo-5/assets/146154079/deb689be-f670-4e14-8ab9-b3bae23f4d63)

![Screenshot from 2023-10-12 19-24-50](https://github.com/addinedu-amr-4th/eda-repo-5/assets/146154079/47a6eb0b-af63-4b17-b0f6-d1b3b1bf4f8b)

![Screenshot from 2023-10-12 19-29-34](https://github.com/addinedu-amr-4th/eda-repo-5/assets/146154079/490ced28-84a7-4559-8395-02630b043d81)

![Screenshot from 2023-10-12 19-30-00](https://github.com/addinedu-amr-4th/eda-repo-5/assets/146154079/facbc341-bf6e-4b6d-9976-b793c624673d)

---
## 06. 💡 결론
1. 무엇을 준비하고 공부해야하는가
2. 어떤 분야의 로봇을 공부해야할까
3. 어디 살면 좀 편하게 출근할 수 있을까
4. 이직은 언제쯤 해야 가능성이 높을까
  
![Screenshot from 2023-10-04 17-04-00](https://github.com/addinedu-amr-4th/eda-repo-5/assets/55674360/4646287a-b4c0-4538-a4b4-87e349caa0de)

![Screenshot from 2023-10-04 17-04-04](https://github.com/addinedu-amr-4th/eda-repo-5/assets/55674360/5d7c8d49-4d0c-42f1-8fba-b25bc70c86e1)

![Screenshot from 2023-10-04 17-04-07](https://github.com/addinedu-amr-4th/eda-repo-5/assets/55674360/45f499ea-be06-4600-af0f-271cfb7cad6d)

![Screenshot from 2023-10-04 17-04-10](https://github.com/addinedu-amr-4th/eda-repo-5/assets/55674360/6dfb2bb0-df3f-435c-86f3-fc23d48a91b8)

![Screenshot from 2023-10-04 17-04-14](https://github.com/addinedu-amr-4th/eda-repo-5/assets/55674360/510b1463-aa87-404d-82a9-b732f1a3a552)

---

