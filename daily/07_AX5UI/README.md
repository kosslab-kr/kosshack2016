# 9월 23일

**참가자들에게 다음 의 내용 공지**

Gitter : https://gitter.im/ax5ui/KOSSLAB2016

## 3가지 레포지터리 사용
- https://github.com/ax5ui/ax5ui-kernel
- https://github.com/ax5ui/ax5docs
- https://github.com/kosslab-kr/ax5ui-quick-start


# 9월 24일

##팀원
금대건, 김동근, 김동영, 김동욱, 김인영, 김태근, 마진형, 박현준, 송다운, 위세라, 이소은, 이한빈, 한대승 (1명 불참)

## 해커톤 진행방법
코드개발, 테스트코드작성, 문서작성, 번역 으로 롤 분배
- 코드개발 : 김동근, 위세라, 이소은, 한대승
- 테스트코드작성 : 금대건, 박현준, 이한빈
- 문서작성 : 김동욱, 김인영, 김태근, 마진형, 송다운
- 번역 : 김동영

### 코드개발
https://github.com/ax5ui/ax5ui-kernel 를 포크하여 소스를 수정후 pull request하도록 안내 및 환경 설정
차주 월요일 모임을 통해 프로젝트 구조와 각각의 코드 개발범위 결정

### 테스트코드작성
ax5core에 대해 https://mochajs.org/ 기반의 테스트코드를 작성하여 ax5core의 메소드들에대해 테스트 자동화 되도록 작업
ax5ui-kernel https://github.com/ax5ui/ax5ui-kernel/tree/KOSS-Hackarthon-test 브랜치를 만들어 https://github.com/ax5ui/ax5ui-kernel/tree/KOSS-Hackarthon-test/src/ax5core/test 에 테스트코드를 커밋하기로 함.

### 문서작성
https://github.com/kosslab-kr/ax5ui-quick-start에 ax5ui 문서를 작성하여 커밋하고 http://guide.ax5.io/로 서비스가 될 수 있도록 하기로 함.

### 번역
프로젝트 전체 영문 문서 내용에 대해 감수하고 수정/보강하여 커밋하기로 함.


## pull request
- https://github.com/ax5ui/ax5ui-kernel/pull/16
- https://github.com/ax5ui/ax5ui-kernel/pull/17
- https://github.com/ax5ui/ax5ui-kernel/pull/18
- https://github.com/ax5ui/ax5ui-kernel/pull/19
- https://github.com/ax5ui/ax5ui-kernel/pull/21

총 5건의 pull request 

## commit
- https://github.com/kosslab-kr/ax5ui-quick-start/commit/2cf48ebcb551e4ed2cab7e296c8258d0fc0cf0ce
- https://github.com/kosslab-kr/ax5ui-quick-start/commit/85477198d977ee41d61c283e1d371928be01c9e2
- https://github.com/kosslab-kr/ax5ui-quick-start/commit/73725d6dd75d5896983229c611ca41e6b2ec6a31
- https://github.com/kosslab-kr/ax5ui-quick-start/commit/f2092d4f78bbe70ff5b0e756cb08edc66b7bfe15
- https://github.com/kosslab-kr/ax5ui-quick-start/commit/38dba95b5d8e42e033eb567cb4df125e5882d320
- https://github.com/kosslab-kr/ax5ui-quick-start/commit/f49ad63d8d0ee07ed4e1f5b1b7ccc11b596ec809
- https://github.com/kosslab-kr/ax5ui-quick-start/commit/0da7db3cbf661e6cae4ba94d5ce67a64f38dd581
- https://github.com/kosslab-kr/ax5ui-quick-start/commit/bc6aa1195e7d63ad9c5b20d462a61512aae934db
- https://github.com/ax5ui/ax5ui-kernel/commit/2fed3f2b5aac86a3cd55dc64b8bb5f015799860b
- https://github.com/ax5ui/ax5ui-kernel/commit/04f4c339b20cec224427e19ebd1ccff299e29d41
- https://github.com/ax5ui/ax5ui-kernel/commit/3c08dbbdabbe489967455555ed049c872581eadd
- https://github.com/ax5ui/ax5ui-kernel/commit/1680373e2530e4ae9393848b378205173a3e19d7
- https://github.com/ax5ui/ax5ui-kernel/commit/121a057e0cf939438259f5134ff3e408cb998df2
- https://github.com/ax5ui/ax5ui-kernel/commit/c63753940fe571f6eff2d0e2dd605652012e30de

총 14건의 commit

## issue
https://github.com/ax5ui/ax5ui-kernel/issues/20

총 1건의 issue


# 9월 25일

