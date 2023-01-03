# Project-No1
게임판매량에 따른 분석

📌 데이터 전처리

데이터셋 크기 : 16598 * 9

분석에 도움이 안되는 Unnamaed:0 column 삭제

데이터 크기가 유독 작은 2017, 2020년은 유의미한 분석이 어려우므로 삭제

총 판매량을 계산하기 위해 Sales 컬럼 추가

출고량 컬럼의 단위를 K로 통일 한다.

결측치가 존재하는 Year column은 평균값, Genre, Publisher column에는 X를 넣었다
<img width="813" alt="image" src="https://user-images.githubusercontent.com/106293559/175891770-032647dd-ec4d-460d-9abf-9c685864c63e.png">

📌 지역에 따라 선호하는 게임장르

-지역에 따라 선호하는 장르의 평균이 유의미한 차이가 있는지 검증(카이제곱검정이용)
<img width="419" alt="image" src="https://user-images.githubusercontent.com/106293559/175892786-ff480c30-b25a-4091-b36c-f609e618316d.png">

- 지역에 따라 선호하는 게임장르(Bar 그래프)
![image](https://user-images.githubusercontent.com/106293559/175893995-c65c5d3d-5a6a-446d-b705-fcd06ee3fb8b.png)


📌 연도별 게임 트랜드 확인

-시대별(5년단위) 게임트랜드의 변화(라인그래프)
![image](https://user-images.githubusercontent.com/106293559/175893595-b5738355-03f7-48d8-a36f-a1789ccf114d.png)


-연도별 게임트랜드의 변화(Bar 그래프)
![image](https://user-images.githubusercontent.com/106293559/175893747-47de0a06-7638-496d-8116-57130f35df58.png)

📌 출고량이 높은 게임에 대한 분석 및 시각화 프로세스

-판매량(Sales) 기준 상위 20개 게임의 장르별 판매량(Pie 그래프)
![image](https://user-images.githubusercontent.com/106293559/175894753-20b7401a-80b9-4892-803a-21dae3a72067.png)


-판매량(Sales) 기준 상위 20개 게임의 플랫폼별 판매량(Pie 그래프)
![image](https://user-images.githubusercontent.com/106293559/175894839-7d3f6333-503b-426b-8fad-d5aa1b0ac1d5.png)

-전체 게임의 연도별, 플랫폼별 판매량(Bar 그래프)
![image](https://user-images.githubusercontent.com/106293559/175895150-8dbab67e-9dd1-45cc-8ea2-e56edc36a65b.png)

-전체 게임 대상으로 판매량 기준 상위 10개 플랫폼별 판매량(Pie 그래프)
![image](https://user-images.githubusercontent.com/106293559/175895368-4026833d-bdfa-42b9-934a-688f4e900d1e.png)

