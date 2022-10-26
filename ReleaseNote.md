## 1.0.3.0 : 2022-10-26 16:16:32

### New feature or Enhancement
##### Client or Server
  - [Editor/Client] Weapon/Costume/Goods DB Folder기능 제거와 이동 (#t4f-368)
  - [Server] 싱글 플레이시 TCP통신 대신 메모리 통신 기능 추가 (#T4F-428)

##### Editor
  - [Content] ProjectSettings 내 ServiceEnabled 옵션을 Private 로 변경 (#t4f-410)
    - Private 옵션을 켜면, VFStudio 등의 프로젝트 리스트에서 제외, VFStudio의 ServiceEnabled 도 함께 제거됨.
  - [Entity] 메타휴먼 캐릭터의 파츠별 LODSync 정보를 파츠 교환 시 머지 후 자동으로 반영되도록 개선 (#t4f-417)
    - 기존 LODSync 정보가 Costume Entity의 MeshParts/AttachParts 별로 별도의 LOD 정보를 가지도록 수정
  - [Action] Action Editor, 말풍선 액션 트랙 추가 (#t4f-331)
  - [Editor/Client] UIOverride에 UIPreview 추가와 Layout 개선 (#t4f-413)
### Bugfix
##### Client or Server 
  - [Client] 메타휴먼 캐릭터의 LODSync 설정이 정상적으로 반영되지 않던 문제 수정 (#t4f-417)
  - [Editor] TileBase, 아이템장착 해제 후 시뮬레이션모드 재진입시 에디터크래쉬가 나는 문제 (#t4f-423)

##### Editor
  - [Portrait] Portrait Genenrator에서 Facial Animation을 사용 하면, 애니매이션 Pause가 안 되는 문제 수정 (#t4f-421)
  - [Portrait] Portrait Genenrator에서 Export Image Sequence 사용 시, 애니매이션 설정 영역 외에도 계속 출력되는 문제 수정(#t4f-421)
  - [Common] 레벨에 T4GameActor 저장 또는 저장된 T4GameActor 로드 금지, 재장 시 제외 처리 (#t4f-431)
    - 작업 과정에 레벨에 T4GameActor가 저장되어 Assert를 유발하는 문제 대응,