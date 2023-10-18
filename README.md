# Lab_Project-SMU
선문대 랩실에서 활동한 것을 기록하는 repo

### 활동기록
  - 1. 마사토와 같이 식물생장 프로젝트 (main project)에서 사용이 가능한 참고 논문 자료를 조사

       [https://m.dongascience.com/news.php?idx=56019](https://m.dongascience.com/news.php?idx=56019)
       [http://contents.kocw.or.kr/document/lec/2011_2/gnue/Practical/05.pdf](http://contents.kocw.or.kr/document/lec/2011_2/gnue/Practical/05.pdf)
       [https://db-koreascholar-com.libproxy.sunmoon.ac.kr/Article/Detail/422101](https://db-koreascholar-com.libproxy.sunmoon.ac.kr/Article/Detail/422101)

  - 2. 탐색적 데이터 분석 작업

       식물 생장 데이터 (nia-50)을 s3브라우저를 통해서 가져와 , 각 식물들의 데이터에 대해서 eda를 진행

         <b>Introduction</b>
         
           - 1. 도구준비
           - 2. S3연결
           - 3. Nia-50 Data EDA
             - 3-1. 데이터 살펴보기
               - 3-1-1. 데이터 정보
               - 3-1-2. 데이터 통계량
             - 3-2. EDA
               - 3-2-1. NA
               - 3-2-2. Cardinality
               - 3-2-3. 이상치
               - 3-2-4. 상관분석
             - 3-3. 전처리
               - 3-3-1. 시간 데이터
               - 3-3-2. 파생변수

        _EDA.ipynb 참고_

    - 3. Sliding Window

         시계열 데이터에서는 , 시간을 슬라이딩 해주면서 각 시점때의 값을 계산해서 <mark>데이터의 양을 늘려줄 수 있다.</mark>
         각 ClassId 별로 나눠서 새로운 csv파일을 만들어 데이터를 늘려주는 작업을 진행

         _SlidingWindowDataProcessing.ipynb 참고_
