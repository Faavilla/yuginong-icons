# Yuginong Icons

Text-label file icons for VS Code, made to pair with the Yuginong Light color theme.

Yuginong Light 컬러 테마와 함께 쓰도록 만든 VS Code 파일·폴더 아이콘 테마입니다. 파일은 그림 대신 확장자 글자로 보여 줍니다.

클로드랑 같이 만들었습니다.

## 특징

<!-- stats:start -->
- 아이콘 424개: 파일 글자 421종과 기본 아이콘 3개(형식을 모르는 파일, 닫힌 폴더, 열린 폴더)입니다. 확장자 671개, 확장자 없는 파일 이름 26개, 언어 ID 148개에 연결됩니다.
<!-- stats:end -->
- 파일은 테두리나 배경 없이 확장자 글자만 보여 줍니다. `.md`는 MD, `.json`은 JSON, `.png`는 PNG입니다.
- 글자는 1.2px 선으로 직접 그린 경로입니다. 설치된 글꼴과 상관없이 어디서나 같은 모양으로 보입니다.
- 글자는 최대 4글자입니다. 1–3글자는 보통 폭으로 글자 사이를 넉넉히 띄우고, 4글자는 좁은 글자로 16px 폭을 꽉 채웁니다.
- 확장자로만 구분합니다. 이미지·영상·폰트·압축·문서 같은 형식 파일은 확장자를 그대로 쓰고, 프로그래밍 언어는 변형 확장자를 하나로 묶습니다(`.ts`, `.mts`, `.cts`는 모두 TS).
- 폴더는 닫힌 폴더와 열린 폴더 두 가지뿐이며, Yuginong Light의 강조색인 녹색입니다.
- Yuginong Light 팔레트에서 가져온 색만 씁니다. 모든 색이 탐색기의 기본·hover·선택 배경에서 대비 3:1 이상입니다.
- lock 파일, 로그, 소스맵, 컴파일 결과물, 백업처럼 만들어지거나 임시로 생기는 파일은 흐린 색으로 구분합니다.
- 라이트 테마 전용입니다.

## 설치

