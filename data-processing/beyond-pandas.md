---
description: Pandas를 보완 혹은 대체하는 역할
---

# Beyond Pandas

## Dask

> Dask is built on top of pandas / Data를 block 단위로 나누어 처리  
> Multi-Processing\(Parallel\) 연산 / Cluster 구성 가능

> Pandas에서 느린 연산은 Dask에서도 느림  
> Parallel 처리가 어려운 함수들은 미지원  e.g. 정렬

**recommended only for datasets that don’t fit in the main memory \( 1차 전처리 용도 \)**

[Are you still using Pandas for big data?](https://towardsdatascience.com/are-you-still-using-pandas-for-big-data-12788018ba1a)  
  -  pandas로 다루기 힘든 큰 데이터에는 Dask를 함께 활용

## Vaex

> 문자열 처리에 특히 뛰어남

[7 reasons why I love Vaex for data science](https://towardsdatascience.com/7-reasons-why-i-love-vaex-for-data-science-99008bc8044b)

[Flying high with Vaex: analysis of over 30 years of flight data in Python](https://towardsdatascience.com/https-medium-com-jovan-veljanoski-flying-high-with-vaex-analysis-of-over-30-years-of-flight-data-in-python-b224825a6d56)

[How to analyse 100 GB of data on your laptop with Python](https://towardsdatascience.com/how-to-analyse-100s-of-gbs-of-data-on-your-laptop-with-python-f83363dda94)

[Vaex: A DataFrame with super strings](https://towardsdatascience.com/vaex-a-dataframe-with-super-strings-789b92e8d861)

## Modin

> Pandas보다는 아직 성능이 좋지 못하다는 평이 많음

## cuDF

> nVidia graphic이 필요

## ETC

[Faster Pandas with parallel processing: cuDF vs. Modin](https://towardsdatascience.com/faster-pandas-with-parallel-processing-cudf-vs-modin-f2318c594084)  
  -  _Pandas보다 항상 빠른 것은 아니다. \(각자 장단점이 있음\)_

참고 : [Database-like ops benchmark](https://h2oai.github.io/db-benchmark/)  
  -  _single machine에서 다양한 라이브러리로 groupby, join 연산 수행 시 성능 비교_
