# 자연어 딥러닝 기술을 활용한 감정분석 

### 0. 실행 환경
- `google colab` 에서 진행.
- 런타임 유형 하드웨어 가속기 : GPU 및 TPU (TPU사용시에는 tpu_use값을 True로 설정)
- `pytorch`, `transformer` 라이브러리 활용
<br>

### 1. NSMC 영화리뷰 데이터 감정 분석 (`nsmc_emotion_analysis_by_BERT.ipynb`)

- <b>모델</b>  <br>
<t>KOELECTRA Version 3 사용</t>

- <b>실행 방법</b>  
<t>1. nsmc 데이터 본인 구글드라이브에 업로드후 경로 설정<br>
<t>2. 모든 셀 실행을 통해 <b>1) 데이터 전처리, 2) 모델 구현 및 학습, 3) test set 결과 확인 및 csv 파일 변환</b> 가능.

- <b>데이터 출처</b>  
<t>[https://github.com/e9t/nsmc.git](https://github.com/e9t/nsmc.git)


- <b>참고문헌 및 코드</b>    

<t>[모델 학습 관련 소스코드 : https://github.com/deepseasw/bert-naver-movie-review](https://github.com/deepseasw/bert-naver-movie-review)

<t>[KoELECTRA 모델 코드: https://github.com/monologg/KoELECTRA](https://github.com/monologg/KoELECTRA)

<t>[한국어 감정 추가 학습데이터: https://github.com/park1200656/KnuSentiLex](https://github.com/park1200656/KnuSentiLex)

<br>

### 2. Friends 영화대본 데이터 감정 분석(`friends_emotion_analysis_by_BERT.ipynb`)

- <b>모델</b><br>
<t>Bert base 사용</t>

- <b>실행 방법</b>  
<t>1. friends 데이터 본인 구글드라이브에 업로드후 경로 설정<br>
<t>2. 모든 셀 실행을 통해 <b>1) 데이터 전처리, 2) 모델 구현 및 학습, 3) test set 결과 확인 및 csv 파일 변환</b> 가능.


- <b>데이터 출처</b>  
<t>[http://doraemon.iis.sinica.edu.tw/emotionlines/index.html](http://doraemon.iis.sinica.edu.tw/emotionlines/index.html)


- <b>참고문헌 및 코드</b>  

<t>[모델 학습 관련 소스코드(실습7) : https://colab.research.google.com/drive/1EMzEfTYjYLgEHjCCP1vEr9oOZLXMocGh?usp=sharing](https://colab.research.google.com/drive/1EMzEfTYjYLgEHjCCP1vEr9oOZLXMocGh?usp=sharing)

<t>[영어 감정 추가 학습데이터: https://www.kaggle.com/praveengovi/emotions-dataset-for-nlp](https://www.kaggle.com/praveengovi/emotions-dataset-for-nlp)

<br>
