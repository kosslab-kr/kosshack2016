# Linux perf: Linux profiling with performance counters
## Member
* 송태웅 (멘토)
* 김동현
* 김선영
* 김재훈
* 김종빈
* 권욱제
* 안이수
* 양낙영
* 조성수
* 최왕용
* 하남봉

## Goal
* 이 프로젝트의 가장 큰 목적은 리눅스 커널 Contribution 을 하기위한 큰 장벽을 허무는데 있습니다.
* git 을 이용해서 수정한 내용에 대해 패치를 만들고 그것을 메일링 리스트에 전송하거나, github 에 pull request 를 보내는 것을 학습하여 리눅스 커널이 개발되는 과정을 학습합니다.
* 해커톤이 끝난 이후에도 지속적으로 perf 툴의 개발 진행상황에 관심을 가지고 지속적인 contribution 을 할 수 있기를 희망합니다.

## Links
perf 를 이해하는데 도움이 되는 링크를 공유합니다.
* http://www.brendangregg.com/perf.html
* http://egloos.zum.com/studyfoss/v/5636485
* http://sandsoftwaresound.net/perf/
* https://perf.wiki.kernel.org/index.php/Tutorial
* http://blog.2ndquadrant.com/tracing-postgresql-perf/
* http://events.linuxfoundation.org/sites/events/files/lcjp13_takata.pdf

## 마일스톤 관리 (각자 미션과 진행사항 표시)
https://github.com/kosslab-kr/linux-perf/milestones
* 중간과정 사진

