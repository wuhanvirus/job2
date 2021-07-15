# article_section_classifier-BERT-   
   
   

### 작동 방식


셀레늄_섹션별기사제목크롤링.ipynb 을 사용하여 섹션별로 classification된 네이버 기사 데이터를 형성합니다.
**(당일 돌리면 약 1주전까지 기사가 크롤링 되며 2만5천건 정도 형성됩니다.)

형성된 데이터를 BERT_article_classification에서 읽을 수 있도록 BERT_article_classification의 첫째줄을 형성시킨 데이터가 있는 파일명으로 바꾸고 코드를 실행합니다

test : valid : test = 6 : 2 : 2의 비율을 형성함 


### 실행 결과


![데이터 3만개 2e 에퐄3 테스트 추가](https://user-images.githubusercontent.com/62196278/125653735-5d229cbd-8d65-4a77-93f3-20dfcccf512c.jpg)
   
   
#### 참고한 사이트: https://medium.com/@eyfydsyd97/bert%EB%A5%BC-%ED%99%9C%EC%9A%A9%ED%95%9C-classification-by-pytorch-2a6d4adaf162
