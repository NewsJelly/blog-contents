---
layout: post
title:  "강젤리의 태블로 활용기#1 라인차트 그리기"
date:   2016-06-19 17:34:25
categories: injell feature
tags: featured
image: /assets/article_images/2014-11-30-mediator_features/night-track.JPG
image2: /assets/article_images/2014-11-30-mediator_features/night-track-mobile.JPG
---

![태블로 기본 화면](https://cloud.githubusercontent.com/assets/10662638/16189347/ee550b0a-3714-11e6-8258-00c868e8d000.png)
> 본격적인 라인 차트 그리기에 앞서 태블로 화면 구성을 간략하게 알아보자! 태블로 화면 구성은 크게 1) 활용가능한 데이터 필드 표시(좌측) 2) 데이터 필드를 이동시켜 놓을 수 있는 행/열 영역(우측 상단) 3) 시각화 유형 및 상세 기능을 조정할 수 있는 marks 영역(중앙)으로 구성된다고 보면 된다. 1)에 있는 데이터 필드는 2), 3) 영역으로 드래그 앤 드롭해서 다양한 형태의 차트를 만들 수 있다.

!(https://cloud.githubusercontent.com/assets/10662638/16189465/750d66ba-3715-11e6-8f72-1648db39f1e1.png)
> 가장 기본적인 라인 차트를 그려보자! 이번 포스팅에서 활용한 데이터는 제주+자연(섬, 오름/산, 폭포, 해변) 키워드별 검색량 데이터다. 먼저 차원(dimension)영역에 있는 '날짜' 필드를 '열' 영역으로 이동시키고, 값(measures) 영역에 있는 '검색량' 필드를 '행' 영역으로 이동시킨다. 이 경우 연도별 전체 검색량 추이를 볼 수 있는 라인 그래프가 그려진다. 키워드별 검색량 데이터를 시각화 하기 위해서는 '키워드' 필드를 marks 영역 내 color 영역으로 이동시키면, 키워드별로 색깔이 구분되면서 여러개의 라인이 그려지는 차트를 만들 수 있다.

!(https://cloud.githubusercontent.com/assets/10662638/16189588/fb2704b8-3715-11e6-8308-32a17b24e876.png)
> 위에서 그린 라인그래프를 좀 더 시각적으로 극대화 시켜보자! 그 방법 중 하나로 검색량이 많아질수록 라인의 굵기를 두껍게 만드는 것이 있다. 방법은 '검색량' 필드를 marks 영역내 size 영역으로 이동시키면 된다. 최근으로 올수록 검색량이 증가하므로, 각각의 라인그래프도 최근으로 올수록 두꺼워진 것을 볼 수 있다. 나아가 size를 조정하거나, color 기능 중 각 라인의 투명도를 조정하는 등의 방법으로 좀 더 이쁘게(?) 만들어 볼 수도 있다.

![위 기능을 활용하여 만든 예시 대시보드 : 위에서 만든 sheet에 제목과 컬러레전드를 삽입했다.](https://cloud.githubusercontent.com/assets/10662638/16189670/89fd8310-3716-11e6-8cdc-ade4ac093fd6.png)

위와 같은 차트를 활용한 데이터랩 4화 [우리도 떠나자! 제주여행 태블로 콘텐츠 보기](https://public.tableau.com/views/_0617/0616_text?:embed=y&:display_count=yes&:showTabs=y&:showVizHome=no#3)
