# WIPI-X 변경 안내

[프로젝트 홈](../README.md) · [테스트 참여 안내](TESTING.md) · [버전별 GitHub 릴리즈](https://github.com/hun99999/wipi-x-releases/releases)

Google Play에 심사 요청하거나 배포한 버전의 변경사항을 최신순으로 기록하며, 각 버전의 제공 상태를 구분합니다. 알파·베타 기록도 정식 출시 후 계속 보존합니다.

## WIPI-X 0.1.32 — 일부 음원의 준비 처리 개선

일부 SMAF 음원을 처음 준비할 때 필요한 계산을 줄였습니다. 음원의 자연스러운 종료 시점을 찾는 처리를 개선했으며, 기존 소리의 길이와 파형은 유지합니다.

- 배포 채널: Google Play 비공개 테스트 Alpha
- 앱 버전 / 빌드 번호: 0.1.32 / 33
- 심사 요청일: 2026년 9월 15일 (한국 시간)
- 상태: 심사 요청 완료 · Play 제공 대기. 실제 제공이 확인된 버전과는 구분합니다.

### 개선 및 수정

- 일부 SMAF 음원의 재생 준비 과정에서 반복 계산을 줄였습니다.
- 기존 소리 합성·재생 속도·게임 진행 및 저장 방식은 유지합니다.
- 기존 게임 ZIP·저장·설정을 이어서 사용할 수 있습니다. 게임 파일을 다시 받을 필요는 없습니다.

### 알려진 문제

이번 수정은 음원 준비 처리에 대한 개선입니다. 미니게임천국2·테라·이노티아2·리듬스타 등에서 재생 중 발생하는 일부 끊김은 계속 확인 중입니다. 모든 게임의 소리 문제를 해결한 버전은 아니며, 지원 판정 파일 수는 기존 12개로 유지합니다.

### 업데이트 안내

공식 설치와 업데이트는 [Google Play](https://play.google.com/store/apps/details?id=com.valiostudio.wipix)에서 제공합니다. [테스트 참여 안내](https://github.com/hun99999/wipi-x-releases/blob/main/docs/TESTING.md)와 [문제 제보](https://github.com/hun99999/wipi-x-releases/issues)를 참고해 주세요.

### English

Reduced the work needed to prepare some SMAF sounds for playback. The natural-length calculation is more efficient while preserving sound duration and PCM output.

- Channel: Google Play closed testing, Alpha
- Version / build: 0.1.32 / 33
- Submitted for review: September 15, 2026 (KST)
- Status: Submitted for review; awaiting Play availability. Submission is distinct from confirmed availability.

Existing sound synthesis, playback speed, game progress and saving behavior are preserved. Existing game ZIPs, saves and settings remain compatible; game files do not need to be downloaded again.

This update improves sound preparation. Some interruptions during playback in MiniGame Paradise 2, Tera, Inotia 2 and Rhythm Star remain under investigation. It does not resolve every audio issue. The existing twelve Supported game files remain unchanged.

Install and update through [Google Play](https://play.google.com/store/apps/details?id=com.valiostudio.wipix). See [testing instructions](https://github.com/hun99999/wipi-x-releases/blob/main/docs/TESTING.md) and [report issues](https://github.com/hun99999/wipi-x-releases/issues).

## WIPI-X 0.1.31 — 짧은 소리의 끝부분 재생 개선

짧게 재생되는 소리의 마지막 부분이 남아 끝까지 출력되지 않던 문제를 수정했습니다. 이노티아2(KTF)의 타이틀에서 마지막 소리가 실제로 출력되는 것을 확인했습니다.

- 배포 채널: Google Play 비공개 테스트 Alpha
- 앱 버전 / 빌드 번호: 0.1.31 / 32
- 심사 요청일: 2026년 9월 15일 (한국 시간)
- 상태: Google Play 알파 테스터에게 제공 중 · 전체 출시. Play Console의 최근 업데이트 시각은 2026-09-15 오후 8:15 (한국 시간)입니다.

### 개선 및 수정

- 재생이 잠시 끊긴 뒤 마지막 짧은 소리가 끝까지 출력되지 않던 문제를 수정했습니다.
- 이노티아2(KTF) 타이틀의 재생 끝부분과 미니게임천국2(KTF)의 짧은 라운드·결과 전환을 확인했습니다.
- 기존 게임 ZIP·저장·설정을 이어서 사용할 수 있습니다. 게임 파일을 다시 받을 필요는 없습니다.

### 알려진 문제

이번 수정은 소리의 끝부분 재생에 대한 개선입니다. 이노티아2·미니게임천국2·테라·리듬스타 등에서 재생 중 발생하는 일부 끊김은 남아 있으며 계속 확인 중입니다. 모든 게임의 소리 품질이나 모든 기기의 실행을 보증하는 업데이트는 아닙니다. 지원 판정 파일 수는 기존 12개로 유지합니다.

### 업데이트 안내

공식 설치와 업데이트는 [Google Play](https://play.google.com/store/apps/details?id=com.valiostudio.wipix)에서 제공합니다. [테스트 참여 안내](https://github.com/hun99999/wipi-x-releases/blob/main/docs/TESTING.md)와 [문제 제보](https://github.com/hun99999/wipi-x-releases/issues)를 참고해 주세요.

### English

Fixed an issue that could leave the final portion of a short sound unplayed after a playback interruption. The ending of the Inotia 2 (KTF) title sound was checked on a device, along with a short MiniGame Paradise 2 (KTF) round and result transition.

- Channel: Google Play closed testing, Alpha
- Version / build: 0.1.31 / 32
- Submitted for review: September 15, 2026 (KST)
- Status: Available to Google Play Alpha testers; fully rolled out. Play Console lists the latest update as September 15, 2026 at 20:15 KST.

Existing game ZIPs, saves and settings remain compatible. Game files do not need to be downloaded again. The existing twelve Supported game files remain unchanged.

This update improves playback of sound endings. Some interruptions during playback in Inotia 2, MiniGame Paradise 2, Tera and Rhythm Star remain under investigation. It does not certify all audio quality or every device.

Install and update through [Google Play](https://play.google.com/store/apps/details?id=com.valiostudio.wipix). See [testing instructions](https://github.com/hun99999/wipi-x-releases/blob/main/docs/TESTING.md) and [report issues](https://github.com/hun99999/wipi-x-releases/issues).

## WIPI-X 0.1.30 — 이노티아2 캐시 메뉴 진입 개선

이노티아2(KTF)의 일반 CASH 메뉴에 들어갈 때 남아 있던 옛 요금·서버 연결 안내를 생략했습니다. 처음 열거나 다시 들어갈 때 원래 아이템 목록으로 바로 이동합니다.

- 배포 채널: Google Play 비공개 테스트 Alpha
- 앱 버전 / 빌드 번호: 0.1.30 / 31
- 심사 요청일: 2026년 9월 15일 (한국 시간)
- 상태: Google Play 알파 테스터에게 제공 중 · 전체 출시. Play Console의 최근 업데이트 시각은 2026년 9월 15일 오후 7:45 (한국 시간)입니다.

### 개선 및 수정

- 이노티아2(KTF): 일반 CASH 메뉴의 오래된 요금한도·서버 동의 안내를 생략해 아이템 목록으로 바로 진입합니다.
- 두 품목의 무료 확인창, 기본 ‘아니오’ 선택과 취소 동작은 유지합니다. 부활의 기도문·강화세트의 지급 및 저장 방식도 그대로입니다.
- 기존 게임 ZIP과 저장을 이어서 사용합니다. 게임 파일을 다시 받을 필요는 없습니다.

### 알려진 문제

일반 CASH 메뉴의 복원 범위는 부활의 기도문·강화세트 두 품목입니다. 과거 서버의 전체 상품 목록이나 별도 전멸 후 부활 구매가 모두 복원된 것은 아닙니다. 일부 게임의 소리 끊김·재생 끝부분과 장시간 동작은 계속 확인 중입니다. 지원 판정 파일 수는 기존 12개로 유지합니다.

### 업데이트 안내

공식 설치와 업데이트는 [Google Play](https://play.google.com/store/apps/details?id=com.valiostudio.wipix)에서 제공합니다. [테스트 참여 안내](https://github.com/hun99999/wipi-x-releases/blob/main/docs/TESTING.md)와 [문제 제보](https://github.com/hun99999/wipi-x-releases/issues)를 참고해 주세요.

### English

Inotia 2 (KTF) now skips obsolete charge and server-consent notices when opening the ordinary CASH menu. First and repeat visits go directly to the original item list.

- Channel: Google Play closed testing, Alpha
- Version / build: 0.1.30 / 31
- Submitted for review: September 15, 2026 (KST)
- Status: Available to Google Play Alpha testers; fully rolled out. Play Console lists the latest update as September 15, 2026 at 19:45 KST.

The free confirmation dialog, default No option and cancellation remain available. The two restored items use the existing grant and save behavior. Existing game ZIPs and saves remain compatible; game files do not need to be downloaded again.

Restoration covers the two ordinary CASH items, not the entire historical server catalogue or the separate party-wipe revival purchase. Audio interruptions, playback tails and longer sessions in some games remain under investigation. The existing twelve Supported game files remain unchanged.

Install and update through [Google Play](https://play.google.com/store/apps/details?id=com.valiostudio.wipix). See [testing instructions](https://github.com/hun99999/wipi-x-releases/blob/main/docs/TESTING.md) and [report issues](https://github.com/hun99999/wipi-x-releases/issues).

## WIPI-X 0.1.29 — 이노티아2 캐시 아이템 복원

이노티아 연대기2 KTF의 일반 CASH 메뉴에서 두 품목을 무료로 받을 수 있도록 복원한 Alpha 업데이트입니다.

배포 채널: Alpha
앱 버전/빌드: 0.1.29/code30
심사 요청일: 2026-09-15 (한국 시간)
배포 상태: Google Play 알파 테스터에게 제공 중 · 전체 출시. Play Console의 최근 업데이트 시각은 2026-09-15 오후 6:37 (한국 시간)입니다.

### 개선 및 수정

- **이노티아2 일반 CASH 메뉴:** 부활의 기도문·강화세트 두 품목을 무료로 받을 수 있습니다. 확인창은 기본 ‘아니오’이며 취소할 수 있습니다. 게임의 원래 가방 용량 확인과 아이템 지급·저장 처리를 사용합니다.
- **저장 복구 확인:** 실제 테스트 기기에서 취소·두 품목 지급·저장을 확인했고, 앱을 완전히 종료한 뒤 다시 실행해 기존 진행과 보유 아이템이 복구되는 것을 확인했습니다.

### 확인 범위와 알려진 문제

복원 범위는 위 두 품목이며 과거 서버의 전체 상품목록은 아닙니다. CASH 메뉴 진입 시 옛 요금 한도·서버 접속 안내가 남아 있지만 실제 결제나 외부 서비스 연결은 없습니다. 파티 전멸 뒤 나타나는 별도 부활 구매는 아직 연결 실패가 남아 있습니다.

이노티아2의 최종 지원 판정과 소리 확인은 진행 중입니다. 지원 판정 파일은 기존 12개로 유지합니다. 테라 타이틀의 소리 끊김·미니게임천국2의 짧은 소리 지연, 리듬스타·놈ZERO의 기존 소리 제보와 와일드프론티어2의 최종 소리 판정도 이번 업데이트의 해결 항목은 아닙니다.

기존 앱을 삭제하지 않고 Google Play에서 업데이트해 주세요. 게임 ZIP을 다시 받을 필요는 없으며 앱에는 게임 파일이 포함되지 않습니다. 새 버전 안내가 Play 제공보다 먼저 보일 수 있습니다.

테스트 참여: https://play.google.com/apps/testing/com.valiostudio.wipix
릴리즈 기록: https://github.com/hun99999/wipi-x-releases/releases

### English

This Alpha update restores two free items in the ordinary CASH menu of Inotia Chronicles 2 (KTF).

Channel: Alpha
Version/build: 0.1.29/code30
Submitted for review: September 15, 2026 (Korea time).
Status: Available to Google Play Alpha testers; fully rolled out. Play Console lists the latest update as September 15, 2026 at 18:37 KST.

### Improvements and fixes

- **Inotia 2 ordinary CASH menu:** The items 부활의 기도문 and 강화세트 are available free. Confirmation defaults to No and can be cancelled. The game retains its original inventory-capacity checks, item-grant and save handling.
- **Save recovery:** On the test device, checked cancellation, both item grants and saving, then fully restarted the app and confirmed recovery of existing progress and owned items.

### Scope and known issues

This restores the two named items, not the complete historical server catalogue. Old payment-limit and server-connection notices remain at CASH-menu entry, but this path makes no real payment or external service connection. The separate revival purchase shown after a party wipe still fails to connect.

Inotia 2's final Supported status and audio checks remain in progress. The existing twelve Supported game files are unchanged. Terra title-screen stutter, brief MiniGame Paradise 2 audio delays, existing Rhythm Star and Nom ZERO audio reports, and the final Wild Frontier 2 audio judgment remain follow-up work.

Update through Google Play without uninstalling. Existing game ZIPs remain usable and no games are bundled. The in-app update notice may appear before Play offers this version.

Join testing: https://play.google.com/apps/testing/com.valiostudio.wipix
Release history: https://github.com/hun99999/wipi-x-releases/releases

## WIPI-X 0.1.28 — 게임 호환성과 실행 성능 개선

0.1.22 이후의 게임 호환성과 실행 성능 개선을 묶은 Alpha 업데이트입니다.

배포 채널: Alpha
앱 버전/빌드: 0.1.28/code29
심사 요청일: 2026-09-15 (한국 시간)
배포 상태: Google Play 알파 테스터에게 제공 중 · 전체 출시. Play Console의 최근 업데이트 시각은 2026-09-15 오후 3:58 (한국 시간)입니다.

### 개선 및 수정

- **지원 게임 추가:** 테일즈위버 이스핀·막시민·루시안칼츠편 LGT의 정확한 검증 파일을 앱에서 ‘지원됨’으로 표시합니다. 기존 9개를 포함해 지원 판정 파일은 12개입니다.
- **미니게임천국2:** 화면 갱신이 요청한 간격보다 늦어지던 타이머 처리를 수정했습니다. 대표 라운드에서 화면 변화와 조작, 최고 기록의 저장·앱 재실행 복구를 확인했습니다.
- **실행 성능:** 일부 게임에서 반복되는 처리 비용을 줄이고, 짧은 처리 지연 뒤 게임 시간 진행을 회복하도록 보완했습니다. 성능 차이는 게임과 기기에 따라 다릅니다.
- **이노티아 연대기2 KTF:** 시작과 새 게임 진입을 막던 호환 문제를 수정했습니다. 도입부·전투·주요 메뉴와 첫 저장 후 앱을 완전히 종료하고 다시 실행했을 때의 진행 복구를 확인했습니다. 이 게임의 최종 지원 판정은 아직 검증 중입니다.

### 확인 범위와 알려진 문제

정확한 검증 파일을 대상으로 대표 기능·조작·화면과 저장 복구를 확인했습니다. 모든 Android 기기나 다른 판본, 후반·엔딩까지 확인한 결과는 아닙니다.

테라의 타이틀 소리 끊김과 미니게임천국2의 일부 짧은 소리 지연은 남아 있습니다. 이노티아2 CASH 메뉴의 오프라인 연결 실패와 일부 소리 확인도 후속 작업입니다. 와일드프론티어2의 최종 소리 판정, 기존 리듬스타의 소리 간격·놈ZERO의 배경음 겹침 제보도 해결 완료로 처리하지 않았습니다.

기존 앱을 삭제하지 않고 Google Play에서 업데이트해 주세요. 게임 ZIP을 다시 받을 필요는 없으며 앱에는 게임 파일이 포함되지 않습니다. 새 버전 안내가 Play 제공보다 먼저 보일 수 있습니다.

테스트 참여: https://play.google.com/apps/testing/com.valiostudio.wipix
릴리즈 기록: https://github.com/hun99999/wipi-x-releases/releases

### English

This Alpha update combines game compatibility and execution performance improvements made since 0.1.22.

Channel: Alpha
Version/build: 0.1.28/code29
Submitted for review: September 15, 2026 (Korea time).
Status: Available to Google Play Alpha testers; fully rolled out. Play Console lists the latest update as September 15, 2026 at 15:58 KST.

### Improvements and fixes

- **Supported games:** The exact verified LGT files for TalesWeaver: Ispin, Maximin and Lucian now appear as Supported. Together with the previous nine, twelve game files have this status.
- **MiniGame Paradise 2:** Fixed timer handling that delayed screen updates beyond the requested interval. Representative rounds covered screen changes, controls, and best-score recovery after fully restarting the app.
- **Execution performance:** Reduced recurring processing costs in some games and improved game-time recovery after brief processing delays. Results vary by game and device.
- **Inotia Chronicles 2 (KTF):** Fixed compatibility issues blocking startup and new-game entry. Checked the prologue, battles, main menus, and progress recovery after the first save and a full app restart. Final Supported status is still under verification.

### Scope and known issues

Checks cover representative features, controls, display and save recovery for exact game files. They do not certify every Android device, different editions, late-game content or endings.

Title-screen audio stutter in Terra and some short audio delays in MiniGame Paradise 2 remain. The offline connection failure in Inotia 2's CASH menu and further audio checks are follow-up work. Wild Frontier 2 still awaits a final audio judgment; previously reported Rhythm Star audio gaps and overlapping music in Nom ZERO remain unresolved.

Update through Google Play without uninstalling the existing app. Existing game ZIPs remain usable and no games are bundled. The in-app update notice may appear before Play offers the new version.

Join testing: https://play.google.com/apps/testing/com.valiostudio.wipix
Release history: https://github.com/hun99999/wipi-x-releases/releases

## WIPI-X 0.1.22 — 호환·저장·터치 조작 개선

0.1.11 이후의 게임별 호환 수정과 저장 보호, 터치 조작·화면 배치 개선을 하나의 Alpha 업데이트로 제공합니다.

배포 채널: Alpha
앱 버전/빌드: 0.1.22/code23
심사 요청일: 2026-09-15 (한국 시간)
배포 상태: Google Play 알파 테스터에게 제공 중 · 전체 출시. Play Console의 최근 업데이트 시각은 2026-09-15 오전 9:13 (한국 시간)입니다.

### 개선 및 수정

- **지원 게임 추가:** 정확한 검증 파일의 이노티아 연대기 KTF, 검은방2·오셔너스·와일드프론티어1 LGT를 앱에서 ‘지원됨’으로 표시합니다. 기존 5개를 포함해 지원 판정 파일은 9개입니다.
- **저장 보호:** 게임 안에서 저장한 뒤 Android 홈 화면으로 이동하는 등 앱이 백그라운드로 전환될 때 저장 내용을 기기에 반영하도록 보완했습니다. 게임 내 저장과 정상 종료, 필요한 저장 백업을 계속 사용해 주세요.
- **게임별 기능:** 이노티아 KTF와 테일즈위버 막시민편의 새 저장 날짜, 검은방2의 키워드·프로필 열쇠 해금, 오셔너스의 소리와 CASH 상품, 와일드프론티어1·2의 로컬 아이템 기능을 보완했습니다. 실제 외부 결제나 통신사 청구는 발생하지 않습니다.
- **추가 호환 보완:** 와일드프론티어2의 실행 파일 처리와 테일즈위버 이스핀·막시민·루시안칼츠편의 문자·대사·메뉴·소리 및 이미지 처리를 수정했습니다. 이 게임들의 앱 내 최종 지원 판정은 아직 검증 대기입니다.
- **터치 조작:** 한 손가락으로 키를 누른 상태에서 다른 손가락이 닿은 뒤, 먼저 누른 손가락을 다른 키로 옮길 때 입력이 반영되지 않던 문제를 수정했습니다.
- **화면 배치:** 일부 기기의 넓은 뒤로 가기 제스처 영역 때문에 게임·라이브러리·설정 화면에 과도한 좌우 여백이 생기거나 양손 키패드 배치가 제한되던 문제를 수정했습니다. 게임의 원래 비율과 필수 시스템 영역은 유지합니다.
- **KTF 화면 처리:** 화면 복사에 쓰는 임시 메모리 할당을 줄였습니다. 일부 구간의 끊김을 모두 해결한 것은 아니며 게임·기기별 성능을 계속 확인합니다.

### 확인 범위와 알려진 문제

지원 판정은 정확한 게임 파일의 대표 실행·조작·화면·소리·저장 및 앱 재실행 복구 확인에 근거합니다. 다른 판본이나 모든 Android 기기, 후반·엔딩까지 확인한 결과는 아닙니다. 터치와 화면 배치는 자동 검사 및 테스트기기 확인을 포함하며, 제보된 ZTE 기기와 S24 Ultra의 Android 16에서는 아직 직접 확인하지 못했습니다.

미니게임천국2의 속도·입력 지연과 테라의 타이틀 소리 끊김은 확인 중입니다. 와일드프론티어2의 실제 소리 판정과 테일즈위버 3편의 최종 지원 등록도 남아 있습니다. 이전에 안내한 리듬스타의 소리 간격, 놈ZERO의 배경음 겹침 제보 등은 해결 완료로 처리하지 않았습니다.

기존 앱을 삭제하지 않고 Google Play에서 업데이트해 주세요. 게임 ZIP을 다시 받을 필요는 없으며, 앱에는 게임 파일이 포함되지 않습니다. 앱의 새 버전 안내가 Play 제공보다 먼저 보일 수 있습니다.

테스트 참여: https://play.google.com/apps/testing/com.valiostudio.wipix
릴리즈 기록: https://github.com/hun99999/wipi-x-releases/releases

### English

This Alpha update combines game compatibility fixes, save protection, touch input and screen layout improvements made since 0.1.11.

Channel: Alpha
Version/build: 0.1.22/code23
Submitted for review: September 15, 2026 (Korea time).
Status: Available to Google Play Alpha testers; fully rolled out. Play Console lists the latest update as September 15, 2026 at 09:13 KST.

### Improvements and fixes

- **Supported games:** The exact verified files for Inotia Chronicles (KTF), Black Room 2, Oceanus and Wild Frontier 1 (LGT) now appear as Supported. Together with the previous five, nine game files have this status.
- **Save protection:** In-game saves are written to device storage when the app moves to the background, such as when returning to Android Home. Continue saving inside the game, exiting normally and exporting backups when needed.
- **Game features:** Improved new save dates in Inotia (KTF) and TalesWeaver: Maximin, keyword and profile key unlocks in Black Room 2, audio and CASH items in Oceanus, and local item features in Wild Frontier 1 and 2. No external payment or carrier billing occurs.
- **Additional compatibility:** Fixed executable handling in Wild Frontier 2 and text, dialogue, menu, audio and image handling in TalesWeaver: Ispin, Maximin and Lucian. These games still await final Supported status in the app.
- **Touch controls:** Fixed missing key changes when the first finger slides to another key after a second finger has touched the keypad.
- **Screen layout:** Fixed excessive side margins and restrictions on split keypad layouts caused by wide back-gesture areas on some devices. This covers the game, library and settings screens while retaining the original game aspect ratio and required system areas.
- **KTF rendering:** Reduced temporary memory allocation during screen copies. This does not resolve every stutter; game and device performance checks continue.

### Scope and known issues

Supported status applies to exact game files checked for representative execution, controls, display, audio, saving and recovery after restarting the app. It does not certify different editions, every Android device, late-game content or endings. Touch and layout checks include automated tests and test devices; the reported ZTE device and S24 Ultra running Android 16 have not been tested directly.

Investigations continue for MiniGame Paradise 2 speed and input latency, and title-screen audio stutter in Terra. Wild Frontier 2 still awaits the final listening judgment, and the three TalesWeaver editions await final support registration. Previously reported issues, including Rhythm Star audio gaps and overlapping music in Nom ZERO, remain unresolved.

Update through Google Play without uninstalling the existing app. Existing game ZIPs remain usable and no games are bundled. The in-app update notice may appear before Play offers the new version.

Join testing: https://play.google.com/apps/testing/com.valiostudio.wipix
Release history: https://github.com/hun99999/wipi-x-releases/releases

## WIPI-X 0.1.11 — 호환 게임 추가와 소리·날짜 수정

붕어빵타이쿤3 KTF와 레전드오브마스터 LGT의 대표 기능 검증을 지원 게임 목록에 반영하고, 일부 게임 음악의 음 종료와 붕어빵타이쿤3의 날짜 처리를 수정했습니다.

배포 채널: Alpha
앱 버전/빌드: 0.1.11/code12
심사 요청일: 2026-09-13 (한국 시간)
배포 상태: 심사 요청 완료 · 제공 대기. 현재 제공이 확인된 버전은0.1.10입니다.

### 개선 및 수정

- 붕어빵타이쿤3 KTF와 레전드오브마스터 LGT를 지원 게임으로 표시합니다. 대표 플레이·주요 기능·소리·저장 및 재실행 복구를 확인한 정확한 게임 파일에 적용됩니다.
- 일부 SMAF 음악에서 같은 음을 반복한 뒤 종료 신호가 잘못 전달되어 음이 길게 남는 문제를 수정했습니다.
- 붕어빵타이쿤3 KTF에서 새로 획득하는 장사일기 기록에 기기의 날짜를 사용합니다. 이미 저장된 과거 기록은 유지합니다.

### 확인 범위와 알려진 한계

지원 판정은 대표 기능 검증 범위이며 전체 스토리·후반·엔딩·장시간 플레이 검증을 뜻하지 않습니다. 이번 소리 수정은 모든 게임의 음질·성능이나 리듬스타의 별도 무음 간격 문제를 해결했다는 뜻은 아닙니다.

테스트 참여: https://play.google.com/apps/testing/com.valiostudio.wipix
릴리즈 기록: https://github.com/hun99999/wipi-x-releases/releases

### English

This update adds Bungeoppang Tycoon 3 (KTF) and Legend of Master (LGT) to the supported game list after representative feature checks, and fixes note release in some game music and the date used by Bungeoppang Tycoon 3.

Channel: Alpha
Version/build: 0.1.11/code12
Submitted for review: September 13, 2026 (Korea time).
Status: Submitted; Play availability is pending. Version 0.1.10 is currently confirmed available.

### Improvements and fixes

- Bungeoppang Tycoon 3 (KTF) and Legend of Master (LGT) appear as supported for the exact game files verified through representative gameplay, key features, audio, saving and recovery after relaunch.
- Fixed some repeated SMAF notes continuing too long because their note-off events were assigned to an older fading voice.
- New business diary achievements in Bungeoppang Tycoon 3 (KTF) use the device date. Previously saved records are preserved.

### Scope and limitations

The support status covers representative feature checks, not complete stories, late-game content, endings or extended play sessions. The sound fix does not establish full audio compatibility for every game or resolve Rhythm Star's separate audio-gap issue.

Join testing: https://play.google.com/apps/testing/com.valiostudio.wipix
Release history: https://github.com/hun99999/wipi-x-releases/releases

## WIPI-X 0.1.10 — 축구·야구·메이플 호환 개선

2010슈퍼사커·2010프로야구의 로컬 G포인트 기능과 메이플스토리 도적편의 화면·속도 문제를 개선했습니다. 기존 0.1.9의 새 키패드 스킨과 플레이 기록도 함께 사용할 수 있습니다.

- **배포 채널:** Google Play 비공개 테스트(Alpha)
- **앱 버전 / 빌드 번호:** 0.1.10 / 11
- **심사 요청일:** 2026-09-12 (한국 시간)
- **Play 상태:** 심사 요청 완료 · 제공 대기. GitHub 기록을 먼저 게시하며, Play에 업데이트가 표시되기까지 시간이 걸릴 수 있습니다. 현재 제공이 확인된 버전은 0.1.9입니다.

### 개선 및 수정

- **2010슈퍼사커(LGT):** G포인트 구매가 실패하던 문제를 수정했습니다. 게임 안에서 선택한 수량의 포인트를 로컬로 반영하고 정상 저장·재실행으로 이어갑니다. 실제 통신사 청구나 외부 결제는 발생하지 않습니다.
- **2010프로야구(LGT):** G포인트 충전 오류를 수정했습니다. 로컬 충전 포인트로 아이템을 사용하고, 선수 능력치와 남은 포인트를 정상 저장·재실행으로 유지할 수 있습니다.
- **메이플스토리 도적편(KTF):** 메뉴를 열 때의 이미지 크기 제한, 작은 수련 맵에서 화면이 위아래로 흔들리는 문제, 게임 속도 ‘상’에서 지나치게 빨라지는 동작을 보정했습니다. ‘중’ 설정과 앱의 배속 선택은 유지합니다.
- **지원 판정:** 정확한 검증 파일의 2010슈퍼사커·2010프로야구·메이플스토리 도적편을 앱에서 ‘지원됨’으로 표시합니다. 제목이 같아도 다른 통신사나 다른 파일에는 같은 판정을 적용하지 않습니다.
- **레전드오브마스터(LGT):** 새 게임 대사가 비거나 읽기 전에 넘어가는 문제를 수정하고, 메뉴 목록을 읽고 비우는 처리 누락을 보완했습니다. 이 게임은 계속 검증 대기 상태입니다.

### 지원 범위와 알려진 문제

이번 지원 판정은 대표 플레이, 주요 기능과 정상 저장·재실행 확인에 근거합니다. 장기 플레이·후반·엔딩, 모든 기기의 일정한 속도·소리 품질을 보장하지 않습니다. 축구·야구의 일부 구간에는 프레임 지연과 소리 간격이 남을 수 있고, 온라인 랭킹·선물·서버 백업은 지원 범위 밖입니다. 메이플의 속도 보정은 원래 피처폰과 같은 속도임을 확인한 결과는 아닙니다.

레전드오브마스터의 이전 메뉴 오류는 제보 당시와 같은 버튼 순서를 확보하지 못했습니다. 대사 개선과 제한된 메뉴 보완을 전체 플레이 완료로 안내하지 않습니다.

리듬스타(KTF) 메인 화면의 소리 간격, 놈ZERO(LGT)의 배경음 겹침 제보, 하이브리드1(LGT)의 일부 기기 속도 저하와 게임 전환 후 간헐적 입력 무반응은 계속 확인 중입니다. 입력이 멈추면 게임을 정상 종료하고 앱을 완전히 종료한 뒤 다시 실행해 주세요.

기존 앱을 삭제하지 않고 같은 Google 계정으로 업데이트해 주세요. 이번 호환 교정은 앱 실행에 적용하며 기존 게임 ZIP을 다시 받을 필요가 없습니다. 앱에는 게임 파일이 포함되지 않습니다. 앱의 업데이트 안내가 Play 반영보다 먼저 보일 수 있습니다.
[테스트 참여 안내](https://github.com/hun99999/wipi-x-releases/blob/main/docs/TESTING.md) · [문제 제보](https://github.com/hun99999/wipi-x-releases/issues/new/choose)

### English

WIPI-X 0.1.10 (build 11) improves local G-point features in 2010 Super Soccer and 2010 Pro Baseball, plus menus, camera movement and the high-speed setting in MapleStory: Thief Edition. It retains the keypad skins and play-time history introduced in 0.1.9.

- **Channel:** Google Play closed test (Alpha).
- **Submitted for review:** September 12, 2026 (Korea time).
- **Play status:** Submitted; availability is pending. These notes precede Play availability. Version 0.1.9 is currently confirmed available.

- **2010 Super Soccer (LGT):** Fixed failed G-point purchases. Selected points are granted locally and persist through normal saving and relaunching, without carrier billing or external payment.
- **2010 Pro Baseball (LGT):** Fixed G-point charging. Locally granted points can be spent on items, with player stats and remaining points preserved by normal saving and relaunching.
- **MapleStory: Thief Edition (KTF):** Fixed the menu image-size limit and camera shaking on a small training map; constrained excessive speed under the game's High setting. The Medium setting and app speed selection remain available.
- **Support status:** The exact verified files for those three games are marked Supported in the app. This does not cover different files or carrier editions with the same title.
- **Legend of Master (LGT):** Fixed empty dialogue or dialogue advancing before it could be read, and completed missing menu-list read/clear handling. The game remains pending verification.

Support decisions cover representative play, main features and normal save/relaunch checks. They do not certify long sessions, late-game content, endings, or consistent speed and audio quality on every device. Soccer and baseball may still show frame delays or audio gaps; online rankings, gifts and server backups are outside scope. MapleStory's speed adjustment has not been validated against original feature-phone timing.

The exact button sequence behind the previously reported Legend of Master menu error remains unavailable. Dialogue improvements and limited menu fixes do not establish full-game compatibility.

Investigations continue for main-screen audio gaps in Rhythm Star (KTF), reported overlapping music in Nom ZERO (LGT), low speed on some devices in Hybrid 1 (LGT), and intermittent input loss after switching games. If input stops, exit the game normally, fully close the app, and reopen it.

Update through Google Play using the same account without uninstalling the app. The compatibility corrections apply during execution, so existing game ZIPs do not need to be downloaded again. No games are bundled with the app. The in-app notice may appear before Play offers the update.
See the [testing guide](https://github.com/hun99999/wipi-x-releases/blob/main/docs/TESTING.md#english) and [support guide](https://github.com/hun99999/wipi-x-releases/blob/main/SUPPORT.md).

## WIPI-X 0.1.9 — 키패드 스킨·플레이 기록·조작 개선

피처폰·레트로 키패드의 새 스킨과 게임별 플레이 기록을 추가하고, 화면 배치와 키 입력 진동을 개선했습니다. 키패드 오버레이 불투명도는 0%까지 조절할 수 있습니다.

- **배포 채널:** Google Play 비공개 테스트(Alpha)
- **앱 버전 / 빌드 번호:** 0.1.9 / 10
- **심사 요청일:** 2026-09-12 (한국 시간)
- **Play 상태:** 심사 요청 완료 · 제공 대기. GitHub 기록을 먼저 게시하며, Play에서 업데이트가 표시되기까지 시간이 걸릴 수 있습니다. 현재 제공이 확인된 버전은 0.1.8입니다.

### 새로운 기능과 개선

- **새 스킨 4종:** 피처폰용 초콜릿 블랙·블루블랙 슬라이더·롤리팝 밀크와 레트로 그래파이트를 추가했습니다. 숫자키에는 작은 한글·영문 표기를 함께 제공합니다. 개별 버튼 그림을 배치하는 방식으로 화면 크기에 대응하며, 기존 공통·게임별 키매핑을 사용합니다.
- **플레이 기록:** 전체·게임별 누적 시간과 최근 7일의 일별 막대 그래프를 확인할 수 있습니다. 기록 목록에 게임 아이콘·제목을 표시하고 해당 게임의 상세 기록으로 연결합니다. 이번 버전부터 기록되는 플레이 시간을 기기 안에 저장합니다.
- **더 큰 가로 게임 화면:** 내장 레트로 스킨의 가로 배치에서 불필요한 상하 여백을 줄이고, 버튼 영역을 고려해 게임을 원래 비율로 확대합니다. 게임 비율·기기 화면·선택한 배치에 따라 여백은 남을 수 있습니다.
- **피처폰 키패드 간격:** 게임 표시 크기를 유지하면서 메뉴·통화·취소 키와 숫자키 사이의 간격을 다듬고, 접었을 때 나타나는 방향키·OK 한 줄을 중앙에 맞췄습니다.
- **키 입력 진동:** 설정이 켜져 있어도 피처폰·레트로 화면 키에서 진동이 나오지 않던 문제를 수정했습니다. 지원되는 짧은 진동 효과를 사용하고, 필요한 기기에는 짧은 기본 진동을 적용합니다. 키 입력 진동과 게임 진동은 별도 설정입니다.
- **불투명도 0–100%:** 오버레이 편집의 최저값을 20%에서 0%로 넓혔습니다. 0%에서는 버튼 그림이 보이지 않아도 해당 위치의 터치 입력은 유지됩니다. 방향키·숫자키 영역을 각각 조절하고 저장할 수 있습니다.
- **설정과 글자:** 설정 항목을 보기 쉽게 정리하고 일반 UI에 Pretendard를 적용했습니다. 기존 도트 영역과 앱의 기본 디자인 방향은 유지합니다.
- **USB 디버깅 안내:** 출시 앱에서 USB 디버깅이 켜진 것으로 감지되면 끈 뒤 다시 확인하도록 안내합니다. 기기 설정을 자동으로 변경하지 않으며, 운영체제가 상태를 제공하지 않는 경우에는 감지되지 않을 수 있습니다.

### 지원 범위와 알려진 문제

새 내장 스킨은 버튼 부품을 분리해 그리지만, 버튼마다 자유롭게 위치·크기를 편집하는 기능은 이번 버전에 포함되지 않습니다. 기존 오버레이 그룹 편집과 키매핑을 사용할 수 있습니다. 스킨 이미지는 화면에 필요한 해상도로 읽고 재사용하며, 이 개선이 모든 게임·기기의 일정한 성능을 보장하지는 않습니다.

리듬스타(KTF) 메인 화면의 소리 간격, 놈ZERO(LGT)의 배경음 겹침 제보, 하이브리드1(LGT)의 일부 기기 속도 저하와 게임 전환 후 간헐적 입력 무반응은 계속 확인 중입니다. 입력이 멈추면 게임을 정상 종료하고 앱을 완전히 종료한 뒤 다시 실행해 주세요.

Play 반영 뒤 기존 앱을 삭제하지 않고 같은 Google 계정으로 업데이트해 주세요. 앱의 업데이트 안내가 Play 반영보다 먼저 보일 수 있습니다. Play에 업데이트 버튼이 아직 없으면 이후 다시 확인해 주세요.
[테스트 참여 안내](https://github.com/hun99999/wipi-x-releases/blob/main/docs/TESTING.md) · [문제 제보](https://github.com/hun99999/wipi-x-releases/issues/new/choose)

### English

WIPI-X 0.1.9 (build 10) adds phone and retro keypad skins and per-game play-time history, improves game layout and key haptics, and extends touch-overlay opacity down to 0%.

- **Channel:** Google Play closed test (Alpha).
- **Submitted for review:** September 12, 2026 (Korea time).
- **Play status:** Submitted; availability is pending. These notes are published before Play availability. Version 0.1.8 is currently confirmed available.

- **Four new skins:** Chocolate Black, Blueblack Slider and Lollipop Milk phone keypads, plus Retro Graphite. Number keys include small Korean and English legends. Separate button artwork adapts to different screen sizes and uses existing global/per-game mappings.
- **Play-time history:** Overall and per-game totals, daily bars for the last seven days, and a history list with each game's icon and title linked to its details. Play time recorded from this version onward stays on the device.
- **Larger landscape game display:** Built-in retro layouts reduce unnecessary vertical space and fit the game at its original aspect ratio around the controls. Some spacing can remain depending on the game, screen and chosen layout.
- **Phone keypad spacing:** Improved separation between menu/call/cancel keys and the number pad without shrinking the game display, and centered the folded direction/OK row.
- **Key haptics:** Fixed enabled key feedback producing no vibration on phone and retro controls. Uses a supported short effect or a brief fallback vibration. Key feedback and in-game vibration remain separate settings.
- **0–100% opacity:** Reduced the overlay editor's minimum from 20% to 0%. Fully transparent buttons remain touchable. Direction and number-pad groups can be adjusted and saved separately.
- **Settings and text:** Clearer settings organization and Pretendard for general UI text, retaining the existing pixel-text areas and overall app design.
- **USB debugging notice:** The release app asks users to disable USB debugging when it detects it as enabled, then check again. It never changes the device setting automatically. Detection may be unavailable when the operating system hides the status.

The new built-in skins use separate button artwork; moving and resizing each individual button freely is not included in this release. Existing overlay-group editing and key mapping remain available. Skin images are decoded at bounded resolutions and reused; performance still varies by game and device.

Investigations continue for main-screen audio gaps in Rhythm Star (KTF), reported overlapping music in Nom ZERO (LGT), low speed on some devices in Hybrid 1 (LGT), and intermittent input loss after switching games. If input stops, exit the game normally, fully close the app, and reopen it.

Update through Google Play using the same account without uninstalling the existing app. The in-app notice may appear before the update is available in Play; check again later if Play does not yet offer it.
See the [testing guide](https://github.com/hun99999/wipi-x-releases/blob/main/docs/TESTING.md#english) and [support guide](https://github.com/hun99999/wipi-x-releases/blob/main/SUPPORT.md).

## WIPI-X 0.1.8 — 피처폰 키패드 배치 수정

세로 피처폰 키패드에서 왼쪽으로 치우쳤던 십자키를 중앙으로 돌리고, 기능키를 양쪽 가장자리에 나누어 배치했습니다.

- **배포 채널:** Google Play 비공개 테스트(Alpha)
- **앱 버전 / 빌드 번호:** 0.1.8 / 9
- **심사 요청일:** 2026-09-12 (한국 시간)
- **Play 상태:** 심사 요청 완료 · 제공 대기. GitHub 기록을 먼저 게시하며, Play에서 업데이트가 표시되기까지 시간이 걸릴 수 있습니다.

### 수정 사항

- **중앙 십자키:** 기본 세로 피처폰 배치에서 방향키와 OK를 화면 중앙에 맞췄습니다. 클래식과 플랫 키패드에 함께 적용됩니다.
- **양쪽 기능키:** 왼쪽 가장자리에는 좌메뉴·통화를 위아래로, 오른쪽 가장자리에는 우메뉴·취소를 위아래로 배치했습니다. 십자키와의 간격을 확보합니다.
- **접기와 게임 화면:** 접었을 때의 기능키 한 줄과 숫자키, 작은 하단 여백은 유지합니다. 기본 배율의 게임 표시 크기와 비율도 유지됩니다.

레트로 스킨·공통/게임별 키매핑과 제노니아 저장 날짜 수정은 0.1.7의 개선을 이어갑니다. 앱 전체 디자인과 게임 엔진은 이번 배치 수정에서 변경하지 않았습니다.

### 알려진 문제와 업데이트

리듬스타(KTF) 메인 화면의 소리 간격, 놈ZERO(LGT)의 배경음 겹침 제보, 하이브리드1(LGT)의 일부 기기 속도 저하와 게임 전환 후 간헐적 입력 무반응은 계속 확인 중입니다. 입력이 멈추면 게임을 정상 종료하고 앱을 완전히 종료한 뒤 다시 실행해 주세요.

Play 반영 뒤 기존 앱을 삭제하지 않고 같은 Google 계정으로 업데이트해 주세요. 앱의 업데이트 안내가 Play 반영보다 먼저 보일 수 있습니다. Play에 업데이트 버튼이 아직 없으면 이후 다시 확인해 주세요.
[테스트 참여 안내](https://github.com/hun99999/wipi-x-releases/blob/main/docs/TESTING.md) · [문제 제보](https://github.com/hun99999/wipi-x-releases/issues/new/choose)

### English

WIPI-X 0.1.8 (build 9) corrects the portrait phone keypad: the D-pad is centered again, with function keys placed at the left and right edges.

- **Channel:** Google Play closed test (Alpha).
- **Submitted for review:** September 12, 2026 (Korea time).
- **Play status:** Submitted; availability is pending. These GitHub notes are published before Play availability, so the update may not appear in Play yet.

- **Centered D-pad:** Direction keys and OK are centered in the default portrait layout, for both Classic and Flat keypads.
- **Function keys at the edges:** Left Menu above Call on the left; Right Menu above Cancel on the right, with space between each group and the D-pad.
- **Folding and game display:** Keeps the folded function-key row, number keys and small bottom spacing. The game display size and aspect ratio at the default scale are preserved.

The retro skins, shared global/per-game mappings and Zenonia save-date fixes from 0.1.7 remain included. This layout correction does not change the overall app design or game engine.

Investigations continue for main-screen audio gaps in Rhythm Star (KTF), reported overlapping music in Nom ZERO (LGT), low speed on some devices in Hybrid 1 (LGT), and intermittent input loss after switching games. If input stops, exit the game normally, fully close the app, and reopen it.

Update through Google Play using the same account, without uninstalling the existing app. The in-app notice may appear before the update is available in Play; check again later if Play does not yet offer an update.
See the [testing guide](https://github.com/hun99999/wipi-x-releases/blob/main/docs/TESTING.md#english) and [support guide](https://github.com/hun99999/wipi-x-releases/blob/main/SUPPORT.md).

## WIPI-X 0.1.7 — 레트로 스킨·키패드·저장 날짜 개선

레트로 게임기 모양의 화면 컨트롤러를 추가하고, 피처폰 키패드의 배치와 접기 기능을 개선했습니다. 제노니아 시리즈의 저장 슬롯 표시와 저장 날짜도 바로잡았습니다.

- **배포 채널:** Google Play 비공개 테스트(Alpha)
- **앱 버전 / 빌드 번호:** 0.1.7 / 8
- **심사 요청일:** 2026-09-12 (한국 시간)
- **Play 상태:** 심사 요청 완료 · 제공 대기. GitHub 기록을 먼저 게시하며, Play에서 업데이트가 표시되기까지 시간이 걸릴 수 있습니다.

### 새로운 기능과 개선

- **레트로 화면 컨트롤러:** WIPI-X 16-bit 실버 스킨과 지원 형식의 `.deltaskin` 가져오기를 제공합니다. 스킨 선택 화면에서 그림 버튼을 눌러 키매핑으로 바로 이동할 수 있습니다.
- **공유 키매핑:** 화면 컨트롤러는 기존 공통·게임별 게임패드 매핑을 그대로 사용합니다. 실제 컨트롤러를 연결하지 않아도 화면에서 설정할 수 있습니다.
- **피처폰 키패드:** 좌메뉴·우메뉴·통화·취소 버튼의 외형을 줄이고, 십자키와 떨어진 오른쪽에 모았습니다. 하단 여백도 조정해 작은 화면의 불필요한 빈 공간을 줄였습니다.
- **십자키 접기:** 오른쪽 위 화살표로 접으면 기능키 네 개가 한 줄로 정리되고 숫자키는 유지됩니다. 확보한 공간에 게임 화면을 비율에 맞춰 배치하며, 게임 크기를 줄이지 않고 여유가 있을 때만 방향키·OK를 한 줄로 표시합니다.
- **저장 슬롯과 날짜:** 제노니아1·2·3(LGT)에서 새로 저장할 때 실제 저장 날짜와 시간이 기록되도록 수정했습니다. 저장이 있는데 EMPTY로 보이던 제노니아2의 슬롯 표시도 수정했습니다. 기존 슬롯의 잘못된 날짜는 게임에서 다시 저장하면 갱신됩니다.
- **작은 화면과 성능:** 스킨 이미지는 필요한 크기로 읽고 재사용합니다. 키패드가 숨겨진 상태에서는 스킨을 불러오지 않으며, 큰 글자에서 매핑 설명이 잘리던 부분도 다듬었습니다.

### 지원 범위와 알려진 문제

외부 Delta 스킨은 SNES·NES·GB·GBC·GBA의 디지털 버튼과 지원되는 PNG/PDF 표현을 대상으로 합니다. DS 다중 화면, 아날로그 입력, 일부 효과와 표현은 지원하지 않습니다. 한 장으로 합쳐진 외부 스킨의 개별 버튼 위치·크기 편집도 포함하지 않습니다.

제노니아 저장 날짜 수정은 확인한 LGT 판본에 적용됩니다. 게임 내부 저장을 사용하며 임의 시점 저장 기능이 추가된 것은 아닙니다. 앱 전체 디자인은 유지합니다.

리듬스타(KTF) 메인 화면의 소리 간격, 놈ZERO(LGT)의 배경음 겹침 제보, 하이브리드1(LGT)의 일부 기기 속도 저하와 게임 전환 후 간헐적 입력 무반응은 계속 확인 중입니다. 입력이 멈추면 게임을 정상 종료하고 앱을 완전히 종료한 뒤 다시 실행해 주세요. 게임·기기·장면에 따른 성능 차이가 있으며 전체 진행이나 모든 기기의 호환을 보증하지 않습니다.

### 업데이트와 문제 제보

Play 반영 뒤 기존 앱을 삭제하지 않고 같은 Google 계정으로 업데이트해 주세요. 앱의 업데이트 안내가 Play 반영보다 먼저 보일 수 있습니다. Play에 업데이트 버튼이 아직 없으면 이후 다시 확인해 주세요.
[테스트 참여 안내](https://github.com/hun99999/wipi-x-releases/blob/main/docs/TESTING.md) · [문제 제보](https://github.com/hun99999/wipi-x-releases/issues/new/choose)

### English

WIPI-X 0.1.7 (build 8) adds retro on-screen controller skins, improves the feature-phone keypad layout and folding controls, and corrects save-slot dates in the Zenonia series.

- **Channel:** Google Play closed test (Alpha).
- **Submitted for review:** September 12, 2026 (Korea time).
- **Play status:** Submitted; availability is pending. These GitHub notes are published before Play availability, so the update may not appear in Play yet.

- **Retro controller skins:** Includes WIPI-X 16-bit Silver and import of supported `.deltaskin` files. Tap a button in the skin editor to open its mapping.
- **Shared mappings:** On-screen controls use the existing global and per-game controller mappings. A physical controller is not required to edit them.
- **Phone keypad:** Smaller menu/call/cancel button artwork, grouped to the right with separation from the D-pad, and reduced excess bottom spacing on small screens.
- **Foldable D-pad:** The arrow above the controls folds the direction pad, places the four function keys in one row, and keeps the number keys. The game fits the available space at its original aspect ratio. A single-row direction/OK strip appears only when it fits without reducing the game image.
- **Save slots and dates:** New in-game saves in the verified LGT versions of Zenonia 1, 2 and 3 record the actual save date and time. Fixed Zenonia 2 showing EMPTY despite an existing save. Save again inside the game to refresh an older slot's incorrect date.
- **Small screens and rendering:** Skin images are decoded at bounded sizes and reused, and are not loaded when the keypad is hidden. Improved clipped mapping labels at larger text sizes.

External skin support covers digital controls and supported PNG/PDF representations for SNES, NES, GB, GBC and GBA. DS multi-screen layouts, analog controls, some effects and representations, and moving/resizing individual buttons within a combined skin image are not supported. The overall app design is retained; these changes do not add save states.

Existing investigations continue for main-screen audio gaps in Rhythm Star (KTF), reported overlapping music in Nom ZERO (LGT), low speed on some devices in Hybrid 1 (LGT), and intermittent input loss after switching games. If input stops, exit the game normally, fully close the app, and reopen it. Performance varies by game, device and scene; this is not a complete-playthrough or all-device compatibility certification.

Update through Google Play using the same account, without uninstalling the existing app. The in-app notice may appear before the update is available in Play; check again later if Play does not yet offer an update.
See the [testing guide](https://github.com/hun99999/wipi-x-releases/blob/main/docs/TESTING.md#english) and [support guide](https://github.com/hun99999/wipi-x-releases/blob/main/SUPPORT.md).

## WIPI-X 0.1.6 — 도트 UI와 라이브러리 조작 개선

라이브러리의 정렬과 보기 전환을 간편하게 만들고, 작은 화면부터 태블릿까지 도트 UI의 배치와 여백을 다듬었습니다. 일시정지 메뉴와 오디오 재개·종료 처리의 안정성도 개선했습니다.

- **배포 채널:** Google Play 비공개 테스트(Alpha)
- **앱 버전 / 빌드 번호:** 0.1.6 / 7
- **배포 확인일:** 2026-09-11 (한국 시간)

### 개선 및 수정

- **바로 바뀌는 정렬:** 별도 선택 화면으로 이동하지 않고 라이브러리에서 최근 실행순과 제목순을 바로 바꿀 수 있습니다. 그리드·목록 전환 버튼의 크기와 선택 표시도 맞췄습니다.
- **즐겨찾기:** 그리드 위에 겹치던 별 버튼을 정리했습니다. 게임을 길게 눌러 게임 정보에서 즐겨찾기를 추가·해제할 수 있으며, 목록형의 오른쪽 별 버튼은 유지합니다.
- **도트 UI:** 라이브러리·즐겨찾기·탐색에 도트 글꼴을 적용하고, 반투명 탐색 영역과 아이콘·글자의 정렬을 다듬었습니다. 밝은 테마와 어두운 테마를 모두 지원합니다.
- **작은 화면과 태블릿:** 작은 앱 창에서는 여백과 UI 크기를 더 촘촘하게 조정합니다. 큰 글자·짧은 가로·정사각형·태블릿 화면에서 목록 공간과 탐색 배치를 개선했습니다.
- **일시정지:** 메뉴를 아이콘 없는 도트 글꼴 버튼으로 통일하고 여백을 줄였습니다. 내용이 넘치면 스크롤바가 표시됩니다. 회전 후 종료 확인 버튼이 잘리던 문제도 수정했습니다.
- **오디오 안정성:** 소리를 재개하거나 종료할 때의 버퍼 처리와 동시 접근을 보강했습니다.

### 알려진 문제

리듬스타(KTF)는 메인 화면에서 소리 끊김이 남을 수 있습니다. 실제 플레이와 구분해 확인 중이며, 이번 업데이트가 모든 소리 간격을 해결했다는 뜻은 아닙니다.

놈ZERO(LGT)의 배경음이 겹친다는 제보는 재현과 원인 확인을 계속하고 있습니다. 하이브리드1(LGT)의 일부 기기에서 큰 속도 저하와 게임·기기·장면별 화면 갱신 간격도 남아 있습니다. 1차 테스트 대상31개의 전체 진행과 모든 기기에서 정상 동작을 보증하는 호환성 승격은 아닙니다.

게임 전환 뒤 입력이 반응하지 않는 현상도 조사 중입니다. 발생하면 게임을 정상 종료하고 앱을 완전히 종료한 뒤 다시 실행해 주세요.

### 업데이트와 문제 제보

기존 앱을 삭제하지 않고 같은 Google 계정의 Google Play에서 업데이트해 주세요. 0.1.5 이상은 **더보기 → 앱 업데이트**에서도 새 버전을 확인할 수 있습니다. 업데이트 안내에서 지금 안 함을 선택했다면 수동으로 확인해 주세요.
새 참여자는 [테스트 참여 안내](https://github.com/hun99999/wipi-x-releases/blob/main/docs/TESTING.md)를 따라 주세요.
[문제 제보](https://github.com/hun99999/wipi-x-releases/issues/new/choose)에는 기기 모델, Android 버전, WIPI-X 버전, 게임·통신사와 재현 순서를 적어 주세요.

### English

WIPI-X 0.1.6 (build 7) simplifies library sorting and view switching, refines the pixel-style interface for small screens and tablets, and improves the pause menu and audio resume/close handling. This Google Play closed-test (Alpha) update was confirmed available on September 11, 2026.

- **Immediate sorting:** Switch between recently played and title order directly in the library. Grid/list buttons now have consistent sizing and selection states.
- **Favorites:** Removed the overlapping star button from grid tiles. Long-press a game to manage favorites in its information screen. The star button on the right of list rows remains available.
- **Pixel-style interface:** Applied the pixel font to the library, favorites and navigation, and refined translucent navigation surfaces and icon/text alignment in both light and dark themes.
- **Small screens and tablets:** More compact sizing and spacing in small app windows, with improved library space and navigation layouts for large text, short landscape windows, square screens and tablets.
- **Pause menu:** Unified actions as centered text buttons using the pixel font, reduced spacing, and kept the scrollbar visible when content overflows. Fixed clipped exit-confirmation buttons after rotation.
- **Audio stability:** Hardened buffer and concurrent-access handling when audio resumes or closes.

Rhythm Star (KTF) may still have audio gaps on its main screen; this is being investigated separately from active gameplay. This update does not resolve every audio gap.

A report of overlapping background music in Nom ZERO (LGT) is still under investigation. Hybrid 1 (LGT) remains significantly slow on some devices, and frame pacing can vary by game, device and scene. This update does not certify complete playthroughs or compatibility across all devices for the 31 first-phase titles.

We are also investigating an observed loss of input after switching games. If this occurs, exit the game normally, close the app completely, and reopen it.

Update through Google Play using the same account, without uninstalling the app. Version 0.1.5 and later also support manual checks under More → App update. Check manually if you previously skipped the update notice.
See the [testing guide](https://github.com/hun99999/wipi-x-releases/blob/main/docs/TESTING.md#english), [support guide](https://github.com/hun99999/wipi-x-releases/blob/main/SUPPORT.md) and [privacy policy](https://wipix.valiostudio.com/privacy/).

## WIPI-X 0.1.5 — 더 편한 화면과 터치 오버레이 편집

화면을 더 촘촘하게 정리하고, 키패드를 직접 움직여 설정할 수 있도록 개선했습니다. 앱을 새로 실행할 때 새 버전도 확인할 수 있습니다.

- **배포 채널:** Google Play 비공개 테스트(Alpha)
- **앱 버전 / 빌드 번호:** 0.1.5 / 6
- **배포 확인일:** 2026-09-10 (한국 시간)

### 개선 및 추가

- **화면과 탐색:** 작은 화면, 큰 글자, 가로 화면과 태블릿에 맞춰 배치와 여백을 조정했습니다. 앱 전반에 공통 픽셀 아이콘을 적용했습니다.
- **더보기:** 세 번째 탭에서 설정, 앱 업데이트, GitHub와 문제 제보에 접근할 수 있습니다. 설정은 하위 화면으로 이동해 조정합니다.
- **설정과 편집:** 불필요한 모달을 줄이고 선택 버튼과 스위치를 정리했습니다. 스크롤이 필요한 영역에는 스크롤바를 표시하며 적용 버튼을 쉽게 찾을 수 있도록 배치했습니다.
- **오버레이:** 가상 게임 화면에서 방향키와 숫자키를 드래그해 옮기고, 모서리 또는 두 손가락으로 크기를 바꿀 수 있습니다. 세로·가로 배치를 각각 조정하고 적용 전 변경을 취소할 수 있습니다.
- **업데이트 안내:** 앱을 새로 실행하면 공개 GitHub 릴리스 정보를 확인합니다. 새 버전이 있으면 Google Play로 이동하거나 지금 안 함을 선택할 수 있습니다. 건너뛴 버전의 자동 안내는 반복하지 않으며 더보기에서 직접 확인할 수 있습니다. 자동 다운로드와 설치는 하지 않습니다.

### 알려진 문제

하이브리드1(LGT)은 일부 기기의 실제 플레이에서 큰 속도 저하가 남아 있습니다. 게임·기기·장면별 화면 갱신과 소리 간격도 계속 확인 중입니다. 1차 테스트 대상 31개의 모든 진행과 모든 기기에서의 정상 동작을 보증하는 호환성 승격은 아닙니다.

게임 전환 뒤 입력이 반응하지 않는 현상도 조사 중입니다. 발생하면 게임을 정상 종료하고 앱을 완전히 종료한 뒤 다시 실행해 주세요.

### 업데이트와 문제 제보

기존 앱을 삭제하지 않고 같은 Google 계정의 Google Play에서 업데이트해 주세요. 0.1.4에는 새 업데이트 안내 기능이 없으므로 이번 업데이트는 Google Play에서 직접 확인해 주세요.
새 참여자는 [테스트 참여 안내](https://github.com/hun99999/wipi-x-releases/blob/main/docs/TESTING.md)를 따라 주세요.
[문제 제보](https://github.com/hun99999/wipi-x-releases/issues/new/choose)에는 기기 모델, Android 버전, WIPI-X 버전, 게임·통신사와 재현 순서를 적어 주세요.
업데이트 조회의 정보 처리는 [개인정보처리방침](https://wipix.valiostudio.com/privacy/)에서 확인할 수 있습니다.

### English

WIPI-X 0.1.5 (build 6) makes the interface more compact and introduces direct touch editing of the virtual keypad. This Google Play closed-test (Alpha) update was confirmed available on September 10, 2026 (Korea time).

- **Interface and navigation:** Adjusted spacing and layouts for small screens, large text, landscape and tablets, with shared pixel icons throughout the app.
- **More tab:** Access settings, updates, GitHub and issue reporting from the third tab. Settings open as nested screens.
- **Settings and editors:** Reduced unnecessary dialogs, refined selection buttons and switches, and made scrollbars and apply actions easier to find.
- **Overlay editing:** Drag the direction and number pads on a virtual game screen. Resize them using a corner handle or two fingers, edit portrait and landscape separately, and cancel changes before applying them.
- **Update notices:** A fresh app launch checks public GitHub releases. Open Google Play to update or skip the offered version. Automatic notices do not repeat for a skipped version, while manual checks remain available under More. Updates are never downloaded or installed automatically.

Hybrid 1 (LGT) still runs significantly below normal speed on some devices. Frame pacing and audio gaps can vary by game, device and scene. This update does not certify complete playthroughs or compatibility across all devices for the 31 first-phase titles.

We are also investigating an observed loss of input after switching games. If this occurs, exit the game normally, close the app completely, and reopen it.

Install through Google Play using the same account, without uninstalling the existing app. Version 0.1.4 has no in-app update notice, so check Google Play directly for this update.
See the [testing guide](https://github.com/hun99999/wipi-x-releases/blob/main/docs/TESTING.md#english), [support guide](https://github.com/hun99999/wipi-x-releases/blob/main/SUPPORT.md) and [privacy policy](https://wipix.valiostudio.com/privacy/).

## WIPI-X 0.1.4 — 투구 화면·입력 반응 개선

2010프로야구의 투구 중 화면이 지워지던 문제와 일부 게임의 추가 입력 지연을 수정했습니다.
LGT 게임의 실행 부담을 줄이고 정상 종료 안내도 바로잡았습니다.

- **배포 채널:** Google Play 비공개 테스트(Alpha)
- **앱 버전 / 빌드 번호:** 0.1.4 / 5
- **배포 확인일:** 2026-09-10 (한국 시간)

### 개선 및 수정

- **2010프로야구(LGT):** 나만의리그 투수편에서 공을 던질 때 점수판과 관중석 일부가 지워지던 화면 갱신 문제를 수정했습니다.
- **버튼 반응:** 제노니아2 등 일부 LGT 게임에서 앞선 처리가 끝난 뒤에도 키 전달이 추가로 기다리던 지연을 줄였습니다.
- **실행 성능:** LGT 게임의 반복 연산과 함수 복귀 처리를 개선해 실행 부담을 줄였습니다.
- **정상 종료:** 게임 안에서 종료했을 때 저장 처리가 끝나기 전에 오류 안내가 나타나던 문제를 수정했습니다.

### 알려진 문제

하이브리드1(LGT)은 일부 기기의 실제 플레이에서 큰 속도 저하가 남아 있습니다.
게임·기기·장면별 화면 갱신과 소리 간격도 계속 확인 중입니다. 이번 개선은 1차 테스트 대상 31개의 모든 진행과 모든 기기에서의 정상 동작을 보증하는 호환성 승격이 아닙니다.

게임 전환 뒤 입력이 반응하지 않는 현상도 조사 중입니다. 발생하면 게임을 정상 종료하고 앱을 완전히 종료한 뒤 다시 실행해 주세요.

### 업데이트와 문제 제보

업데이트는 기존 앱을 삭제하지 않고 같은 Google 계정의 Google Play에서 설치해 주세요.
새 참여자는 [테스트 참여 안내](https://github.com/hun99999/wipi-x-releases/blob/main/docs/TESTING.md)를 따라 주세요.
[문제 제보](https://github.com/hun99999/wipi-x-releases/issues/new/choose)에는 기기 모델,
Android 버전, WIPI-X 버전, 게임·통신사와 재현 순서를 적어 주세요.

### English

WIPI-X 0.1.4 (build 5) fixes disappearing graphics during pitching in 2010 Pro Baseball,
reduces an extra input-delivery delay in some LGT games, lowers runtime overhead,
and fixes a misleading error message on a normal game exit. This Google Play closed-test
(Alpha) update was confirmed available on September 10, 2026 (Korea time).

- **2010 Pro Baseball (LGT):** Fixed the scoreboard and parts of the stadium disappearing when throwing a pitch in My League's pitcher mode.
- **Input:** Reduced an extra wait before ready key events reached games such as Zenonia 2 (LGT).
- **Performance:** Reduced overhead in repeated operations and function returns in LGT games.
- **Normal exit:** Fixed an error message appearing before save completion when exiting through a game's own menu.

Hybrid 1 (LGT) still runs significantly below normal speed on some devices. Frame pacing
and audio gaps can also vary by game, device, and scene. This update does not certify
complete playthroughs or compatibility across all devices for the 31 first-phase titles.

We are also investigating an observed loss of input after switching games. If this occurs, exit the game normally, close the app completely, and reopen it.

Install updates through Google Play using the same account, without uninstalling the existing app.
New testers can follow the [testing guide](https://github.com/hun99999/wipi-x-releases/blob/main/docs/TESTING.md#english).
See the [support guide](https://github.com/hun99999/wipi-x-releases/blob/main/SUPPORT.md) to report issues.

## WIPI-X 0.1.3 — 조작 반응·소리·프레임 개선

게임의 화면 처리가 오래 걸릴 때 버튼 반응까지 지연되던 문제를 개선했습니다.
슈퍼액션히어로3·액션퍼즐패밀리3의 실행 부담과 일부 게임의 소리 누락·끊김도 줄였습니다.

- **배포 채널:** Google Play 비공개 테스트(Alpha)
- **앱 버전 / 빌드 번호:** 0.1.3 / 4
- **배포 확인일:** 2026-09-09 (한국 시간)

### 개선 및 수정

- **버튼 반응:** 게임의 무거운 화면 처리 때문에 화면 키패드와 입력 전달이 함께 기다리던 문제를 수정했습니다.
- **프레임과 실행 성능:** 슈퍼액션히어로3·액션퍼즐패밀리3(LGT)의 실행 처리를 개선하고, 템페스트(LGT)의 반투명 화면 효과에서 발생하던 큰 속도 저하를 줄였습니다.
- **소리 끊김:** 일부 Android 기기에서 출력 버퍼에 쌓인 소리가 버려지던 문제를 수정했습니다.
- **누락된 효과음:** 질주쾌감스케쳐1·2(KTF)에서 일부 내장 음원이 재생되지 않던 문제를 수정했습니다.

### 알려진 문제

하이브리드1(LGT)은 일부 기기의 실제 플레이에서 큰 속도 저하가 남아 있습니다.
게임·기기·장면별 화면 갱신과 소리 간격도 계속 확인 중입니다. 이번 개선은 1차 테스트 대상
31개의 모든 진행과 모든 기기에서의 정상 동작을 보증하는 호환성 승격이 아닙니다.

### 업데이트와 문제 제보

업데이트는 기존 앱을 삭제하지 않고 같은 Google 계정의 Google Play에서 설치해 주세요.
새 참여자는 [테스트 참여 안내](https://github.com/hun99999/wipi-x-releases/blob/main/docs/TESTING.md)를 따라 주세요.
[문제 제보](https://github.com/hun99999/wipi-x-releases/issues/new/choose)에는 기기 모델,
Android 버전, WIPI-X 버전, 게임·통신사와 재현 순서를 적어 주세요.

### English

WIPI-X 0.1.3 (build 4) improves input responsiveness during heavy rendering, reduces
processing overhead in Super Action Hero 3 and Action Puzzle Family 3, and addresses
missing effects and audio dropouts in some games. This Google Play closed-test (Alpha)
update was confirmed available on September 9, 2026 (Korea time).

- **Input:** Fixed input delivery and the on-screen keypad waiting for long game rendering operations.
- **Performance:** Improved execution in Super Action Hero 3 and Action Puzzle Family 3 (LGT), and reduced major slowdowns during translucent effects in Tempest (LGT).
- **Audio dropouts:** Fixed queued audio being discarded on some Android devices.
- **Missing effects:** Restored playback of some embedded sounds in Speed Sketcher 1 and 2 (KTF).

Hybrid 1 (LGT) still runs significantly below normal speed on some devices. Frame pacing
and audio gaps can also vary by game, device, and scene. This update does not certify
complete playthroughs or compatibility across all devices for the 31 first-phase titles.

Install updates through Google Play using the same account, without uninstalling the existing app.
New testers can follow the [testing guide](https://github.com/hun99999/wipi-x-releases/blob/main/docs/TESTING.md#english).
See the [support guide](https://github.com/hun99999/wipi-x-releases/blob/main/SUPPORT.md) to report issues.

## WIPI-X 0.1.2 — 소리와 실행 성능 개선

일부 게임에서 소리가 나오지 않던 문제를 수정하고, 게임 진행 중 속도 저하와 프레임
끊김을 줄였습니다. 장시간 실행할 때 임시 데이터가 계속 쌓이던 문제도 개선했습니다.

- **배포 채널:** Google Play 비공개 테스트(Alpha)
- **앱 버전 / 빌드 번호:** 0.1.2 / 3
- **배포 확인일:** 2026-09-09 (한국 시간)

### 개선 및 수정

- **소리 재생:** 일부 LGT 게임에서 배경음과 효과음이 나오지 않던 문제를 수정했습니다.
- **실행 성능:** 게임 진행 중 불필요한 처리 부담을 줄여 속도 저하와 프레임 끊김을 완화했습니다.
- **장시간 실행:** 사용이 끝난 임시 문자열 데이터를 회수해 메모리 누적으로 게임이 종료되는 문제를 개선했습니다.

### 업데이트와 문제 제보

업데이트는 기존 앱을 삭제하지 않고 같은 Google 계정의 Google Play에서 설치해 주세요.
새 참여자는 [테스트 참여 안내](https://github.com/hun99999/wipi-x-releases/blob/main/docs/TESTING.md)를 따라 주세요.

[문제 제보](https://github.com/hun99999/wipi-x-releases/issues/new/choose)에는 기기 모델,
Android 버전, WIPI-X 버전, 게임·통신사와 재현 순서를 적어 주세요.

### English

WIPI-X 0.1.2 (build 3) fixes missing audio in some games, reduces runtime overhead that
caused slowdowns and uneven frame delivery, and improves memory use during extended play.
This Google Play closed-test (Alpha) update was confirmed available on September 9, 2026 (Korea time).

- **Audio:** Fixed missing background music and sound effects in some LGT games.
- **Performance:** Reduced unnecessary processing during gameplay to ease slowdowns and frame stutter.
- **Extended play:** Reclaim temporary string data that is no longer in use to reduce game exits caused by memory accumulation.

Install updates through Google Play using the same account, without uninstalling the existing app.
New testers can follow the [testing guide](https://github.com/hun99999/wipi-x-releases/blob/main/docs/TESTING.md#english).
See the [support guide](https://github.com/hun99999/wipi-x-releases/blob/main/SUPPORT.md) to report issues.

## WIPI-X 0.1.1 — 실행 안정성과 성능 개선

게임 중 연속으로 키를 누르거나 효과가 표시될 때 화면이 끊기는 현상을 줄였습니다.
이름 변경·캐릭터 생성 중 게임이 종료되는 문제와, 게임을 종료한 뒤에도 저장 파일을
내보낼 수 없던 문제를 수정했습니다.

- **배포 채널:** Google Play 비공개 테스트(Alpha)
- **앱 버전 / 빌드 번호:** 0.1.1 / 2
- **배포 확인일:** 2026-09-09 (한국 시간)
- **심사 요청일:** 2026-09-09 (한국 시간)

### 개선 및 수정

- **프레임과 실행 성능:** 리듬스타(KTF) 등에서 연속 키 입력과 효과 처리 중 화면 갱신이
  지연되는 현상을 개선했습니다.
- **이름 변경:** 액션퍼즐패밀리1(KTF)의 결과 화면에서 기존 이름 사용 여부에 ‘아니오’를
  선택해 이름을 바꾸려 하면 게임이 종료되는 문제를 수정했습니다.
- **캐릭터 생성:** 제노니아2(LGT)에서 새 캐릭터를 생성하는 도중 게임이 종료되는 문제를
  수정했습니다.
- **재실행 안정성:** 이전 실행의 오류가 다음 게임 실행에 영향을 주는 일부 경로를 수정했습니다.
- **저장 백업:** 게임을 정상 종료한 뒤에도 ‘게임을 정상 종료하고 다른 파일 작업이 끝난 뒤
  저장 관리를 이용해 주세요’라는 안내와 함께 내보내기가 차단되는 문제를 수정했습니다.

### 업데이트와 문제 제보

기존 테스터는 같은 Google 계정의 Google Play에서 0.1.1로 업데이트할 수 있습니다. 업데이트를 위해 기존 앱을 삭제할 필요는 없습니다. 새 참여자는
[테스트 참여 안내](https://github.com/hun99999/wipi-x-releases/blob/main/docs/TESTING.md)를
따라 주세요. 앱을 삭제하거나 데이터를 지우기 전에 필요한 저장을 앱 바깥에 백업해 주세요.

[문제 제보](https://github.com/hun99999/wipi-x-releases/issues/new/choose)에는 기기 모델,
Android 버전, WIPI-X 버전, 게임·통신사와 재현 순서를 적어 주세요. 게임 원본·저장 파일·
개인정보는 공개 이슈에 첨부하지 마세요.

### English

WIPI-X 0.1.1 (build 2) reduces delayed frame updates during rapid input and visual effects,
fixes crashes during name editing and character creation, and fixes save export after a normal
game exit. This Google Play closed-test (Alpha) update was confirmed available on September 9,
2026 (Korea time), the same date the review request was submitted.

- **Performance:** Improved frame delivery during rapid input and effects in KTF games,
  including Rhythm Star.
- **Name editing:** Fixed a crash when selecting “No” to change the result name in
  Action Puzzle Family 1 (KTF).
- **Character creation:** Fixed a crash during new character creation in Zenonia 2 (LGT).
- **Restart stability:** Fixed some paths where an earlier error affected the next game launch.
- **Save backup:** Fixed save export being blocked by a message asking users to exit the game
  and finish other file operations, even after the game had already exited normally.

Existing testers can update to 0.1.1 through Google Play using the same account.
There is no need to uninstall the existing app to update. New testers can follow
the [testing guide](https://github.com/hun99999/wipi-x-releases/blob/main/docs/TESTING.md#english).
Back up important saves outside the app before uninstalling or clearing app data. See the
[support guide](https://github.com/hun99999/wipi-x-releases/blob/main/SUPPORT.md) to report issues.

## WIPI-X 0.1.0 — 첫 알파 테스트

WIPI-X의 첫 비공개 테스트를 시작했습니다. KTF·LGT WIPI 게임을 Android에서 실행하고, 화면 키패드와 게임패드로 조작할 수 있습니다.

- **배포 채널:** Google Play 비공개 테스트(Alpha)
- **앱 버전 / 빌드 번호:** 0.1.0 / 1
- **배포 확인일:** 2026-09-09 (한국 시간)
- **심사 요청일:** 2026-09-08
- **테스트 대상:** 대한민국의 만 18세 이상 사용자, Android 8.0 이상

### 이번 버전에서 사용할 수 있는 기능

- **게임 가져오기:** KTF·LGT 게임 파일을 여러 개 선택하거나 지정한 폴더에서 새 파일을 찾습니다.
- **피쳐폰 키패드:** 클래식·플랫 디자인과 가로·세로 배치를 제공합니다. 키패드를 숨겨 게임패드로 플레이할 수도 있습니다.
- **문자 입력:** 게임 속 이름 입력 등에 천지인 한글·영문 반복 누르기를 사용합니다.
- **게임패드:** 레트로·Xbox·PlayStation 배열과 공통·게임별 키매핑을 제공합니다. 매핑 화면에서 누른 버튼을 표시하며 RG Rotate의 L2·R2 디지털 입력을 지원합니다.
- **화면과 속도:** 화면 비율을 유지한 확대, 0.5–4배속, 라이트·다크·시스템 테마, 상태바와 진동을 설정합니다.
- **저장 백업:** 게임별 저장 내보내기·가져오기를 제공합니다. 앱 삭제나 데이터 지우기 전에 필요한 저장을 앱 바깥에 보관할 수 있습니다.
- **개인정보처리방침:** 앱 정보에서 오프라인으로 읽을 수 있습니다.

### 호환성과 알려진 제한

- 1차 테스트 대상은 **31개(KTF 18개 · LGT 13개)**입니다. 기존 28개에 리듬스타(KTF)·2010프로야구(LGT)·템페스트(LGT)를 포함합니다.
- 대상 선정은 전체 게임 진행이나 모든 기기에서의 정상 동작을 보증하지 않습니다. 게임·기기에 따라 실행, 문자 입력, 저장, 화면·소리 반응에 문제가 있을 수 있으며 테스트를 통해 확인하고 있습니다.
- 게임 파일은 앱에 포함되어 있지 않습니다. 이용 권한이 있는 파일을 직접 준비해 주세요. 게임 한 개짜리 ZIP은 압축을 풀지 않고 가져올 수 있습니다.
- 자세한 대상과 확인 범위는 [호환성 안내](https://github.com/hun99999/wipi-x-releases/blob/main/docs/COMPATIBILITY.md)에서 확인하세요.

### 설치와 문제 제보

1. [WIPI-X 테스트 그룹](https://groups.google.com/g/wipi-x-testers/about)에 가입합니다.
2. **같은 Google 계정**으로 [Google Play 테스트 참여](https://play.google.com/apps/testing/com.valiostudio.wipix)를 신청합니다.
3. 참여 페이지의 Google Play 링크로 설치합니다. 앱 설치와 업데이트는 Google Play에서만 제공합니다.

[자세한 참여 안내](https://github.com/hun99999/wipi-x-releases/blob/main/docs/TESTING.md) · [문제 제보](https://github.com/hun99999/wipi-x-releases/issues/new/choose)

제보에는 기기 모델, Android 버전, WIPI-X 버전, 게임·통신사와 재현 순서를 적어 주세요. 게임 원본·저장 파일·개인정보는 공개 이슈에 첨부하지 마세요.

### English

WIPI-X 0.1.0 (build 1) is the first Google Play closed test (Alpha), confirmed available on September 9, 2026 (Korea time). It was submitted for review on September 8. The test is configured for users aged 18 or older in South Korea, on Android 8.0 or later.

This version includes KTF/LGT file import and folder scanning; classic and flat keypads; portrait and landscape layouts; Korean Cheonjiin and multi-tap English input; configurable retro, Xbox, and PlayStation controller layouts; live mapping feedback and RG Rotate L2/R2 input; playback speed, themes, status-bar and vibration settings; per-game save export/import; and an offline privacy policy in app information.

The initial roster contains 31 games (18 KTF and 13 LGT), including Rhythm Star, 2010 Pro Baseball, and Tempest. Roster inclusion does not establish full compatibility. Execution, text input, saves, graphics, and audio may vary by game and device. The app does not include game files.

Join the [testers group](https://groups.google.com/g/wipi-x-testers/about), [opt in to the Google Play test](https://play.google.com/apps/testing/com.valiostudio.wipix) using the same account, and install through Google Play. See the [testing guide](https://github.com/hun99999/wipi-x-releases/blob/main/docs/TESTING.md#english) and [support guide](https://github.com/hun99999/wipi-x-releases/blob/main/SUPPORT.md) for details.
