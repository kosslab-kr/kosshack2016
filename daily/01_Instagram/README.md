# OneTeam

## Goal

- 각자 기여할 수 있는 부분에 꾸준히 기여를 해보자.
- 서로 부족한 부분, 혹은 발전될 부분을 도와주자.
- **모두 빠짐없이** 프로젝트에 자신의 흔적을 남기자.
- 첫 번째 릴리즈 버전 배포
 - 릴리즈 버전을 기반으로  새로운 모듈 생성 및 NPM 업로드

## 사전지식

- Git / Github / Markdown
- Node.js / NPM
- JavaScript : [Airbnb/JavaScript](https://github.com/tipjs/javascript-style-guide)

## Repository

[JeffGuKang/npm-webpack-boilerplate](https://github.com/JeffGuKang/npm-webpack-boilerplate)

# Team
주로 맡을 역할을 조(Group) 단위로 나눴습니다. Git 초보분과 숙련자분들을 조마다 함께 배정하였습니다.
![team structure](./teamstructure.png)

### Task : 개발
- 신미르 ([@TylorShin](https://github.com/TylorShin)) : Group Leader
- 이태순 ([LeeTaeSoon](https://github.com/LeeTaeSoon))
- 박경원 ([cosmicboon](https://github.com/cosmicboon))

### Test : 테스트 코드 작성

- 오도근 ([ohdoking](https://github.com/ohdoking)) : Group Leader / 테스트 코드 작성
- 이현주 ([lacieliz](https://github.com/lacieliz)) / Git와 JavaScript 학습 및 복습
- 이동기 (unknow) / 테스트 코드 리뷰

### Example(A-Yo) : 예제 코드 작성

- 조승윤 ([@choseungyoon](https://github.com/choseungyoon)) : Group Leader
- 성대경 ([@sdk115](https://github.com/sdk115))
- 이성현 ([@nygosh](https://github.com/nygosh))


### Docs : 문서 작성 및 Daily Report 관리

- 김무훈([@MuhunKim](https://github.com/MuhunKim)) : Group Leader / `README.md` 작성 및 팀 보고서 교정
- 이기신 ([@kshinlee](https://github.com/kshinlee)) : Team Leader / Git 학습 및 작성된 문서 리뷰
- 최규호 ([@gyuho26](https://github.com/gyuho26)) / Git 학습 및 작성된 문서 리뷰
- 김강민 ([@kangmin93](https://github.com/kangmin93)) / Git 학습 및 작성된 문서 리뷰

## 일정 목표

1. 27일까지 [npm-webpack-boilerplate](https://github.com/JeffGuKang/npm-webpack-boilerplate) 릴리즈 첫 버전 배포
2. 30일까지 [릴리즈 버전을 기반](https://github.com/JeffGuKang/npm-webpack-boilerplate)으로 새로운 모듈 생성 및 NPM 업로드

## Project

> [npm-webpack-boilerplate](https://github.com/JeffGuKang/npm-webpack-boilerplate)를 기반으로 한 새 모듈의 개발 방향을 작성합니다.

## 온라인 커뮤니케이션

- Slack : [kosshackathon1.slack.com](https://kosshackathon1.slack.com)
- Github : 이슈 코멘트 / Pull-Request 코드 리뷰

## 2016년 9월 24일

* 해커톤 개회식 당일
* 자기소개 및 의견 발표 겸 토론
* 조 모집 브리핑 : 자유의사에 의한 팀 분할
* 팀별 목표 설정 / 역할 분배
* 모든 팀원 Slack에 등록 / Slack에 팀별 Channel 등록
* 조별마다 팀의 Github Repository를 포크 해서 관리 / 조별 Collaborator 등록

#### Task

- 신미르 : [@TylorShin](https://github.com/TylorShin) : Group Leader
 - [Pull-Request #8](https://github.com/JeffGuKang/npm-webpack-boilerplate/pull/8)
	- Webpack을 통해 Build 및 Dev server를 실행할 수 있도록 해당 Packages와 Scripts를 추가하였습니다.
	- `package.json` 을 업데이트하였습니다.
	- ESLINT 설정을 잡았습니다.

#### TEST

- 오도근
	- 조원에게 Git의 사용법을 알려주고 역할을 분배했습니다.
	- 역할
		- 오도근: 테스트툴 조사 후 해당 툴로 테스트 코드 작성
		- 이동기: 작성된 테스트 코드 리뷰
		- 이현주: Git과 JavaScript 학습 및 복습

#### Docs
*
* 김무훈([@MuhunKim](https://github.com/MuhunKim)) : Group Leader
 * [Pull-Request #6](https://github.com/JeffGuKang/npm-webpack-boilerplate/pull/6)  : `package.json`에서 `author` 키워드 대신 `contributors`로 변경 후 `author` 목록 추가
 ```js
 "contributors": {
	 "author": "Jeff Gu Kang",
	 "author": "Muhun Kim <muhun.kim@gmail.com> (http://blog.muhun.kim)"
 },
 ```
 * [Pull-Request #8](https://github.com/JeffGuKang/npm-webpack-boilerplate/pull/8#pullrequestreview-1436878) 코드리뷰 : Git을 시험삼아 쓰기 위해 Git 초보분들이 수정한 코드를 직접 원래대로 되돌리는것도 좋을거라는 의견을 남겼습니다.
   * 해당 의견을 바탕으로 [Issue #11](https://github.com/JeffGuKang/npm-webpack-boilerplate/issues/11) 생성
	 * 해결이 완료된걸 [코드리뷰로 확인함](https://github.com/JeffGuKang/npm-webpack-boilerplate/pull/12#pullrequestreview-1453734)

## 2016년 9월 25일
### Docs
* **Group Goal**
 * 모든 Docs 조원들에게 Collaborator 등록 확인받기
 * 일일 레포트 작성하기
   * Markdwon 사용법 배우기 : [튜토리얼](http://www.markdowntutorial.com/)
   * 개인별로 일일 레포트 작성 저장소인 [kosslab-kr/kosshack2016](https://github.com/kosslab-kr/kosshack2016) 포크하기
    * 일일 레포트를 작성을 위해 git bash로 `git clone`, `add`, `commit`, `push`, `pull` 해보기
    * [kosslab-kr/kosshack2016](https://github.com/kosslab-kr/kosshack2016)로 Pull-Request 보내기

* 김무훈([@MuhunKim](https://github.com/MuhunKim)) : Group Leader
 * 팀원들에게 Collaborator 권한 부여
 ![](./c-team-collaborator.png)
 * 조원들의 Git 사용법에 관한 질문을 받음
 * `README.md`에 쓸 목록들을 정리하기 위해 Task Group이 올려놓은 코드를 직접 빌드하고 실행해봄
- 최규호 ([@gyuho26](https://github.com/gyuho26))
	- Atom Editor 설치
	- Slack에 올라온 linter와 linter-eslint 설치
	- Slack에 올라온 Git 관련 블로그 일부 읽음
	- Github에서 Docs Group의 저장소인 [MuhunKim/npm-gulp-es2015-boilerplate](hthttps://github.com/MuhunKim/npm-gulp-es2015-boilerplate)가 갱신되는것을 확인받기 위해 watch 눌러놓음
	- 'OneTeam'의 사전지식에 적혀있는 [Airbnb/JavaScript](https://github.com/tipjs/javascript-style-guide)에 대한 부분 일부 읽음
	- Markdown 문법에 관한 간략한 조사

  - Git / Github 사용법 익히기
   - 조장님의 저장소에서 같이 작업하기 위해 협업 권한을 받음(이메일로 확인)
   - 일일 보고서를 작성하기 위해 [kosslab-kr/kosshack2016](https://github.com/kosslab-kr/kosshack2016) 저장소를 포크함
   - `git clone`, `add` , `commit`, `push`를 직접 해보고 Pull-Request를 전송함

- 김강민 ([@kangmin93](https://github.com/kangmin93))
  - 하루패드 설치
  - Markdown 문법 익히기
  - Git / Github 사용법 익히기
   - 조장님에게 협업 권한을 받음
   - 모르는 부분이 있어서 조장님의 도움을 받음
   - 일일 보고서를 작성하기 위해 [kosslab-kr/kosshack2016](https://github.com/kosslab-kr/kosshack2016) 저장소를 포크함
   - `git clone`, `add` , `commit`, `push`를 직접 해보고 Pull-Request를 전송함

### Test

- **Group Goal**
	- 해당 boilerpate에 테스트를 할 수 있는 환경 설정을 하고 예제 테스트 코드를 작성한다.

- 오도근
	- 테스트 도구 선정 (Karma & jasmine)
	- 선정 기준: 신뢰도 및 이용 점유율(출처: https://ashleynolan.co.uk/blog/frontend-tooling-survey-2015-results)
	- 테스트 도구 학습
	- 테스트 도구 boilerpate 참조(출처: https://github.com/zyml/es6-karma-jasmine-webpack-boilerplate)

### Example(A-Yo)

- **Group Goal**
	- GitHub 사용법 숙달
	- 다른 Open-Source Example 살펴보기
	- NPM, Webpack 사용하여 Example 수정

- 개인활동 사항
	- 이성현
		- GitHub Pull-Request 요청
		- Brach로 `add`, `commit`, `push` 등 소스 수정
		- 기본 `src`폴더 내의 코드들을 `console.log()` 대신 `return`으로 수정하여 Example 구성

  - 조승윤
    - 팀원들 Github 질문 받아주기
    - 다른 Open-Source Example 분석

	- 성대경
		- Github 기본 개념 학습
		- 자바스크립트 기본 개념 학습

### Task

- **Group Goal**
	- Webpack 이해하고 사용하기
	- Git 숙달
	- ES6 문법에 맞춘 코드 스타일 통일

- 신미르
	- build script 작성
	- 안쓰는 gulp logic 제거
	- 기본 module system example 작성
	- conflict 제거

- 이태순
	- Webpack document, 블로그 등을 통해 webpack 구조 이해
	- build 에 필요한 파일과 develop 에 필요한 파일 분류
	- Git shell 명령어 공부
	- ES6 문법 공부 & 문법에 맞게 코드 수정

- 박경원
	- Git 개념 & 명령어 공부
	- ES6 문법 공부

## 2016년 9월 26일
### Docs
* Group Goal
 * `README.md` 작성
 * daily Report 교정
* 김무훈([@MuhunKim](https://github.com/MuhunKim)) : Group Leader
 * [Pull-Request #19](https://github.com/JeffGuKang/npm-webpack-boilerplate/pull/19): `README.md` 작성 및 라이선스 카피라이터 수정
 * 메인 저장소의 세부 설명 수정
 ```
 :page_with_curl: Boilerplate for npm/node module. Write with webpack & ES6
 ```
 * [Pull-Request #23](https://github.com/JeffGuKang/npm-webpack-boilerplate/pull/23) : `README.md` 재작성 및 `package.json`에 조장들의 이름을 `contributors`에 추가함
 * [Pull-Request #22](https://github.com/JeffGuKang/npm-webpack-boilserplate/pull/22#discussion_r80473266)(테스트 환경 구축) 코드리뷰
 * #8 : `daily/01_instagram` 문서를 전체적으로 교정함
   * 링크 걸기 & 팀원 Tagging
   * 보고서 이름을 `README.md`로 변경
 * UpdateTime with <p> tag in https://kosslab-kr.github.io/kosshack2016

- 최규호 ([@gyuho26](https://github.com/gyuho26))
  - Github 사용법 숙지
  - CMD로 Pull-Request 전송

### Test
- Team Goal
	- 해당 boilerpate에 테스트를 할 수 있는 환경 설정을 하고 예제 테스트 코드를 작성한다.

- 오도근
	- 테스트 툴 선정 (Karma & jasmine)
	- 선정 기준: 신뢰도 및 이용 점유율(출처: https://ashleynolan.co.uk/blog/frontend-tooling-survey-2015-results)
	- 테스트 툴 학습
	- 테스트 툴 boilerpate 참조(출처: https://github.com/zyml/es6-karma-jasmine-webpack-boilerplate)

### Example(A-Yo)

- Team Goal
  - Webpack 이해
  - 전체 process 이해
  - Git 활용
  - Example 코드 작성

- 개인활동 사항
  - 조승윤
    - Webpack 이해
    - Node.js 및 NPM 개념 파악
    - Sample example src 작성

	- 이성현
		- Webpack plugin 적용하여 test index 확인
		- ES6문법과 Babel에 대한 이해
		- ES6문법으로 간단하게 index 수정


### Task

- Team Goal
	- Webpack 이해하고 사용하기
	- Git 숙달
	- ES6 문법에 맞춘 코드 스타일 통일

- 신미르
	- Watch mode 도입
	- Conflicts 해결
	- 팀원들 질문 받아주기

- 이태순
	- Webpack 공부
	- 프로젝트 폴더 정리
		- 사용하지 않던 이전 파일 삭제
		- `scripts`, `src`, `views` 폴더를 기본으로 파일 정리

- 박경원
	- Github 실습
	- NPM 개념
	- ES6 의 차이점과 promise 개념
	- Webpack과 Babel 의 관계 이해

## 2016년 9월 27일

### Docs
* **Group Goal**
 * `README.md` 내용 보충 및 업데이트
 * 오타 고치기

* 김무훈([@MuhunKim](https://github.com/MuhunKim)) : Group Leader
 * `daily/01_instagram` 오타 고침 & 첫 영문자를 대문자로 수정(Capital letter)
 * `daily/01_instagram` 전체적으로 2차 수정
   * 조원 별 역할을 추가함
   * Docs Group의 Report 내용 보충 및 추가

- 최규호 ([@gyuho26](https://github.com/gyuho26))
	- Github 사용법 숙지
	- Git 명령어 공부
	- daily report 갱신을 위해 original repository에 Pull-Request.

### Example(A-Yo)

- Team Goal

- 개인활동 사항
	- 이성현
		- karma로 테스트 실행(`npm run test`)
		- FireFox, 크롬 미설치시 버그 발견, 이슈 작성
		- 오프라인 모임!!(사진 개인적으로 전송 부탁드립니다.^^)
