# Titanium Boiler Plate Template

## Member & Role (Github ID)

- Mentor
	- 김동우 (gimdongwoo) : Mentor
- Project [Brand New]
	- 서장원 (wkddnjset) : Team Manager, Document, Reaction, etc
	- 최석환 (soulmade00) : Frontend UI, Push Notification
	- 김유진 (Yoojinn) : Frontend UI, Push Notification
	- 이필구 (Feelgu) : Frontend UI, Push Notification
	- 유승연 (dbtmddus) : Backend Server Logic
	- 조소영 (s2s22) : Backend Server Logic
	- 오충협 (ChungHyup) : Backend Server Logic
- Project [Save My Friends]
	- 김덕윤 (kimdeokyun) : Team Manager, SMS Parser/Sender, Filter
	- 진재언 (jinjaeeon) : SMS Parser/Sender, Filter
	- 최형필 (Hyeongpil) : Contacts Load, Deduplication
	- 김정래 (suprodigy) : Contacts Load, Deduplication
	- 함유경 (ykhaam) : Frontend UI
	- 김치현 (ChiHyeonKim) : Testing, Debugging, Bug fix
	- 양준영 (yjy0431) : Testing, Debugging, Bug fix

## Goal

- 대부분의 참가자들이 이제 막 개발을 시작한 초급이고, 일주일의 시간 동안에 큰 성과를 내기에는 어려움이 있습니다.
- 오픈소스 프로젝트를 경험해 보는 것만으로도 해커톤은 성공이라고 생각합니다.
- 목표를 정하고, 팀원을 조직하고, 역할을 분담하고, 지속적으로 해나가는 것을 목표로 합니다.

## Project

- 인원을 절반으로 나누어 2개의 프로젝트를 경쟁적으로 진행합니다.

### Project [Brand New]
	- 오픈마켓에 입점하지 않는 중소 온라인 패션 쇼핑몰 들이 많이 있습니다.
	- 개성있는 제품을 소량 생산하기 때문에, 구매 기회를 놓치는 경우가 많습니다.
	- 또한 오픈 마켓이라고 하더라도 자신의 취향에 맞는 제품의 새로운 정보를 제공 받기는 불가능합니다.
	- 이러한 니즈를 반영하여, 신제품 정보를 제공하는 어플리케이션을 개발합니다.
	- 자신의 취향/기호/선호 쇼핑몰을 선택하여, 신상품이 올라오면 push 메시지로 알려줍니다.
	- 비정형화 된 쇼핑몰을 각각 Parsing해야 하는 기술적 어려움이 예상됩니다.
	- 취향에 맞는 제품을 Define해야하는 기술적 어려움이 예상됩니다.

### Project [Save My Friends]
	- 국가에서 발송하는 재난문자는 기술적/물리적 한계로 인해 동시에 모든 국민에게 전달되지 않습니다.
	- 나와 내 친구들 중에 재난문자를 가장 먼저 받는 사람이 있다면, 그것을 친구들에게 전파한다면 어떨까요?
	- 문자메시지 뿐 아니라 Push 메시지로 전파한다면 어떨까요?
	- 재난상황에서 재난 정보 전달의 효율성을 높이고자 하는 요구로 인해 프로젝트가 시작되었습니다.
	- 상당수의 모바일 요금제에서 문자메시지가 무제한으로 포함되어 있습니다. 이것을 활용합니다.
	- Push 메시지는 tcp/ip로 전달되어, 문자 메시지보다 재난상황에서 전달력이 높습니다.
	- 실제로 동일본 대지진 때 모든 GSM/CDMA통신은 불가능했지만, VOIP를 이용한 메신저는 동작했습니다.
	- 내가 전파한 재난메시지로 인해서 나의 친구와 가족을 위험에서 구할 수 있습니다.

## Communication

