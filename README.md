# ReviewCrawler
Selenium 활용 리뷰 데이터 Crawler

### 개발기간
    2021.08.11~2021.08.11(1일)   
    
### 개발인원
    1인 개발

### 내용
    호텔 이용 리뷰 데이터 수집을 위한 크롤러 개발
    
### 개발배경   
    - 딥러닝 감성분석 텍스트 데이터 필요
    - 호텔 이용 고객 피드백 분석 데이터 필요
   
### 목적   
    리뷰 텍스트 데이터 수집
   
### 개발 중 문제점 및 해결   
    [문제] 인터파크 서버에서 봇으로 인지하여 특정 Action 취할시 테스트 크롬 강제 종료
    [해결] 테스트용 크롬이 아닌 디버깅용 크롬을 띄워 봇으로 인지하지 못하도록 우회
    
    [문제] 리뷰 데이터 중 평점/평점카테고리 항목이 2019.12.04 ~ 2019.12.11 사이에 추가되어 오류 발생
    [해결] 예외 처리 구현하여 평점/평점카테고리가 없는 리뷰의 경우 Nan 처리

### 활용 라이브러리
    - selenium
    - pandas
