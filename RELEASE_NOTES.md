# This is a Viewer 0.2.2

Version: `0.2.2 (13)`

## English

### Changes

- Added a collapsible folder navigator next to the thumbnail sidebar.
- Added Favorites and Recents for folders, ZIP files and CBZ files. Favorites
  can be reordered by dragging, and add, remove, reorder and clear actions can
  be undone with `Command-Z`.
- Added lazy folder-tree expansion and an option to include supported media
  from descendant folders.
- Added direct drag-and-drop opening. A folder or archive is saved as a
  Favorite only when it is dropped on the folder navigator.
- Added container-first natural sorting when several folders or ZIP/CBZ
  archives are opened together, keeping each container's images together.
- Improved video audio controls and kept the selected mute state while the
  app remains open. Each new app launch still starts muted.
- Prevented the Delete shortcut from removing a real folder or the currently
  viewed media while keyboard focus is in the folder navigator.

The update signing information has changed, so this update must be installed
manually once. Download the 0.2.2 DMG and install it over the existing app.
Automatic updates will resume after that.

### Supported environment

- macOS 14 Sonoma or later
- Apple Silicon Mac
- Direct and Mac App Store editions
- ZIP and CBZ archives

RAR, 7z and CBR are not supported in this release. ZIP and CBZ files appear as
single items in the folder tree; folders inside an archive are not expanded in
the tree.

---

## 한국어

### 변경 사항

- 썸네일 사이드바 옆에 접을 수 있는 폴더 탐색 패널을 추가했습니다.
- 폴더·ZIP·CBZ 즐겨찾기와 최근 항목을 추가했습니다. 즐겨찾기는 드래그로
  순서를 바꿀 수 있고 추가·제거·순서 변경·전체 제거를 `Command-Z`로
  되돌릴 수 있습니다.
- 필요한 시점에만 폴더 트리를 펼치며, 하위 폴더의 지원 미디어까지
  포함하는 옵션을 추가했습니다.
- 드래그 앤 드롭으로 바로 열 수 있습니다. 폴더 탐색 영역에 놓은
  폴더·압축파일만 즐겨찾기에 저장됩니다.
- 여러 폴더·ZIP·CBZ를 함께 열 때 컨테이너 우선 자연 정렬을 적용해 각
  폴더나 압축파일의 이미지가 서로 섞이지 않게 했습니다.
- 영상 음량 조절을 개선하고 앱을 종료하기 전까지 선택한 음소거 상태를
  유지합니다. 앱을 새로 실행할 때는 기본 음소거로 시작합니다.
- 폴더 탐색기에 키보드 포커스가 있을 때 Delete 단축키가 실제 폴더나
  현재 미디어를 삭제하지 않도록 차단했습니다.

업데이트 서명 정보가 변경되어 이번 업데이트만 직접 설치해야 합니다.
0.2.2 DMG를 받아 기존 앱 위에 설치하면 됩니다. 이후부터는 다시 자동
업데이트됩니다.

### 지원 환경

- macOS 14 Sonoma 이상
- Apple Silicon Mac
- Direct판과 Mac App Store판
- ZIP·CBZ 압축파일

RAR·7z·CBR는 이번 버전에서 지원하지 않습니다. ZIP·CBZ는 폴더 트리에서
하나의 파일 항목으로 표시하며 압축파일 내부 폴더를 트리로 펼치지는
않습니다.
