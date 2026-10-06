# Yuginong Icons

Outline file and folder icons for VS Code, made to pair with the Yuginong Light color theme.

Yuginong Light 컬러 테마와 함께 쓰도록 만든 VS Code 파일·폴더 아이콘 테마입니다.

클로드랑 같이 만들었습니다.

## 특징

<!-- stats:start -->
- 아이콘 300개: 파일 아이콘 158종, 폴더 아이콘 71종(닫힘·열림). 확장자 494개, 파일 이름 346개, 언어 ID 148개, 폴더 이름 244개에 연결됩니다.
<!-- stats:end -->
- 16×16 픽셀 그리드에 맞춘 1px 아웃라인입니다. 선을 픽셀 경계에 맞춰서 16px에서도 흐려지지 않습니다.
- Hugo 블로그 구조(`archetypes`, `layouts/_partials`, `_index.md`, `hugo.toml` 등)를 먼저 챙기고, 웹·모바일·시스템·데이터·문서 프로젝트까지 폭넓게 다룹니다.
- Yuginong Light 팔레트에서 가져온 색만 씁니다. 모든 색이 탐색기의 기본·hover·선택 배경에서 대비 3:1 이상입니다.
- 생성물과 외부 코드(`node_modules`, `dist`, lock 파일, 컴파일 결과물 등)는 흐린 색으로 구분합니다.
- 라이트 테마 전용입니다.

## 설치

