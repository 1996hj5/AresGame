# ARES 게임 플랫폼 (gradle)

이 프로젝트는 2019년 11월 11일 부터 만들었졌으며,  2019년 12월 25일에 완료하였습니다.

저희 프로젝트는 대표적으로 2가지로 구성됩니다.
> 사용자 페이지 &nbsp;&nbsp; Make. 김가람

> 매니저 페이지 &nbsp;&nbsp; Make. 최현종

너무 많은 기능을 제외하고, 기본적인 기능들로만 구성되었습니다.

실제로 게임을 파일로 구성하지 못하였어서 게임을 다운로드 기능을 뺀 나머지 기능들은 존재합니다.

# 주의사항

1. 사용자페이지 Logic /  매니저페이지 Logic 이 서로다릅니다. (서로 다르게 만들었기 때문)
2. 서로 매칭이 안되어있을경우가 있습니다.
3. 각자의 페이지에서 기능들만 봐주셨으면 합니다.
4. 완성이 안된 기능들이 있습니다. 그부분을 제외하고 보셔주시면 감사하겠습니다.
5. 오픈소스로 제출하니, Js파일 및 css파일을 안만들고, 페이지의 일부러 노출한 것들도 있습니다.

> 사용자 페이지 기능들
1. ajax로 댓글등록, 수정, 페이징 이용
2. 게시판 제목검색
3. 회원가입시 비밀번호 암호화
4. SMTP 이메일인증으로 회원찾기
> 매니저 페이지 기능들
1. ChartJs를이용 매분마다 일별로판매현황 보기
2. 각페이지의 ajax 이용 (검색, 페이징 등)
3. 상품 등록때, 다중이미지 MultiPartFile을 이용 (각각의 변수의 맞춰 사용하였음)
----------------------------------------

> 부가기능
1. 채팅하기(로그인시, 채팅가능)
> 김가람 군의 vue로 만든 포트폴리오
1. > http://waiting/karamPortpolio      여기를 들어가게되면은 김가람군의 vuejs 기반의 포트폴리오가 나타납니다. ( front-end )



# Vue Js와 Express Js를 이용한 채팅서버 입니다.
##### Make. 최현종
대표적인 메뉴로는 이 3가지가 존재합니다.
> #### 친구목록

> #### 채팅목록

> #### 친구관리

메뉴들에 기능들은
> 친구목록
1. 채팅하기 ( ID 클릭시 )
2. 친구삭제 ( ID 클릭시 )
3. 친구검색 ( ID 검색 )

> 채팅목록
1. 채팅방입장 ( ROOM 클릭 )
2. 채팅방삭제 ( 클릭하면 icon이 나타납니다. )
3. 채팅방 알림 (실시간으로 상대가 방나갈시, 알림으로 나타내준다.)

> 친구관리
1. 친구수락 및 거절( 상대방이 친구추가시 나타납니다.)

--------
### 대표적인 기능에는 총 2가지입니다.

> 실시간 접속현황
>> 실시간으로 친구창에서 접속했는지 알려줍니다.

> 실시간 채팅
>> socket.io를 이용하여 실시간 채팅이 이루어집니다.

--------

#### 여러번의 디버깅을 시도해보고 하였지만 새로고침이 필요할 때가 있습니다.
ex) 방을 생성하였는데 방이 안나타날경우

