# semiconductor-lot-test-sample
analyze post thickness which is measered after some test

1. 데이터
- data : 25 lot ( etch 테스트 2개, CVD 테스트 3개, CMP 테스트 2개 적용 이력 존재 )
- column name : S Lot	/ Post Thickness(A) /	dressing step sec /	Etch Si RIE /	Chamber	/ Etch test 적용 이력	/ CVD test 적용 이력



2. 공정능력지수
 - dressing step 시간 단축 테스트 적용된 CMP 공정의 post thickness 데이터
 - CMP 공정능력

    Mean=5154.48, Std=180.84

    Cp=0.737, Cpk=0.453
   
<img width="869" height="564" alt="image" src="https://github.com/user-attachments/assets/77c26129-736b-42d2-90b2-b3b68ccaca36" />




 - Etch Si RIE post thickness 데이터
 - Etch 공정능력
 
    Mean=4798.16, Std=85.73

    Cp=1.555, Cpk=0.771

<img width="861" height="563" alt="image" src="https://github.com/user-attachments/assets/42b00787-c313-45c1-8928-291e2227c6cd" />







3. I-MR 관리도
   *슈하트 규칙 적용
   
(1) dressing step 2초 하향 적용
  <img width="1169" height="564" alt="image" src="https://github.com/user-attachments/assets/fa41cfa5-108c-421a-82fb-8ad8e0541db7" />


  <img width="1160" height="564" alt="image" src="https://github.com/user-attachments/assets/19b1aa6a-241b-4b79-8170-81eb99499d53" />


 - #3 (Value=5455): Rule 1: Beyond control limit
 - #9 (Value=5411): Rule 1: Beyond control limit

   
(2) dressing step 4초 하향 적용
  <img width="1169" height="564" alt="image" src="https://github.com/user-attachments/assets/d98f80f0-054f-4c6f-9d24-c1447b40ca0d" />


  <img width="1160" height="564" alt="image" src="https://github.com/user-attachments/assets/b353bad0-561d-4f26-a17b-44bbd2262fbd" />


 - #21 (Value=5477): Rule 1: Beyond control limit



4. Etch  테스트 적용 이력

- 각 테스트 별 구간 그림
  
<img width="857" height="544" alt="image" src="https://github.com/user-attachments/assets/98caff69-419a-4a99-a735-be98626daa1b" />


<img width="702" height="545" alt="image" src="https://github.com/user-attachments/assets/a13e41a2-7533-4c89-9cd5-954e5ce69723" />


#그룹별 통계치  
- test1
  - mean  = 4685.4
  - std   = 26.101724
  - count = 5

- test2           
  - mean  = 4929.4
  - std   = 19.705329
  - count = 5

#t-test 결과:

t=-16.683, p=0.0000

결론: 두 테스트 그룹간의 유의미한 차이가 존재