마켓플레이스에는 올리지 않고 [GitHub Releases](https://github.com/Faavilla/yuginong-icons/releases)에서 `.vsix`로 배포합니다.

1. Releases에서 `yuginong-icons-<버전>.vsix`를 내려받습니다.
2. VS Code 명령 팔레트에서 `Extensions: Install from VSIX...`를 실행하거나, 터미널에서 설치합니다.

   ```bash
   code --install-extension yuginong-icons-0.2.0.vsix
   ```

3. 명령 팔레트에서 `Preferences: File Icon Theme`를 열고 **Yuginong Icons**를 고릅니다.

자동 업데이트는 되지 않습니다. 새 버전의 `.vsix`를 같은 방법으로 설치하면 기존 버전을 덮어씁니다.

## 색

| 색 | 쓰임 |
|---|---|
| `#585C78` 중립 | 형식을 모르는 파일, 텍스트, 설정, 셸 |
| `#686C88` 흐린 중립 | 생성물·임시 파일 |
| `#8B2B4E` 와인 | CSS·Sass, Ruby, Scala, 인증서·키, 디자인 파일 등 |
| `#4D337B` 보라 | Markdown·문서, 폰트, 전자책, Kotlin, C# 등 |
| `#832508` 주황 | HTML·템플릿, Git, Rust, Java, Swift, 빌드 도구 등 |
| `#6C5001` 호박 | JavaScript, JSON·TOML·YAML 등 데이터, 압축 파일 |
| `#205462` 파랑 | TypeScript, Python, Docker, C·C++, 워드 문서 등 |
| `#0A7272` 청록 | Go, 이미지·오디오·영상·3D·자막 등 |
| `#13694D` 녹색 | 폴더 |

## 아이콘

<!-- icons:start -->
| 아이콘 | 쓰임 |
|---|---|
| 파일 모양 (중립) | 형식을 모르는 파일 |
| 닫힌 폴더 (녹색) | 모든 폴더 |
| 열린 폴더 (녹색) | 펼친 폴더 |

<details>
<summary>파일 글자 421종</summary>

| 글자 | 색 | 확장자 | 파일 이름 | 언어 ID |
|---|---|---|---|---|
| 3DM | 청록 | `.3dm` |  |  |
| 3DS | 청록 | `.3ds` |  |  |
| 3GP | 청록 | `.3gp` |  |  |
| 3MF | 청록 | `.3mf` |  |  |
| 7Z | 호박 | `.7z` |  |  |
| AAB | 호박 | `.aab` |  |  |
| AAC | 청록 | `.aac` |  |  |
| AAR | 호박 | `.aar` |  |  |
| ABC | 청록 | `.abc` |  |  |
| ADA | 파랑 | `.ada`, `.adb`, `.ads` |  | `ada` |
| ADOC | 보라 | `.adoc`, `.asciidoc` |  |  |
| AFD | 와인 | `.afdesign` |  |  |
| AFM | 보라 | `.afm` |  |  |
| AFP | 와인 | `.afphoto` |  |  |
| AI | 와인 | `.ai` |  |  |
| AIFF | 청록 | `.aif`, `.aiff` |  |  |
| AMR | 청록 | `.amr` |  |  |
| APE | 청록 | `.ape` |  |  |
| APK | 호박 | `.apk` |  |  |
| APNG | 청록 | `.apng` |  |  |
| APPX | 호박 | `.appx` |  |  |
| ASC | 와인 | `.asc` |  |  |
| ASDF | 중립 | `.tool-versions` |  |  |
| ASE | 와인 | `.ase`, `.aseprite` |  |  |
| ASM | 중립 | `.asm`, `.nasm`, `.s` |  | `arm`, `asm`, `nasm` |
| ASS | 청록 | `.ass` |  |  |
| ASTR | 보라 | `.astro` |  | `astro` |
| AUTH | 보라 |  | `authors`, `contributors`, `maintainers` |  |
| AVI | 청록 | `.avi` |  |  |
| AVIF | 청록 | `.avif` |  |  |
| AVRO | 호박 | `.avro`, `.avsc` |  |  |
| AWK | 중립 | `.awk` |  | `awk` |
| AZW | 보라 | `.azw` |  |  |
| AZW3 | 보라 | `.azw3` |  |  |
| BABL | 호박 | `.babelrc` |  |  |
| BAK | 흐린 중립 | `.bak`, `.old` |  |  |
| BAL | 청록 | `.bal` |  |  |
| BAT | 중립 | `.bat` |  | `bat` |
| BDF | 보라 | `.bdf` |  |  |
| BIB | 보라 | `.bib` |  | `bibtex` |
| BICP | 파랑 | `.bicep` |  |  |
| BIN | 흐린 중립 | `.a`, `.bin`, `.class`, `.dll`, `.dylib`, `.elf`, `.exe`, `.gch`, `.ilk`, `.lib`, `.o`, `.obj`, `.out`, `.pch`, `.pdb`, `.pyc`, `.pyd`, `.pyo`, `.rlib`, `.so` |  |  |
| BLND | 청록 | `.blend` |  |  |
| BMP | 청록 | `.bmp` |  |  |
| BREW | 와인 |  | `brewfile` |  |
| BZ2 | 호박 | `.bz2` |  |  |
| BZL | 주황 | `.bazel`, `.bzl`, `.star` |  | `bazel`, `starlark` |
| C | 파랑 | `.c` |  | `c` |
| C# | 보라 | `.cs`, `.csx` |  | `csharp` |
| C4D | 청록 | `.c4d` |  |  |
| CAB | 호박 | `.cab` |  |  |
| CADY | 청록 |  | `caddyfile` |  |
| CAF | 청록 | `.caf` |  |  |
| CBL | 파랑 | `.cbl`, `.cob`, `.cpy` |  | `cobol` |
| CBR | 보라 | `.cbr` |  |  |
| CBZ | 보라 | `.cbz` |  |  |
| CDR | 와인 | `.cdr` |  |  |
| CFG | 중립 | `.browserslistrc`, `.cfg`, `.code-workspace`, `.conf`, `.editorconfig`, `.entitlements`, `.ini`, `.mf`, `.nvmrc`, `.pbxproj`, `.plist`, `.properties`, `.swcrc`, `.xcconfig` |  | `ini`, `properties` |
| CHG | 보라 |  | `changelog` |  |
| CHM | 보라 | `.chm` |  |  |
| CKPT | 보라 | `.ckpt` |  |  |
| CLIP | 와인 | `.clip` |  |  |
| CLJ | 파랑 | `.clj`, `.cljc`, `.cljs` |  | `clojure` |
| CMAK | 주황 | `.cmake` |  | `cmake` |
| CMD | 중립 | `.cmd` |  |  |
| CNAM | 파랑 |  | `cname` |  |
| COF | 호박 | `.coffee`, `.litcoffee` |  | `coffeescript` |
| CPIO | 호박 | `.cpio` |  |  |
| CPP | 파랑 | `.c++`, `.cc`, `.ccm`, `.cpp`, `.cppm`, `.cxx`, `.ixx` |  | `cpp` |
| CR | 중립 | `.cr` |  | `crystal` |
| CRT | 와인 | `.cer`, `.crt` |  |  |
| CRX | 호박 | `.crx` |  |  |
| CSS | 와인 | `.css` |  | `css` |
| CSV | 호박 | `.csv` |  |  |
| CU | 청록 | `.cu`, `.cuh` |  | `cuda`, `cuda-cpp` |
| D | 와인 | `.d`, `.di` |  | `d` |
| D2 | 주황 | `.d2` |  | `d2` |
| DAE | 청록 | `.dae` |  |  |
| DART | 청록 | `.dart` |  | `dart` |
| DB | 호박 | `.db`, `.sqlite`, `.sqlite3` |  |  |
| DDS | 청록 | `.dds` |  |  |
| DEB | 호박 | `.deb` |  |  |
| DEX | 흐린 중립 | `.dex` |  |  |
| DIFF | 주황 | `.diff`, `.rej` |  | `diff` |
| DIO | 주황 | `.dio`, `.drawio` |  |  |
| DJVU | 보라 | `.djvu` |  |  |
| DMG | 호박 | `.dmg` |  |  |
| DO | 파랑 | `.ado`, `.do` |  |  |
| DOC | 파랑 | `.doc` |  |  |
| DOCK | 파랑 | `.dockerfile` | `containerfile`, `dockerfile` | `dockercompose`, `dockerfile` |
| DOCX | 파랑 | `.docx` |  |  |
| DOT | 주황 | `.dot`, `.gv` |  |  |
| DWG | 청록 | `.dwg` |  |  |
| DXF | 청록 | `.dxf` |  |  |
| EAR | 호박 | `.ear` |  |  |
| EDN | 파랑 | `.edn` |  |  |
| EGG | 호박 | `.egg` |  |  |
| EJS | 주황 | `.ejs` |  |  |
| EL | 중립 | `.el` |  | `emacs-lisp` |
| ELM | 청록 | `.elm` |  | `elm` |
| EMF | 청록 | `.emf` |  |  |
| EML | 파랑 | `.eml`, `.msg` |  |  |
| ENV | 호박 | `.env`, `.envrc` |  | `dotenv` |
| EOT | 보라 | `.eot` |  |  |
| EPS | 와인 | `.eps` |  |  |
| EPUB | 보라 | `.epub` |  |  |
| ERB | 와인 | `.erb` |  | `erb` |
| ERL | 와인 | `.erl`, `.hrl` |  | `erlang` |
| ESL | 보라 | `.eslintrc` |  |  |
| EX | 보라 | `.eex`, `.ex`, `.exs`, `.heex` |  | `elixir` |
| EXC | 주황 | `.excalidraw` |  |  |
| EXR | 청록 | `.exr` |  |  |
| F# | 파랑 | `.fs`, `.fsi`, `.fsx` |  | `fsharp` |
| FB2 | 보라 | `.fb2` |  |  |
| FBS | 호박 | `.fbs` |  |  |
| FBX | 청록 | `.fbx` |  |  |
| FEAT | 청록 | `.feature` |  |  |
| FIG | 와인 | `.fig` |  |  |
| FISH | 중립 | `.fish` |  | `fish` |
| FLAC | 청록 | `.flac` |  |  |
| FLV | 청록 | `.flv` |  |  |
| FNL | 중립 | `.fnl` |  |  |
| FNT | 보라 | `.fnt` |  |  |
| FTH | 중립 | `.4th`, `.forth`, `.fth` |  |  |
| FTN | 보라 | `.f`, `.f03`, `.f08`, `.f77`, `.f90`, `.f95`, `.for` |  | `FortranFreeForm`, `fortran`, `fortran-modern` |
| GD | 파랑 | `.gd`, `.gdshader`, `.godot`, `.tres`, `.tscn` |  | `gdscript` |
| GEM | 와인 |  | `gemfile` |  |
| GEM | 호박 | `.gem` |  |  |
| GGUF | 보라 | `.gguf` |  |  |
| GIF | 청록 | `.gif` |  |  |
| GIT | 주황 | `.gitattributes`, `.gitignore`, `.gitkeep`, `.gitmodules`, `.mailmap` |  |  |
| GLB | 청록 | `.glb` |  |  |
| GLM | 와인 | `.gleam` |  | `gleam` |
| GLSL | 보라 | `.comp`, `.frag`, `.geom`, `.glsl`, `.tesc`, `.tese`, `.vert` |  | `glsl` |
| GLTF | 청록 | `.gltf` |  |  |
| GO | 청록 | `.go`, `.mod` |  | `go` |
| GP | 중립 | `.gnuplot`, `.gp`, `.plt` |  |  |
| GQL | 와인 | `.gql`, `.graphql`, `.graphqls` |  | `graphql` |
| GRDL | 주황 | `.gradle` |  |  |
| GVY | 파랑 | `.groovy`, `.gsh`, `.gvy`, `.gy` |  | `groovy` |
| GZ | 호박 | `.gz` |  |  |
| H | 보라 | `.h`, `.inl`, `.ipp`, `.tcc`, `.tpp`, `.txx` |  |  |
| H5 | 호박 | `.h5`, `.hdf5` |  |  |
| HAML | 주황 | `.haml` |  |  |
| HBS | 주황 | `.handlebars`, `.hbs` |  | `handlebars` |
| HDR | 청록 | `.hdr` |  |  |
| HEIC | 청록 | `.heic`, `.heif` |  |  |
| HLSL | 보라 | `.hlsl` |  | `hlsl` |
| HPP | 보라 | `.h++`, `.hh`, `.hpp`, `.hxx` |  |  |
| HS | 보라 | `.cabal`, `.hs`, `.lhs` |  | `haskell` |
| HTAC | 청록 | `.htaccess` |  |  |
| HTML | 주황 | `.ftl`, `.gotmpl`, `.htm`, `.html`, `.mustache`, `.tmpl`, `.xhtml` |  | `blade`, `html` |
| HTTP | 청록 | `.http`, `.rest` |  | `http` |
| HX | 주황 | `.hx`, `.hxml` |  | `haxe` |
| ICNS | 청록 | `.icns` |  |  |
| ICO | 청록 | `.ico` |  |  |
| ICS | 파랑 | `.ical`, `.ics`, `.ifb`, `.vcs` |  |  |
| IDR | 와인 | `.idr` |  |  |
| IFC | 청록 | `.ifc` |  |  |
| IGES | 청록 | `.iges`, `.igs` |  |  |
| IGN | 중립 | `.dockerignore`, `.eslintignore`, `.npmignore`, `.prettierignore`, `.vscodeignore` |  | `ignore` |
| IMG | 호박 | `.img` |  |  |
| INDD | 와인 | `.indd` |  |  |
| INO | 청록 | `.ino` |  |  |
| IPA | 호박 | `.ipa` |  |  |
| IPY | 주황 | `.ipynb` |  |  |
| ISO | 호박 | `.iso` |  |  |
| JAR | 호박 | `.jar` |  |  |
| JAVA | 주황 | `.java` |  | `java` |
| JENK | 파랑 |  | `jenkinsfile` |  |
| JINJ | 주황 | `.j2`, `.jinja`, `.jinja2` |  | `jinja` |
| JL | 보라 | `.jl` |  | `julia` |
| JP2 | 청록 | `.j2k`, `.jp2` |  |  |
| JPG | 청록 | `.jpeg`, `.jpg` |  |  |
| JQ | 호박 | `.jq` |  |  |
| JS | 호박 | `.cjs`, `.js`, `.mjs` |  | `javascript` |
| JSNL | 호박 | `.jsonl`, `.ndjson` |  |  |
| JSNT | 파랑 | `.jsonnet`, `.libsonnet` |  |  |
| JSON | 호박 | `.json`, `.json5`, `.jsonc`, `.webmanifest` |  | `json`, `json5`, `jsonc` |
| JSP | 주황 | `.jsp`, `.jspx` |  |  |
| JSX | 호박 | `.jsx` |  | `javascriptreact` |
| JUST | 주황 |  | `justfile` |  |
| JXL | 청록 | `.jxl` |  |  |
| K8S | 파랑 |  |  | `helm` |
| KDL | 호박 | `.kdl` |  |  |
| KEY | 와인 | `.csr`, `.der`, `.gpg`, `.jks`, `.key`, `.keystore`, `.p12`, `.pfx`, `.pgp` |  |  |
| KRA | 와인 | `.kra` |  |  |
| KT | 보라 | `.kt`, `.kts` |  | `kotlin` |
| LEAN | 중립 | `.lean` |  | `lean`, `lean4` |
| LESS | 와인 | `.less` |  | `less` |
| LIC | 중립 |  | `copying`, `licence`, `license`, `unlicense` |  |
| LIQ | 주황 | `.liquid` |  | `liquid` |
| LISP | 중립 | `.lisp`, `.lsp` |  | `commonlisp`, `lisp` |
| LOCK | 흐린 중립 | `.lock` |  |  |
| LOG | 흐린 중립 | `.log` |  | `log` |
| LRC | 청록 | `.lrc` |  |  |
| LS | 청록 | `.ls` |  |  |
| LUA | 파랑 | `.lua` |  | `lua` |
| LY | 청록 | `.ly` |  |  |
| LZ | 호박 | `.lz` |  |  |
| LZ4 | 호박 | `.lz4` |  |  |
| LZH | 호박 | `.lha`, `.lzh` |  |  |
| LZMA | 호박 | `.lzma` |  |  |
| M2TS | 청록 | `.m2ts` |  |  |
| M4A | 청록 | `.m4a` |  |  |
| M4V | 청록 | `.m4v` |  |  |
| MAKE | 주황 | `.mak`, `.mk`, `.ninja`, `.props`, `.targets`, `.vcxproj` | `gnumakefile`, `makefile` | `makefile`, `meson` |
| MAP | 흐린 중립 | `.map`, `.tsbuildinfo` |  |  |
| MAT | 주황 | `.mlx` |  | `matlab` |
| MAX | 청록 | `.max` |  |  |
| MAYA | 청록 | `.ma`, `.mb` |  |  |
| MD | 보라 | `.markdown`, `.md` |  | `markdown` |
| MDB | 호박 | `.accdb`, `.mdb` |  |  |
| MDX | 보라 | `.mdx` |  | `mdx` |
| MID | 청록 | `.mid`, `.midi` |  |  |
| MJML | 주황 | `.mjml` |  |  |
| MKV | 청록 | `.mkv` |  |  |
| ML | 주황 | `.ml`, `.mli`, `.opam` |  | `ocaml` |
| MMD | 주황 | `.mermaid`, `.mmd` |  | `mermaid` |
| MOBI | 보라 | `.mobi` |  |  |
| MOJO | 주황 | `.mojo`, `.🔥` |  | `mojo` |
| MOON | 호박 | `.moon` |  |  |
| MOV | 청록 | `.mov` |  |  |
| MOVE | 파랑 | `.move` |  |  |
| MP3 | 청록 | `.mp3` |  |  |
| MP4 | 청록 | `.mp4` |  |  |
| MPG | 청록 | `.mpeg`, `.mpg` |  |  |
| MPP | 파랑 | `.mpp` |  |  |
| MSI | 호박 | `.msi` |  |  |
| MSIX | 호박 | `.msix` |  |  |
| MTL | 보라 | `.metal` |  |  |
| NF | 청록 | `.nf` |  |  |
| NFO | 중립 | `.nfo` |  |  |
| NIM | 호박 | `.nim`, `.nimble`, `.nims` |  | `nim` |
| NIX | 파랑 | `.nix` |  | `nix` |
| NJK | 주황 | `.njk` |  |  |
| NODE | 청록 | `.node-version` |  |  |
| NPKG | 호박 | `.nupkg` |  |  |
| NPM | 호박 | `.npmrc` |  |  |
| NPY | 파랑 | `.npy`, `.npz` |  |  |
| NU | 중립 | `.nu` |  | `nushell` |
| NUMB | 청록 | `.numbers` |  |  |
| OBJC | 파랑 | `.mm` |  | `objective-c`, `objective-cpp` |
| ODG | 와인 | `.odg` |  |  |
| ODIN | 파랑 | `.odin` |  |  |
| ODP | 주황 | `.odp` |  |  |
| ODS | 청록 | `.ods` |  |  |
| ODT | 파랑 | `.odt` |  |  |
| OGG | 청록 | `.oga`, `.ogg` |  |  |
| OGV | 청록 | `.ogv` |  |  |
| ONE | 보라 | `.one` |  |  |
| ONNX | 보라 | `.onnx` |  |  |
| OPUS | 청록 | `.opus` |  |  |
| ORG | 보라 | `.org` |  |  |
| ORIG | 흐린 중립 | `.orig` |  |  |
| OTF | 보라 | `.otf` |  |  |
| OVA | 호박 | `.ova` |  |  |
| OWN | 보라 |  | `codeowners` |  |
| PAGE | 파랑 | `.pages` |  |  |
| PARQ | 호박 | `.parquet` |  |  |
| PAS | 파랑 | `.dpr`, `.lpr`, `.pas` |  | `objectpascal`, `pascal` |
| PB | 호박 | `.proto` |  | `proto`, `proto3` |
| PCSS | 와인 | `.pcss`, `.postcss` |  | `postcss` |
| PDF | 와인 | `.pdf` |  |  |
| PEM | 와인 | `.pem` |  |  |
| PFB | 보라 | `.pfb` |  |  |
| PHP | 파랑 | `.php`, `.phtml` |  | `php` |
| PIP | 파랑 |  | `pipfile` |  |
| PKG | 호박 | `.nuspec`, `.pkg` |  |  |
| PKL | 파랑 | `.pickle`, `.pkl` |  |  |
| PL | 파랑 | `.pl`, `.pm` |  | `perl` |
| PLY | 청록 | `.ply` |  |  |
| PNG | 청록 | `.png` |  |  |
| POD | 호박 |  | `podfile` |  |
| PPT | 주황 | `.ppt` |  |  |
| PPTX | 주황 | `.pptx` |  |  |
| PRCR | 와인 | `.procreate` |  |  |
| PRET | 중립 | `.prettierrc` |  |  |
| PROC | 파랑 |  | `procfile` |  |
| PROJ | 보라 | `.csproj` |  |  |
| PROJ | 파랑 | `.fsproj` |  |  |
| PRSM | 파랑 | `.prisma` |  | `prisma` |
| PS | 중립 | `.ps` |  |  |
| PS1 | 파랑 | `.ps1`, `.psd1`, `.psm1` |  | `powershell` |
| PSD | 와인 | `.psd` |  |  |
| PT | 주황 | `.pt`, `.pth` |  |  |
| PTCH | 주황 | `.patch` |  |  |
| PUB | 파랑 | `.pub` |  |  |
| PUG | 주황 | `.pug` |  | `pug` |
| PUML | 주황 | `.iuml`, `.plantuml`, `.puml` |  | `plantuml` |
| PURS | 중립 | `.purs` |  |  |
| PY | 파랑 | `.py`, `.pyi`, `.python-version`, `.pyw` |  | `python` |
| PYX | 파랑 | `.pxd`, `.pyx` |  |  |
| QCOW | 호박 | `.qcow2` |  |  |
| QMD | 파랑 | `.qmd` |  | `quarto` |
| QS | 보라 | `.qs` |  |  |
| R | 파랑 | `.r`, `.rmd` |  | `r`, `rmd` |
| RAKE | 와인 |  | `rakefile` |  |
| RAKU | 호박 | `.raku`, `.rakumod`, `.rakutest` |  | `perl6`, `raku` |
| RAR | 호박 | `.rar` |  |  |
| RAW | 청록 | `.arw`, `.cr2`, `.cr3`, `.dng`, `.nef`, `.orf`, `.raf`, `.raw`, `.rw2` |  |  |
| RAZR | 보라 | `.cshtml`, `.razor`, `.vbhtml` |  | `aspnetcorerazor`, `razor` |
| RB | 와인 | `.gemspec`, `.rake`, `.rb`, `.ru`, `.ruby-version` |  | `ruby` |
| RDS | 파랑 | `.rdata`, `.rds` |  |  |
| READ | 파랑 |  | `readme` |  |
| REG | 파랑 | `.reg` |  |  |
| REGO | 파랑 | `.rego` |  |  |
| RES | 와인 | `.re`, `.rei`, `.res`, `.resi` |  | `reason`, `rescript` |
| RKT | 중립 | `.rkt` |  | `racket` |
| RPM | 호박 | `.rpm` |  |  |
| RS | 주황 | `.rs` |  | `rust` |
| RSS | 주황 | `.rss` |  |  |
| RST | 보라 | `.rst` |  |  |
| RTF | 파랑 | `.rtf` |  |  |
| SAFE | 보라 | `.safetensors` |  |  |
| SAS | 파랑 | `.sas` |  |  |
| SASS | 와인 | `.sass` |  | `sass` |
| SBV | 청록 | `.sbv` |  |  |
| SC | 와인 | `.sbt`, `.sc`, `.scala` |  | `scala` |
| SCAD | 호박 | `.scad` |  |  |
| SCM | 중립 | `.scm`, `.ss` |  | `scheme` |
| SCPT | 중립 | `.applescript`, `.scpt` |  | `applescript` |
| SCSS | 와인 | `.scss` |  | `scss` |
| SED | 중립 | `.sed` |  |  |
| SH | 중립 | `.bash`, `.command`, `.csh`, `.ksh`, `.sh`, `.zsh` |  | `shellscript` |
| SHD | 보라 | `.shader` |  | `shaderlab` |
| SIG | 와인 | `.sig` |  |  |
| SKCH | 와인 | `.sketch` |  |  |
| SKP | 청록 | `.skp` |  |  |
| SLIM | 와인 | `.slim` |  |  |
| SLN | 보라 | `.sln`, `.slnx` |  |  |
| SLNT | 보라 | `.stylelintrc` |  |  |
| SMI | 청록 | `.sami`, `.smi` |  |  |
| SML | 주황 | `.sml` |  |  |
| SNAP | 흐린 중립 | `.snap` |  |  |
| SOL | 중립 | `.sol` |  | `solidity` |
| SQL | 호박 | `.mysql`, `.pgsql`, `.psql`, `.sql` |  | `sql` |
| SRT | 청록 | `.srt` |  |  |
| SRV | 청록 |  |  | `apacheconf`, `caddyfile`, `nginx` |
| SSA | 청록 | `.ssa` |  |  |
| ST | 파랑 | `.st` |  |  |
| STAN | 와인 | `.stan` |  |  |
| STEP | 청록 | `.step`, `.stp` |  |  |
| STL | 청록 | `.stl` |  |  |
| STYL | 와인 | `.styl` |  | `stylus` |
| SUB | 청록 | `.sub` |  |  |
| SUM | 흐린 중립 | `.md5`, `.sha1`, `.sha256`, `.sha512`, `.sum` |  |  |
| SV | 중립 | `.sv`, `.svh`, `.vh` |  | `systemverilog`, `verilog` |
| SVG | 청록 | `.svg` |  |  |
| SVGZ | 청록 | `.svgz` |  |  |
| SVLT | 주황 | `.svelte` |  | `svelte` |
| SWFT | 주황 | `.swift` |  | `swift` |
| SWP | 흐린 중립 | `.swp` |  |  |
| TAR | 호박 | `.tar` |  |  |
| TBZ | 호박 | `.tbz`, `.tbz2` |  |  |
| TCL | 파랑 | `.tcl` |  | `tcl` |
| TEX | 보라 | `.cls`, `.ltx`, `.sty`, `.tex` |  | `latex`, `tex` |
| TF | 보라 | `.hcl`, `.tf`, `.tfvars` |  | `hcl`, `terraform` |
| TGA | 청록 | `.tga` |  |  |
| TGZ | 호박 | `.tgz` |  |  |
| TIF | 청록 | `.tif`, `.tiff` |  |  |
| TMP | 흐린 중립 | `.tmp` |  |  |
| TODO | 호박 | `.taskpaper`, `.todo` | `todo` |  |
| TOML | 호박 | `.toml` |  | `toml` |
| TS | 파랑 | `.cts`, `.mts`, `.ts` |  | `typescript` |
| TSV | 호박 | `.tsv` |  |  |
| TSX | 파랑 | `.tsx` |  | `typescriptreact` |
| TTC | 보라 | `.ttc` |  |  |
| TTF | 보라 | `.ttf` |  |  |
| TTML | 청록 | `.dfxp`, `.ttml` |  |  |
| TWIG | 주황 | `.twig` |  | `twig` |
| TXT | 중립 | `.txt` |  |  |
| TXZ | 호박 | `.txz` |  |  |
| TYP | 청록 | `.typ` |  | `typst` |
| UNTY | 중립 | `.anim`, `.asset`, `.prefab`, `.unity`, `.unitypackage` |  |  |
| URL | 청록 | `.url`, `.webloc` |  |  |
| USD | 청록 | `.usd` |  |  |
| USDZ | 청록 | `.usdz` |  |  |
| VAGR | 파랑 |  | `vagrantfile` |  |
| VALA | 보라 | `.vala`, `.vapi` |  | `vala` |
| VB | 파랑 | `.bas`, `.vb` |  | `vb` |
| VBS | 파랑 | `.vbs` |  |  |
| VCF | 파랑 | `.vcard`, `.vcf` |  |  |
| VHDL | 중립 | `.vhd`, `.vhdl` |  | `vhdl` |
| VIM | 청록 | `.vim` |  | `vim`, `viml` |
| VMDK | 호박 | `.vmdk` |  |  |
| VOX | 청록 | `.vox` |  |  |
| VSD | 파랑 | `.vsd`, `.vsdx` |  |  |
| VSIX | 호박 | `.vsix` |  |  |
| VTT | 청록 | `.vtt` |  |  |
| VUE | 청록 | `.vue` |  | `vue` |
| WAR | 호박 | `.war` |  |  |
| WASM | 보라 | `.wasm`, `.wast`, `.wat` |  | `wat` |
| WAV | 청록 | `.wav` |  |  |
| WDL | 파랑 | `.wdl` |  |  |
| WEBM | 청록 | `.webm` |  |  |
| WEBP | 청록 | `.webp` |  |  |
| WGSL | 보라 | `.wgsl` |  | `wgsl` |
| WHL | 호박 | `.whl` |  |  |
| WL | 주황 | `.wl`, `.wls` |  |  |
| WMA | 청록 | `.wma` |  |  |
| WMV | 청록 | `.wmv` |  |  |
| WOFF | 보라 | `.woff`, `.woff2` |  |  |
| X3D | 청록 | `.x3d` |  |  |
| XAML | 주황 | `.xaml` |  |  |
| XCF | 와인 | `.xcf` |  |  |
| XD | 와인 | `.xd` |  |  |
| XLS | 청록 | `.xls` |  |  |
| XLSM | 청록 | `.xlsm` |  |  |
| XLSX | 청록 | `.xlsx` |  |  |
| XML | 주황 | `.atom`, `.dtd`, `.resx`, `.storyboard`, `.xib`, `.xml`, `.xsd`, `.xsl` |  | `xml`, `xsl` |
| XPI | 호박 | `.xpi` |  |  |
| XPS | 파랑 | `.xps` |  |  |
| XQ | 주황 | `.xq`, `.xquery`, `.xqy` |  |  |
| XZ | 호박 | `.xz` |  |  |
| YARA | 와인 | `.yar`, `.yara` |  |  |
| YARN | 호박 | `.yarnrc` |  |  |
| YML | 호박 | `.yaml`, `.yml` |  | `yaml` |
| ZIG | 호박 | `.zig`, `.zon` |  | `zig` |
| ZIP | 호박 | `.zip` |  |  |
| ZST | 호박 | `.zst` |  |  |

</details>
<!-- icons:end -->

## 알아둘 점

- 확장자가 없는 이름(`LICENSE`, `Dockerfile`, `Makefile`, `Procfile` 등)은 이름을 줄인 글자로 보여 줍니다. 점으로 시작하는 파일(`.gitignore`, `.editorconfig` 등)은 VS Code가 점 뒤를 확장자로 보기 때문에 확장자처럼 연결합니다.
- `README.md`, `package.json`, `tsconfig.json`처럼 확장자가 있는 파일은 이름과 상관없이 확장자 글자(MD, JSON)로 보입니다. `*.test.ts`, `*.d.ts`, `*.min.js`도 마지막 확장자(TS, JS)를 따릅니다.
- 목록에 없는 확장자는 VS Code가 알아본 언어의 글자로 보이고, 그것도 없으면 기본 파일 아이콘으로 보입니다.
- `.m`(Objective-C·MATLAB), `.v`(Verilog·V·Coq)처럼 여러 언어가 같이 쓰는 확장자는 VS Code가 판단한 언어로 구분합니다. 해당 언어 확장이 설치돼 있어야 맞는 글자가 나옵니다.
- 폴더는 이름과 상관없이 모두 같은 모양입니다. 열림과 닫힘만 구분합니다.
- 다크 테마용 변형은 없습니다.

## 릴리스

1. `package.json`의 `version`과 `CHANGELOG.md`를 고쳐서 커밋합니다.
2. 같은 버전으로 태그를 푸시하면 GitHub Actions가 `.vsix`를 만들어 Release에 올립니다.

   ```bash
   git tag v0.2.0
   git push origin v0.2.0
   ```

태그와 `package.json`의 버전이 다르면 빌드가 실패합니다. 릴리스 노트는 GitHub가 커밋 기록으로 자동으로 만듭니다.

`vsce`는 README 안의 SVG 이미지를 허용하지 않으므로 README에는 이미지를 넣지 않습니다.

## 라이선스

[MIT](LICENSE)
