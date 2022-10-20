## 1.0.2.6 : 2022-10-20 16:03:06

### New feature or Enhancement
##### Editor
  - [Action] 플레이어 스폰 시 이동 및 점프 관련 값을 Testing 옵션을 통해 제어할 수 있는 옵션 추가 (#t4f-397)
    - 기본값(0)을 사용할 경우 Character Entity의 경우 Entity Testing 값을 사용
  - [Action] FacialAnimation Action, LiveLink 레코딩 시 자동 녹화 딜레이 및 종료 옵션 추가 (#t4f-374)
  - [Level] T4Framework Mode내 MainProject SpawnData 와 Replay를 플레이할 수 있는 기능 추가 (#t4f-403)

### Bugfix
##### Editor
  - [Entity] Costume Entity, CostumePartMeshData에서 bFace처리 삭제 - PartName이 Face만 체크 (#t4f-396)
  - [Common] T4F 에디터에서 오픈한 레벨을 레벨에디터에서 다시 오픈할 경우 발생하는 크래시 수정 (#t4f-395)

## 1.0.2.5 : 2022-10-18 17:00:45

### New feature or Enhancement
##### Editor
  - [Action] Animation/ControlRig/FacialAnimation Track 우클릭 서브메뉴에 Change PlayMode Duration (AutoFit) 추가 (#t4f-374)
  - [Action] Facial Animation Action내 LiveLinkFace와 연동한 AnimSequence 레코딩 기능 추가 (#t4f-374)
  - [Entity/Portrait Generator] 애니메이션의 일부 구간을 지정한 Sec 간격으로 다수의 이미지를 생성해주는 기능 추가 (#t4f-360)

### Bugfix
##### Editor
  - [Action] Reaction Action이 타임라인 TogglePlay(Pause/Play)가 적용되지 않던 문제 수정 (#t4f-380)
  - [Entity] Skill Layer의 AnimSequence Name (Skill)이 추가되지 않는 문제 수정 (#t4f-378)
  - [Animation] 메타휴먼 데이터가 없는 사용자 프로젝트 쿠킹 시, 메타휴먼용 Facial Anim Instance Cook 오류 문제 수정 (#t4f-391)
\t- 에디터 실행 시 meta human data 존재 여부에 따라  target skeleton을 변경
  - [Animation] Facial AnimBP의 live link 관련 노드가 깨지는 문제 수정 (#t4f-391),