# 🪑Room & Boolm (1인용 가구 쇼핑몰)

<img width="484" alt="room bloom" src="https://github.com/AN-YEJU/team4_project/assets/126753514/26479f9c-55da-41b0-a288-a98bccdc5038">


### 증가하는 1인 가구들을 위한 가구 셀렉트샵

제품 등록, 장바구니 추가, 주문하기 등 쇼핑몰의 핵심 서비스를 구현

<br/><br/>

## ⏰ 개발 일정(간트 차트)
<img width="527" alt="team" src="https://github.com/AN-YEJU/team4_project/assets/126753514/42e5eb00-d1fb-42bb-a376-b5fcab818704">


## ✅ 서비스 주요 기능

### 💡 회원가입
- 아이디 비밀번호 유효성 검사 수행
- 등록 이메일을 통해 사용자가 매우 많은 id를 소유할 수 없게함
- 카카오 api도입으로 간결한 회원가입
- <details><summary>시연 모습</summary><img width="730" alt="login" src="https://github.com/AN-YEJU/team4_project/assets/126753514/c8c59caa-c45c-41d3-96d7-44c913c228bb"></details>


### 💡 로그인
- 소셜로그인 가능
- 아이디 / 비밀번호 찾기 및 수정
- <details><summary>시연 모습</summary><img width="728" alt="login2" src="https://github.com/AN-YEJU/team4_project/assets/126753514/c6acbe96-5c37-4e5f-9f50-687a5ca2d874"><img width="728" alt="login3" src="https://github.com/AN-YEJU/team4_project/assets/126753514/decc6840-29e0-4df4-b7f2-b5fa7cddd24c"></details>


### 💡 홈
- 좌측 카테고리 탭을 통해 카테고리별 제품 열람 가능
- 제품 클릭시 상세정보 열람
- <details><summary>시연 모습</summary><img width="704" alt="bed" src="https://github.com/AN-YEJU/team4_project/assets/126753514/e7b7af0b-aad0-49fb-b014-d9abc8fb84c9"><img width="731" alt="bed2" src="https://github.com/AN-YEJU/team4_project/assets/126753514/d58b73a7-1139-40fc-8cd2-cecb7bc0bd7c"></details>


### 💡 상세페이지 / 장바구니 / 결제
- 상품 상세정보 열람
- 장바구니에 담기
- 장바구니 리스트 중 선택적으로 구매 가능
- <details><summary>시연 영상</summary><img width="514" alt="상세" src="https://github.com/AN-YEJU/team4_project/assets/126753514/419ceed5-7670-4251-8a67-85064931cf8a"><img width="488" alt="장바구니" src="https://github.com/AN-YEJU/team4_project/assets/126753514/85b2c5f8-d88b-4dcd-82af-a2d6767b08c1"><img width="509" alt="결제" src="https://github.com/AN-YEJU/team4_project/assets/126753514/c8300d0b-f61f-4d86-b5c1-062aca09ed4e">
</details>

### 💡 구매평
- 상세페이지에서 구매평 작성·수정·삭제
- 해당 상품 구매자만 가능하도록 처리

### 💡 일반 회원 - 정보 관리
- 관리자와 일반사용자를 구분하여 페이지 변환
- 회원의 구매금액에 따른 등급 확인
- 보유 쿠폰 열람 및 사용
- 주문목록 열람 및 수정
- 회원정보변경 및 탈퇴
- <details><summary>시연 영상</summary><img width="620" alt="회원정보" src="https://github.com/AN-YEJU/team4_project/assets/126753514/f5928b5f-960a-4334-a17d-da9c88db591e"></details>


### 💡 관리자 - 주문 관리
- 주문 취소 가능
  - 주문이 완전히 삭제되지 않고 '관리자에 의한 취소'로 상태 변경 (데이터 보존)
- 배송상태(배송준비중, 배송중, 배송완료) 변경 가능
  -  배송완료로 변경 후에는 수정 불가
- <details><summary>시연 영상</summary><img width="943" alt="주문현황" src="https://github.com/AN-YEJU/team4_project/assets/126753514/c0c7ff81-814e-403e-8d9a-1fb986ddec88"></details>


### 💡 관리자 - 상품 관리
- 상품을 추가 및 수정
- multer를 통해 이미지 업로드
- 상품 삭제시, 구매자가 있는 경우에는 상품이 사라지지 않고 '판매중지' 처리됨
- 카테고리가 삭제된 상품은 '미설정' 카테고리에서 확인 가능(데이터 보존)
- <details><summary>시연 영상</summary><img width="1060" alt="상품관리" src="https://github.com/AN-YEJU/team4_project/assets/126753514/d7387d37-541e-43a9-8e22-1b49dc96e13f"><img width="1093" alt="상품등록" src="https://github.com/AN-YEJU/team4_project/assets/126753514/89674ade-9c47-4738-a873-885349dfdd9b"></details>

<br/><br/>

## ✅ 기술스택
<img width="656" alt="기술" src="https://github.com/AN-YEJU/team4_project/assets/126753514/a45d0428-d613-4e7d-877e-40eb0cbdbecb">

### 프론트엔드
<img width="174" alt="front" src="https://github.com/AN-YEJU/team4_project/assets/126753514/42741c4f-1d28-41c5-a91b-c9e70a718e4e">

### 백엔드
<img width="568" alt="back" src="https://github.com/AN-YEJU/team4_project/assets/126753514/744ccdfe-039d-4757-abc5-4ac02d74660c">

### 형상관리
<img width="137" alt="git" src="https://github.com/AN-YEJU/team4_project/assets/126753514/175781e2-4e4a-4015-a614-72c9c3969041">

<br/>
<br/>

## ✅ 기획

### 1. 정보구조도(다이어그램)
<img width="645" alt="145843" src="https://github.com/AN-YEJU/team4_project/assets/126753514/dee77770-4c6a-4104-9097-0c82463cecf1">

### 2. ERD
<img width="649" alt="erd" src="https://github.com/AN-YEJU/team4_project/assets/126753514/504a900f-8583-471e-8c17-f4d5738c1599">

### 3. [와이어 프레임](https://www.figma.com/file/7mTVSIZPz6HJyIOl6LjDYd/TP_4%EC%A1%B0-%EC%87%BC%ED%95%91%EB%AA%B0?type=design&node-id=0-1&mode=design&t=p50DF7K2ime0xLu0-0)


<br/>

<br/>

## ✅ 제작자

| 이름   | 담당 업무 |
| ------ | --------- |
| 박동명 | 팀장/BE   |
| 구나현 | BE        |
| 안예주 | BE        |
| 김효진 | BE        |
| 박정훈 | FE        |
| 조은유 | FE        |

<br />
