---
layout: post
title:  "강젤 테스트"
date:   2016-06-20 16:20:25
categories: mediator feature
tags: featured
image: /assets/article_images/2014-11-30-mediator_features/night-track.JPG
image2: /assets/article_images/2014-11-30-mediator_features/night-track-mobile.JPG
---

#강젤리의 태블로 활용기
>네이버 데이터랩 콘텐츠 등 태블로를 활용한 다양한 차트 만드는 방법을 포스팅합니다.

##굵기에 값을 반영한 라인차트 그리기

![image](https://cloud.githubusercontent.com/assets/10662638/16186494/c7cea22a-3705-11e6-9719-21ed75f7fc13.png)
> 태블로 화면은 크게 1)데이터 필드가 표시되는 부분(좌) 2)필드를 각각 행/열 값으로 설정할 수 있는 영역(우측 상단) 3) 차트 시각화의 다양한 기능을 넣을 수 있는 marks(중앙) 영역으로 구성된다고 보면된다. 데이터의 개별 필드는 2), 3) 영역으로 이동하면서 다양한 형태의 차트를 만들 수 있다.

![image](https://cloud.githubusercontent.com/assets/10662638/16186610/6dc3c70a-3706-11e6-8b3c-feff06f938bf.png)
> 가장 기본적인 라인차트를 그려보자. 예시로 활용된 데이터는 제주+자연(섬, 오름, 해변, 폭포) 키워드 검색량 데이터다. '날짜' 필드는 '열' 영역으로 '검색량' 필드는 '행' 영역으로 드래그 앤 드롭해 연도별 검색량 차트를 그린다.(여기까지 하면 라인이 하나 있는 차트가 만들어진다.) 연도에 따른 키워드별 검색량을 비교하는 라인차트를 그리고 싶을 때에는 '키워드' 필드를 marks 영역에 있는 color 부분으로 드래그 앤 드롭한다. 키워드별 색을 달리하는 라인그래프가 그려진다.

![image](https://cloud.githubusercontent.com/assets/10662638/16186741/22cf4f7a-3707-11e6-80a7-3f23769eac92.png)
> 이제 마지막으로 라인 그래프에 검색량 수치를 굵기로 표현해보자. 방법은 '검색량' 필드를 marks 영역에 있는 size 부분으로 이동시킨다. 검색량이 많을 수록 라인 그래프가 두꺼워지는 것을 볼 수 있다. 이후 size를 조정하거나, color 기능 내 투명도를 조정해서 시각적으로 잘 보이도록 만들수도 있다.

![image](https://cloud.githubusercontent.com/assets/10662638/16186834/c778beee-3707-11e6-8859-d3e532f50ea6.png)
> 참고) 완성된 예시 대시보드 이미지

위의 차트를 활용해 제작한 네이버 데이터랩 4화 '우리도 떠나요~! 제주여행' [태블로 콘텐츠](https://public.tableau.com/views/_0617/0616_text?:embed=y&:display_count=yes&:showTabs=y&:showVizHome=no#3) 보러가기
