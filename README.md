
- 심심할 때마다 코드에 설명 넣음


## 노래추천
- 1001 Cosmic - Redvelvet
- 1002 괴물이 피는 숲 (+1Key) - Dovivi
- 1004 Hunch Gray - zutomayo
- 1005 군청 - Yoasobi(ikura, Ayase)
- 1006 Love Wins All - IU
- 1007 메아리 - QWER




## 4 type of data definiton 및 성질에 의거한 AOP-1Prod[IN]-2Listener[IN, Extern] MSA 구조 (1주차, 1차)
![aad drawio](https://github.com/user-attachments/assets/4111cf42-ff41-4fb3-b844-ef141f9db5b6)


#### Listener를 In(same port) Ex(Integate Port)로 나누어서, 통신 특성 및 데이터 정의에 따라 나눠서 최적화 및 데이터 관리 및 공급 API 용이성 강화
#### INNER Listener에 2 Type으로 나눠서, IN - IN (data props), EX-IN(event-API-stimulation by pub-sub)으로 관리

![data 4 tpye11 drawio](https://github.com/user-attachments/assets/b3c04d51-05f5-437d-9904-8e0d7bbf68e4)


## Event-Transactional-block
    Str[PK] = 0000 0000 0000 0000 , Type FROM(N-layer) To(T-N layer) etc
    PK[0,4,8,12] => key Props
    
    Body : transactional data? , event data container?


## 4 data type -> 이 지역 특성에 따른 Data를 Extern, Internal 에서 나눠서 관리
    1. explict(IN)
    2. implict(EX)
    3. interval(IN,EX 지역성에 따른)
    4. clusterProps(EX)








## 설명 preview

#### 1. https://github.com/DotBlossom/flask-api-actual

![스크린샷 2024-10-05 150956](https://github.com/user-attachments/assets/b4ea7299-327a-41d1-83b7-39370220275f)

<br/> 
<hr/>
<br/>

#### 2. https://github.com/DotBlossom/SNSProjectKafkaMixIn

![fsfsf](https://github.com/user-attachments/assets/824eb59a-970d-4692-a90c-8e920605a690)


