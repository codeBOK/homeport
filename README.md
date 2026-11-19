# Homeport

리컴파일 PC 포트(리컴프) 게임을 한곳에 모아 실행하고, 새 버전이 나오면 알려 주는 Windows 런처입니다.
키보드, 마우스, 게임패드로 모두 쓸 수 있습니다.

> A Windows launcher for recompiled PC ports. Keeps your recomps in one place, detects installed versions and tells you when a new release is out. (UI is Korean for now.)

## 내려받기

오른쪽 **[Releases](https://github.com/codeBOK/homeport/releases/latest)**에서 `Homeport-Setup-x.y.z.exe`를 받아 실행합니다.

- 코드 서명이 없어 처음 한 번은 Windows PC 보호 경고가 뜹니다. **추가 정보 → 실행**을 누르세요.
- 설치한 뒤에는 Homeport가 새 버전을 스스로 받아 업데이트합니다.
- 데이터는 `%APPDATA%\Homeport`에 저장됩니다.

## 할 수 있는 것

- 폴더를 고르면 리컴프 실행 파일을 찾아 목록에 넣습니다. 알려진 리컴프는 미리 체크됩니다.
- 설치된 버전을 알아내고 GitHub·Forgejo 릴리스와 비교해 업데이트를 알려 줍니다. 상세 화면에서 바뀐 점을 요약해 보여 줍니다.
- 100개가 넘는 리컴프 프로젝트를 기종별로 정리한 라이브러리
- 게임별 플레이 시간과 날짜별 기록, Discord 표시, 콘솔 모드(전체화면·패드 전원 메뉴)
- 게임마다 배경·아이콘·타이틀 위치를 꾸미는 화면 설정

## 이 저장소에 있는 것

- **Releases**: 설치 파일
- **catalog.json**: 라이브러리 목록. 설치된 Homeport가 이 파일을 읽어 목록을 갱신합니다.

소스 코드는 공개하지 않습니다.

## 라이선스

© 2026 codeBOK. All rights reserved. 무료로 내려받아 개인적으로 사용할 수 있습니다. 복제·수정·재배포는 허락 없이 금지됩니다.
각 리컴프 프로젝트와 원작 게임의 권리는 각 소유자에게 있습니다. Homeport는 게임 파일을 포함하거나 내려받지 않습니다.
