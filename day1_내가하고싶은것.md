# 내가 지금 개발중인 서버에서 하고싶은 것. 사실 해야하는 것
- 개발서버와 운영서버에서 값이 다른 파라미터가 있다. 그거 처리하기
- 개발서버에서 데이터베이스를 수정하고 아무생각없이 운영서버로 올릴때가 있다.....휴우.

  flyway 사용해서 db migration하기
- swagger를 api doc으로 사용하고 있는데 뭔가 부족하다.
  
  직접 실행해볼 수 있다는 장점은 있지만 api설명이 부족하다.
  
  api를 사용하는 사람이 한명이었어서 물어보면 구두로 대답해줬었는데 개발자가 늘어나도 일일이 구두로 답해주면... 내 일은 언제해
  
  그리고 어제의 내가 개발한 api 설명이 없으니까 모르겠다..ㅎㅎ
  
  swagger보완 / 다른 api doc 라이브러리 찾기
- 데이터를 보고싶으면 데이터베이스에서 쿼리문을 실행해서 봐야한다.
  
  데이터를 보고싶은 사람은 쿼리문을 다룰 수 있어야하는데 이게 불가능하고 만약 가능하다고 해도 잘못해서 데이터를 수정하거나 구조를 바꾸면...이건 큰일
  
  이게 답답해서 어드민페이지를 만들고싶은데 아직 시간이 없어서 못했다.
  
  vaadin으로 해볼까 고려중
- 이건 진짜 너무 문제 **테스트코드 없음**
  
  말도 안되는데 진짜... 각잡고 하고싶은 마음이 있고 허술하게 만들었다가 사실 성공인테 실패로 떠서 빌드가 안된다면.. 골치..(변명)
  
  테스트코드 작성해야함
- https 적용
  
  아니..모르겠어요.. 전에 한번 실패한 경험이 있어서 쫄아있는데 도와줄 사람은 없고 서버는 죽으면 안되고... 무서워염..(변명)
- 가짜 자동로그인..ㅎㅎ
  
  앱에서 자동로그인을 하고 있다. 디바이스에 아이디와 비밀번호를 저장하고 앱 실행시 로그인을 한다.
  
  현재 spring security를 사용하고, token으로 값을 받고 있어서 refresh token를 만들고 조금 뭔가 하면 될것같은데 이거도 시간이 없어서 못하는중..(변명)
- Spring Boot Data Jpa를 사용해서 개발하고 있다. JpaRepository를 사용하면 개꿀인데 커스터마이징이 힘들다. 메서드네임이 막...
  
  <img width="886" alt="image" src="https://user-images.githubusercontent.com/60127173/157212215-45499437-cc99-48a9-a89e-2269b9800af2.png">
  
  이래

# 그니까
다 변명을 하고 있어서 변명 하는김에 더 해보자면 개발을 위해 주어지는 시간이 너무 적다.

운영서버는 돌고 있기 때문에 운영을 하다가 문제상황이 생기거나 수정할 것이 있으면 바로 연락이 오고 보통 큰 일이 아니기때문에 바로 수정해서 배포한다. 

그리고 내가 아직 못한 것들.. 어떤 이유로 당장 기능 개발이 급하다보니 후순위로 밀리게 된다. (근데 저거 있으면 진짜 시간절약 될텐데...)

결정적으로 다 내가 안해본것들이어서 어느정도의 시간이 필요한지 가늠이 안간다. 시간이 여유로울때 하고싶은데 
그건 내 욕심..ㅎㅎ 입사후 여유로웠던 적.. 초반 일주일빼고 없다.

그래서 못하고 있는건데

여기에 적었으니까 빠른 시일내에 가능한거부터 하나씩 처리해야지
