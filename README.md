# Data_ton_ssu
데이터톤_경진대회_구현 소스코드




## Step_1
#### 연출입건수 대비 연대출권수 구하기 
###### target 대상에 대한 문제점 해결하기 (개인정보공개 불가 문제)
###### outer join을 적용하고 중복을 제거하는 과정에서 랜덤성이 적용이 되어서 해결이 필요
![image](https://user-images.githubusercontent.com/68888169/180140894-20a9c951-70c0-47a5-9773-ec485e683c6c.png)

###### 피어슨 상관계수
![image](https://user-images.githubusercontent.com/68888169/180142043-bb00c3b2-2695-45fd-8341-35cb35627de5.png)



## Step_2
#### 연출입건수 대비 연대출권수 구하기 
#### 위에서 발생한 딜레마 해결 -> 학생에 집중하여서 생김(학과,학번으로 구분)
![image](https://user-images.githubusercontent.com/68888169/180141824-87331ddd-15c5-4c84-8174-55e71efc658a.png)

##### 피어슨 상관계수
![image](https://user-images.githubusercontent.com/68888169/180141900-0f21df67-2dfc-4cec-80cc-8928d239f294.png)


## Step_3
#### 추천서비스 구현을 위한 단행본대출 데이터 분석(EDA)
![image](https://user-images.githubusercontent.com/68888169/180142731-c3296872-392d-4251-bf89-5fe5236d4f48.png)
![image](https://user-images.githubusercontent.com/68888169/180142606-e416339e-4907-4d77-9fe8-7e22aa3a22ff.png)
![image](https://user-images.githubusercontent.com/68888169/180142626-c42f3d49-b769-4642-ace7-a7199f9d4300.png)



## 저작권 이슈 및 배포 문제
모든 데이터의 저작권은 숭실대학교 중앙도서관에 있음을 명시합니다

공개가 불가능하여 데이터의 미리보기만 제공합니다




# 사용 데이터 구성 
#### 데이터_단행본대출.csv
![image](https://user-images.githubusercontent.com/68888169/180140006-c9c9c7f2-bd37-43b9-a6d2-d71da5a978ea.png)

#### 데이터_도서관출입.csv
![image](https://user-images.githubusercontent.com/68888169/180140133-eaaec644-370a-448b-ac14-b77b61acbf0f.png)

#### 데이터_단행본도서.csv
![image](https://user-images.githubusercontent.com/68888169/180140443-4918f598-a0f1-45eb-8893-f16b3085c652.png)
