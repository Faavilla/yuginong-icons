# Changelog

## 0.1.1

- 게시자(publisher)를 색 테마와 같은 `yuginong-themes`로 바꿈. 확장 ID가 `faavilla.yuginong-icons`에서 `yuginong-themes.yuginong-icons`로 바뀌므로, 0.1.0을 설치했다면 먼저 지우고 설치해야 함 (`code --uninstall-extension faavilla.yuginong-icons`)
- 아이콘 테마 ID를 `yuginong-icons`에서 `Yuginong Icons`로 바꿈. 설정에 `"workbench.iconTheme": "Yuginong Icons"`로 저장되어 색 테마(`"workbench.colorTheme": "Yuginong Light"`)와 같은 형식이 됨. 업데이트 후 기본 아이콘으로 돌아가면 `Preferences: File Icon Theme`에서 다시 골라야 함
- `package.json`을 색 테마와 같은 형식으로 정리: 한국어 설명, VS Code 1.90 이상, 같은 필드 구성
- 아이콘 변경 없음

## 0.1.0

첫 릴리스입니다.

- 16×16 아웃라인 아이콘 300개: 파일 아이콘 158종, 폴더 아이콘 71종(닫힘·열림)
- 확장자 494개, 파일 이름 346개, 언어 ID 148개, 폴더 이름 244개 연결
- Hugo 블로그 구조 우선 지원 (`hugo.toml`, `_index.md`, `archetypes`, `layouts/_partials`, `_shortcodes`, `_markup` 등)
- 웹 프레임워크, 60종이 넘는 프로그래밍·설정 언어, 빌드 도구, CI, 인프라, 문서·미디어 파일 지원
- 생성물·외부 코드를 흐린 색으로 구분
- 워크스페이스 루트 폴더 전용 녹색 아이콘