![screenshot from 2016-09-27 23-56-22](https://cloud.githubusercontent.com/assets/3875235/18986875/e844d112-8739-11e6-81c3-d281c6c13f7a.png)


## Day by Day 미션내용
https://github.com/kosslab-kr/linux-perf/milestone/1
![screenshot from 2016-09-30 18-13-33](https://cloud.githubusercontent.com/assets/3875235/18986880/f6bd3acc-8739-11e6-9eb0-42270a8b1edb.png)


## Daily Did List
### 2016.09.24 (Offline)
* 장소 : D.Camp
* 시간 : 15:00 - 20:00
* 작업 내용
  * 팀원 소개 및 perf 에 대한 소개
      * perf 사용법 소개 및 시연
            * linux kernel contribution process 소개

![aa](https://dl.dropboxusercontent.com/u/53671575/kosshack2016-15.jpg)

## 2016.09.25 (Online)
* perf 개발 환경 구축
* git 기초 명령어 학습 (add, commit, push, pull)
* git 심화 명령어 학습 (checkout, reset, rebase)
* perf 에 대해서 개별 조사

* 각종 이슈

![img_2542](https://cloud.githubusercontent.com/assets/3875235/18987318/04f18902-873c-11e6-8b27-239396208847.PNG)

* 카카오톡으로 소통

![img_2539](https://cloud.githubusercontent.com/assets/3875235/18987329/0e76c514-873c-11e6-8e57-da5966c6af5f.PNG)


## 2016.09.26 (Offline)
* 장소 : kosslab 센터
* 시간 : 19:00 - 20:30
* 작업 내용
  * git 기초 / 심화 명령어 실습*
    * perf 로 간단한 프로그램 성능 테스트
      * uftrace 를 이용한 프로그램 실행 시 함수 호출 trace 실습
        * vim + ctags 를 이용한 perf 개발 환경 구축
	  * git 을 이용하여 수정 내용 패치 생성 및 메일링 리스트에 패치 전송 실습
	    * github 으로 pull request 생성 실습

![bb](https://dl.dropboxusercontent.com/u/53671575/kosshack2016-14.jpg)

## 2016.09.27 (Online)
* perf의 Documentation/tips.txt 실제적용 및 추가라인 만들기
* perf 소스리딩 tool 익히기 미션

* 온라인 작업중인 최왕용씨

![img_2546](https://cloud.githubusercontent.com/assets/3875235/18988955/284d7b56-8744-11e6-8f84-e1707f1cad24.JPG)

* 온라인 작업중인 양낙영씨

![img_2547](https://cloud.githubusercontent.com/assets/3875235/18989881/7c4c7acc-8749-11e6-9eca-4114477ac5a4.JPG)


## 2016.09.28 (Online)
* perf 소스리딩미션 "perf.data에서 이벤트샘플정보 읽어서 evlist에 어떻게 세팅하는가 ?"
* perf 소스리딩 미션 "subcommand는 어떻게 실행되는가?"
* perf 새로운 stat diff 만들기 관련 토의

* perf diff 기능관련 상의중 캡쳐

![img_2541](https://cloud.githubusercontent.com/assets/3875235/18987351/2ccf63ea-873c-11e6-8be9-94f7c97ad015.JPG)

* 새로운 perf stat diff 명령 (아이디어) 결과 사진

![nambong_ha](https://cloud.githubusercontent.com/assets/3875235/18988770/185ba64c-8743-11e6-9eaa-ec7eed5c9266.png)

* subcommand 실행 과정 분석과정

![screenshot from 2016-09-30 20-24-26](https://cloud.githubusercontent.com/assets/3875235/18990331/15ce1a50-874c-11e6-9f14-e4f86be9a242.png)


* perf config --list 가 parse 되는 과정 분석중

![screenshot from 2016-09-30 20-24-43](https://cloud.githubusercontent.com/assets/3875235/18990334/182e36f4-874c-11e6-954b-6c3660410acd.png)


## 2016.09.29 (Offline)
* (분석 정리) perf 소스리딩 미션 "subcommand는 어떻게 실행되는가?"
* (분석 정리) perf 소스리딩미션 "perf.data에서 이벤트샘플정보 읽어서 evlist에 어떻게 세팅하는가 ?"
* perf의 Documentation/tips.txt 실제적용 및 추가라인 만들기 (각자 실제 작업진행)
### * 총 5명 리눅스커널 메인라인에 PATCH 전송 성공 (2명은 답변받고 적용대기중)

![cc](https://scontent-icn1-1.xx.fbcdn.net/v/t1.0-9/14462726_1114507448638285_7182862245342389193_n.jpg?oh=b3d994b2242c17307fe40c02f6e2e6d1&oe=587AF4F1)

![dd](https://scontent-icn1-1.xx.fbcdn.net/v/t1.0-9/14433161_1114507458638284_3595453085873871599_n.jpg?oh=6a5c82e46bd09ee2c2c572af05725459&oe=5864B5DA)

![ee](https://scontent-icn1-1.xx.fbcdn.net/v/t1.0-9/14448940_1114507495304947_7552113958873401715_n.jpg?oh=f5a6532e881c97f630de228b972d382c&oe=587C3277)

![ff](https://scontent-icn1-1.xx.fbcdn.net/v/t1.0-9/14470602_1114507531971610_5587578741555345690_n.jpg?oh=ab1311fda9f2e77322da9ca30cbcf1dd&oe=586D5AEB)

![img_2513](https://cloud.githubusercontent.com/assets/3875235/18987472/c591e4e0-873c-11e6-919d-e5cdbcf11acf.JPG)

![img_2533](https://cloud.githubusercontent.com/assets/3875235/18987485/d1382746-873c-11e6-8d66-05c81b9e9f44.JPG)


### * 마지막 커널패치 5명 모두 전송후 사진 (2명은 메인테이너(Arnaldo)에게 답변받고 적용 대기중)
### * 커널에 보낸 PATCH 내용은 동일하게 pull-request도 연습
https://github.com/kosslab-kr/linux-perf/pull/154
https://github.com/kosslab-kr/linux-perf/pull/153
https://github.com/kosslab-kr/linux-perf/pull/152
https://github.com/kosslab-kr/linux-perf/pull/151
https://github.com/kosslab-kr/linux-perf/pull/150
https://github.com/kosslab-kr/linux-perf/pull/149
https://github.com/kosslab-kr/linux-perf/pull/148
https://github.com/kosslab-kr/linux-perf/pull/147

* 12시간 밤샘작업후 7시 반에 기쁨의 사진 :+1:

![img_2534](https://cloud.githubusercontent.com/assets/3875235/18987456/b303485a-873c-11e6-9267-2d9d430bbd7f.JPG)

* 하남봉씨 Arnaldo (Linux Kernel - perf 메인테이너) 답장 받은 사진

![img_2543](https://cloud.githubusercontent.com/assets/3875235/18987586/34b5127a-873d-11e6-92a3-b8addeef9aac.PNG)

* 김선영 씨 Arnaldo (Linux Kernel - perf 메인테이너) 답장 받은 사진

![img_2544](https://cloud.githubusercontent.com/assets/3875235/18987587/38ce525e-873d-11e6-83fc-5afd96b056ec.JPG)

* 조성수씨 PATCH 메일 전송 결과

<img width="1251" alt="img_2548" src="https://cloud.githubusercontent.com/assets/3875235/18990027/48e5fc8e-874a-11e6-850c-90ce93ca24ee.PNG">

* 하남봉씨 PATCH 메일 내용

![img_2549](https://cloud.githubusercontent.com/assets/3875235/18990029/4b55e592-874a-11e6-94ae-917fda27e0ad.JPG)



## 2016.09.30 (Online, Offline)
* 도커를 활용한 perf 개발 테스트 환경 구축 작업
* Linux Kernel - perf 프로젝트 초보개발자를 위한 가이드문서
* 발표자료 작업 진행

![img_2550](https://cloud.githubusercontent.com/assets/3875235/18990039/571a007a-874a-11e6-8861-bab4cae45a14.PNG)


