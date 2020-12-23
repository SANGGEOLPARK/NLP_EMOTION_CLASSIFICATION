# NLP_EMOTION_CLASSIFICATION

개발 환경 : Colab Pro - GPU


## 1. 한국어 감정 분석(NSMC)
  
  ### 1) KOELECTRA 모델 이용(캐글 제출모델)
     NSMC_KOELEC_BASE3.ipynb
     
  * 평가 파일 본인 구글드라이브 저장(ko_data.csv)
  
참고 : https://github.com/monologg/KoELECTRA \n
       https://heegyukim.medium.com/huggingface-koelectra%EB%A1%9C-nsmc-%EA%B0%90%EC%84%B1%EB%B6%84%EB%A5%98%EB%AA%A8%EB%8D%B8%ED%95%99%EC%8A%B5%ED%95%98%EA%B8%B0-1a23a0c704af
 
  ### 2) 머신러닝 모델 VOTING 기반 CLASSIFICATION
      NSMC_ML_TFIDF_VOTE.ipynb
  
  * 평가 파일 본인 구글드라이브 저장(ko_data.csv)

## 2. 영어 감정 분석(FRIENDS)
   
   ### 1) ELECTRA 모델 이용(캐글 제출모델)
       FRIENDS_ELEC_LARGE.ipynb
   
   * 본인 구글드라이브에 EmotionLines_friends_annotation.tar.gz 저장
   * 평가 파일 본인 구글드라이브 저장(en_data.csv) 
   
참고 : https://colab.research.google.com/drive/1tIf0Ugdqg4qT7gcxia3tL7und64Rv1dP \n
       https://github.com/jiwonny/nlp_emotion_classification
  
  
   ### 2) 머신러닝 모델 VOTING 기반 CLASSIFICATION
      FRIENDS_ML_TFIDF_VOTE.ipynb
      
   * 본인 구글드라이브에 EmotionLines_friends_annotation.tar.gz 저장
   * 평가 파일 본인 구글드라이브 저장(en_data.csv) 
