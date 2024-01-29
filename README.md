# HUGS for Breadho

The Large Legacy Treasury Program "The HST Legacy Survey of Galactic Globular Clusters: Shedding UV Light on Their Populations and Formation" (GO-13297, PI: G. Piotto, 131 orbits) 

허블 우주 망원경을 이용하여 우리 은하의 구상성단을 조사하는 프로젝트인 HST UV Globular Cluster Survey의 데이터를 활용하는 사이드 프로젝트 

**요약** 

- WFC3/UVIS의 F275W, F336W, F438W의 fits 파일을 이용하여 lupton-RGB 함수를 통해 이미지화를 실시
- photutils의 starfinder 함수를 이용, 각 이미지에서 별들을 찾고 magnitude를 계산
- F336W 필터 이미지에서 계산된 magnitude와 F275W 필터 이미지에서 계산된 magnitude의 차이를 계산하여 색등급도(CMD) 생성
- Piotto 연구팀에서 수행한 광도 측정 방법으로 얻은 데이터를 바탕으로 그린 CMD와 비교
