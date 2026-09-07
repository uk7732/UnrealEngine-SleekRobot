# UnrealEngine-SleekRobot

## 📄 기술문서

프로젝트의 구현 내용은 아래 기술문서에서 확인할 수 있습니다.

### [⬇️ 기술문서 PDF 다운로드](https://github.com/uk7732/UnrealEngine-SleekRobot/raw/refs/heads/main/박동욱_기술문서.pdf)

[GitHub에서 기술문서 바로 보기](./박동욱_기술문서.pdf)

파일: **박동욱_기술문서.pdf** (약 20 MB)

## 소스 코드 살펴보기

Unreal Engine 5.5 프로젝트의 C++ 코드와 프로젝트 설정을 정리한 저장소입니다.

| 구현 영역 | 코드 위치 |
| --- | --- |
| 캐릭터 및 플레이어 제어 | [Characters](Source/FrontendUI/Private/Characters), [Controllers](Source/FrontendUI/Private/Controllers) |
| 능력치·장비·인벤토리·스킬 컴포넌트 | [Component](Source/FrontendUI/Private/Component) |
| 스킬 동작 및 투사체 | [SkillAction](Source/FrontendUI/Private/SkillAction), [Actor](Source/FrontendUI/Private/Actor) |
| 몬스터 AI 및 스폰 | [BTService](Source/FrontendUI/Private/BTService), [TaskNode](Source/FrontendUI/Private/TaskNode), [Spawn](Source/FrontendUI/Private/Spawn) |
| 게임 진행 및 스테이지 | [GameMode](Source/FrontendUI/Private/GameMode), [TriggerBox](Source/FrontendUI/Private/TriggerBox) |
| UI 및 옵션 화면 | [Widgets](Source/FrontendUI/Private/Widgets), [Subsytems](Source/FrontendUI/Private/Subsytems) |
| 데이터 테이블 로딩 및 구조 | [TableSubsystem.cpp](Source/FrontendUI/Private/Instance/TableSubsystem.cpp), [TableDatas.h](Source/FrontendUI/Public/Table/TableDatas.h) |

## 저장소 구성

- [Source/](Source): C++ 소스·헤더, 모듈 빌드 설정 및 게임·에디터 타깃 파일
- [FrontendUI.uproject](FrontendUI.uproject): 엔진 버전, 모듈 및 플러그인 설정
- [Config/](Config): 입력, 충돌 채널, 기본 맵, UI 및 게임플레이 태그 설정
- [TableCSV/](TableCSV): 데이터 테이블의 열 구조를 담은 CSV 템플릿 23개. 현재 파일은 헤더만 있으며 실제 게임 데이터 행은 포함하지 않습니다.

