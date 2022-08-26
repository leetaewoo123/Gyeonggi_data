<div align="center">
  <h1>경기도 데이터 산업인력 양성교육 프로젝트</h1>
  <h3>경기도 산사태 원인 파악과 해결방안 제시</h3>
  <p>
</div>

<br><br><br>

## 0. 팀원 소개
- 황지영(팀장), 신동후, 심양관, 이연희, 이태우

<br><br>

## 1. 제안 개요

<details>
  <summary>집주 호우로 인한 피해</summary>
   <div markdown="0" align="center">       
     <br>
     <img src="https://github.com/leetaewoo123/Gyeonggi_data_Project/blob/main/readme/%EC%A7%91%EC%A4%91%ED%98%B8%EC%9A%B0.png">
     <br>
     <br>
   </div>
</details>

<details>
  <summary>태양광 시설물이 산사태 발생의 직접적인 원인이 되지 않을까?</summary>
   <div markdown="0" align="center">       
     <br>
     <img src="사진첨부">
     <br>
   </div>
</details>

<details>
  <summary>안심할 수 없는 경기도 산사태 발생</summary>
     <div markdown="0" align="center">       
       <br>
       <img src="https://github.com/leetaewoo123/Gyeonggi_data_Project/blob/main/readme/%EC%95%88%EC%8B%ACX%EA%B2%BD%EA%B8%B0%EB%8F%84.png">
       <br>
     </div>
</details>

<details>
  <summary>가설</summary>
     <div markdown="0">       
       <br>
       <text> :black_small_square: 인공시설물들이 많이 분포한 지역은 산사태가 많이 발생할 것이다.</text>
       <br>
     </div>
</details>

<details>
  <summary>DATA 분석 계획</summary>
     <div markdown="0">       
       <br>
       <text> :black_small_square: 전처리된 태양광 발전 시설 위치 데이터와 터널 위치데이터를 과거 해당 지역의 산사태 발생 횟수 및 면적과 비교해서 연관성을 파악</text>
       <br>
     </div>
</details>
<br>

<br><br>

## 2. 활용 데이터
<details>
  <summary>자료 탐색</summary>
     <div markdown="0">       
       <br>
       <img src="https://github.com/leetaewoo123/Gyeonggi_data_Project/blob/main/readme/%EC%9E%90%EB%A3%8C%ED%83%90%EC%83%89.png">
       <br>
     </div>
</details>

<details>
  <summary>데이터 탐색 및 전처리</summary>
     <div markdown="0">       
       <br>
       <img src="https://github.com/leetaewoo123/Gyeonggi_data_Project/blob/main/readme/%EB%8D%B0%EC%9D%B4%ED%84%B0_%ED%83%90%EC%83%89_%EB%B0%8F_%EC%A0%84%EC%B2%98%EB%A6%AC.png">
       <br>
     </div>
</details>

<br>

<br><br>

## 3. 분석

<details>
  <summary>강수량</summary><blockquote>
  <details>
     <summary>2019-2020 평균 강수량 비교</summary>
     <div markdown="0" align="center">       
     <text>:black_small_square: 2020년 강수량이 전년인 2019년도보다 높음 -> 2020년의 강수량 기준으로 산사태 발생 건수 및 면적을 분석</text>
     <br><br>
     <img src="https://github.com/leetaewoo123/Gyeonggi_data_Project/blob/main/readme/%EA%B0%95%EC%88%98%EB%9F%89_%EB%B9%84%EA%B5%90.png">
     <br>
   </div>
  </details>
  <details>
     <summary>비교 결과</summary>
     <div markdown="0" align="center">   
     <text>:black_small_square: 안성 > 인천 > 용인 > 가평 > 양평 > 연천 순으로 산사태 피해가 큼</text>
     <br><br>
     <img src="https://github.com/leetaewoo123/Gyeonggi_data_Project/blob/main/readme/%EA%B0%95%EC%88%98%EB%9F%89_%EC%82%B0%EC%82%AC%ED%83%9C_%EA%B1%B4%EC%88%98.png">
     <br>
     <br>
   </div>
  </details>
</blockquote></details>

<details>
  <summary>태양광 발전소</summary>
   <div markdown="0" align="center">    
     <br>
     <text>:black_small_square: 가평, 양평, 이천, 연천이 연관성이 있음</text>
     <br>
     <img src="https://github.com/leetaewoo123/Gyeonggi_data_Project/blob/main/readme/%ED%83%9C%EC%96%91%EA%B4%91_%EC%82%B0%EC%82%AC%ED%83%9C.png">
     <br> 
     <br>
   </div>
</details>

<details>
  <summary>터널</summary>
   <div markdown="0" align="center">    
     <br>
     <text>:black_small_square: 가평, 양평이 연관성 있음</text>
     <br><br>
     <img src="https://github.com/leetaewoo123/Gyeonggi_data_Project/blob/main/readme/%EC%82%B0%EC%82%AC%ED%83%9C_%ED%84%B0%EB%84%90.png">
     <br>
     <br>
   </div>
</details>

