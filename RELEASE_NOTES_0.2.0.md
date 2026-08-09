# This is a Viewer 0.2.0

## English

This release adds lightweight playback for short local video clips while
keeping the app focused on fast image browsing.

### What’s New

- Open MP4, M4V, and MOV files alongside images in folders and file lists.
- Play or pause, scrub through time, change speed between 0.5× and 2×, loop
  automatically, and toggle mute with `M`. `Page Up` and `Page Down` seek one
  second backward or forward. New videos always start muted.
- Show motion badges for videos, GIF, APNG, and animated WebP thumbnails, with
  optional duration labels.
- Select and copy an area from a paused video frame or animation without
  modifying the source file.
- Keep the status bar height and right-side metadata positions stable when
  switching among still images, animations, and videos.
- Prevent stale images or late video loads from replacing the final item after
  rapid navigation.

### Compatibility

Video decoding uses the codecs available through AVFoundation on macOS. This
release does not add WebM, streaming, subtitles, a volume mixer, or video
editing. Read-only PDF viewing is planned separately for 0.3.0.

Requires an Apple Silicon Mac with macOS 14 or later.

## 한국어

빠른 이미지 탐색이라는 제품 범위를 유지하면서 로컬의 짧은 영상형
움짤을 함께 볼 수 있게 한 버전입니다.

### 새로운 기능

- 폴더와 파일 목록에서 이미지와 함께 MP4·M4V·MOV를 엽니다.
- 재생·중지, 시간 탐색, 0.5×·1×·1.5×·2× 배속, 자동 반복과 `M` 음소거
  전환을 지원합니다. `Page Up`과 `Page Down`은 1초씩 뒤로·앞으로
  이동합니다. 새로 선택한 비디오는 항상 음소거로 시작합니다.
- 비디오·GIF·APNG·animated WebP 썸네일에 모션 배지를 표시하고, 재생
  시간은 선택적으로 표시할 수 있습니다.
- 원본을 변경하지 않고 정지한 비디오 프레임이나 애니메이션에서 영역을
  선택해 복사할 수 있습니다.
- 정지 이미지·애니메이션·비디오를 전환해도 상태 막대 높이와 우측
  metadata 위치가 움직이지 않습니다.
- 빠르게 탐색할 때 늦게 끝난 비디오 요청이나 이전 이미지가 마지막
  선택을 덮어쓰지 않게 했습니다.

### 호환성

비디오는 macOS AVFoundation이 제공하는 코덱으로 재생합니다. WebM,
스트리밍, 자막, 음량 믹서와 영상 편집은 포함하지 않습니다. 읽기 전용
PDF 보기는 0.3.0에서 별도로 진행할 예정입니다.

macOS 14 이상이 설치된 Apple Silicon Mac이 필요합니다.
