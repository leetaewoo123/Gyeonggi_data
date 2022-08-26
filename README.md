<div align="center">
  <h3>경기도 데이터 산업인력 양성교육 프로젝트</h3>
  <h5>경기도 산사태 원인 파악과 해결방안 제시</h5>
  <p>
</div>

<br>

## 1. 제안 개요

<details>
  <summary>집주 호우로 인한 피해</summary>
   <div markdown="0" align="center">       
     <br>
     <img src="사진첨부">
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
       <img src="사진첨부">
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

## 2. 활용 데이터
<details>
  <summary>자료 탐색</summary>
     <div markdown="0">       
       <br>
       <img src="사진첨부">
       <br>
     </div>
</details>

<details>
  <summary>데이터 탐색 및 전처리</summary>
     <div markdown="0">       
       <br>
       <img src="사진첨부">
       <br>
     </div>
</details>

<br>

## 3. 분석

<details>
  <summary>강수량</summary><blockquote>
  <details>
     <summary>2019-2020 평균 강수량 비교</summary>
     <div markdown="0" align="center">       
     <br>
     <img src="사진첨부">
     <br>
     <text>:black_small_square: 2020년 강수량이 전년인 2019년도보다 높음 -> 2020년의 강수량 기준으로 산사태 발생 건수 및 면적을 분석</text>
     <br>
   </div>
  </details>
  <details>
     <summary>비교 결과</summary>
     <div markdown="0" align="center">       
     <br>
     <img src="사진첨부">
     <br>
     <text>:black_small_square: 안성 > 인천 > 용인 > 가평 > 양평 > 연천 순으로 산사태 피해가 큼</text>
     <br>
   </div>
  </details>
</blockquote></details>

<details>
  <summary>태양광 발전소</summary>
   <div markdown="0" align="center">       
     <br>
     <img src="사진첨부">
     <br>
     <text>:black_small_square: 가평, 양평, 이천, 연천이 연관성이 있음</text>
     <br>
   </div>
</details>

<details>
  <summary>터널</summary>
   <div markdown="0" align="center">       
     <br>
     <img src="사진첨부">
     <br>
     <text>:black_small_square: 가평, 양평이 연관성 있음</text>
     <br>
   </div>
</details>

<details>
  <summary>모델링</summary><blockquote>
  <details>
     <summary>Train / Test 셋 나누기</summary>
     <div markdown="0" align="center">       
     <br>
     <img src="사진첨부">
     <br>
   </div>
  </details>
  <details>
     <summary>OLS 모델 만들기</summary>
     <div markdown="0" align="center">       
     <br>
     <img src="사진첨부">
     <br>
   </div>
  </details>
  <details>
     <summary>StandardScaler</summary>
     <div markdown="0" align="center">       
     <br>
     <img src="사진첨부">
     <br>
   </div>
  </details>
  <details>
     <summary>Random Forest Regressor 확률 예측</summary>
     <div markdown="0" align="center">       
     <br>
     <img src="사진첨부">
     <br>
   </div>
  </details>
</blockquote></details>
