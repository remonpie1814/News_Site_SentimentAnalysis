# News_Site_SentimentAnalysis by 한예지

10.21 네이퍼 쇼핑리뷰, 영화 리뷰, AIhub 감성 대화 말뭉치 데이터를 다운로드 해 하나의 데이터프레임으로 만들고 LSTM, GRU을 쓴 모델에 학습시켜봤다.  

10.23 문장을 형태소 분석하고, 자주 쓰인 단어를 뽑아봤다.  
모델을 불러 와 빈출 단어가 쓰인 문장이 긍정적인지 부정적인지 판별했다.  
긍정적인 문장에 자주 쓰인 단어는 파란색으로, 부정적인 문장에 자주 쓰인 단어는 빨간색으로, 둘 중 어느 것도 아닌 단어는 초록색으로 표시해 wordcloud에 표시해봤다.  
kibana에 입력하기 위해 단어, 빈도, 긍정/부정 문장의 개수를 적은 데이터프레임을 만들어 csv 파일로 저장했다.  

다음으로 할 것 --> 오늘 한 것을 입력=데이터 출력=csv파일인 함수 하나로 묶어두기  
같은 문장을 여러 번 모델에 예측시키고 있다. 개선할 것.


10.25 뉴스 크롤링.
news_crawl_chosun -> 조선일보 크롤링 코드.
