# Springboot-JPA-Blog-2

### 1. 회원가입 페이지
#### 1-1) id : github1234, password : 1234, email : github1234@naver.com
![image](https://user-images.githubusercontent.com/81174840/182274174-33b26dd3-0127-46ef-a2c0-b8e072a52efd.png)


#### 1-2) 회원가입 전 User Table의 데이터
![image](https://user-images.githubusercontent.com/81174840/182274504-eee3c348-7854-4421-8c1d-ec6f09b082ac.png)

#### ::: 회원가입을 하는 경우 같은 id를 가진 컬럼이 user Table에 존재하면 HttpStatus.INTERNAL_SERVER_ERROR.value() = 500 인 에러를 인지하여 회원가입을 하지 못했다는 알림을 보여주고 같은 id를 가진 컬럼이 user Table에 존재하지 않는 경우에는 HttpStatus.OK.value() = 200 을 보여주고 회원가입이 이루어진다.

### 2. 로그인 페이지
#### 2-1) id : github1234, password : 1234 을 입력한다(올바르게 입력한 경우에만 로그인이 가능하다)
![image](https://user-images.githubusercontent.com/81174840/182274851-1744ef40-eea5-470e-897c-c3d85de8d0d5.png)

#### 2-2) 회원가입을 완료한 User Table DB 
##### id, password(해쉬키), email 정보가 들어간 것을 볼 수 있다.
![image](https://user-images.githubusercontent.com/81174840/182275015-0f574a64-01a6-42c0-8cdd-01734c692934.png)

### 3. 로그인 후 헤더가 바뀐 상황
![image](https://user-images.githubusercontent.com/81174840/182275151-2307b577-7bc5-43e7-8659-957d86321f9e.png)



