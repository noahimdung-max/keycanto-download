# KeyCanto 받기

친구끼리 나눠 쓰는 무료 Windows 프로그램 두 가지의 설치 파일입니다. (소스 코드는 여기 없어요)

| 프로그램 | 하는 일 | 받기 |
|---|---|---|
| **KeyCanto** | 텍스트 악보·MIDI 파일을 게임 속 피아노로 자동 연주 | [Releases](../../releases/latest) 의 `KeyCanto-1.1.0-Setup.exe` (약 15MB) |
| **KeyCanto Scribe** | 노래·피아노 음악 파일을 MIDI 와 KeyCanto 악보로 변환 | [Releases](../../releases/latest) 의 `KeyCantoScribe-1.1.0-Setup.exe` (약 315MB) |

Windows 10/11 64비트용입니다. 1.1.0 부터 새 디자인(밝게·어둡게 테마)이에요. 예전 1.0.0 은 [Releases](../../releases) 에 남아 있어요.

## 경고 창이 떠도 놀라지 마세요

코드 서명 인증서가 없는 무료 프로그램이라 처음 보는 파일로 경고가 나올 수 있어요.

- **크롬·엣지**에서 "흔하게 다운로드되는 파일이 아닙니다"가 뜨면: 다운로드 목록에서 파일 옆 메뉴 → **유지**
- **Windows의 PC 보호** 파란 창이 뜨면: **추가 정보** → **실행**
- 일부 백신이 잘못 막을 수 있어요. 걱정되면 아래 SHA-256 으로 파일이 맞는지 확인하세요.

## 받은 파일이 맞는지 확인하기 (선택)

받은 폴더에서 PowerShell 을 열고 `Get-FileHash .\파일이름.exe` 를 입력하면 나오는 값이 아래와 같아야 해요.

| 파일 | SHA-256 |
|---|---|
| KeyCanto-1.1.0-Setup.exe | `f8038ff9d846a859016e69e75803a1078ffdfa1ab4a0c0b48b4965ddb899e628` |
| KeyCantoScribe-1.1.0-Setup.exe | `642603ee54745f8988f01d66d9c9c3e5df2a3b896f8abc5300831fc93afc0bfb` |

## 사용법

설치 뒤 프로그램의 **도움말** 버튼을 누르면 자세한 사용법이 나와요. 오픈소스·모델 라이선스 전문은 설치 폴더의 `licenses` 폴더에 있어요.
