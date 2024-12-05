# 이 파일은 서울,대구,부산 광역시에 소품샵을 분류하여 시각화 한 파일로 프로젝트 작성자의 개인적인 주관에따라 필터링을 한 것을 유의하여 봐주시면 감사하겠습니다.
# 프로젝트의 목적 : 소품샵의 정보를 알고 데이터를 가져와 소품샵의 정의 세우기.<br>
소품샵의 정보는 지역별 소상공인 상가 정보이며 제가 생각한 소품샵의 정의는 가챠샵+문구점 느낌의 소품샵이기때문에 굿즈나 1차 창작물을 이용한 상품을 판매하는 매장을 특정하여 조사하였습니다.<br>
# 소품샵의 정의에 의거해 관련 데이터 추출 후 데이터 csv를 따로 만들기<br>
소품샵의 정의에 의거해 데이터를 상권업종중분류명은 오락용품, 표준산업분류명은 인형, 상권업종대분류명은 G2, 마지막으로 상호명으로 분류한 것은 각 지역별로 낚시,스포츠,건담 등등 맞지 않는 분야들을 소거하는 방식으로 분류 했습니다. 이 방법을 이용하여 분류했을때, 원하는 항목만을 세세하게 분류할 수 있다는 장점이 있으나, 데이터셋을 모두 봐야한다는 점과 조건과 맞지않는 부분은 직접 소거해야 한다는 단점이 있습니다.<br>
# 만들어진 csv를 지역별로 나누기 <br>
각각 12만개 22만개 48만개의 데이터들을 최대한 필터링하여 지역별로 나누었습니다.
# csv를 활용해 지역별 점포 개수를 찾기 <br>
# 지역별 분포도 및 차트 작성하기 <br>
위도와 경도를 통해 분포도를 작성하고, 시군구명으로 구분해 차트를 작성합니다.<br>
# 각 지역별 지도 그리기 <br>
위도와 경도를 통해 맵에 위치를 찾고 popup을 통해 마커 클릭시 상호명과 시군구명을 보여줍니다. 마커 색상은 블루로 지정합니다.<br>
위의 내용이 이번 프로젝트의 주요 내용이며 앞으로 더 필요한 것들을 추가할 예정입니다. 
<br>