- 온라인 커뮤니케이션
	- Slack : https://titanium-hackathon.slack.com
	- Github : (waffle.io를 활용한 이슈관리)
		- https://github.com/kosslab-kr/Titanium-BrandNew
		- https://github.com/kosslab-kr/Titanium-SaveMyFriend
	- Tidev.kr : 한국 타이타늄 사용자 모임
		- 기술적 어려움에 대해 조언을 구하는 Q&A 채널로 활용
	
- 오프라인 커뮤니케이션
	- Office Hour : 9월 26(월), 27(화), 29(목), 30(금)일 사이에 저녁 7시-저녁11시 사이에 멘토의 사무실에 방문하시면 직접적인 도움을 드립니다.
		- 서울시 서초구 서초대로42길 82 미광빌딩 5층
		- 동시에 4명까지만 가능합니다. Slack을 통해 방문에 관해 협의합니다.

## Daily Report

### 2016-09-24 (토)
	- 해카톤 당일
	- 주제 선정 브래인스토밍 / 의견 발표 / 토론 / 아이디어 선호도 투표
	- 팀 모집 브리핑 / 자유의사에 의한 팀 분할
	- 팀별 목표 설정 / 역할 분배 / 할일 목록화
	- Slack에 팀 별 Channel 등록 / 모든 팀원 Slack에 등록
	- Github Repository 생성 / Collaborator 등록

	- 멘토가 한일 : 해카톤 진행, 멘티가 읽을 거리 작성 (http://tidev.kr/t/topic/1832)

### 2016-09-25 (일)
	- 각자의 feature를 쪼개서 waffle.io를 통해 github 이슈 등록
	- SourceTree를 이용한 git과 github 사용법 학습
	- Titanium 개발환경 구축 (Studio IDE, Titanium/Android SDK, NodeJS 기반 설치)
	- Rss Reader 샘플 코드 import & build
	- JavaScript 기초 및 Titanium Code 구조 학습
	- Main Repository import & build
	- 백엔드 서버인 Parse Server 로컬 개발환경 구축 및 학습

	- Project (Brand New) 등록 이슈 : 25건 중 완료 3건
		https://github.com/kosslab-kr/Titanium-BrandNew/issues

	- Project (Save My Friend) 등록 이슈 : 18건 중 완료 3건
		https://github.com/kosslab-kr/Titanium-SaveMyFriend/issues

	- 멘토가 한일 : 개발환경 구축 및 샘플 코드 빌드 가이드, 백엔드 서버 구축
		읽을 거리 작성 (http://tidev.kr/t/topic/1833)

### 2016-09-26 (월)
	- Project [Brand New]
		- 서장원 (wkddnjset) : 
			- 타이타늄 샘플 아직도 못하고 있습니다ㅠ 계속 똑같은 오류가뜹니다.
			- 깃헙에서 Zip파일로 다운받은다음 import 했는데 다시 해봐야될것 같습니다
			- Sourcetree를 이용해 README의 내용을 수정해 보았습니다
		- 최석환 (soulmade00) : 
			- parse server로 URL 주고 받기
			- 몽고DB에 데이터 넣고 요청해보기
		- 김유진 (Yoojinn) : 
			- 개발환경 구축
			- 자바스크립트 기초적인 문법 공부
			- 올려주신 자료(기초) 영상 시청
		- 이필구 (Feelgu) : 
			- 타이타늄 사용법 연습
			- 타이타늄 소스 학습
			- 자바스크립트 학습
		- 유승연 (dbtmddus) : 
			- parse server 개발환경 세팅 완료
			- heroku로 parse-server폴더를 clone시키고, 내부 cloud 폴더를 다시 push시키는것 까지 완료
			- java script 공부 중
			- cloud 내부 js소스들을 보다가 7시반에 잠이 듭니다!
		- 조소영 (s2s22) : 
			- 타이타늄 사용법 연습
			- 자바스크립트 학습
			- parse-server 학습
		- 오충협 (ChungHyup) : 
			- Html 파싱 및 데이터 가공
			- Parse-server, Parse 학습
	- Project [Save My Friends]
		- 김덕윤 (kimdeokyun) : 
			- git에서 패치받아 Studio에 update되는 것 확인.
			- 타이타늄 동영상 강의보고 실습
			- SaveMyFriend의 코드 읽어 봄.
		- 진재언 (jinjaeeon) : 
			- 타이타늄 기초 강의 동영상 5개 학습 및 실습 수행
			- 재난 문자 종류를 파악하기 위한 문자열 검색 로직 작성 ( 보완 필요 )
			- sms 수신 모듈 소스 코드 분석 中
		- 최형필 (Hyeongpil) : 
			- login.js, core.js, index.js, smsreceive.js 코드 분석 후 주석 달아 커밋
			- git에 푸시를 요청하였으나 권한이 없어 실패
			- JavaScript 강의 수강중
			- 타이타늄 기초 강의 5개 실습
		- 김정래 (suprodigy) : 
			- 타이타늄 동영상 실습
			- 전화번호 파일 IO 구현을 위해 아래 자료 참고하여 공부 중
			- JavaScript 재입문하기
			- 자바스크립트 핵심 가이드(더글라스 크락포드 저) 책
			- SaveMyFriend에 올려주신 코드 한 번 읽어봄
		- 함유경 (ykhaam) : 
			- UI 초안 올리고 피드백 받아서 수정 중
			- 다른 UI나 디자인 참고 공부중
			- 개발이 현재 어떻게 이루어지는 지 파악중
		- 김치현 (ChiHyeonKim) : 
			- 재난 문자 필터링을 위해서 참고가 될 만한 사이트 조사
			- 재난 문자 개념, 재난 문자 사례, 재난 문자 종류, CBS 기술 설명과 재난문자 송출 기준
			- JavaScript로 공부중
		- 양준영 (yjy0431) : 
			- 현재 In Progress에 있는 모두 할일중 프로젝트 리파지터리 코드 실행해보기를 제외하고 다했고
			- 프로젝트 리파지터리 코드 실행해보기를 하는중입니다.

### 2016-09-27 (화)
	- Project [Brand New]
		- 서장원 (wkddnjset) : 
			- HTML작성..중입니다
			- SourceTree를 통해 GitHub에 Web폴더를 푸쉬했습니당~
			- 칭찬해주세요~
		- 최석환 (soulmade00) : 
			- 이필구, 조소영님 개발에 도움
			- listview 이해
		- 김유진 (Yoojinn) : 
			- 리더님께서 올려주신 listView 소스분석.
			- 다른 listview 예제 찾아봄.
		- 이필구 (Feelgu) : 
			- 개발환경 셋팅 완료, 사용법 숙지
			- ( 최석환형의 도움으로..)
		- 유승연 (dbtmddus) : 
			- html scrap 구현
			- 쇼핑몰 html,css, js 구성 인식
			- java sript - 이번 서버, db관련 패키지,함수들 학습 중
		- 조소영 (s2s22) : 
			- 개발환경 셋팅, 코드 리뷰 중
			- (오프라인에서 최석환 님 도움 받음)
		- 오충협 (ChungHyup) : 
			- Html scrap / parsing / save 구현
			- 이전 데이터와 비교를 통한 업데이트 여부 확인 구현중
		- 1차 오프라인 모임 : 최석환, 이필구, 유승연, 조소영, 오충협 참석
	- Project [Save My Friends]
		- 김덕윤 (kimdeokyun) : 
			- README 초안 작성 및 푸쉬
			- 타이타늄 모바일 앱 프로그래밍(보이들리 폴렌타인)이란 책을 빌려서 정독하고 있습니다.
			- 국민안전처에서 제공한 재난 문자 발송 기록을 조사했습니다.
			- 갑작스럽게 IDE에서 run이 안되는 바람에 시간을 많이 허비했네요 ㅠㅠ 화이팅합시다
		- 진재언 (jinjaeeon) : 
			- sms 파싱 및 스위치UI를 통해 재난 메시지 선택 제어 기능 구현 및 github push
			- 아직은 재난 문자별로 수신되지 않고 일단 "홍수"에 대해서만 정적으로 구현했고
				내일부터 대표적인 큰 재난에 대한 스위치 설정 및 동적으로 구현할 생각입니다!!
			- 오픈소스S/W의 정의, 장점, 중요성 등에 대해서 멘토님께 질문을 했고 답변 받았습니다.
			- github의 PullRequest에 대해 @Hyeongpil 에게 질문했고 답변 받았습니다.
		- 최형필 (Hyeongpil) : 
			- 핸드폰에 내장된 연락처를 가져오기 위해 Titanium API 문서 분석
			- 앱에 핸드폰에 내장된 연락처 데이터를 가져와 Console Log로 출력 - Github에 push
			- JavaScript 공부 - 삼위일체 웹 프로그래밍 도서
		- 김정래 (suprodigy) : 
			- 자바스크립트 공부
			- 핸드폰 화면 보면서 소스 코드 분석
		- 함유경 (ykhaam) : 
			- readme 수정
			- 소스 읽어보기
			- 저도 너무 도움이 못되어드려서 죄송합니다ㅠㅠ 도와드릴게 있으면 말해주세요!
		- 김치현 (ChiHyeonKim) : 
			- 소스와 주석 전체적으로 살펴보기
		- 양준영 (yjy0431) : 
			- Savemyfriend 클론 받아서 실행해보기

### 2016-09-28 (수)
	- Project [Brand New]
		- 서장원 (wkddnjset) : 
			- 
		- 최석환 (soulmade00) : 
			- 
		- 김유진 (Yoojinn) : 
			- 
		- 이필구 (Feelgu) : 
			- 
		- 유승연 (dbtmddus) : 
			- 
		- 조소영 (s2s22) : 
			- 
		- 오충협 (ChungHyup) : 
			- 
	- Project [Save My Friends]
		- 김덕윤 (kimdeokyun) : 
			- 
		- 진재언 (jinjaeeon) : 
			- 
		- 최형필 (Hyeongpil) : 
			- 
		- 김정래 (suprodigy) : 
			- 
		- 함유경 (ykhaam) : 
			- 
		- 김치현 (ChiHyeonKim) : 
			- 
		- 양준영 (yjy0431) : 
			-

### 2016-09-29 (목)
	- Project [Brand New]
		- 서장원 (wkddnjset) : 
			- 
		- 최석환 (soulmade00) : 
			- 
		- 김유진 (Yoojinn) : 
			- 
		- 이필구 (Feelgu) : 
			- 
		- 유승연 (dbtmddus) : 
			- 
		- 조소영 (s2s22) : 
			- 
		- 오충협 (ChungHyup) : 
			- 
	- Project [Save My Friends]
		- 김덕윤 (kimdeokyun) : 
			- 
		- 진재언 (jinjaeeon) : 
			- 
		- 최형필 (Hyeongpil) : 
			- 
		- 김정래 (suprodigy) : 
			- 
		- 함유경 (ykhaam) : 
			- 
		- 김치현 (ChiHyeonKim) : 
			- 
		- 양준영 (yjy0431) : 
			-

### 2016-09-30 (금)
	- Project [Brand New]
		- 서장원 (wkddnjset) : 
			- 
		- 최석환 (soulmade00) : 
			- 
		- 김유진 (Yoojinn) : 
			- 
		- 이필구 (Feelgu) : 
			- 
		- 유승연 (dbtmddus) : 
			- 
		- 조소영 (s2s22) : 
			- 
		- 오충협 (ChungHyup) : 
			- 
	- Project [Save My Friends]
		- 김덕윤 (kimdeokyun) : 
			- 
		- 진재언 (jinjaeeon) : 
			- 
		- 최형필 (Hyeongpil) : 
			- 
		- 김정래 (suprodigy) : 
			- 
		- 함유경 (ykhaam) : 
			- 
		- 김치현 (ChiHyeonKim) : 
			- 
		- 양준영 (yjy0431) : 
			-

			