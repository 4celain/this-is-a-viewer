# This is a Viewer 0.2.1

## English

This maintenance update improves tall-image navigation and keeps the viewer
stable during video playback.

### What’s New

- Start vertically scrollable screenshots and other tall images at the top
  instead of the middle. Images that fit entirely in the viewport remain
  centered.
- Use Up Arrow and Down Arrow to scroll the focused image canvas. Page Up and
  Page Down scroll by one viewport for still images, while retaining frame or
  one-second seeking for animation and video.
- Keep Up Arrow and Down Arrow thumbnail navigation when the sidebar owns
  keyboard focus.
- Prevent repeated window and toolbar layout updates from making the sidebar
  appear to shake while an MP4, M4V, or MOV file is playing.

Requires an Apple Silicon Mac with macOS 14 or later.

## 한국어

긴 이미지 탐색을 자연스럽게 다듬고 비디오 재생 중 화면 안정성을
개선한 유지보수 업데이트입니다.

### 새로운 기능

- 세로로 긴 스크린샷처럼 화면 높이를 넘는 이미지는 중앙이 아닌
  최상단부터 표시합니다. 화면 안에 전체가 들어오는 이미지는 기존처럼
  중앙에 표시합니다.
- 이미지 화면에 키보드 포커스가 있으면 `↑`·`↓`로 조금씩 스크롤하고,
  정지 이미지에서는 `Page Up`·`Page Down`으로 한 화면씩 이동합니다.
  애니메이션과 비디오에서는 기존 프레임·1초 이동 동작을 유지합니다.
- 사이드바에 키보드 포커스가 있으면 `↑`·`↓`로 이전·다음 썸네일을
  탐색하는 기존 동작을 유지합니다.
- MP4·M4V·MOV 재생 중 반복적인 창·도구 막대 레이아웃 갱신 때문에
  사이드바가 흔들려 보이던 현상을 수정했습니다.

macOS 14 이상이 설치된 Apple Silicon Mac이 필요합니다.
