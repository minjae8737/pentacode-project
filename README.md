# 운동 커뮤니티 플랫폼 Localfit

<br>

## 프로젝트 소개
- '서울시 예약 가능 공공체육시설 데이터' 를 기반으로 운동 모임이 가능한 운동 커뮤니티 플랫폼

<br>

## 개발 기간
25.02.03 ~ 25.02.28

<br>

## 🛠️ 기술 스택
- **Backend**: Java, Spring Boot, Spring Security, Spring Data, Spring Batch, Kafka, Elasticsearch, OAuth2.0, JWT, Websocket
- **Frontend**: React, CSS, JavaScript, MUI, Zustand
- **Database**: MySQL, Redis, MongoDB
- **Tools**: IntelliJ IDEA, AWS S3
- **버전 및 이슈관리** : GitLab
- **협업 툴** : Discord, Notion

<br>

## 주요 기능
- 시설
    - 시설
        - 공공 api데이터를 요청후 DB에 저장
        - 운동 종목별, 지역별 목록 표시
- 모임
    - 모임
        - 모임 대표 썸네일 표시
    - 모임 조건
        - 선착순, 신청제 
        - 모임 요일, 시간대 선택
        - 해시태그
    - 모임 관리
        - 가입 신청 수락, 거절
- 유저
    - 시큐리티 적용
    - OAuth 로그인
    - 이메일 로그인
    - 회원가입
    - 마이페이지
    - 어드민페이지
- 채팅
  - 채팅목록
    - 가입된 채팅방 목록 표시
    - 안읽은 메세지수 표시
  - 채팅방
    - 실시간 접속자 표시
    - 방장이 다른회원 강퇴 기능
    - 새로운 회원 입장,퇴장시 시스템 메세지 출력
- 운동맵
  - 카카오맵API 를 이용한 서울시 체육시설 표시
  - 마커를 클릭하면 해당 체육시설 정보제공
- 라운지
    - 피드 목록
      - 인기순, 최신순 정렬
      - 무한 스크롤
    - 피드 생성
      - React Quill 을 사용하여 스타일 적용
      - React DnD 를 사용하여 사진 순서 변경
    - 피드 
      - data-fns 를 사용하여 생성 날짜 표기
      - 좋아요(추천) 기능
      - 댓글, 대댓글
      - 프로필사진 클릭 시 개인 프로필 이동
      - 팔로우 기능
      - 해시태그
- 검색
  - 엘라스틱서치를 사용한 해시태그, 시설 검색 자동완성 기능
<br>

## ERD
<img width="1634" alt="Image" src="https://github.com/user-attachments/assets/3403a91c-3f36-4fe4-9771-98886f83debc" />

<br>

## WireFrame
<img width="1353" alt="Image" src="https://github.com/user-attachments/assets/46758fd5-8fe2-4641-b719-18109dd6f704" />

<br>

## 동작 화면
### 메인 페이지
<img width="1898" alt="Image" src="https://github.com/user-attachments/assets/2f76f328-ce6e-448e-b6af-5a536fa0af85" />
<img width="1905" alt="Image" src="https://github.com/user-attachments/assets/7d206d71-c293-4a03-b6a4-ddc4b2c3d3ba" />

### 로그인
<img width="491" alt="Image" src="https://github.com/user-attachments/assets/ac69c35a-fb52-4c80-95d1-b4afa8f3ad6f" />


### 마이페이지
<img width="1210" alt="Image" src="https://github.com/user-attachments/assets/b8f3bfa4-448c-4fc8-8755-76a1b1da63f8" />

### 시설
<img width="1391" alt="Image" src="https://github.com/user-attachments/assets/7becd6dc-1830-4c07-aae8-fb78b3f8c119" />
<img width="1240" alt="Image" src="https://github.com/user-attachments/assets/f56f0813-1fb6-4345-8c8f-b2bd0aaf06e7" />

### 시설 상세 화면
<img width="1192" alt="Image" src="https://github.com/user-attachments/assets/dd8be337-dca9-400a-b783-caaf7433151f" />

### 내가 개설한 모임 목록
<img width="1163" alt="Image" src="https://github.com/user-attachments/assets/44488df8-d573-480f-8794-96f1ee04fdab" />

### 모임 상세페이지
<img width="930" alt="Image" src="https://github.com/user-attachments/assets/d2686a99-6ba1-402a-a688-e4468824a078" />

### 라운지
<img width="1270" alt="Image" src="https://github.com/user-attachments/assets/11c37e9c-0486-4a1e-af37-9b3db21cc27a" />

### 피드 상세
<img width="596" alt="Image" src="https://github.com/user-attachments/assets/60fede59-7094-49b1-a976-d6d364159377" />

### 채팅방
<img width="1294" alt="Image" src="https://github.com/user-attachments/assets/e87fbd2d-f9b9-462d-bcf8-4364830b06ef" />
<img width="1207" alt="Image" src="https://github.com/user-attachments/assets/982fcdd8-2b5d-4249-ac91-66533272f8da" />

### 운동맵
<img width="1629" alt="Image" src="https://github.com/user-attachments/assets/67e6c50a-c892-40cd-9e2b-69f0bce85b55" />


<br>

## 프로젝트 후기

마지막 한 달 프로젝트를 하였다.

이번 프로젝트도 주제를 정할때 꽤 시간이 걸려 첫 주 마지막날이 되고서야 프로젝트 세팅을 들어가게 되었다.
공공 데이터를 이용한 주제로 프로젝트를 하려다 보니 데이터를 선정하는대 고민이 많이 되었다.

이번 프로젝트에 적용된 다른 많은 기술들이 있지만 
나는 리액트를 처음 배워서 적용하면서 리액트에 적응하느라 시간을 많이 사용한것 같다.

이번 시설과 모임을 개발하면서 기본 기능 이후 좀 더 기능을 개발하고 싶었는대 
첫 주에 주제선정과 마지막주에는 프로젝트 세팅 후 배포 작업이 제대로 되지않아서
그 쪽에 시간을 거의 다 할애하게 되어 조금 아쉬웠다.

다 같이 배우고 싶은 기술을 적용하여 여러기술이 적용 되다 보니 세팅하기 힘들었고 결국 배포를 하지는 못했지만 
각자 공부를 하기위한 프로젝트 였으니 모두 새로운 경험을 할 수 있었던 좋은 시간이었다.





