# WIPI-X 시작 안내

[프로젝트 홈](../README.md) · [테스트 참여 안내](TESTING.md) · [앱 출시 안내](https://wipix.valiostudio.com/ko/download/)

이 문서는 0.1.4 테스트 앱의 사용 흐름을 설명합니다. Android 8.0 이상이 필요하며, 앱 설치와 업데이트는 Google Play에서 제공합니다. 2026년 9월 10일 기준 비공개 테스트(Alpha)가 진행 중입니다. [테스트 참여 안내](TESTING.md)에 따라 그룹 가입과 Play 테스트 참여를 마친 뒤 설치하세요.

## 게임 가져오기

1. Android 파일 관리자에서 `Download/WIPI-X Games` 같은 게임 전용 폴더를 만듭니다.
2. 이용 권한이 있는 게임 파일을 그 폴더에 넣습니다. **게임 한 개짜리 `.zip`은 그대로 불러옵니다.** 여러 게임을 한꺼번에 묶은 별도 보관용 압축파일만 풀어 개별 게임 ZIP을 준비합니다. 개별 ZIP 안의 JAR나 리소스를 다시 풀거나 재압축하지 마세요.
3. WIPI-X의 **폴더 지정**에서 해당 폴더를 선택합니다. 하위 폴더도 함께 검색됩니다. Android가 `Download` 전체 선택을 허용하지 않으면 그 안의 전용 폴더를 선택하세요.
4. 새 게임을 폴더에 추가한 뒤에는 앱의 **스캔** 버튼을 누릅니다. 결과에서 새로 추가된 게임, 이미 있는 게임, 확인이 필요한 파일을 볼 수 있습니다.
5. 게임 카드를 눌러 실행합니다. 조작이 낯설면 설정의 **시작·조작 안내**를 확인하세요.

파일을 개별 선택해 가져오는 방법도 사용할 수 있습니다. 앱은 가져온 사본을 사용하므로 원본 폴더를 변경하거나 삭제해도 그 변경이 앱 내부 게임 삭제로 자동 반영되지는 않습니다.

`게임명_통신사_wipiX호환.zip`은 별도로 관리하는 파일의 이름 규칙입니다. 이름만으로 모든 기능의 지원을 뜻하지는 않습니다. 기존 `.wipix` 게임 파일도 불러올 수 있습니다.

## 키패드와 게임패드

설정에서 클래식·플랫 키패드와 가로·세로 배치를 선택하고 **키패드 미리보기**로 위치를 확인할 수 있습니다. 게임 안의 이름 입력에는 천지인 한글과 영문 반복 누르기를 사용합니다.

**게임패드 키매핑**에서는 레트로·Xbox·PlayStation 배열을 고르고 화면의 버튼을 눌러 대응하는 피쳐폰 키를 지정합니다. 패드 버튼을 직접 누르면 해당 위치가 켜집니다. 변경은 **적용**으로 저장하며, 공통 매핑과 게임별 매핑을 따로 사용할 수 있습니다.

화면 크기, 키패드 표시, 0.5–4배속, 상태바와 진동도 설정할 수 있습니다. 높은 배속의 실제 속도는 기기 성능과 게임에 따라 달라집니다.

## 저장 백업

게임 자체의 저장 메뉴로 진행을 저장한 뒤 정상 종료합니다. 라이브러리에서 게임 카드를 길게 누르고 **저장 파일 내보내기**를 선택하면 앱 밖에 백업할 수 있습니다.

복원할 때는 같은 게임을 먼저 가져온 뒤 **저장 파일 가져오기**를 사용합니다. 복원은 해당 게임의 기존 저장을 교체하므로, 보관할 현재 진행은 먼저 내보내세요.

게임 제목이 같아도 파일 내용이 다른 판본 사이의 저장 이전은 지원하지 않을 수 있습니다. 게임 원본과 그 게임의 백업을 함께 보관하세요. 앱 삭제나 Android 앱 데이터 지우기 전에 필요한 저장을 내보내야 합니다. 자동 클라우드 백업은 제공하지 않습니다.

## 실행에 문제가 있다면

[호환성 안내](COMPATIBILITY.md)를 확인하고 [문제 제보 양식](https://github.com/hun99999/wipi-x-releases/issues/new?template=bug_report.yml)에 기기·앱 버전·게임·통신사와 재현 과정을 적어 주세요. 게임 원본과 저장 파일은 공개 이슈에 첨부하지 않습니다.

## Quick start in English

The 0.1.4 closed test (Alpha) is available to eligible testers as of September 10, 2026. Follow the [testing guide](TESTING.md#english), join the testers group, opt in, and install through Google Play. Android 8.0 or later is required.

Put your game files in a dedicated Android folder and select it in WIPI-X. **Keep each individual game's ZIP intact.** Extract only a separate outer collection archive that contains several game ZIPs. Do not unpack the JAR or resources inside an individual game package. Subfolders are included when scanning. Use the scan button after adding new files, or import several files directly.

Settings include classic and flat keypads, portrait and landscape layouts, Korean Cheonjiin and multi-tap English input, gamepad mappings, themes, and playback speed. In the mapping dialog, pressing a controller button highlights its position; use the on-screen controls to edit and apply mappings.

Save inside the game and exit normally before exporting a backup from the game card's long-press menu. Restoring replaces that game's existing save. Keep the matching game file with the backup; backups are not automatically migrated between different game-file contents. There is no automatic cloud backup.
