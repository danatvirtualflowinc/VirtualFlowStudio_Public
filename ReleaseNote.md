## 1.0.2.4 : 2022-10-14 18:35:43

## 1.0.2.3 : 2022-10-14 17:44:07

### New feature or Enhancement
##### Editor
  - [Entity] Portrait 설정 시 Facial Anim Layer에 있는 Animation Section 도 사용할 수 있도록 옵션 기능 처리 (#t4f-377)
  - [Entity] Portrait 생성 이미지 품질 개선 (모아레 제거, 최대 4096 해상도까지 지원) (#t4f-382)
  - [Entity] Entity/Portrait Preview World로 MapEntity를 사용할 수 있도록 기능 처리 (#t4f-361)

### Bugfix
##### Client or Server 
  - [Server] NPC Behavior 옵션 EnemyType 설정이 정상적으로 동작하지 않던 문제 수정 (#t4f-369)

##### Editor
  - [Action] 시뮬레이션 모드에서의 좌클릭 액션 플레이가 동작하지 않던 문제 수정 (#t4f-379)
    - 좌클릭은 리플레이 등의 다른 기능과 연계가 많아 편집 중인 액션 플레이를 \"F\" 키로 변경함
  - [Action] Timeline TogglePlay 시 Animation/Facial Track의 애니메이션이 반응하지 않던 문제 수정 (#t4f-380)

### AssetUpdate (Dev to TD)
  - Content\\VirtualFlow\\SystemPack\\System\\AnimBP\\RefSkeleton\\BP_Human_MetaHuman_Face_Skeleton
  - Content\\VirtualFlow\\SystemPack\\System\\AnimBP\\RefSkeleton\\RefMocap\\mh_arkit_mapping_anim
  - Content\\VirtualFlow\\SystemPack\\System\\AnimBP\\RefSkeleton\\RefMocap\\mh_arkit_mapping_pose
  - Content\\VirtualFlow\\SystemPack\\System\\AnimBP\\T4AnimBP_Human_BasicFace
  - Content\\VirtualFlow\\SystemPack\\System\\AnimBP\\T4AnimBP_Human_MetaHumanFace

## 1.0.2.2 : 2022-10-13 19:13:37

### Bugfix
##### Editor
  - [World] 실행 시 간헐적으로 설정된 MapEntity 레벨 로드 시 발생하는 크래시 예외 처리 (#t4f-376)

##### Common
  - [Common] 패키징 종료 시 발생하는 크래시 수정 (#t4f-375)

## 1.0.2.1 : 2022-10-13 14:01:01

### New feature or Enhancement
##### Client or Server
  - [Editor/Client] TileBase일때 장비창의 Costume의 Group분류 (#t4f-339)
  - [Client] 점프 중 충돌 시, 점프는 종료하고 낙하 상태로 전이되도록 수정 (#t4f-365)

##### Editor
  - [Action] CameraWork Action 프로퍼티 이름 변경 (Use Looping => Pause At The End) (#t4f-321)
    - 마지막 카메라 위치에서 멈추는 옵션이라 네이밍을 정리함

##### Common
  - [Action] Facial Animation Action 기능 추가 (#t4f-299)
    - 참조 : [Facial Animation Action 제작](https://virtualflow.atlassian.net/wiki/spaces/VIRTUALFLOWINTERNAL/pages/98631702/Face+Mesh+Module+Facial+Animation+Action)


### Bugfix
##### Client or Server 
  - [Client/Server] NPC 간 이동중 충돌이 발생할 경우 클라이언트 위치가 어긋나는 문제 수정 (#t4f-367)
  - [Editor/Client] 특정한 상황에서 Dialogue 2D의 Z order가 꼬이는 문제 (#t4f-333)
  - [Editor/Client] PIE Mode, NPC와의 인터렉트 이후 Quest를 통해 영상 재생 시 이전 대화 상자가 Hide 되지 않는 문제 (#t4f-353)
  - [Client] DialogueTalk의 UseLookAt 옵션 적용이 일정 시간 이후 초기화 되는 문제 수정 (#t4f-321)
  - [Server] Effect의 Chain Effect로 Hit Effect를 사용하는 경우, 데미지 적용이 되지 않는 문제 수정 (#t4f-337)

##### Editor
  - [GameDB] 일부 구버전 프로젝트DB 테이블의 폴더 내 아이템이 DB에 출력되지 않던 문제 수정 (#1230)
  - [Character/Costume] Customizing Rig가 적용 된 부분(Face)이 MaterPart가 될 때, Mesh 출력이 되지 않는 문제 수정 (#t4f-355)

### AssetUpdate (Dev to TD)
  - #t4f-339 테이블 데이터 업데이트
   - Localization/Editor/T4EditorMasterConstantTable.uasset
   - Localization/Editor/Constants/T4Constant_EquipPartsGroupTable.uasset
   - Localization/System/T4GameplayEquipPartsGroupDataTable.uasset,