<details>
  <summary>모델링</summary><blockquote>
  <details>
     <summary>Train / Test 셋 나누기</summary>
     <div markdown="0" align="center">       
     <br>
     <img src="https://github.com/leetaewoo123/Gyeonggi_data_Project/blob/main/readme/Train_Test.png">
     <br>
   </div>
  </details>
  <details>
     <summary>OLS 모델 만들기</summary>
     <div markdown="0" align="center">       
     <br>
     <img src="https://github.com/leetaewoo123/Gyeonggi_data_Project/blob/main/readme/OLS_%EB%AA%A8%EB%8D%B8.png">
     <br>
   </div>
  </details>
  <details>
     <summary>StandardScaler</summary>
     <div markdown="0" align="center">       
     <br>
     <img src="https://github.com/leetaewoo123/Gyeonggi_data_Project/blob/main/readme/Scaler.png">
     <br>
   </div>
  </details>
  <details>
     <summary>Random Forest Regressor 확률 예측</summary>
     <div markdown="0" align="center">       
     <br>
     <img src="https://github.com/leetaewoo123/Gyeonggi_data_Project/blob/main/readme/RandomForestRegressor.png">
     <br>
   </div>
  </details>
</blockquote></details>

<br><br>

## 4. 활용방안 및 기대효과

<details>
  <summary>예산 투입의 방향성</summary>
   <div markdown="0" align="center">    
     <br>
     <text>
       :black_small_square: 사방사업 예산을 분석해서 산사태가 많이 발생하는 지역에 예산을 더 투입<br><br>
       :black_small_square: 고양, 부천, 수원, 성남, 용인 -> 연천, 포천, 안성 -> 파주, 여주 순으로 사방사업 지원많이 받음<br><br>
       :black_small_square: 포천, 광주, 고양, 시흥, 수원, 성남, 광주, 여주가 산사태 발생횟수에 비해 사방사업 지원을 많이 받음 -> 예산을 낭비하고 있을 가능성<br><br>
       :black_small_square: 어두운 색의 지역일수록 예산을 더 투입해야함<br>
     </text>
     <br>
     <img src="https://github.com/leetaewoo123/Gyeonggi_data_Project/blob/main/readme/%EC%82%AC%EB%B0%A9%EC%82%AC%EC%97%85%EC%98%88%EC%82%B0.png">
     <br><br>
   </div>
</details>

<details>
  <summary>인공시설물에 대한 법규 강화</summary>
   <div markdown="0" align="center">    
     <br>
     <text>
       :black_small_square: 산사태 위험지역 근처에 인공시설물 제한, 벌금 부과<br><br>
       :black_small_square: 공사 중 길을 뚫어 놓은 후 방치하거나 과도한 벌목, 태양광 발전소 안전 관리에 대한 법규 강화
     </text>
     <br>
   </div>
</details>

<details>
  <summary>친환경 바이오 폴리머 제방 설치</summary>
   <div markdown="0" align="center">    
     <br>
     <text>
       :black_small_square: 산사태 위험지역에 친환경 바이오 폴리머 제방 설치<br><br>
       :black_small_square: 친환경 바이오 폴리머는 반나절이면 시공가능하고 기존의 건설비용 30%, 유지비용 70% 절감 가능
     </text>
     <br><br>
     <img src="https://github.com/leetaewoo123/Gyeonggi_data_Project/blob/main/readme/%EB%B0%94%EC%9D%B4%EC%98%A4%ED%8F%B4%EB%A6%AC%EB%A8%B8.png">
      <br><br>
   </div>
</details>

<br><br>

## 5. 데이터 / 아이디어 출처
- <a href="https://www.index.go.kr/potal/main/EachDtlPageDetail.do?idx_cd=1311">산사태 피해현황</a>
- <a href="https://www.index.go.kr/potal/main/EachDtlPageDetail.do?idx_cd=1311">산사태 태양광</a>
- <a href="https://www.youtube.com/watch?v=4m45pcD5ldY">바이오 폴리머</a>
- <a href="https://www.bigdata-map.kr/search/theme?searchKey=%EC%82%B0%EC%82%AC%ED%83%9C">통합데이터 지도</a>
- <a href="https://kin.naver.com/qna/detail.naver?d1id=11&dirId=1122&docId=372322928&qb=7Yis7IiY7Y+s7J6l&enc=http://www.climate.go.kr/home/">기후정보포털</a>
- <a href="http://www.kyeongin.com/main/view.php?key=20220813010002453">탄천 피해</a>
- <a href="https://data.gg.go.kr/portal/data/service/selectServicePage.do?page=1&rows=10&sortColumn=&sortDirectionhttps://newsis.com/view/?id=NISX20220820_0001984899&cID=10401&pID=10400">태양광</a>
- <a href="http://news.tvchosun.com/site/data/html_dir/2020/08/28/2020082890102.html">산사태 원인>태양광</a>
- <a href="http://data.ex.co.kr/portal/fdwn/view?type=ETC&num=T3&requestfrom=dataset#">산사태 위험지역</a>
- <a href="https://data.gg.go.kr/portal/data/service/selectServicePage.do?infId=VI0D9IY634MNRGJITBI527985650&infSeq=1">경기도 태양광 발전소 설치 현황</a>
- <a href="https://newsis.com/view/?id=NISX20220820_0001984899&cID=10401&pID=10400">안전취약태양광</a>
- <a href="https://www.youtube.com/watch?v=VS6D0Pu_hI0">친환경보강공법</a>
- <a href="https://news.kbs.co.kr/news/view.do?ncd=5537268">수해복구 비용</a>


