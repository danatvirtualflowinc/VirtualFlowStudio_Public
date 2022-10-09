## 1.0.2.0 : 2022-10-09 21:37:23

### New feature or Enhancement
##### Editor
  - [Common] 에디터 StatusBar \"버추얼플로우 스튜디오\" 레이아웃 개선 (#t4f-359)

### Bugfix
##### Client or Server 
  - [Common] 2단점프와 Enable Movement While Jumping 옵션이 동작하지 않는 문제 수정 (#t4f-348)

##### Editor
  - [World] Map Entity 오픈 후 WorldExplorer에서 Map Entity 세팅 시 발생하는 크래시 수정 (#t4f-356)
    - 해당 조건에서는 메시지를 띄운 후 WorldExplorer 실행을 취소하도록 처리 (다른 툴을 닫고 다시 시도)
  - [World] 미니맵 생성을 위해 Map Entity 세팅 시 발생하는 크래시 수정 (#t4f-349)
  - [Action] Timeline Play or Pause로 편집 ActionPack 플레이가 정상적으로 동작하지 않던 문제 수정 (#t4f-305)
  - [Entity] Weapon Entity, EditMode AttachPoint 변경 시 기즈모 업데이트가 되지 않던 문제 수정 (#t4f-357)
,