마켓플레이스에는 올리지 않고 [GitHub Releases](https://github.com/Faavilla/yuginong-icons/releases)에서 `.vsix`로 배포합니다.

1. Releases에서 `yuginong-icons-<버전>.vsix`를 내려받습니다.
2. VS Code 명령 팔레트에서 `Extensions: Install from VSIX...`를 실행하거나, 터미널에서 설치합니다.

   ```bash
   code --install-extension yuginong-icons-0.1.0.vsix
   ```

3. 명령 팔레트에서 `Preferences: File Icon Theme`를 열고 **Yuginong Icons**를 고릅니다.

## 색

| 색 | 쓰임 |
|---|---|
| `#585C78` 중립 | 기본 파일·폴더, 텍스트, 설정 |
| `#686C88` 흐린 중립 | 생성물·외부 코드 |
| `#8B2B4E` 와인 | Hugo, CSS·Sass, Ruby, Scala 등 붉은 계열 브랜드 |
| `#4D337B` 보라 | 문서·콘텐츠, Kotlin, C#, Haskell 등 |
| `#832508` 주황 | HTML·템플릿, Git, Rust, Java, Swift 등 |
| `#6C5001` 호박 | JavaScript, JSON·TOML·YAML 등 데이터 |
| `#205462` 파랑 | TypeScript, Python, Docker, C·C++ 등 |
| `#0A7272` 청록 | Go, 이미지·오디오·비디오, Dart 등 |
| `#13694D` 녹색 | 워크스페이스 루트 폴더 |

## 아이콘

<!-- icons:start -->
<details>
<summary>파일 아이콘 158종</summary>

| 아이콘 | 확장자 | 파일 이름 | 언어 ID |
|---|---|---|---|
| file (기본) |  |  |  |
| hugo |  | `hugo.toml`, `hugo.yaml`, `hugo.yml`, `hugo.json` |  |
| hugo-stats |  | `hugo_stats.json` |  |
| markdown | `.md`, `.markdown`, `.mdx` |  | `markdown`, `mdx` |
| markdown-index |  | `_index.md`, `_index.markdown` |  |
| readme |  | `readme.md`, `readme`, `readme.txt`, `readme.markdown`, `readme.rst` |  |
| changelog |  | `changelog.md`, `changelog`, `changelog.txt`, `changes.md`, `history.md` |  |
| license |  | `license`, `license.md`, `license.txt`, `licence`, `licence.md`, `copying`, `copying.md`, `unlicense` |  |
| text | `.txt` |  |  |
| log | `.log` |  | `log` |
| pdf | `.pdf` |  |  |
| robots |  | `robots.txt` |  |
| font | `.woff`, `.woff2`, `.ttf`, `.otf`, `.eot` |  |  |
| html | `.html`, `.htm`, `.xhtml`, `.gotmpl`, `.tmpl`, `.hbs`, `.handlebars`, `.mustache`, `.ejs`, `.njk`, `.liquid`, `.twig`, `.jinja`, `.jinja2`, `.j2`, `.pug`, `.erb`, `.blade.php`, `.jsp`, `.jspx`, `.ftl`, `.razor`, `.cshtml`, `.vbhtml` |  | `html`, `handlebars`, `jinja`, `twig`, `pug`, `erb`, `blade`, `liquid`, `razor`, `aspnetcorerazor` |
| xml | `.xml`, `.rss`, `.atom`, `.xsl`, `.xsd`, `.dtd`, `.resx`, `.xaml`, `.storyboard`, `.xib` |  | `xml`, `xsl` |
| css | `.css`, `.less`, `.styl`, `.pcss`, `.postcss` |  | `css`, `less`, `stylus`, `postcss` |
| css-min | `.min.css` |  |  |
| scss | `.scss`, `.sass` |  | `scss`, `sass` |
| javascript | `.js`, `.mjs`, `.cjs` |  | `javascript` |
| javascript-min | `.min.js`, `.min.mjs` |  |  |
| typescript | `.ts`, `.mts`, `.cts` |  | `typescript` |
| typescript-def | `.d.ts`, `.d.mts`, `.d.cts` |  |  |
| jsx | `.jsx` |  | `javascriptreact` |
| tsx | `.tsx` |  | `typescriptreact` |
| test-js | `.test.js`, `.spec.js`, `.test.mjs`, `.spec.mjs`, `.test.cjs`, `.spec.cjs`, `.test.jsx`, `.spec.jsx` |  |  |
| test-ts | `.test.ts`, `.spec.ts`, `.test.mts`, `.spec.mts`, `.test.cts`, `.spec.cts`, `.test.tsx`, `.spec.tsx` |  |  |
| test-py |  | `conftest.py`, `pytest.ini` |  |
| test-php |  | `phpunit.xml`, `phpunit.xml.dist` |  |
| test-rb |  | `.rspec` |  |
| storybook | `.stories.js`, `.stories.jsx`, `.stories.ts`, `.stories.tsx`, `.stories.mdx`, `.stories.svelte`, `.stories.vue` |  |  |
| vue | `.vue` |  | `vue` |
| svelte | `.svelte` |  | `svelte` |
| astro | `.astro` |  | `astro` |
| go | `.go` | `go.mod`, `go.work` | `go` |
| python | `.py`, `.pyi`, `.pyw` | `requirements.txt`, `requirements-dev.txt`, `requirements.in`, `pyproject.toml`, `setup.cfg`, `pipfile`, `.python-version`, `environment.yml` | `python` |
| rust | `.rs` | `cargo.toml`, `rust-toolchain`, `rust-toolchain.toml` | `rust` |
| ruby | `.rb`, `.rake`, `.gemspec`, `.ru` | `gemfile`, `rakefile`, `.ruby-version`, `brewfile`, `guardfile`, `capfile`, `.irbrc`, `.pryrc` | `ruby` |
| php | `.php`, `.phtml` | `composer.json`, `artisan` | `php` |
| java | `.java` | `pom.xml` | `java` |
| kotlin | `.kt`, `.kts` |  | `kotlin` |
| c | `.c` |  | `c` |
| cpp | `.cpp`, `.cc`, `.cxx`, `.c++`, `.cppm`, `.ixx`, `.ccm`, `.ino` |  | `cpp` |
| h | `.h`, `.hpp`, `.hh`, `.hxx`, `.h++`, `.inl`, `.ipp`, `.tpp`, `.txx`, `.tcc` |  |  |
| csharp | `.cs`, `.csx`, `.csproj`, `.sln`, `.slnx` |  | `csharp` |
| binary | `.o`, `.obj`, `.a`, `.lib`, `.so`, `.dylib`, `.dll`, `.exe`, `.out`, `.elf`, `.bin`, `.pdb`, `.ilk`, `.pch`, `.gch`, `.rlib`, `.class`, `.pyc`, `.pyo`, `.pyd` |  |  |
| swift | `.swift` |  | `swift` |
| lua | `.lua` |  | `lua` |
| shell | `.sh`, `.bash`, `.zsh`, `.fish`, `.ksh`, `.csh`, `.command`, `.bat`, `.cmd`, `.nu` | `.bashrc`, `.zshrc`, `.profile`, `.bash_profile`, `.zprofile`, `.zshenv` | `shellscript`, `bat`, `fish`, `nushell` |
| powershell | `.ps1`, `.psm1`, `.psd1` |  | `powershell` |
| sql | `.sql`, `.psql`, `.mysql`, `.pgsql`, `.db`, `.sqlite`, `.sqlite3`, `.prisma` |  | `sql`, `prisma` |
| dart | `.dart` | `pubspec.yaml` | `dart` |
| scala | `.scala`, `.sc`, `.sbt` |  | `scala` |
| haskell | `.hs`, `.lhs`, `.cabal` | `stack.yaml` | `haskell` |
| elixir | `.ex`, `.exs`, `.heex`, `.eex` |  | `elixir` |
| erlang | `.erl`, `.hrl` | `rebar.config` | `erlang` |
| clojure | `.clj`, `.cljs`, `.cljc`, `.edn` |  | `clojure` |
| lisp | `.lisp`, `.lsp`, `.el`, `.scm`, `.ss`, `.rkt`, `.fnl` | `.emacs` | `lisp`, `commonlisp`, `scheme`, `racket`, `emacs-lisp` |
| fsharp | `.fs`, `.fsi`, `.fsx`, `.fsproj` |  | `fsharp` |
| ocaml | `.ml`, `.mli`, `.opam` | `dune`, `dune-project` | `ocaml` |
| r | `.r`, `.rmd` |  | `r`, `rmd` |
| julia | `.jl` |  | `julia` |
| perl | `.pl`, `.pm` | `cpanfile` | `perl` |
| raku | `.raku`, `.rakumod`, `.rakutest` |  | `raku`, `perl6` |
| zig | `.zig`, `.zon` |  | `zig` |
| nim | `.nim`, `.nims`, `.nimble` |  | `nim` |
| crystal | `.cr` | `shard.yml` | `crystal` |
| d | `.d`, `.di` |  | `d` |
| gleam | `.gleam` | `gleam.toml` | `gleam` |
| mojo | `.mojo`, `.🔥` |  | `mojo` |
| vala | `.vala`, `.vapi` |  | `vala` |
| haxe | `.hx`, `.hxml` |  | `haxe` |
| groovy | `.groovy`, `.gvy`, `.gy`, `.gsh` |  | `groovy` |
| elm | `.elm` | `elm.json` | `elm` |
| objective-c | `.mm` |  | `objective-c`, `objective-cpp` |
| matlab | `.mlx` |  | `matlab` |
| fortran | `.f`, `.f77`, `.f90`, `.f95`, `.f03`, `.f08`, `.for` |  | `fortran`, `FortranFreeForm`, `fortran-modern` |
| cobol | `.cbl`, `.cob`, `.cpy` |  | `cobol` |
| pascal | `.pas`, `.dpr`, `.lpr` |  | `pascal`, `objectpascal` |
| ada | `.ada`, `.adb`, `.ads` |  | `ada` |
| vb | `.vb`, `.vbs`, `.bas` |  | `vb` |
| assembly | `.asm`, `.s`, `.nasm` |  | `asm`, `arm`, `nasm` |
| verilog | `.sv`, `.svh`, `.vh` |  | `verilog`, `systemverilog` |
| vhdl | `.vhd`, `.vhdl` |  | `vhdl` |
| cuda | `.cu`, `.cuh` |  | `cuda-cpp`, `cuda` |
| shader | `.glsl`, `.vert`, `.frag`, `.geom`, `.tesc`, `.tese`, `.comp`, `.hlsl`, `.wgsl`, `.metal`, `.shader` |  | `glsl`, `hlsl`, `wgsl`, `shaderlab` |
| solidity | `.sol` |  | `solidity` |
| tcl | `.tcl` |  | `tcl` |
| awk | `.awk` |  | `awk` |
| applescript | `.applescript`, `.scpt` |  | `applescript` |
| coffeescript | `.coffee`, `.litcoffee` |  | `coffeescript` |
| rescript | `.res`, `.resi`, `.re`, `.rei` |  | `rescript`, `reason` |
| lean | `.lean` |  | `lean`, `lean4` |
| vim | `.vim` | `.vimrc`, `.gvimrc`, `_vimrc` | `viml`, `vim` |
| wasm | `.wasm`, `.wat`, `.wast` |  | `wat` |
| graphql | `.graphql`, `.gql`, `.graphqls` |  | `graphql` |
| protobuf | `.proto` |  | `proto3`, `proto` |
| terraform | `.tf`, `.tfvars`, `.hcl` |  | `terraform`, `hcl` |
| nix | `.nix` |  | `nix` |
| latex | `.tex`, `.ltx`, `.sty`, `.cls`, `.bib` |  | `latex`, `tex`, `bibtex` |
| typst | `.typ` |  | `typst` |
| json | `.json`, `.jsonc`, `.json5`, `.webmanifest` |  | `json`, `jsonc`, `json5` |
| sourcemap | `.map`, `.tsbuildinfo` |  |  |
| toml | `.toml` |  | `toml` |
| yaml | `.yaml`, `.yml` |  | `yaml` |
| csv | `.csv`, `.tsv` |  |  |
| package | `.nuspec` | `package.json`, `.npmrc`, `.yarnrc`, `.yarnrc.yml`, `pnpm-workspace.yaml`, `conanfile.txt`, `conanfile.py`, `vcpkg.json`, `vcpkg-configuration.json`, `nuget.config`, `packages.config`, `podfile`, `cartfile` |  |
| config | `.config.js`, `.config.mjs`, `.config.cjs`, `.config.ts`, `.config.mts`, `.ini`, `.cfg`, `.conf`, `.properties`, `.plist`, `.entitlements`, `.xcconfig`, `.pbxproj`, `.mf`, `.code-workspace` | `.editorconfig`, `.prettierrc`, `.prettierrc.json`, `.prettierrc.yaml`, `.prettierrc.yml`, `.prettierrc.js`, `.nvmrc`, `.node-version`, `.browserslistrc`, `.clang-format`, `.clangd`, `.gdbinit`, `doxyfile`, `rustfmt.toml`, `.rustfmt.toml`, `.babelrc`, `.babelrc.json`, `turbo.json`, `nx.json`, `lerna.json`, `deno.json`, `deno.jsonc`, `bunfig.toml`, `.pypirc`, `appsettings.json`, `appsettings.development.json`, `appsettings.production.json`, `global.json`, `proguard-rules.pro` | `ini`, `properties` |
| tsconfig |  | `tsconfig.json`, `tsconfig.base.json`, `tsconfig.app.json`, `tsconfig.node.json`, `tsconfig.build.json`, `tsconfig.spec.json`, `tsconfig.lib.json` |  |
| jsconfig |  | `jsconfig.json` |  |
| lint |  | `.eslintrc`, `.eslintrc.js`, `.eslintrc.cjs`, `.eslintrc.json`, `.eslintrc.yml`, `.eslintrc.yaml`, `eslint.config.js`, `eslint.config.mjs`, `eslint.config.cjs`, `eslint.config.ts`, `.stylelintrc`, `.stylelintrc.json`, `stylelint.config.js`, `.markdownlint.json`, `biome.json`, `biome.jsonc`, `.oxlintrc.json`, `.clang-tidy`, `.golangci.yml`, `.golangci.yaml`, `clippy.toml`, `.clippy.toml`, `.rubocop.yml`, `.flake8`, `.pylintrc`, `pylintrc`, `ruff.toml`, `.ruff.toml`, `.swiftlint.yml`, `analysis_options.yaml`, `.php-cs-fixer.php`, `.php-cs-fixer.dist.php`, `phpstan.neon`, `phpstan.neon.dist`, `checkstyle.xml`, `detekt.yml` |  |
| env | `.env` | `.env`, `.env.local`, `.env.example`, `.env.development`, `.env.development.local`, `.env.production`, `.env.production.local`, `.env.test`, `.env.staging`, `.envrc` | `dotenv` |
| certificate | `.pem`, `.crt`, `.cer`, `.key`, `.csr`, `.der`, `.p12`, `.pfx`, `.jks`, `.keystore`, `.gpg`, `.pgp` | `id_rsa`, `id_ecdsa`, `id_ed25519`, `known_hosts`, `authorized_keys` |  |
| ignore |  | `.npmignore`, `.prettierignore`, `.eslintignore`, `.vscodeignore`, `.stylelintignore` | `ignore` |
| lock | `.lock` | `go.sum`, `go.work.sum`, `package-lock.json`, `pnpm-lock.yaml`, `bun.lockb`, `.terraform.lock.hcl`, `manifest.toml`, `package.resolved`, `cartfile.resolved` |  |
| image | `.png`, `.jpg`, `.jpeg`, `.gif`, `.webp`, `.avif`, `.bmp`, `.ico`, `.tif`, `.tiff` |  |  |
| svg | `.svg` |  |  |
| audio | `.mp3`, `.wav`, `.flac`, `.ogg`, `.m4a`, `.aac`, `.opus` |  |  |
| video | `.mp4`, `.mov`, `.webm`, `.mkv`, `.avi`, `.m4v` |  |  |
| archive | `.zip`, `.tar`, `.gz`, `.tgz`, `.bz2`, `.xz`, `.7z`, `.rar`, `.zst`, `.jar`, `.war`, `.ear`, `.apk`, `.aab`, `.ipa`, `.whl`, `.egg`, `.nupkg`, `.gem`, `.deb`, `.rpm`, `.dmg`, `.iso`, `.vsix` |  |  |
| git |  | `.gitignore`, `.gitattributes`, `.gitmodules`, `.gitkeep`, `.git-blame-ignore-revs` |  |
| docker | `.dockerfile` | `dockerfile`, `containerfile`, `.dockerignore`, `docker-compose.yml`, `docker-compose.yaml`, `compose.yml`, `compose.yaml` | `dockerfile`, `dockercompose` |
| make | `.mk`, `.mak`, `.cmake`, `.gradle`, `.gradle.kts`, `.bzl`, `.bazel`, `.star`, `.ninja`, `.props`, `.targets`, `.vcxproj` | `makefile`, `gnumakefile`, `cmakelists.txt`, `cmakepresets.json`, `cmakeuserpresets.json`, `compile_commands.json`, `configure`, `configure.ac`, `makefile.am`, `makefile.in`, `justfile`, `.justfile`, `build.bazel`, `workspace.bazel`, `module.bazel`, `meson.build`, `build.zig`, `build.ninja`, `build.rs`, `gradlew`, `gradlew.bat`, `mvnw`, `mvnw.cmd`, `build.xml` | `makefile`, `cmake`, `starlark`, `bazel`, `meson` |
| ci |  | `.gitlab-ci.yml`, `.travis.yml`, `jenkinsfile`, `azure-pipelines.yml`, `bitbucket-pipelines.yml`, `.drone.yml`, `appveyor.yml`, `.appveyor.yml`, `cloudbuild.yaml`, `codemagic.yaml` |  |
| deploy |  | `netlify.toml`, `vercel.json`, `wrangler.toml`, `wrangler.json`, `wrangler.jsonc`, `_redirects`, `_headers`, `procfile`, `fly.toml`, `render.yaml`, `railway.json`, `railway.toml`, `firebase.json`, `.firebaserc` |  |
| cname |  | `cname` |  |
| bot |  | `renovate.json`, `renovate.json5`, `.renovaterc`, `.renovaterc.json`, `dependabot.yml`, `dependabot.yaml`, `.mergify.yml` |  |
| server |  | `nginx.conf`, `.htaccess`, `httpd.conf`, `apache2.conf`, `caddyfile` | `nginx`, `apacheconf`, `caddyfile` |
| kubernetes | `.k8s.yaml`, `.k8s.yml` | `chart.yaml`, `values.yaml`, `kustomization.yaml`, `kustomization.yml`, `skaffold.yaml`, `helmfile.yaml` | `helm` |
| vagrant |  | `vagrantfile` |  |
| api | `.http`, `.rest`, `.postman_collection.json` | `openapi.yaml`, `openapi.yml`, `openapi.json`, `swagger.yaml`, `swagger.yml`, `swagger.json` | `http` |
| diff | `.diff`, `.patch`, `.rej` |  | `diff` |
| angular | `.component.ts`, `.directive.ts`, `.pipe.ts` | `angular.json`, `.angular-cli.json` |  |
| next |  | `next.config.js`, `next.config.mjs`, `next.config.ts` |  |
| nuxt |  | `nuxt.config.ts`, `nuxt.config.js`, `.nuxtrc` |  |
| vite |  | `vite.config.ts`, `vite.config.js`, `vite.config.mjs`, `vite.config.mts`, `vite.config.cjs` |  |
| webpack |  | `webpack.config.js`, `webpack.config.ts`, `webpack.config.cjs`, `webpack.config.mjs`, `webpack.common.js`, `webpack.dev.js`, `webpack.prod.js` |  |
| tailwind |  | `tailwind.config.js`, `tailwind.config.ts`, `tailwind.config.cjs`, `tailwind.config.mjs` |  |
| test-config |  | `jest.config.js`, `jest.config.ts`, `jest.config.mjs`, `jest.config.cjs`, `jest.config.json`, `jest.setup.js`, `jest.setup.ts`, `vitest.config.ts`, `vitest.config.js`, `vitest.config.mts`, `vitest.config.mjs`, `vitest.workspace.ts`, `playwright.config.ts`, `playwright.config.js`, `cypress.config.ts`, `cypress.config.js`, `karma.conf.js`, `.mocharc.json`, `.mocharc.yml`, `.mocharc.js` |  |
| snapshot | `.snap` |  |  |
| godot | `.gd`, `.tscn`, `.tres`, `.godot`, `.gdshader` |  | `gdscript` |
| unity | `.unity`, `.prefab`, `.asset`, `.unitypackage`, `.anim` |  |  |
| jupyter | `.ipynb` |  |  |
| quarto | `.qmd` |  | `quarto` |
| diagram | `.drawio`, `.dio`, `.excalidraw`, `.mmd`, `.mermaid`, `.puml`, `.plantuml`, `.iuml`, `.d2` |  | `mermaid`, `plantuml`, `d2` |
| ebook | `.epub`, `.mobi`, `.azw3`, `.djvu` |  |  |
| word | `.doc`, `.docx`, `.odt`, `.rtf`, `.pages` |  |  |
| spreadsheet | `.xls`, `.xlsx`, `.xlsm`, `.ods`, `.numbers` |  |  |
| presentation | `.ppt`, `.pptx`, `.odp` |  |  |
| todo | `.todo`, `.taskpaper` | `todo`, `todo.md`, `todo.txt`, `.todo` |  |
| contributing |  | `contributing.md`, `contributing`, `code_of_conduct.md`, `code-of-conduct.md`, `support.md`, `funding.yml`, `.all-contributorsrc` |  |
| authors |  | `authors`, `authors.md`, `authors.txt`, `contributors`, `contributors.md`, `codeowners`, `maintainers`, `maintainers.md`, `owners` |  |
| security |  | `security.md`, `security.txt` |  |
| model3d | `.stl`, `.fbx`, `.gltf`, `.glb`, `.blend`, `.dae`, `.3ds`, `.usd`, `.usdz`, `.ply`, `.3mf` |  |  |
| design | `.fig`, `.sketch`, `.psd`, `.ai`, `.xd`, `.afdesign`, `.afphoto`, `.kra`, `.xcf`, `.eps`, `.indd` |  |  |
| subtitle | `.srt`, `.vtt`, `.ass`, `.ssa` |  |  |
| calendar | `.ics`, `.ical`, `.ifb`, `.vcs` |  |  |
| contact | `.vcf`, `.vcard` |  |  |
| checksum | `.sha1`, `.sha256`, `.sha512`, `.md5` | `sha256sums`, `sha256sums.txt`, `sha512sums`, `md5sums`, `checksums.txt` |  |

</details>

<details>
<summary>폴더 아이콘 71종</summary>

| 아이콘 | 폴더 이름 |
|---|---|
| folder | (기본) |
| root-folder | (워크스페이스 루트) |
| folder-archetypes | `archetypes` |
| folder-assets | `assets` |
| folder-config | `config`, `meta-inf`, `web-inf`, `.mvn` |
| folder-content | `content`, `posts`, `post`, `blog` |
| folder-data | `data`, `dataset`, `datasets` |
| folder-i18n | `i18n`, `locales`, `locale`, `translations` |
| folder-layout | `layouts`, `_default`, `views`, `templates`, `template` |
| folder-partials | `_partials`, `partials` |
| folder-shortcodes | `_shortcodes`, `shortcodes` |
| folder-markup | `_markup` |
| folder-static | `static` |
| folder-themes | `themes` |
| folder-images | `images`, `image`, `img`, `imgs`, `pictures`, `photos`, `drawable`, `assets.xcassets` |
| folder-styles | `css`, `scss`, `sass`, `styles`, `style`, `stylesheets` |
| folder-js | `js`, `javascript` |
| folder-fonts | `fonts`, `font` |
| folder-audio | `audio`, `sounds`, `sound`, `music` |
| folder-video | `videos`, `video`, `movies` |
| folder-src | `src`, `source`, `sources` |
| folder-lib | `lib`, `libs`, `pkg`, `packages`, `crates` |
| folder-components | `components`, `component` |
| folder-types | `types`, `@types`, `typings` |
| folder-utils | `utils`, `util`, `helpers`, `helper`, `tools` |
| folder-scripts | `scripts`, `script`, `bin`, `cmd` |
| folder-test | `test`, `tests`, `__tests__`, `spec`, `specs`, `e2e`, `androidtest`, `testing` |
| folder-include | `include`, `includes`, `inc` |
| folder-java | `java` |
| folder-kotlin | `kotlin` |
| folder-build-tools | `cmake`, `gradle` |
| folder-docs | `docs`, `doc`, `documentation`, `wiki` |
| folder-database | `db`, `database`, `migrations`, `seeds`, `seeders` |
| folder-api | `api`, `apis`, `endpoints`, `controllers`, `controller` |
| folder-server | `server`, `servers`, `backend`, `services`, `service` |
| folder-client | `client`, `frontend`, `ui` |
| folder-hooks | `hooks`, `composables` |
| folder-middleware | `middleware`, `middlewares` |
| folder-models | `models`, `model`, `entities`, `entity`, `schemas`, `schema` |
| folder-store | `store`, `stores`, `state`, `redux` |
| folder-security | `auth`, `authentication`, `security`, `permissions`, `guards` |
| folder-secrets | `secrets`, `.secrets`, `keys`, `certs`, `certificates`, `ssl` |
| folder-plugins | `plugins`, `plugin`, `extensions`, `addons` |
| folder-mocks | `__mocks__`, `mocks`, `mock`, `fixtures`, `__fixtures__`, `stubs` |
| folder-examples | `examples`, `example`, `samples`, `sample`, `demo`, `demos` |
| folder-benchmarks | `bench`, `benches`, `benchmark`, `benchmarks` |
| folder-icons | `icons`, `icon`, `favicons`, `favicon` |
| folder-design | `design`, `designs`, `mockups`, `figma` |
| folder-notebooks | `notebooks` |
| folder-archive | `archive`, `archives`, `backup`, `backups` |
| folder-k8s | `k8s`, `kubernetes`, `helm`, `charts` |
| folder-terraform | `terraform`, `infra`, `infrastructure` |
| folder-android | `android` |
| folder-ios | `ios` |
| folder-github | `.github`, `.gitlab`, `.gitea` |
| folder-husky | `.husky` |
| folder-workflows | `workflows`, `.circleci` |
| folder-storybook | `.storybook` |
| folder-vscode | `.vscode` |
| folder-docker | `docker`, `.docker`, `.devcontainer` |
| folder-git | `.git` |
| folder-public | `public` |
| folder-resources | `resources` |
| folder-node-modules | `node_modules` |
| folder-vendor | `vendor`, `third_party`, `third-party`, `3rdparty`, `external`, `deps` |
| folder-dist | `dist`, `build`, `out`, `output`, `.output`, `target`, `obj`, `_build`, `.build`, `.next`, `.nuxt`, `.svelte-kit` |
| folder-coverage | `coverage`, `.nyc_output` |
| folder-logs | `logs`, `log` |
| folder-idea | `.idea`, `.vs`, `.settings`, `.fleet` |
| folder-venv | `.venv`, `venv`, `.virtualenv` |
| folder-temp | `.cache`, `cache`, `tmp`, `temp`, `.tmp`, `.temp`, `__pycache__`, `.pytest_cache`, `.mypy_cache`, `.ruff_cache`, `.tox`, `.gradle`, `.dart_tool`, `.turbo`, `.parcel-cache`, `.vercel`, `.netlify`, `.astro`, `.angular`, `.sass-cache` |

</details>
<!-- icons:end -->

## 알아둘 점

- VS Code는 파일 이름을 점(`.`)으로 나눈 뒤쪽만 확장자로 봅니다. 그래서 `test_*.py`, `*_test.go`처럼 점이 아닌 문자로 붙는 이름 패턴에는 아이콘을 따로 줄 수 없습니다.
- `.m`(Objective-C·MATLAB), `.v`(Verilog·V·Coq)처럼 여러 언어가 같이 쓰는 확장자는 VS Code가 판단한 언어로 구분합니다. 해당 언어 확장이 설치돼 있어야 맞는 아이콘이 나옵니다.
- `public`, `resources`, `build`처럼 프로젝트마다 뜻이 다른 폴더는 가장 흔한 쓰임새를 기준으로 했습니다.
- 다크 테마용 변형은 없습니다.

## 릴리스

1. `package.json`의 `version`과 `CHANGELOG.md`를 고쳐서 커밋합니다.
2. 같은 버전으로 태그를 푸시하면 GitHub Actions가 `.vsix`를 만들어 Release에 올립니다.

   ```bash
   git tag v0.1.0
   git push origin v0.1.0
   ```

태그와 `package.json`의 버전이 다르면 빌드가 실패합니다. 릴리스 노트는 GitHub가 커밋 기록으로 자동으로 만듭니다.

`vsce`는 README 안의 SVG 이미지를 허용하지 않으므로 README에는 이미지를 넣지 않습니다.

## 라이선스

[MIT](LICENSE)
