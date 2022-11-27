# 서울시 착한가격 업소 현황조사 및 소비자 만족도 분석
![image](https://user-images.githubusercontent.com/108858076/204014633-aacc8135-b67e-48e0-ac1f-36f598e68de5.png)
--------------
### [기획배경]
- 최근 물가 및 외식비 상승에 착안하여 물가 안정을 위해 정부가 운영하는 제도인 착한가격업소 음식점에 대한 운영현황과 소비자 만족도에 대한 조사와 분석을 통해 제도의 본 취지와 방향성에 맞게 운영되고 있는지 살펴보고자 함.
- 프로세스 : 데이터수집 > 데이터전처리 > 데이터시각화분석
--------------
### [사용데이터]
|데이터출처|소스데이터|수집방법|데이터내용|
|----------------|----------|-----------|------------|
|KAKAO MAP|위경도좌표|API|착한가격업소위치정보|
|네이버MYPLACE|메뉴,가격,별점,키워드리뷰|크롤링|착한가격업소의 메뉴,가격,별점,키워드리뷰|
|서울열린데이터광장|서울시착한가격업소현황.csv||업소명,주소,전화번호|
|한국소비자원|외식품목별가격현황.csv||외식대표품목 냉면, 김치찌개, 자장면, 칼국수 등의 가격|
|통계청|서울시 대표품목별외식비물가평균||가격정보|
----------------
### [데이터전처리]
- 위경도 좌표
<img width="618" alt="image" src="https://user-images.githubusercontent.com/108858076/204019705-2601cc5e-f94d-4aba-8adb-49c4deb1501b.png">
- 메뉴,가격,별점,키워드리뷰 크롤링 
----------------
### [최종데이터셋]
![image](https://user-images.githubusercontent.com/108858076/204020071-af6180ff-64cb-4270-88e5-d30a8e0d46aa.png)
----------------
### [결론]
- 키워드 순위에서 가성비는 순위가 하위권이고 친절, 특별한 메뉴가 있어요, 특별한 날 가기좋아요 같이 가심비와 관련된 키워드들이 상위권에 있었다
- 일반음식점에 비해 별점이 다소 가격도 확실히 저렴한걸로 나와 착한가격업소는 가성비쪽에 포커스가 맞춰져 있는데 가성비에 치중하기보다 가심비도 어느정도 잡을 수 있는 방향으로 가야한다
