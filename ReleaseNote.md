## 1.0.2.9 : 2022-10-24 18:21:39

### New feature or Enhancement
##### Client or Server
  - [Editor/Client] Weapon/Costume/Goods DB Folder기능 제거와 이동 (#t4f-368)

##### Editor
  - [Content] 프로젝트 신규 생성 시 자동 생성 애셋들은 생후 자동 저장하도록 개선 (#t4f-156)
  - [Action] Entity Browser, Drag&Drop 한 캐릭터를 \"CTRL + 마우스 좌클릭\"로 플레이어 캐릭터 교체 지원 (#t4f-305)
  - [VFStudio] 프로젝트 리스트에서 \"Set MainProject\" 클릭 시 스크롤이 최상단으로 이동하도록 개선 (#t4f-410)
  - [Customizing Rig] Rig Group 이름을 사용자가 지정할 수 있도록 개선 (#t4f-371)
  - [Level] T4Framework Mode, 스폰 위치를 LeftShift + Mouse L-Click 으로 업데이트 할 수 있도록 개선 (#t4f-403)

### Bugfix
##### Client or Server 
  - [Client] 에디터를 통해 서버 실행시 DB파일 못찾는 문제 수정

##### Editor
  - [Action] Reaction Action의 TogglePlay가 정상적으로 동작하지 않던 문제 수정 (#t4f-380)
  - [Action] ActionPlayMode Looping 시 MaxPlayTimeSec와 관계없이 무한정 플레이 바가 이동하는 문제 수정 (#t4f-380)
  - [Entity] Character Entity 생성 후 애니메이션 적용 시 뷰포트 내 캐릭터 위치가 내려앉는 문제 수정 (#t4f-372)
  - [Level] T4Framework Mode, 모듈러 파츠 캐릭터의 파츠에 애니메이션이 적용되지 않던 문제 수정 (#t4f-407)
  - [Level] T4Framework Mode, 뷰포트  마우스 좌클릭 시 Selection SubMenu가 출력되는 문제 수정 (#t4f-403)
  - [VFStudio] Project Search 메뉴가 동작하지 않던 문제 수정 (#t4f-410)

### AssetUpdate (Dev to TD)
  - Editor 테이블
   - Content\\VirtualFlow\\Localization\\Editor\\T4EditorMessageDataTable.uasset
  - UI 리소스
   - Content\\VirtualFlow\\UIPack\\Template\\TileBase\\InGame\\T4Inventory_TileBase.uasset,