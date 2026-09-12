# WIPI-X 시작 안내

[프로젝트 홈](../README.md) · [테스트 참여 안내](TESTING.md) · [앱 출시 안내](https://wipix.valiostudio.com/ko/download/)

이 문서는 0.1.10 테스트 앱의 사용 흐름을 설명합니다. 2026년 9월 12일 심사 요청했으며 Play 제공은 대기 중입니다. 현재 제공 확인 버전은 0.1.9입니다. Android 8.0 이상이 필요하며, 앱 설치와 업데이트는 Google Play에서 제공합니다. [테스트 참여 안내](TESTING.md)에 따라 그룹 가입과 Play 테스트 참여를 마친 뒤 설치하세요.

## 게임 가져오기

1. Android 파일 관리자에서 `Download/WIPI-X Games` 같은 게임 전용 폴더를 만듭니다.
2. 이용 권한이 있는 게임 파일을 그 폴더에 넣습니다. **게임 한 개짜리 `.zip`은 그대로 불러옵니다.** 여러 게임을 한꺼번에 묶은 별도 보관용 압축파일만 풀어 개별 게임 ZIP을 준비합니다. 개별 ZIP 안의 JAR나 리소스를 다시 풀거나 재압축하지 마세요.
3. WIPI-X의 **가져오기 → 폴더 지정**에서 해당 폴더를 선택합니다. 하위 폴더도 함께 검색됩니다. Android가 `Download` 전체 선택을 허용하지 않으면 그 안의 전용 폴더를 선택하세요.
4. 새 게임을 폴더에 추가한 뒤에는 **가져오기 → 스캔** 버튼을 누릅니다. 결과에서 새로 추가된 게임, 이미 있는 게임, 확인이 필요한 파일을 볼 수 있습니다.
5. 게임 카드를 눌러 실행합니다. 조작이 낯설면 더보기의 **도움말**을 확인하세요.

파일을 개별 선택해 가져오는 방법도 사용할 수 있습니다. 앱은 가져온 사본을 사용하므로 원본 폴더를 변경하거나 삭제해도 그 변경이 앱 내부 게임 삭제로 자동 반영되지는 않습니다.

`게임명_통신사_wipiX호환.zip`은 별도로 관리하는 파일의 이름 규칙입니다. 이름만으로 모든 기능의 지원을 뜻하지는 않습니다. 기존 `.wipix` 게임 파일도 불러올 수 있습니다.

이번 호환 교정은 앱 실행에 적용됩니다. 기존 게임 ZIP을 다시 다운로드할 필요는 없습니다. 같은 제목이라도 다른 통신사·다른 파일의 지원 여부는 다를 수 있습니다.

## 라이브러리 정리

정렬 버튼으로 최근 실행순·제목순을 바로 바꿉니다. 그리드·목록 버튼으로 보기 방식을 선택할 수 있습니다. 그리드에서는 게임을 길게 눌러 게임 정보에서 즐겨찾기를 추가·해제하고, 목록에서는 오른쪽 별 버튼을 사용할 수 있습니다.

## 키패드와 게임패드

**더보기 → 설정 → 화면 · 키패드**에서 클래식·플랫과 새 피처폰 스킨 3종, 가로·세로 배치를 선택하고 **키패드 미리보기**로 위치를 확인할 수 있습니다. 게임 안의 이름 입력에는 천지인 한글과 영문 반복 누르기를 사용합니다.

**오버레이 위치 및 크기 편집**에서는 가상 화면의 방향키·숫자키를 끌어 이동하고 모서리나 두 손가락으로 크기를 바꿉니다. 불투명도는 0–100%로 조절하며, 0%에서도 터치 입력은 유지됩니다. 세로·가로 배치를 따로 조정한 뒤 **이 배치 사용 → 적용**으로 저장합니다. 적용 전에는 뒤로 돌아가 변경을 취소할 수 있습니다.

**게임패드 키매핑**에서는 레트로·Xbox·PlayStation 배열을 고르고 화면의 버튼을 눌러 대응하는 피쳐폰 키를 지정합니다. 패드 버튼을 직접 누르면 해당 위치가 켜집니다. 변경은 **적용**으로 저장하며, 공통 매핑과 게임별 매핑을 따로 사용할 수 있습니다.

**레트로 스킨**에서 내장 WIPI-X 16-bit 실버·레트로 그래파이트나 지원되는 `.deltaskin`을 선택합니다. 스킨 그림의 버튼을 누르면 기존 키매핑을 편집할 수 있으며 실제 패드 연결은 필요하지 않습니다. 지원 범위는 [버전별 변경 안내](UPDATES.md)를 확인하세요.

0.1.9의 세로 기본 피처폰 배치는 십자키·OK가 중앙에 있고, 왼쪽 가장자리에 좌메뉴·통화, 오른쪽 가장자리에 우메뉴·취소가 위아래로 놓입니다. 오른쪽 위 화살표로 십자키를 접고 펼칠 수 있습니다. 접으면 기능키 네 개가 한 줄로 정리되고 숫자키는 유지됩니다. 방향키·OK 한 줄은 게임 화면을 줄이지 않고 남는 공간에 들어갈 때만 표시합니다.

화면 크기, 키패드 표시, 0.5–4배속, 상태바와 진동도 설정할 수 있습니다. 높은 배속의 실제 속도는 기기 성능과 게임에 따라 달라집니다.

## 플레이 기록

더보기의 **플레이 기록**에서 전체 누적 시간과 최근 7일의 일별 막대 그래프를 확인합니다. 게임 아이콘·제목이 있는 목록에서 게임을 선택하면 해당 게임의 기록으로 이동합니다. 이 버전부터 기록되는 시간은 기기 안에 저장합니다.

## USB 디버깅 안내

앱 시작 시 USB 디버깅을 끄라는 안내가 보이면 **개발자 옵션 열기**에서 USB 디버깅을 끈 뒤 앱으로 돌아와 **다시 확인**을 누르세요. 앱이 기기 설정을 자동으로 변경하지 않습니다.

## 업데이트 확인

앱을 새로 실행하면 GitHub의 공개 릴리스 정보를 확인합니다. 새 버전 안내에서 **업데이트**를 누르면 Google Play로 이동하며, **지금 안 함**을 선택한 버전은 자동 안내를 반복하지 않습니다. **더보기 → 앱 업데이트**에서 언제든 직접 확인할 수 있고 더 높은 새 버전은 다시 안내합니다. 자동 다운로드·설치는 하지 않습니다.

심사 요청한 새 릴리즈의 앱 안내가 Play 반영보다 먼저 보일 수 있습니다. Play에 업데이트 버튼이 없으면 이후 다시 확인해 주세요.

0.1.4 이하에서는 Google Play에서 직접 확인해 주세요. 기존 앱을 삭제할 필요는 없습니다.

## 저장 백업

게임 자체의 저장 메뉴로 진행을 저장한 뒤 정상 종료합니다. 라이브러리에서 게임 카드를 길게 누르고 **저장 파일 내보내기**를 선택하면 앱 밖에 백업할 수 있습니다.

복원할 때는 같은 게임을 먼저 가져온 뒤 **저장 파일 가져오기**를 사용합니다. 복원은 해당 게임의 기존 저장을 교체하므로, 보관할 현재 진행은 먼저 내보내세요.

게임 제목이 같아도 파일 내용이 다른 판본 사이의 저장 이전은 지원하지 않을 수 있습니다. 게임 원본과 그 게임의 백업을 함께 보관하세요. 앱 삭제나 Android 앱 데이터 지우기 전에 필요한 저장을 내보내야 합니다. 자동 클라우드 백업은 제공하지 않습니다.

## 실행에 문제가 있다면

[호환성 안내](COMPATIBILITY.md)를 확인하고 [문제 제보 양식](https://github.com/hun99999/wipi-x-releases/issues/new?template=bug_report.yml)에 기기·앱 버전·게임·통신사와 재현 과정을 적어 주세요. 게임 원본과 저장 파일은 공개 이슈에 첨부하지 않습니다.

## Quick start in English

This guide describes 0.1.10 (Alpha), submitted for review on September 12, 2026. Play availability is pending; 0.1.9 remains the version confirmed available. Follow the [testing guide](TESTING.md#english), join the testers group, opt in, and install through Google Play. Android 8.0 or later is required.

The compatibility corrections apply during execution, so existing game ZIPs do not need to be downloaded again. Support status depends on the exact file and carrier edition.

Put your game files in a dedicated Android folder and select it in WIPI-X. **Keep each individual game's ZIP intact.** Extract only a separate outer collection archive that contains several game ZIPs. Do not unpack the JAR or resources inside an individual game package. Subfolders are included when scanning. Use the scan button after adding new files, or import several files directly.

Switch between recent/title sorting and grid/list views directly in the library. Long-press a grid tile to manage favorites in game information, or use the star button in a list row.

Settings include classic and flat keypads, portrait and landscape layouts, Korean Cheonjiin and multi-tap English input, gamepad mappings, themes, and playback speed. In the mapping screen, pressing a controller button highlights its position; use the on-screen controls to edit and apply mappings.

The Retro skin setting, introduced in 0.1.7, is available for WIPI-X 16-bit Silver, Retro Graphite and supported `.deltaskin` imports. Tap the skin buttons to edit the same global/per-game mappings; a physical pad is not required. In the default portrait layout in 0.1.9, the D-pad and OK are centered, with Left Menu above Call at the left edge and Right Menu above Cancel at the right edge. Use the arrow to fold the D-pad into a shorter layout with one row of function keys and unchanged number keys. A direction/OK row appears only when spare space permits it without shrinking the game. See the [release notes](UPDATES.md) for supported skin formats.

Open settings under More. Drag and resize keypad groups on the virtual overlay canvas, select Use this layout, then Apply. Portrait and landscape layouts are separate. Opacity supports 0–100%; fully transparent controls remain touchable. A fresh app launch checks public releases; skip an offered version to stop its automatic notice, or check manually under More → App update. On version 0.1.4 or earlier, check Google Play directly without uninstalling the app.

Under More, Play history shows overall and per-game totals and daily bars for the last seven days, with icons and titles linking to game details. Recording starts with this version and stays on the device. If a USB debugging notice appears, open Developer options, disable USB debugging, return to the app and select Check again.

An in-app update notice may precede Play availability. Check again later if Play does not yet offer the update.

Save inside the game and exit normally before exporting a backup from the game card's long-press menu. Restoring replaces that game's existing save. Keep the matching game file with the backup; backups are not automatically migrated between different game-file contents. There is no automatic cloud backup.
