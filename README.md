# 한다시 앱 약관 모음

앱 스토어(Google Play · App Store)는 **로그인 없이 열리는 웹 주소**로
개인정보처리방침을 요구한다. 앱 안에 문서가 있는 것만으로는 등록이 안 된다.

## ⚠️ 이 파일들을 손으로 고치지 않는다

원본은 각 앱의 코드 안에 있다. 여기 있는 건 거기서 뽑아낸 사본이다.
따로 고치면 **"앱에 적힌 것과 스토어에 낸 것이 다른" 상태**가 되는데,
법률 문서에서 그건 그냥 문제다.

| 폴더 | 원본 | 뽑는 법 |
|---|---|---|
| `bug/` | 곤충탐험대 `app/lib/features/auth/presentation/legal_document_page.dart` | `python tools/build_legal.py` 뒤 `legal/index.html`을 복사 |
| `salespt/delete/` | 셀즈PT 약관·처리방침은 `salespt.kr/terms`·`/privacy`(sales-pt 레포 `src/app/privacy/page.tsx`)에 있다. 여기엔 Google Play용 계정 삭제 안내만 둔다 | 처리방침 6·7조(탈퇴 후 1년 보관, 고객 휴지통 30일)가 바뀌면 손으로 맞춘다 |
| `soomora/` | 숨모라 `soomora` 레포 `store/privacy.html` | 내용이 바뀌면 손으로 옮겨 적는다 (자동화 스크립트 없음. 계정·서버가 없어 조항이 짧다) |

곤충탐험대 저장소의 `test/legal_web_test.dart`가 둘이 어긋나면 실패한다.
