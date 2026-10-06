# awesome-devtools-ko — 직접 설치해 써본 개발·AI 도구 표

직접 설치·실행해 본 오픈소스 개발 도구·AI 도구를 한국어 한 줄 설명, 설치 명령, 라이선스, 심화 글과 함께 정리한 표. data/tools.json 제공.

직접 설치해 실행한 기록(Debian 12 LXC 샌드박스)을 바탕으로 만든 표입니다. 각 행의 **심화 글**에 설치 과정·첫 화면·실제 출력이 있습니다. 기계 판독용 데이터는 [`data/tools.json`](data/tools.json).

갱신 2026-10-06 · 도구 22개 · 라이선스 [CC BY 4.0](LICENSE)

## 전체 표

| 도구 | 무엇 | 설치 한 줄 | 라이선스 | 심화 글 |
|---|---|---|---|---|
| [Bastardica](https://bastardica.mitpit.com/) | 브라우저에서 글꼴 두 개를 섞어 새 폰트 파일을 만드는 웹 도구 | 설치 없음 — 브라우저에서 바로 | 해당 없음(웹 서비스) | [Bastardica 사용법, 글꼴 두 개를 섞어 새 폰트로](https://review.kimwon.com/bastardica-%ec%82%ac%ec%9a%a9%eb%b2%95/) |
| [Book of Shapes](https://bookofshapes.com/) | 값을 조절해 SVG로 내려받는 생성형 패턴 모음 웹 사이트 | 설치 없음 — 브라우저에서 바로 | 해당 없음(웹 서비스) | [Book of Shapes, 무엇이고 누구에게 맞나](https://review.kimwon.com/bookofshapes-svg-%ed%8c%a8%ed%84%b4/) |
| [bzip3](https://github.com/iczelia/bzip3) | bzip2를 잇는 블록 정렬 기반 고압축률 명령줄 압축기 | `brew install bzip3` | LGPL-3.0 | [bzip3, 무엇이고 누구에게 맞나](https://review.kimwon.com/bzip3-what-it-is-and-who-its-for/) |
| [Cloudflare Python Workers](https://github.com/cloudflare/python-workers-examples) | Cloudflare 엣지에서 Python 코드를 실행하는 서버리스 런타임 | `uv tool install workers-py` | Apache-2.0 | [Cloudflare Python Workers가 달라진 점](https://review.kimwon.com/cloudflare-python-workers-%ec%86%8c%ea%b0%9c/) |
| [Cloudflare Quick Tunnels](https://developers.cloudflare.com/cloudflare-one/networks/connectors/cloudflare-tunnel/do-more-with-tunnels/trycloudflare/) | 계정 없이 로컬 서버에 공개 HTTPS 주소를 붙이는 cloudflared 기능 | `brew install cloudflared` | Apache-2.0 | [Quick Tunnels 사용법, 로컬을 공개 URL로](https://review.kimwon.com/cloudflare-quick-tunnels-%ec%82%ac%ec%9a%a9%eb%b2%95/) |
| [dbt Charts](https://docs.dbtcharts.com/) | SQL과 YAML 파일 하나로 대시보드를 정의하는 dbt Labs 도구 | `uv tool install dbt-charts` | Apache-2.0 | [dbt Charts 사용법: 설치부터 첫 보드까지](https://review.kimwon.com/dbt-charts-%ec%82%ac%ec%9a%a9%eb%b2%95/) |
| [fnprint](https://github.com/1rhino2/fnprint) | 심볼 없는 x86-64 ELF 함수를 동작 기반으로 식별하는 도구 | `git clone https://github.com/1rhino2/fnprint && cd fnprint && cargo build --release` | MIT | [fnprint, 동작으로 함수를 찾아내는 도구](https://review.kimwon.com/fnprint-%eb%b0%94%ec%9d%b4%eb%84%88%eb%a6%ac-%eb%b6%84%ec%84%9d/) |
| [Gemini 3.8 Flash TTS](https://ai.google.dev/gemini-api/docs/speech-generation) | 프롬프트로 목소리를 설계하고 연기를 지시하는 구글 TTS 모델 | 설치 없음 — Gemini API로 호출 | 해당 없음(Google API) | [Gemini 3.8 Flash TTS, 무엇이고 누구에게 맞나](https://review.kimwon.com/gemini-38-flash-tts-%ec%9d%8c%ec%84%b1%ed%95%a9%ec%84%b1/) |
| [Globestudio](https://globestudio.app) | 점 지도와 3D 지구본을 만들어 이미지·영상으로 내보내는 오픈소스 웹 도구 | `git clone https://github.com/alevizio/globestudio && cd globestudio && npm install` | MIT | [Globestudio 사용법, 점 지도와 3D 지구본을 무료로](https://review.kimwon.com/globestudio-%ec%82%ac%ec%9a%a9%eb%b2%95/) |
| [Google Home MCP](https://developers.home.google.com/mcp/home) | AI 에이전트가 Google Home 기기를 읽고 제어하게 하는 공식 MCP 서버 | 설치 없음 — 원격 MCP 서버(Home Premium Advanced 구독) | 해당 없음(Google 서비스) | [Google Home MCP, 무엇이고 누구에게 맞나](https://review.kimwon.com/google-home-mcp-%ec%8a%a4%eb%a7%88%ed%8a%b8%ed%99%88-ai/) |
| [HN Watch](https://github.com/sourabhbgp/hn-watch) | Claude 에이전트로 해커뉴스를 감시해 관심 글을 골라 주는 macOS 앱 | `git clone https://github.com/sourabhbgp/hn-watch && cd hn-watch && npm install` | MIT | [HN Watch, 해커뉴스를 대신 지켜보는 맥 앱](https://review.kimwon.com/hn-watch-%ed%95%b4%ec%bb%a4%eb%89%b4%ec%8a%a4-%ec%95%8c%eb%a6%bc/) |
| [Ledge](https://ledge.sh/) | 마크다운 노트 속 코드 블록을 그 자리에서 실행하는 노트 앱 | 공식 사이트 설치 파일(macOS·Linux·Windows·모바일) | Apache-2.0 | [Ledge, 실행되는 마크다운 노트는 누구에게 맞나](https://review.kimwon.com/ledge-%eb%a7%88%ed%81%ac%eb%8b%a4%ec%9a%b4-%eb%85%b8%ed%8a%b8-%ec%bd%94%eb%93%9c%ec%8b%a4%ed%96%89/) |
| [Lofi Cities](https://loficities.com) | 픽셀아트 도시 야경과 실시간 합성 로파이 음악을 트는 무료 웹 앱 | 설치 없음 — 브라우저에서 바로 | 해당 없음(웹 서비스) | [Lofi Cities 사용법, 설치 없이 켜는 작업용 로파이](https://review.kimwon.com/lofi-cities-%ec%82%ac%ec%9a%a9%eb%b2%95/) |
| [MCPJam](https://www.mcpjam.com/) | MCP 서버·앱을 채팅하며 검사·디버깅하는 테스트 도구 | `npm i -g @mcpjam/cli` | Apache-2.0(일부 별도) | [MCPJam 사용법: 설치부터 첫 명령까지](https://review.kimwon.com/mcpjam-%ec%82%ac%ec%9a%a9%eb%b2%95/) |
| [NVIDIA Personal AI Router](https://github.com/NVIDIA/Personal-AI-Router) | 집 안 여러 컴퓨터에 로컬 AI 추론 요청을 나눠 보내는 라우터 | 릴리스 페이지 설치 파일(exe·deb·dmg) | Apache-2.0 | [PC 여러 대로 AI 돌리는 NVIDIA PAIR](https://review.kimwon.com/personal-ai-router-%eb%a1%9c%ec%bb%ac-ai-%eb%9d%bc%ec%9a%b0%ed%84%b0/) |
| [omnibin](https://github.com/kitamura-felipe/omnibin) | 의료 AI 모델 평가 결과를 신뢰구간 포함 PDF 리포트로 만드는 파이썬 패키지 | `pip install omnibin` | MIT | [omnibin, 의료 AI 평가 리포트를 자동으로](https://review.kimwon.com/omnibin-%eb%aa%a8%eb%8d%b8-%ed%8f%89%ea%b0%80-%eb%a6%ac%ed%8f%ac%ed%8a%b8/) |
| [Pass Designer](https://developer.apple.com/pass-designer) | Apple Wallet 패스 템플릿을 보면서 편집하는 Apple의 Mac 앱 | Apple Developer 사이트에서 내려받기(macOS 27+) | 해당 없음(Apple 무료 앱) | [Apple Pass Designer, 무엇이고 누구에게 맞나](https://review.kimwon.com/pass-designer-%ec%95%a0%ed%94%8c%ec%9b%94%eb%a0%9b%ed%8c%a8%ec%8a%a4/) |
| [Pirate Face](https://pirateface.co) | 공개 AI 모델을 검증된 토렌트로 보존·배포하는 웹 서비스 | 설치 없음 — 브라우저에서 바로 | 해당 없음(웹 서비스) | [Pirate Face 사용법, AI 모델을 토렌트로 보존](https://review.kimwon.com/pirateface-%ec%82%ac%ec%9a%a9%eb%b2%95/) |
| [skills](https://skills.sh) | GitHub 저장소의 에이전트 스킬을 코딩 에이전트에 설치·관리하는 CLI | `npx skills add <owner/repo>` | MIT | [skills 사용법: 설치부터 첫 스킬 적용까지](https://review.kimwon.com/skills-cli-%ec%82%ac%ec%9a%a9%eb%b2%95/) |
| [Tcl/Tk](https://www.tcl-lang.org/) | 스크립트 언어 Tcl과 GUI 툴킷 Tk를 묶은 조합 | `brew install tcl-tk` | TCL | [Tcl/Tk 9.1, 무엇이 달라졌고 누구에게 맞나](https://review.kimwon.com/tcltk-91-%ec%83%88%ea%b8%b0%eb%8a%a5/) |
| [trynix](https://trynix.dev) | 브라우저 탭에서 nixpkgs 패키지를 설치 없이 바로 실행하는 웹 도구 | 설치 없음 — 브라우저에서 바로 | MIT | [trynix 사용법, 브라우저 탭에서 패키지 바로 실행](https://review.kimwon.com/trynix-%ec%82%ac%ec%9a%a9%eb%b2%95/) |
| [unslop](https://github.com/theclaymethod/unslop) | AI 글투를 줄 단위로 찾아내는 파이썬 글쓰기 검사 도구 | `git clone https://github.com/theclaymethod/unslop` | MIT(README 표기) | [unslop 사용법: 설치부터 첫 검사까지](https://review.kimwon.com/unslop-%ec%82%ac%ec%9a%a9%eb%b2%95/) |

## CLI·터미널

- **bzip3** — bzip2를 잇는 블록 정렬 기반 고압축률 명령줄 압축기 (C · ★ 1,495 · [GitHub](https://github.com/iczelia/bzip3))  
  `brew install bzip3`  
  심화 글: [bzip3, 무엇이고 누구에게 맞나](https://review.kimwon.com/bzip3-what-it-is-and-who-its-for/) · 2026-09-09

## 개발 도구

- **fnprint** — 심볼 없는 x86-64 ELF 함수를 동작 기반으로 식별하는 도구 (Rust · ★ 44 · [GitHub](https://github.com/1rhino2/fnprint))  
  `git clone https://github.com/1rhino2/fnprint && cd fnprint && cargo build --release`  
  심화 글: [fnprint, 동작으로 함수를 찾아내는 도구](https://review.kimwon.com/fnprint-%eb%b0%94%ec%9d%b4%eb%84%88%eb%a6%ac-%eb%b6%84%ec%84%9d/) · 2026-09-09
- **Ledge** — 마크다운 노트 속 코드 블록을 그 자리에서 실행하는 노트 앱 (TypeScript · ★ 309 · [GitHub](https://github.com/ledgesh/ledge))  
  공식 사이트 설치 파일(macOS·Linux·Windows·모바일)  
  심화 글: [Ledge, 실행되는 마크다운 노트는 누구에게 맞나](https://review.kimwon.com/ledge-%eb%a7%88%ed%81%ac%eb%8b%a4%ec%9a%b4-%eb%85%b8%ed%8a%b8-%ec%bd%94%eb%93%9c%ec%8b%a4%ed%96%89/) · 2026-10-05
- **Pass Designer** — Apple Wallet 패스 템플릿을 보면서 편집하는 Apple의 Mac 앱  
  Apple Developer 사이트에서 내려받기(macOS 27+)  
  심화 글: [Apple Pass Designer, 무엇이고 누구에게 맞나](https://review.kimwon.com/pass-designer-%ec%95%a0%ed%94%8c%ec%9b%94%eb%a0%9b%ed%8c%a8%ec%8a%a4/) · 2026-10-03
- **Tcl/Tk** — 스크립트 언어 Tcl과 GUI 툴킷 Tk를 묶은 조합  
  `brew install tcl-tk`  
  심화 글: [Tcl/Tk 9.1, 무엇이 달라졌고 누구에게 맞나](https://review.kimwon.com/tcltk-91-%ec%83%88%ea%b8%b0%eb%8a%a5/) · 2026-09-30
- **trynix** — 브라우저 탭에서 nixpkgs 패키지를 설치 없이 바로 실행하는 웹 도구 (JavaScript · ★ 159 · [GitHub](https://github.com/fzakaria/trynix))  
  설치 없음 — 브라우저에서 바로  
  심화 글: [trynix 사용법, 브라우저 탭에서 패키지 바로 실행](https://review.kimwon.com/trynix-%ec%82%ac%ec%9a%a9%eb%b2%95/) · 2026-09-13

## AI·LLM

- **Gemini 3.8 Flash TTS** — 프롬프트로 목소리를 설계하고 연기를 지시하는 구글 TTS 모델  
  설치 없음 — Gemini API로 호출  
  심화 글: [Gemini 3.8 Flash TTS, 무엇이고 누구에게 맞나](https://review.kimwon.com/gemini-38-flash-tts-%ec%9d%8c%ec%84%b1%ed%95%a9%ec%84%b1/) · 2026-09-24
- **Google Home MCP** — AI 에이전트가 Google Home 기기를 읽고 제어하게 하는 공식 MCP 서버  
  설치 없음 — 원격 MCP 서버(Home Premium Advanced 구독)  
  심화 글: [Google Home MCP, 무엇이고 누구에게 맞나](https://review.kimwon.com/google-home-mcp-%ec%8a%a4%eb%a7%88%ed%8a%b8%ed%99%88-ai/) · 2026-09-17
- **HN Watch** — Claude 에이전트로 해커뉴스를 감시해 관심 글을 골라 주는 macOS 앱 (Rust · ★ 1 · [GitHub](https://github.com/sourabhbgp/hn-watch))  
  `git clone https://github.com/sourabhbgp/hn-watch && cd hn-watch && npm install`  
  심화 글: [HN Watch, 해커뉴스를 대신 지켜보는 맥 앱](https://review.kimwon.com/hn-watch-%ed%95%b4%ec%bb%a4%eb%89%b4%ec%8a%a4-%ec%95%8c%eb%a6%bc/) · 2026-09-29
- **MCPJam** — MCP 서버·앱을 채팅하며 검사·디버깅하는 테스트 도구 (TypeScript · ★ 2,238 · [GitHub](https://github.com/MCPJam/inspector))  
  `npm i -g @mcpjam/cli`  
  심화 글: [MCPJam 사용법: 설치부터 첫 명령까지](https://review.kimwon.com/mcpjam-%ec%82%ac%ec%9a%a9%eb%b2%95/) · 2026-09-18
- **NVIDIA Personal AI Router** — 집 안 여러 컴퓨터에 로컬 AI 추론 요청을 나눠 보내는 라우터 (Go · ★ 1,552 · [GitHub](https://github.com/NVIDIA/Personal-AI-Router))  
  릴리스 페이지 설치 파일(exe·deb·dmg)  
  심화 글: [PC 여러 대로 AI 돌리는 NVIDIA PAIR](https://review.kimwon.com/personal-ai-router-%eb%a1%9c%ec%bb%ac-ai-%eb%9d%bc%ec%9a%b0%ed%84%b0/) · 2026-09-14
- **omnibin** — 의료 AI 모델 평가 결과를 신뢰구간 포함 PDF 리포트로 만드는 파이썬 패키지 (Python · ★ 3 · [GitHub](https://github.com/kitamura-felipe/omnibin))  
  `pip install omnibin`  
  심화 글: [omnibin, 의료 AI 평가 리포트를 자동으로](https://review.kimwon.com/omnibin-%eb%aa%a8%eb%8d%b8-%ed%8f%89%ea%b0%80-%eb%a6%ac%ed%8f%ac%ed%8a%b8/) · 2026-09-27
- **Pirate Face** — 공개 AI 모델을 검증된 토렌트로 보존·배포하는 웹 서비스  
  설치 없음 — 브라우저에서 바로  
  심화 글: [Pirate Face 사용법, AI 모델을 토렌트로 보존](https://review.kimwon.com/pirateface-%ec%82%ac%ec%9a%a9%eb%b2%95/) · 2026-09-21
- **skills** — GitHub 저장소의 에이전트 스킬을 코딩 에이전트에 설치·관리하는 CLI (TypeScript · ★ 33,220 · [GitHub](https://github.com/vercel-labs/skills))  
  `npx skills add <owner/repo>`  
  심화 글: [skills 사용법: 설치부터 첫 스킬 적용까지](https://review.kimwon.com/skills-cli-%ec%82%ac%ec%9a%a9%eb%b2%95/) · 2026-09-11
- **unslop** — AI 글투를 줄 단위로 찾아내는 파이썬 글쓰기 검사 도구 (Python · ★ 505 · [GitHub](https://github.com/theclaymethod/unslop))  
  `git clone https://github.com/theclaymethod/unslop`  
  심화 글: [unslop 사용법: 설치부터 첫 검사까지](https://review.kimwon.com/unslop-%ec%82%ac%ec%9a%a9%eb%b2%95/) · 2026-09-12

## 데이터·문서

- **dbt Charts** — SQL과 YAML 파일 하나로 대시보드를 정의하는 dbt Labs 도구 (Python · ★ 550 · [GitHub](https://github.com/dbt-labs/dbt-charts))  
  `uv tool install dbt-charts`  
  심화 글: [dbt Charts 사용법: 설치부터 첫 보드까지](https://review.kimwon.com/dbt-charts-%ec%82%ac%ec%9a%a9%eb%b2%95/) · 2026-09-16

## 웹·앱

- **Bastardica** — 브라우저에서 글꼴 두 개를 섞어 새 폰트 파일을 만드는 웹 도구  
  설치 없음 — 브라우저에서 바로  
  심화 글: [Bastardica 사용법, 글꼴 두 개를 섞어 새 폰트로](https://review.kimwon.com/bastardica-%ec%82%ac%ec%9a%a9%eb%b2%95/) · 2026-09-25
- **Book of Shapes** — 값을 조절해 SVG로 내려받는 생성형 패턴 모음 웹 사이트  
  설치 없음 — 브라우저에서 바로  
  심화 글: [Book of Shapes, 무엇이고 누구에게 맞나](https://review.kimwon.com/bookofshapes-svg-%ed%8c%a8%ed%84%b4/) · 2026-10-02
- **Globestudio** — 점 지도와 3D 지구본을 만들어 이미지·영상으로 내보내는 오픈소스 웹 도구 (JavaScript · ★ 12 · [GitHub](https://github.com/alevizio/globestudio))  
  `git clone https://github.com/alevizio/globestudio && cd globestudio && npm install`  
  심화 글: [Globestudio 사용법, 점 지도와 3D 지구본을 무료로](https://review.kimwon.com/globestudio-%ec%82%ac%ec%9a%a9%eb%b2%95/) · 2026-10-04
- **Lofi Cities** — 픽셀아트 도시 야경과 실시간 합성 로파이 음악을 트는 무료 웹 앱  
  설치 없음 — 브라우저에서 바로  
  심화 글: [Lofi Cities 사용법, 설치 없이 켜는 작업용 로파이](https://review.kimwon.com/lofi-cities-%ec%82%ac%ec%9a%a9%eb%b2%95/) · 2026-09-28

## 인프라·자동화

- **Cloudflare Python Workers** — Cloudflare 엣지에서 Python 코드를 실행하는 서버리스 런타임 (Python · ★ 334 · [GitHub](https://github.com/cloudflare/python-workers-examples))  
  `uv tool install workers-py`  
  심화 글: [Cloudflare Python Workers가 달라진 점](https://review.kimwon.com/cloudflare-python-workers-%ec%86%8c%ea%b0%9c/) · 2026-09-23
- **Cloudflare Quick Tunnels** — 계정 없이 로컬 서버에 공개 HTTPS 주소를 붙이는 cloudflared 기능 (Go · ★ 16,035 · [GitHub](https://github.com/cloudflare/cloudflared))  
  `brew install cloudflared`  
  심화 글: [Quick Tunnels 사용법, 로컬을 공개 URL로](https://review.kimwon.com/cloudflare-quick-tunnels-%ec%82%ac%ec%9a%a9%eb%b2%95/) · 2026-09-19

## 출처·원칙

- 설치 명령은 공식 README 기준이며 실행 시점의 버전에 따라 달라질 수 있습니다.
- 라이선스·별 수는 GitHub API 값입니다. 오류·누락은 이슈로 알려주세요.
- 표의 문장과 데이터는 CC BY 4.0, 각 도구의 이름·로고·코드는 해당 프로젝트의 라이선스를 따릅니다.
- 블로그: [리뷰노트](https://review.kimwon.com) · 링크허브: [links.kimwon.com](https://links.kimwon.com/review/)
