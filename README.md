<div align="center">
  <img src="https://github.com/user-attachments/assets/f6054677-661c-409b-aa00-745a2c649991">
  <h3>날씨 데이터와 서울시 공공 자전거 데이터를 활용한 관리자용 웹사이트 제작</h3>
</div>

## 👥 Team Members

<table>
  <tr>
   <td align="center">
      <a href="https://github.com/hewwwn">
        <img src="https://github.com/hewwwn.png" width="100px;" alt="장희원"/><br />
        <sub><b>장희원</b></sub>
      </a><br />
      <sub>Frontend</sub>
    </td>   
    <td align="center">
      <a href="https://github.com/subeend">
        <img src="https://github.com/subeend.png" width="100px;" alt="송수빈"/><br />
        <sub><b>송수빈</b></sub>
      </a><br />
      <sub>Frontend</sub>
    </td>
    <td align="center">
      <a href="https://github.com/chyun7114">
        <img src="https://github.com/chyun7114.png" width="100px;" alt="윤창현"/><br />
        <sub><b>윤창현</b></sub>
      </a><br />
      <sub>Backend</sub>
    </td>
    <td align="center">
      <a href="https://github.com/hscho0048">
        <img src="https://github.com/hscho0048.png" width="100px;" alt="조호성"/><br />
        <sub><b>조호성</b></sub>
      </a><br />
      <sub>Backend</sub>
    </td>
    <td align="center">
      <a href="https://github.com/wonbne">
        <img src="https://github.com/wonbne.png" width="100px;" alt="이원빈"/><br />
        <sub><b>이원빈</b></sub>
      </a><br />
      <sub>Backend</sub>
    </td>
  </tr>
</table>

## 📋 서비스 소개
저희가 만든 서비스는 서울시 공공 자전거 따릉이의 일일 대여 수요를 주변 환경, 현재 날씨들을 활용하여 예측하고,
따릉이 대여 서비스 관리자가 편리하게 대여소를 관리할 수 있게 도와주는 서비스입니다.

## ✅ 핵심 기능

### 날씨 기반 따릉이 대여 수요 예측 서비스
- 각 대여소별 날씨 정보, 주변 환경 정보를 활용하여 수요 예측
- 향후 5일간의 날씨 정보를 이용해 예측
- 앞으로 5일간의 대여소 수요 정보 활용 가능

### 지도를 활용한 대여소 정보 보기
- 카카오맵 API를 활용한 지도를 제공
- 현재 대여소 위치 확인 가능
- 주변 대여소 정보와 연게하여 확인 가능

### 각 대여소별 현재 날씨 확인하기
- OpenWeatherAPI를 활용한 위도, 경도 기반 날씨 조회 가능
- 대여소별 실시간 날씨 및 날시 예보를 확인 가능

## 🌟 개발 예정 기능
- 시간대별 대여소 수요 예측 기능
- 가까운 대여소 추천 기능
- 서울시 공공 기관과의 연계 사업

  ## 🛠️ 시스템 실행 방법

### **1. 프론트엔드 설정 및 실행**
1. **프론트엔드 클론**
   ```bash
   git clone https://github.com/OpenswTeamProject/frontend.git
   ```
2. **의존성 설치**
   ```bash
   cd <프론트엔드 디렉토리>
   npm install
   ```
3. **개발 서버 실행**
   ```bash
   npm run dev
   ```

### **2. 백엔드 설정 및 실행**
1. **백엔드 클론**
   ```bash
   git clone https://github.com/OpenswTeamProject/back-end.git
   ```
2. **미니큐브 실행**
   - 로컬 Kubernetes 환경을 미니큐브로 설정 및 실행합니다.

3. **배포 파일 적용**
   ```bash
   kubectl apply -f deployment.yaml
   ```

4. **서비스 접속**
   - 브라우저에서 아래 주소를 입력합니다:
     ```
     http://localhost:5173
     ```
