# WIPI-X 변경 안내

[프로젝트 홈](../README.md) · [테스트 참여 안내](TESTING.md) · [버전별 GitHub 릴리즈](https://github.com/hun99999/wipi-x-releases/releases)

Google Play에 배포된 버전의 변경사항을 최신순으로 기록합니다. 알파·베타 기록도 정식 출시 후 계속 보존합니다.

## 0.1.3 — 조작 반응·소리·프레임 개선

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

## 0.1.2 — 소리와 실행 성능 개선

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

## 0.1.1 — 실행 안정성과 성능 개선

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

## 0.1.0 — 첫 알파 테스트

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
