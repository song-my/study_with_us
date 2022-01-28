# Study With Us
랜덤 스터디 멤버 구하기 서비스


## 👨‍👨‍👧‍👦 Contibute (git id)
* [SongMinyoung](https://github.com/song-my)
* [RyuMyunggi](https://github.com/RyuMyunggi)

## 📁 Directory Tree

```
.
├── README.md
├── manage.py
└── study_with_us
    ├── __init__.py
    ├── settings.py
    ├── urls.py
    └── wsgi.py

```

## 💭 Branch 규칙
* master
* 기능 개발 시 master branch에서 branch 따서 작성 (ex. feature/login)

## 🗳 issue

## 👀 commit 규칙
* type : 어떤 의도로 커밋했는지를 type에 명시합니다.
  ```text
  Feat: 새로운 기능을 추가할 경우 
  Fix: 버그를 고친 경우 
  Design: CSS 등 사용자 UI 디자인 변경 
  !BREAKING CHANGE: 커다란 API 변경의 경우 
  !HOTFIX: 급하게 치명적인 버그를 고쳐야하는 경우 
  Style: 코드 포맷 변경, 세미 콜론 누락, 코드 수정이 없는 경우 
  Refactor: 프로덕션 코드 리팩토링 
  Comment: 필요한 주석 추가 및 변경 
  Docs: 문서를 수정한 경우 
  Test: 테스트 추가, 테스트 리팩토링(프로덕션 코드 변경 X) 
  Chore: 빌드 태스트 업데이트, 패키지 매니저를 설정하는 경우(프로덕션 코드 변경 X) 
  Rename: 파일 혹은 폴더명을 수정하거나 옮기는 작업만인 경우 Remove 파일을 삭제하는 작업만 수행한 경우
  ```
* subject : 최대 50글자가 넘지 않도록 하고 마침표는 찍지 않습니다. 영문으로 표기하는 경우 동사(원형)를 가장 앞에 두고 첫 글자는 대문자로 표기합니다. 
* body : 긴 설명이 필요한 경우에 작성합니다. 어떻게 했는지가 아니라, 무엇을 왜 했는지를 작성합니다. 최대 75자를 넘기지 않도록 합니다. 
* footer : issue tracker ID를 명시하고 싶은 경우에 작성합니다.
* ex)
    ```text
    Feat: "추가 로그인 함수"
    
    로그인 API 개발
    
    Resolves: #123
    Ref: #456
    Related to: #48, #45
    ```
* 커밋 컨벤션
[commit convention](https://overcome-the-limits.tistory.com/entry/%ED%98%91%EC%97%85-%ED%98%91%EC%97%85%EC%9D%84-%EC%9C%84%ED%95%9C-%EA%B8%B0%EB%B3%B8%EC%A0%81%EC%9D%B8-git-%EC%BB%A4%EB%B0%8B%EC%BB%A8%EB%B2%A4%EC%85%98-%EC%84%A4%EC%A0%95%ED%95%98%EA%B8%B0)

## 😀 pr / merge 규칙
### 📍 pr message 양식
<img width="560" alt="pr message example" src="https://user-images.githubusercontent.com/76977926/151426101-50919890-436e-4dee-b8e1-bbd6a55a1015.png">

* PR 소개
* 변경점
* 변경 부분 스크린샷
* 테스트 체크리스트

### 📍 merge
* 팀원과 pr에 대해 리뷰를 나눈 후 origin master branch merge 진행

## 🌟 review 
* 자신의 의견을 망설이지 않고 표출하는 것이 중요!
* 개선점 및 칭찬, 이모티콘 등 자유롭게 의견을 표현