# NeprItem

Sephiria용 독립 아이템 모드. 기존 Nepr 아이템 41개와 버프 7개를 포함합니다.

## 설치

[최신 Releases](https://github.com/JYGOOD00/NeprItem/releases/latest)에서 NeprItem 버전 ZIP을 받고 압축 안의 NeprItem 폴더를 게임의 AddOns에 넣으세요. 게임을 종료한 상태에서 설치하세요. ModMakerRuntime과 편집기는 플레이에 필요하지 않습니다. 구형 ModMakerRuntime/Mods/Nepr을 함께 사용하면 중복 ID가 발생합니다.

## 자동 업데이트

게임 시작 후 새 버전이 있으면 게임 기본 예/아니오 창이 표시됩니다. 예를 누르면 다운로드와 해시 검증 후 게임 종료 시 설치합니다. 아니오는 이번 실행에서 건너뜁니다. 설치 완료는 다음 실행에서 안내합니다. 다른 모드와 무기 모드는 변경하지 않습니다. latest.json은 업데이트용이며 직접 내려받을 필요는 없습니다.

## 전용 편집기

NeprItemEditor.zip 전체를 압축 해제하여 NeprItemEditor.exe를 실행하세요. 게임 폴더의 NeprProjects/NeprItem/mod.json을 엽니다. 기본 수치, 강화별 스탯, 발동 효과, 조건, 장착 이미지, 설명/번역, 버프를 편집할 수 있습니다. 원본 프로젝트가 있어야 편집과 빌드가 가능합니다. 빌드에는 .NET SDK 8 및 PowerShell 7이 필요합니다. 실행 중인 게임에는 DLL을 덮어쓰지 않습니다. 실시간 아이템 적용은 현재 제공하지 않습니다.

## 검증 범위

독립 DLL 빌드, 기존 설정과 Assets 보존, 배포 해시, 업데이트 실패 복구를 검사했습니다. 실제 전투와 원격 게스트 전체 실플레이 검증은 아직 필요합니다.

## 출처

MIT 라이선스의 ModMaker 아이템 처리 코드 일부를 독립 런타임으로 이식했습니다. 배포본에 원저작권 및 Harmony 라이선스를 포함합니다. ModMakerRuntime.dll을 로드하거나 의존하지 않습니다.
