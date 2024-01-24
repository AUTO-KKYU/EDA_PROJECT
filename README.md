# 🤖 로봇공학 산업의 취업 시장 동향 및 핵심 기업 분석
# Employment Trends and Key Company Analysis in the Robotics Engineering Industry 

---
## 01. 🏁 프로젝트 소개
잡코리아, 사람인 등 구직 사이트에서 우리에게 필요한 역량 및 업계 동향 등 필요한 정보들을 분석

---
## 02. 🫂 프로젝트 멤버
- 팀명: 오란씨
- 팀장: 이충한
- 팀원: 강병철 김창미 이수민

---
## 03. 📝 프로젝트 기술

![Screenshot from 2023-10-04 16-10-07](https://github.com/addinedu-amr-4th/eda-repo-5/assets/141194237/3671598a-1cd0-447f-8583-e0e31232449c)

---
## 04. 🔎 데이터수집

---
## 05. 📊 데이터 분석
### 05-1. 로봇 유형
### 05-2. 상장 여부
### 05-3. 필요한 경력 및 학력
### 05-4. 필요한 역량
### 05-5. 채용포지션, 담당업무, 지원자격, 우대사항

![image](https://github.com/addinedu-amr-4th/eda-repo-5/assets/141194237/9716f8cf-b955-4275-b643-dbc3dac99088)

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

