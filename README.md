# TEXT MINING COURSE

- 실습과제는 상황에 따라 변경될 수 있습니다.
---
## Curriculum

#### WEEK 01. Python 기초문법 알아보기
- 강의개요 소개
- [비정형 텍스트 데이터 분석 기본개념](https://github.com/thejungwon/text-mining-course/blob/master/lecture/week-01.pdf)
- 실습  
  > _실습환경: Python 3.7 & Google Colaboratory_  
  > _W01-1. 텍스트 데이터를 다루기 위한 Python: 기본문법_  
  > _W01-2. 텍스트 데이터를 다루기 위한 Python: 자료구조_  
  > _W01-3. 텍스트 데이터를 다루기 위한 Python: 반복문과 조건문_  
  > _TASK 01: 노래 가사에서 한글과 영어 단어 개수 세기_  

#### WEEK 02. Python으로 텍스트 데이터 다루기
- [텍스트 데이터 실무 활용사례](https://github.com/thejungwon/text-mining-course/blob/master/lecture/week-02.pdf)
- 실습  
  > _W02-1. 텍스트 데이터를 다루기 위한 Python: 정규식_  
  > _W02-2. 텍스트 데이터를 다루기 위한 Python: 파일 입출력_   
  > _W02-3. 텍스트 데이터를 다루기 위한 Python: Numpy 패키지 익히기_  
  > _W02-4. 텍스트 데이터를 다루기 위한 Python: Pandas 패키지 익히기_  
  > _W02-5. 텍스트 데이터를 다루기 위한 Python: Matplotlib 패키지 익히기_  
- 시청각 자료: [뜻밖의 텍스트 마이닝, 네오플 ](https://www.youtube.com/watch?v=DEFU0ZrWBhA)
#### WEEK 03. 텍스트 데이터 수집하기
- [텍스트 데이터 수집유형 및 웹크롤링](https://github.com/thejungwon/text-mining-course/blob/master/lecture/week-03.pdf)
- 실습  
  > _W03-1. Open API 활용하기_  
  > _W03-2. 정적페이지 수집하기: BeautifulSoup, Requests_  
  > _W03-3. 크롤링을 이용한 링크 추출_   
  > _TASK 01: 연속으로 크롤링_ 

#### WEEK 04. 웹크롤링 실전 활용 & 텍스트 데이터 전처리 이해하기
- [텍스트 데이터 전처리 소개](https://github.com/thejungwon/text-mining-course/blob/master/lecture/week-04.pdf)
- 실습  
  > _W04-1. 동적페이지 수집하기: Requests_  
  > _W04-2. 동적페이지 수집하기: Selenium_  
  > _W04-3. 기타 데이터에서 텍스트 추출하기_

#### WEEK 05. 텍스트 데이터 전처리 실전 적용하기
- [형태소분석과 개체명인식](https://github.com/thejungwon/text-mining-course/blob/master/lecture/week-05.pdf)
- 실습  
  > _W05-1. 한국어 텍스트 데이터 전처리하기: KoNLPy_  
  > _W05-2. 영어 텍스트 데이터 전처리하기: NLTK_

#### WEEK 06. 텍스트 데이터 분석하기: 단어 가중치
- [단어빈도분석](https://github.com/thejungwon/text-mining-course/blob/master/lecture/week-06.pdf)
- TF-IDF
- 실습  
  > _W06-1. 단어빈도와 TF-IDF 계산하기_  
  > _W06-2. 단어 가중치를 활용해 워드클라우드 생성하기_  
  > _TASK 01 [(optional): 크롤링 + TF-IDF](https://colab.research.google.com/github/thejungwon/text-mining-course/blob/master/practice/week-07/W07-1_text-mining-for-practice_python-co-word-SOLUTION.ipynb)_
  
#### WEEK 07. 텍스트 데이터 분석하기: 단어 네트워크
- [동시출현분석(연관어분석)](https://github.com/thejungwon/text-mining-course/blob/master/lecture/week-07.pdf)
- 단어 네트워크 분석
- 실습  
  > _[W07-1. 동시출현빈도 계산과 단어 네트워크 생성하기](https://colab.research.google.com/github/thejungwon/text-mining-course/blob/master/practice/week-07/W07-1_text-mining-for-practice_python-co-word.ipynb)_  

#### WEEK 08. 텍스트 데이터 분석하기: 군집화
- [단어/문서 군집화](https://github.com/thejungwon/text-mining-course/blob/master/lecture/week-08.pdf)
- 토픽모델링
- 실습  
  > _W08-1. 뉴스기사 군집화로 이슈 모아보기_  
  > _W08-2. 뉴스기사에서 주제 찾아내기_  

#### WEEK 09. 텍스트 데이터 분석하기: 감성분석 & 키워드추출
- [텍스트 감성분석과 활용, 문서요약과 키워드추출](https://github.com/thejungwon/text-mining-course/blob/master/lecture/week-09.pdf)
- 실습  
  > _W09-1. 키워드 추출 및 문서요약 (TextRank)_  
  > _과제소개: 영화 줄거리로 예상관객 성별 맞추기_  
  > _참고자료: [캐글](https://www.kaggle.com/nicapotato/womens-ecommerce-clothing-reviews/kernels)_  

#### WEEK 10. 텍스트 데이터 분석하기: 단어 임베딩
- [단어 임베딩: Word2Vec, Glove](https://github.com/thejungwon/text-mining-course/blob/master/lecture/week-10.pdf)
- 단어와 문서를 벡터로 표현하는 방법: Word2Vec, Doc2Vec
- 실습  
  > _W10-1. 뉴스기사 텍스트 데이터를 벡터로 표현하기_  
  > _W10-2. 위키피디아 텍스트 데이터를 벡터로 표현하기_
- 참고 사이트: [http://word2vec.kr/](http://word2vec.kr/)

#### WEEK 11. 텍스트 데이터로 머신러닝/딥러닝 적용하기
- [비정형 데이터와 머신러닝](https://github.com/thejungwon/text-mining-course/blob/master/lecture/week-11.pdf)
- 실습  
  > _W11-1. Keras를 이용한 Text Classification 1_   
  > _W11-2. Keras를 이용한 Text Classification 2_   
  > _W11-3. Keras를 이용한 단어 임베딩 생성_   
  > _W11-4. Keras RNN을 이용한 Text Classification 3 [Colab](https://colab.research.google.com/github/tensorflow/docs/blob/master/site/en/tutorials/text/text_classification_rnn.ipynb?hl=ko)_   
  > _W11-5. Keras RNN을 이용한 Text Generation [Colab](https://colab.research.google.com/github/tensorflow/docs/blob/master/site/ko/tutorials/text/text_generation.ipynb?hl=ko)_   

#### WEEK 12. 비정형 데이터 분석 리뷰
- 비정형 데이터 분석 리뷰
- 실습  
  > _W12-1. TBD_  

---
## References
> 본 강의자료는 아래 문헌들을 참고해 구성되었습니다.
- TEXT MINING for PRACTICE, 전병진, https://github.com/fingeredman/text-mining-for-practice
- Byte of Python
- 패스트캠퍼스 <텍스트 분석 유치원 1기~5기> 실습자료
- 텍스트 마이닝(Text Mining), 송민 지음, 청람출판사, 2017
- 파이썬을 이용한 머신러닝, 딥러닝 실전 개발 입문, 쿠지라 히코우즈쿠에, 위키북스, 2017
- Natural Language Processing with PyTorch, 김기현, https://kh-kim.gitbook.io/natural-language-processing-with-pytorch/
