# Dev_Forum
> 개발자 정보 공유 서비스

![posts](https://user-images.githubusercontent.com/114655005/230790161-f0f19c2f-28b4-491b-b208-9feae125616d.png)

![profile](https://user-images.githubusercontent.com/114655005/230790274-1e01510b-bffc-4262-b5af-34a6b6c4d2c5.png)

![profileupdate](https://user-images.githubusercontent.com/114655005/230790168-49bd1d57-b4d1-4d84-b713-8535e063083d.png)

## 1. 필수 기능
### 네비게이션 바
* 로그인 사용자 버튼
  * 회원 정보 수정
  * 로그아웃
  * 회원탈퇴
* 비로그인 사용자 버튼
  * 회원가입
  * 로그인

### 게시글 CRUD
* 게시글 CRUD 구현
* 비로그인 사용자에 대해 상세조회/ 생성/ 수정 권한 제한

### 카테고리 사이드 바
* 특정 카테고리 버튼을 클릭하면 해당 카테고리 게시글 전체 조회

## 2. 도전 기능
### category 필드 커스텀 폼
* `PostForm`을 커스텀 하여 category필드를 select로 수정
### User 모델 확장
* birthday 필드 추가하기
### 회원가입 라벨 변경
* 회원가입 폼 `CustomUserCreationForm` 을 수정하여 회원가입 라벨 수정

## 3. 그 외 추가 기능
### 최근 한 시간이내에 게시물에 대해 new 태그 붙이기
* javascript로 new 강조하기
### 최신순/오랜순 정렬

### 내 프로필 페이지 생성

### 제한된 사용자로 접근시 로그인 후 원하던 페이지로 redirect
* query string의 'next'키값을 받아서 redirect

### 공지 사항 게시물 분리
* 공지 체크된 게시물 최상단 노출
### 회원정보 수정 폼 커스텀

### bootstrap의 input-group으로 폼 커스텀

---

# coworker
> 박현준, 김소은, 정광배