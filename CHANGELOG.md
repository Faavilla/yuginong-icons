# Changelog

## 0.2.1

글자를 픽셀 격자에 맞춰 다시 배치했습니다. 글자 표·색·연결은 0.2.0과 같고, `.lockb`만 추가했습니다.

- 모든 획 중심을 0.5px 격자에 맞춤. 일반(1x) 화면에서 4글자 라벨(HTML·JSON·TOML·SCSS 등)이 뭉개지던 것과 레티나에서 획 양옆이 흐리던 것을 줄임
- 글자 사이를 1픽셀로 통일. 1–2글자는 가운데, 3–4글자는 왼쪽 첫 열부터 시작해 목록에서 세로줄이 맞음
- 4글자의 좁은 글자 폭 2.114 → 2. 4글자 안의 M·W는 보통 글자를 3/4 폭으로 줄여 씀 (한 라벨에 M·W가 둘이면 좁은 글자 유지)
- V의 세로획을 짧게, 사선을 길게 해 U와 구분
- 선 굵기 1.2px 유지
- `.lockb`(bun) → LOCK
- README: 색 설명(중립·흐린 중립은 테마 회색을 조정한 색)과 lock 파일 설명을 실제 동작에 맞게 고침

## 0.2.0

그림 기호 대신 확장자 글자를 보여 주는 디자인으로 다시 만들었습니다. 확장 ID와 아이콘 테마 ID는 0.1.1과 같아서 새 `.vsix`를 설치하면 그대로 바뀝니다.

### 파일

- 테두리·배경 없이 확장자 글자만 표시 (`.md`는 MD, `.json`은 JSON). 1.2px 선으로 그린 경로라 글꼴과 상관없이 같은 모양
- 최대 4글자. 1–3글자는 보통 폭에 글자 사이 최대 1.2px, 4글자는 좁은 글자로 16px을 채움
- 확장자로만 구분: 파일 이름별 아이콘(`README.md`, `package.json`, `hugo.toml`, `_index.md` 등)과 두 단 확장자(`*.test.ts`, `*.d.ts`, `*.min.js`) 연결을 없앰. 이런 파일은 마지막 확장자 글자로 보임
- 확장자 없는 이름 26개(`LICENSE`, `Dockerfile`, `Makefile`, `Procfile` 등)만 이름 약어로 연결. 점으로 시작하는 파일(`.gitignore`, `.editorconfig`)은 확장자로 연결
- 이미지·오디오·영상·폰트·압축·오피스·3D·디자인 파일은 확장자 그대로 표시 (PNG, JPG, MP4, WOFF, ZIP 등)
- 한 아이콘을 같이 쓰던 다른 형식·언어를 나눔: 셸(BAT, CMD, FISH, NU), 템플릿 엔진(PUG, NJK, LIQ, TWIG, HBS, EJS, ERB, JINJ, JSP, RAZR), 빌드(CMAK, GRDL, BZL), 다이어그램(DIO, MMD, PUML, EXC, D2), 셰이더(GLSL, HLSL, WGSL, MTL) 등
- 확장자 추가: 이미지(HEIC, JXL, 카메라 RAW 등), 영상·오디오, 3D·CAD, 압축·설치 파일, 문서·전자책·자막, 데이터·머신러닝 파일, 언어 30여 종
- 형식을 모르는 파일은 기본 파일 모양

### 폴더

- 닫힌 폴더·열린 폴더 두 가지만 남김. 특수 폴더 아이콘 70종과 루트 폴더 아이콘 없앰
- 색을 중립 회색 → Yuginong Light 강조색 녹색 `#13694D`으로 바꿈

### 수치

- 아이콘 300개 → 424개 (파일 글자 421종 + 파일·폴더·열린 폴더)
- 연결: 확장자 494개 → 671개, 파일 이름 346개 → 26개, 언어 ID 148개, 폴더 이름 244개 → 0개

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
