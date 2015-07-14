# keti

#### 기술개발 항목
  1. Python 기반 데이터 분석 소프트웨어
    - Python의 다양한 API를 이용하여 데이터를 수집, 분석하는 소프트웨어 개발
    - 웹 컨텐츠에서 필요한 데이터를 수집, 처리, 필터링
    - DB 또는 Log 파일에서 필요 정보 추출 및 처리
 
####세부계획
  1. Python의 다양한 API를 이용하여 데이터를 수집, 분석하는 소프트웨어 개발
    - Python에서 데이터 수집, 분석하는데 사용하거나 필요한 API, Library 알아볼 것. 장단점 비교, 분석
      - Python 을 이용한 기본적인 데이터 분석 
        - Scikit , IPython, numpy, pandas 등 활용
      - Python for Data Analysis 책 읽기
        - 3장 IPython: An Interactive Computing and Development Environment
        - 4장 NumPy Basics: Arrays and Vectorized Computation
        - 5장 Getting Started with pandas
        - 6장 Data Loading, Storage, and File Formats
        - 7장 Data Wrangling: Clean, Transform, Merge, Reshape
        - 8장 Plotting and Visualization
        - 9장 Data Aggregation and Group Operations
    - 기존에 Python을 이용해 데이터 분석한 사례, 예를 정리
      - https://www.kaggle.com/ 기계학습 관련 사이트
    - 데이터 수집 방법
      - 웹 클로러 : 소프트웨어가 웹페이지 링크를 따라 다니면서 모든 문자 수집
      - 시스템 로그 : 서비스 동작중에 발생하는 모든 로그 파일을 분석, 대부분 일정한 패턴으로 동일한 값을 갖는 경우가 많고, 이상 발생시 일부 필드가 변경됨. 자연어 처리에 대한 부담이 적음. 증권/실시간 웹광고 등에 대한 로그 분석으로 실시간 상황 (이익발생) 현황을 분석함 - 근래 많이 사업화 되고 있음
      - 센서 데이터 : 아직 아무도 진행을 별로 하지 않은 분야. 센서 데이터를 사람이 차트보면서 분석하는 것처럼 컴퓨터가 분석함. 예를 들어 1달동안의 전력 미터기 사용 패턴과 날씨 중 외부 온도와 상관도가 얼마나 되는지 분석 
    - 데이터 수집 방법은.. .여러가지가 있으나.. 대상 분야에 따라 세부 내용이 바뀜
      - 웹 크롤러 같은 경우는.. 자연어 처리도 해야함. ㅠ.ㅠ
      - 지난번 미세먼지 웹 추출 같은 경우가. 기초적인 데이터 수집 방법임
      - 빅데이터라고 하면 1TB 정도 인데... 현재 빅데이터를 모으는것도 어려운 문제이고. KETI 에서 보유하고 있는 건물의 센서 정보를 활용하는 것은 편리할 것임
      - 빅데이터 분석을 문자 차원에서 할 것인지. 측정 데이터 차원에서 할것인지가 첫번째 선택사항이라고 볼 수 있음. 문자 차원으로 실험을 하려면 한글로 할것인지. 영어로 할것인지에 따라 데이터를 구할수 있는지 없는지가 결정될 것임
        - 검색어  의미 분석
          - word2vec 
            - https://radimrehurek.com/gensim/models/word2vec.html - gensim word2vec 
            - 설명 : http://alwaysnext.tistory.com/55
            - 관련 데모 : http://w.elnn.kr/search/?query=%EC%99%95%EC%9E%90-%EB%82%A8%EC%9E%90%2B%EC%97%AC%EC%9E%90
            - 데모버전은 한글을 인식하지만 기본적으로 영어를 기반으로 인식함.(한글은 정확도가 낮아 보임)


  1. 웹 컨텐츠에서 필요한 데이터를 수집, 처리, 필터링
    - 웹 컨텐츠로 사용할 때 데이터를 어떤 형태로 전송해야 하는가
    - 기존의 데이터를 어떻게 가공해서 넘겨줄 것인가
  1. DB 또는 Log 파일에서 필요 정보 추출 및 처리
    - string, 배열 형태의 데이터에서 효율적으로 정보 추출하기
  
  - 기계학습
    - https://www.kaggle.com/ 타이타닉 생존자 파악하기
    - 기준데이터를 토대로 사망자/생존자 예측하기
    - 성별, 나이, 가족수, 티켓 가격 등등 여러 데이터를 토대로 최대한 survived 확률 맞추기.

####논문 읽기 리스트
  - http://web.stanford.edu/class/cs344a/readings.html
  
####방학 계획
  - ~7월3,4,5일 : 소프트웨어 마에스트로 오리엔테이션(완료)
  - ~7월11일 : 동아리 앱잼(앱개발 및 발표)(완료)
  - ~7월27일 : 졸업작품 개발 및 중간발표(80%이상 완성)
  - 7월13일~7월31일 : 창업팀 프로토타입 제작
  - 7월6일~8월18일 : 소프트웨어 마에스트로 집체교육(세미나) 시간 : 1~6시 날짜 : 불규칙
  - 8월22,23,24일 : 제주도 여행
  - ~8월31일 : 소프트웨어 마에스트로 1차 프로젝트 마감.
