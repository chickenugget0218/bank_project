# bank_project
- 은행 프로젝트
</br>
</br>
</br>

## 데이터
- 시중은행 데이터: 전국은행연합회 반기별 데이터(2022.06) 추출(국민,신한,우리,하나,sc,한국씨티,농협,기업,산업,수협)
- 지역농축협 데이터: 농협 홈페이지 크롤링해 추출
- 새마을금고 데이터: 새마을금고 홈페이지 크롤링
- 우체국 데이터: 금융취급관서만 취급, 군사우체국 제외
- 지방은행(부산,대구,경남,광주,전북,제주) 데이터: 전국은행연합회 반기별 데이터(2022.06) 추출
</br>
</br>

## 파일설명
- 2022_06 은행경향성,2022_06 은행경향성 2.ipynb: 은행 EDA
- 농협지오코딩.ipynb: 카카오 api를 이용하여 지오코딩
- 농협지점.ipynb: 전국 농축협 지점 크롤링
- 새마을금고_구별.ipynb: 전국 새마을금고를 지역, 구 별로 크롤링
- 새마을금고_서울_합치기.ipynb: 구별로 추출한 새마을금고 df로 합침
- 우체국지오코딩.ipynb: 공공데이터포털에 나와있는 우체국 관서 데이터를 불러온 후, 지오코딩
