# 2016-09-24

팀 슬랙을 사용하기로 하였고 @closer27 님의 도움으로 생성하였습니다.
팀원 미팅과 함께 프로젝트 개요에 대한 이야기를 나누고
전원이 개발환경 구축을 마치고
할일을 정하고 다음과 같이 작업에 착수했습니다.

오늘은 개막식으로 인증을 대체합니다.

## 주제 선정

* @closer27: [#1](https://github.com/youknowone/Say/issues/1) 백엔드 NSSpeechSynthesizer 로 교체
* @sikeeo: [#2](https://github.com/youknowone/Say/issues/2) 비동기 재생
* @sikeeo & @Amanida: [#16](https://github.com/youknowone/Say/issues/16) iOS버전 개발
* @AWEEKJ: [#14](https://github.com/youknowone/Say/issues/14) 지정시간에 울리는 알람 기능 개발
* @kjy95: [#15](https://github.com/youknowone/Say/issues/15) URL을 넣으면 웹페이지 읽어주기
* @pmw9027: [#19](https://github.com/youknowone/Say/issues/19) 텍스트파일 불러오기 기능 개발
* @tobark: [#20](https://github.com/youknowone/Say/pull/20) 언어 선택 박스에 아무 문자나 입력할 수 있는 문제 수정
* @deffjoowon: [#8](https://github.com/youknowone/Say/issues/8) 다른 언어로 번역 후 읽어주는 기능을 추가
* @eeneguee [#22](https://github.com/youknowone/Say/issues/22) 선택한 텍스트가 있을 경우 선택한 텍스트만 재생

## 기타 활동

* @closer27: 많은 분들의 git/코드 이슈 해결을 도와주시고 있습니다.
* @tobark: [#10](https://github.com/youknowone/Say/issues/10) mp3로 다운받기를 추가하려 하였으나 시스템에서 지원이 되지 않는 것을 확인했습니다.

## 머지된 커밋
* @sikeeo: [#13](https://github.com/youknowone/Say/pull/13) Cocoapods 없는 환경에서 빌드할 수 있도록 프로젝트 설정 수정
* @tobark: [#20](https://github.com/youknowone/Say/pull/20) #20 완료
* @eeneguee: [#22](https://github.com/youknowone/Say/issues/22) 완료

![](20160924_1.png)

# 2016-09-25

오늘은 오프라인 활동 없이 온라인으로만 활동하였습니다.

## 활동

* @pmw9027: [#21](https://github.com/youknowone/Say/pull/21) 에서 파일 불러오기 패치를 수정중이고 일시정지 및 다시 재생 기능 추가중
* @Amanida: [#23](https://github.com/youknowone/Say/pull/23) iOS 버전을 개발중입니다.
* @kjy95: [#25](https://github.com/youknowone/Say/pull/25) URL을 넣으면 내용을 읽어주는 기능을 개발중이고, 현재 제목을 읽어주는 단계까지 왔습니다.


#2016-09-26

## 오프라인 활동
- 오후 4시-오후11시까지 오프라인에서 작업을 하였습니다.
- 장소: 토즈 신촌본점 및 신촌 TOMS & TOMS

* @tobark
* @pmw9027
* @Amanida
* @AWEEKJ

![](20160926_1.jpg)
![](20160926_2.jpg)
![](20160926_3.jpg)

## 활동
* @pmw9027: [#21](https://github.com/youknowone/Say/pull/21) 파일 불러오기 기능을 완성하고 연관된 UI 이슈도 수정하여 머지
* @Amanida: [#23](https://github.com/youknowone/Say/pull/23) [#39](https://github.com/youknowone/Say/pull/39) iOS 버전의 기본적인 기능을 구현하여 머지
* @AWEEKJ: [#37](https://github.com/youknowone/Say/pull/37) [#40](https://github.com/youknowone/Say/pull/40) 알람 기능과 연관된 UI 이슈를 구현 및 수정하여 머지
* @tobark: [#34](https://github.com/youknowone/Say/pull/34) 선택한 텍스트 재생 기능으로 인해 발생한 버그 수정 ([#22](https://github.com/youknowone/Say/pull/22))
* @closer27: [#36](https://github.com/youknowone/Say/pull/36) 말하기 백엔드를 명령줄 기반에서 NSSpeechSynthesizer로 완전히 교체

![](slack1_1.png)

#2016-09-27

## 오프라인 활동
- 오후 4시-오후10시 30분까지 오프라인에서 작업을 하였습니다.
- 장소: 토즈 신촌본점 및 토즈 아트레온점

## 참가자
* @tobark
* @kjy95
* @deffjoowon
* @pmw9027
* @Amanida
* @AWEEKJ

![](20160927_1.jpg)
![](20160927_2.jpg)
![](20160927_3.jpg)
![](20160927_4.jpg)

## 활동
* @tobark: [#41](https://github.com/youknowone/Say/pull/41) UI의 사소한 오류를 바로잡음
  * 창이 너무 작게 줄어들들지 않도록 방지
  * 목소리 선택 콤보박스 동작 개선
* @kjy95: [#58](https://github.com/youknowone/Say/pull/58) URL 읽어주기 기능 계속 진행. 제목 읽기까지 머지하고 @tobark 님의 조언에 따라 본문 읽기도 진행 중
* @closer27: 맥 버전과 iOS 버전의 다른 백엔드 인터페이스를 통합
* @deffjoowon: 네이버 번역 API를 적용 중
* @AWEEKJ: 투데이 확장에 일시정지 기능 도입 시도

![](slack2_1.png)

#2016-09-28

## 오프라인 활동
- 오후 7시-오후 10시까지 오프라인에서 작업을 하였습니다
- 장소: 토즈 선릉점

* @Amanida
* @pmw9027
* @kjy95

![](20160928_1.jpg)
![](20160928_2.jpg)
![](20160928_3.jpg)

## 활동
* @Amanida: [#48](https://github.com/youknowone/Say/pull/48) iOS 재생-정지 기능
* @AWEEKJ: [#56](https://github.com/youknowone/Say/pull/56) @tobark 님의 제안에 따라 알람 UI 개편 중
* @kjy95: [#58](https://github.com/youknowone/Say/pull/58) 본문 읽어주기 기능 계속 진행
* @tobark: [#52](https://github.com/youknowone/Say/pull/52) UI에 stack 도입
* @closer27: 프로젝트의 Collaborator로 등록하여 이슈를 관리하고 코드 리뷰

![](slack3_1.png)

#2016-09-29

## 오프라인 활동
- 오후 4시-오후 8시까지 오프라인에서 작업을 하였습니다
- 장소: 토즈 신촌본점

* @kjy95
* @tobark
* @pmw9027
* @sikeeo
* @eeneguee
* @AWEEKJ

![](20160929_1.jpg)

## 활동
* @kjy95: [#58](https://github.com/youknowone/Say/pull/58) 오랜 작업 끝에 드디어 결실을 맺어 URL 내용을 읽어주는 기능을 완성했습니다.
* @pmw9027: [#54](https://github.com/youknowone/Say/pull/54) 정지 기능 개선
* @sikeeo: [#55](https://github.com/youknowone/Say/pull/55) iOS에서 편집을 시작하면 키보드를 가릴 수 없던 문제 수정
* @eeneguee: [#27](https://github.com/youknowone/Say/issues/27) 맥/iOS버전이 iCloud에 사용 내역 저장해 공유하도록
* @AWEEKJ: [#56](https://github.com/youknowone/Say/pull/56) 알람 UI 개편 완료

![](slack4_1.png)

#2016-09-30

## 오프라인 활동
- 오후 4시-오후 12시까지 오프라인에서 작업을 하였습니다.
- 장소: 메가젠토즈타워점

* @kjy95
* @tobark
* @eeneguee
* @AWEEKJ
* @deffjoowon
* @closer27

![](20160930_1.jpg)
![](20160930_2.jpg)
![](20160930_3.jpg)
![](20160930_4.jpg)

## 활동

* @kjy95: @deffjoowon 님의 문제 해결을 도와주었습니다
* @tobark: [#67](https://github.com/youknowone/Say/pull/67) UI 개선. 정지 아이콘이 노출되지 않는 문제
* @eeneguee: 발표 준비
* @AWEEKJ: 발표 준비 [#69](https://github.com/youknowone/Say/pull/69) Today 확장에 일시정지 기능 추가 [#66]((https://github.com/youknowone/Say/pull/66) 정지 기능 버그 수정
* @deffjoowon: [#68](https://github.com/youknowone/Say/pull/68) 번역해서 읽기 기능 기초를 완성
* @closer27: 코드 리뷰 및 다른 사람들의 코드 작성을 도와주었습니다

![](slack5_1.png)
![](slack5_2.png)

# 종합보고

* 목표: Say는 오픈소스 연습용 프로젝트.
  * 모두가 오픈소스 문화를 체험해 보자
  * 모두가 지금의 & 미래의 오픈소스 컨트리뷰터가 되자

## 통계

* 프로젝트 기여자 1명 -> 10명 (9명 전원 참가)
* 이슈 32개. 해결된 이슈 19개.
* 풀리퀘스트 30개. 1인당 3개 이상.
* 코드 리뷰 100건
* 이슈 토론 150건
* 모든 사람이 1개 이상의 풀리퀘스트를 제출하여 성공적으로 패치를 제출하고 머지되었습니다.
* 모든 사람이 이슈를 제출하고 하나 이상의 이슈를 수정했습니다.
* 코드 리뷰에는 9명 중 8명이 참여했습니다.

## 기여사항
* iOS버전 구현: @Amanida @sikeeo
* 텍스트 파일 불러오기: @pmw9027
* 알람: @AWEEKJ
* 웹페이지 본문 읽어주기: @kjy95
* 재생 및 일시정지: @pmw9027 @AWEEKJ
* 선택한 텍스트만 읽어주기: @eeneguee @tobark
* UI 개선: @tobark
* 백엔드 현대화: @closer27

## 오프라인 모임
* 전원 1회 이상 참석
* 월화수목금 빠짐없이 매일매일 모임
* 참석 인원 25사람·일 or 140사람·시간
* 1인당 평균 2.7일 15.5시간 참여
* 매우 활발한 진행
