[2024_lab] <br>
<h2>LLM 기반 개인 맞춤형 러닝 경로 추천 앱</h2>
<hr>

:four_leaf_clover: <strong>프로젝트 소개</strong> <br>
본 프로젝트는 LLM(대규모 언어 모델)과 다양한 API를 활용하여 개인의 러닝 경험을 
혁신적으로 개선하고자 한다. 사용자의 환경, 경사도, 시설 등 세부적인 요구사항을 반영한 
경로 추천과 실시간 피드백을 제공함으로써, 사용자의 운동 효율성을 높이고 장기적인 운동 
습관 형성을 돕는 것을 목표로 한다.
<hr>

:four_leaf_clover: <strong>활용 데이터 및 API</strong> <br>
- <em>OpenStreetMap(OSM)</em>:  OSM 데이터를 활용하여 사용자가 선호하는 조건에 적합한 경로를 생성<br>
- <em>Google Maps API</em>: 사용자가 입력한 출발지와 도착지는 Google Maps API의 geocode를 호출하여 location(경도와 위도)을 불러옴<br>
- <em>Open AI API</em>: 사용자의 입력을 바탕으로 OSM 데이터의 태그 추출을 위해 AI를 호출하여 데이터 추출<br>
<hr>

:four_leaf_clover: <strong>구현 과정</strong> <br>
![Image](https://github.com/user-attachments/assets/f288edf8-ac58-4dea-8e27-30508a7b3027)


