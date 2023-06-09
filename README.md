## 📌 서비스 소개

- 제주도 오름찾기 서비스 오름 올래?

<br>

## 🤵‍♂️ 팀원 소개

|이름|MBTI|역할|한 마디|
|---|---|---|---|
|김성진|ISFJ|디자인 피그마 작업, BootStrap 디자인 피그마에 맞게 수정|짧은 시간이지만, 좋은 추억이 되도록 열심히 해볼게요~|
|오흥식|INFP|BE(장고 환경 구축 + 디스커스 적용), 기능별 담당업무|짧고 굵고 재미있게~ 화이팅 해요!!|
|허진영|ISFJ|BE(오름관련 데이터 수집), Database ERD 작업|시간이 많지 않아 아쉬운 부분도 있지만 보람 있는 프로젝트 만들어보겠습니다.|
|이진혁|ESFJ|BE(Session, update, delete) 작업|아직은 낯설기만한 장고이지만 열심히 만들어보겠습니다!|

<br>

## 🔥 Ground Rule

- 회의 장소 : 디스코드
- 평일 정규회의시간 : 오후 9시
- 모르거나 막히는 부분이 있으면 언제든지 공유
- 문의사항이 있을경우 디스코드 채널에 남기기
- 평일 정규회의시간 : 오후 9시

<br>

## 📅 개발 일정

8월 28일 ~ 9월 2일 (5일)

<br>

## ⭐️ 기능 소개

1. 첫 페이지에는 닉네임을 입력받을 수 있는 창이 보여진다. (로그인 대체)

2. 메인화면에는 제주 지도를 보여준다.

3. 제주에서 각 지역마다 어떤 오름이 있는지 파악할 수 있다.

4. 오름의 상세 화면페이지에서는 오름의 여러 이미지들과 자세한 내용을 확인 하는 기능

5. 상세페이지에선 메인 이미지 뿐만아니라 서브이미지도 볼 수 있는 캐러셀 기능

6. 닉네임별로 내가 등록한 오름을 수정 & 삭제 할 수 있는 기능 (내가 등록한 오름이 아니라면 상세페이지에는 수정, 삭제 버튼이 보여지지 않는다.)

7. 간단하게 오름별로 방명록을 남길 수 있도록 디스커스 서비스 적용

<br>

**오름 올래?**

![Oreum.icu](https://user-images.githubusercontent.com/112479335/243328515-d4859c8d-c2e3-4431-bf66-7705ac2421f2.gif)



**오름 등록**

![Oreum_save](https://user-images.githubusercontent.com/112479335/243333874-828ff0ae-64c4-4b46-9268-7bf4b26eae60.gif)



**관리자**

![Oreum_Admin](https://user-images.githubusercontent.com/112479335/243327949-79cd04ab-588f-4a3b-95fd-90e987cccf72.gif)



<br>

## 🎨 UI

https://www.figma.com/file/HZkAK8Q7rPcwfE8vVBPW2O/jeju-hackathon?node-id=0%3A1

![Figma](https://user-images.githubusercontent.com/112479335/243325101-240e0cd3-f24c-41a9-b8d9-2b17176d52a1.png)

<br>

## 💽 ERD

https://cdn.discordapp.com/attachments/1012601385889562638/1015257386556084346/unknown.png

![ERD](https://user-images.githubusercontent.com/112479335/243324061-c87e7065-b314-47e3-bb4e-5084c2e69de7.png)

<br>

## 🔧 개발 환경 및 배포 URL

http://www.oreum.icu

<br>

## 🛠 Tools

django, html, css, javascript, AWS lightsail

<br>

## 🌈 Branch 전략

```
└── main
    └── deploy
    └── dev
         ├── BE
         │    ├── BE-IssueName
         │    └── BE-IssueName
         ├── FE
         │    ├── FE-IssueName
         │    └── FE-IssueName
```

- `deploy`: 목표한 기능이 완성되면, merge해서 배포
- dev 브랜치로 PR을 보낼 때는 정상적으로 빌드가 되는지, 꼭 확인하고 PR을 보냅니다.
- dev 브랜치로의 PR의 경우, 스스로 merge하는 것이 아니라 PR을 공유하고 다른 팀원에게 merge를 부탁합니다. 

<br>

## 📝 git commit Convention

| 타입       | 설명                                         |
| ---------- | -------------------------------------------- |
| `feat`     | 새로운 기능 추가                             |
| `fix`      | 버그 수정                                    |
| `docs`     | 문서 작업, 수정                              |
| `refactor` | 코드 리팩토링                                |
| `style`    | 코드 컨벤션 수정(함수/ 변수명 변경 포함)     |
| `chore`    | 소스 코드를 건들지 않는 작업(빌드 업무 수정) |

<br>

## 🗂 Issue & PR
- Issue 로 기능 관리 + Pull Request로 소스 관리