## 테스트코드 작성
|성명|링크|활동내역|파일수|추가된줄수|삭제된줄수|
|---|---|---|---|---|---|
|이한빈|https://github.com/ax5ui/ax5ui-kernel/commit/5eae7e1d68136c2df4b4c85074e87847b7b021e5|ax5.util.search test 추가|1|32|0|
|금대건|https://github.com/ax5ui/ax5ui-kernel/commit/4e116e12533a97ca9b17859568e5d7e41865b006|ax5.util.string TEST|2|117|0|
|박현준|https://github.com/ax5ui/ax5ui-kernel/commit/89a7c31d5dd79a9a9427a8c4e85a24a006bd6bfb|ax5.util.toArray TEST|2|21|8|
| |https://github.com/ax5ui/ax5ui-kernel/commit/3f308535139badafa54c8e2b38453eecf5973c9a|ax5.util.toJson TEST|1|41|0|
| |https://github.com/ax5ui/ax5ui-kernel/commit/8063136f448463fbdb0e032c648c43413a9d4535|doc title change more specify|2|2|2|
| |https://github.com/ax5ui/ax5ui-kernel/commit/6d767d8bcc9cac673cff1029211b990579c8a390|ax5.util.parseJson TEST|1|19|0|
| |https://github.com/ax5ui/ax5ui-kernel/commit/68764596ec66c8bbe65d8ad3383c8c363d6e52a5|misc.param, isType grouping  …|3|128|91|
| |https://github.com/ax5ui/ax5ui-kernel/commit/1b24ac22e8a22502eaee81eb746224959fc7c431|TYPE 완료~!|1|180|5|

## 문서작성
|성명|링크|활동내역|파일수|추가된줄수|삭제된줄수|
|---|---|---|---|---|---|
|송다운|https://github.com/kosslab-kr/ax5ui-quick-start/commit/3b15fd3b4f88266db1fbe573f3cb37dd45cf7a42|add mdpath & mdfile|11|790|8|
|김동욱(sksdong)|https://github.com/kosslab-kr/ax5ui-quick-start/commit/fdf6603e40e6bb973609ffa90623bf0c202ac776|화면 바뀌는지 시도..|7|309|136|
| |https://github.com/kosslab-kr/ax5ui-quick-start/commit/9fdb3ee8249be2da293d18cb9c1dec6791fb7373|add menu|1|31|0|
| |https://github.com/kosslab-kr/ax5ui-quick-start/commit/c0a2aa5d83c03e3346a699f1d08686c1f1e8cf43|npm and gulp install doc|3|39|4|
|마진형|https://github.com/kosslab-kr/ax5ui-quick-start/commit/fdbaea155d417b8fc216909272fa9ff6e5b31a33|Ma || howtoinstall tmpfile|1|1|0|

## 코드개발
|성명|링크|활동내역|파일수|추가된줄수|삭제된줄수|
|---|---|---|---|---|---|
|이소은|https://github.com/ax5ui/ax5ui-kernel/commit/d1327c49dbe5fb4e891bea56f43f76bffbb05b54|feat: For showing double alerts, Add two kind of alert test button (#30)|1|15|0|
|한대승|https://github.com/ax5ui/ax5ui-kernel/commit/e9180f0f3dde4e9eddb3326d494a52e0dcf761fa|25일 프로젝트 분석 내용 (#29)|1|1|2|
|위세라|https://github.com/ax5ui/ax5ui-kernel/commit/118ac75f67f528620487e760a7072e9f00a4df17|버튼 위치 수정 및 이름 변경|2|20|16|
|김동근|https://github.com/ax5ui/ax5ui-kernel/commit/e69ca9d6f4dd0e9aff9a0f1e53e209954a2fa5d0|변수 명명규칙 변경(callback)|16|122|123|

## 번역
|성명|링크|활동내역|파일수|추가된줄수|삭제된줄수|
|---|---|---|---|---|---|
|김동영|https://github.com/ax5ui/ax5ui-kernel/commit/cff06d7fbe80ae8912a7b55c9e2db798b672d555|Documentation Content Fix - ax5ui-select|2|15|16|
| |https://github.com/ax5ui/ax5ui-kernel/commit/1e28d0289abfa6c1928ea88eccd744785463b08f|Has fixed doc content / ax5ui-mask / further refinement |2|12|11|
| |https://github.com/ax5ui/ax5ui-kernel/commit/edaace04bab8480129528a404e0dad1eb3666185|Has fixed doc content / ax5ui-mask|1|1|2|
| |https://github.com/ax5ui/ax5ui-kernel/commit/a5f6f6cbb42e8b953ba9c5e7c0486f5f91f2682b|Has fixed doc content / ax5ui-menu|1|15|15|
| |https://github.com/ax5ui/ax5ui-kernel/commit/9eb8ccf9cc7b34d138169943b0f83731c9f600ae|Has fixed doc content /ax5ui-mask / CDN urls|1|1|1|
| |https://github.com/ax5ui/ax5ui-kernel/commit/92ee80d338d7df748665925352892396f46b2802|Has fixed doc content /ax5ui-mask / HTML HEAD|1|3|3|
| |https://github.com/ax5ui/ax5ui-kernel/commit/a9a10b5e850e251feefa6afc17d24d71c2cbc771|Has fixed doc content /ax5ui-mask / gulp and grunt|1|3|3|
| |https://github.com/ax5ui/ax5ui-kernel/commit/aff3423ba5b36be22fa553155df8336ffc51fe28|Has fixed doc content /ax5ui-mask / install by npm|1|5|5|
| |https://github.com/ax5ui/ax5ui-kernel/commit/d485fa133947307d32f3c3c05988870b79c693be|Has fixed doc content _install by bower|1|1|1|