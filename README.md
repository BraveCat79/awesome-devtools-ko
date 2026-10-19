# awesome-devtools-ko — 직접 설치해 써본 개발·AI 도구 표

직접 설치·실행해 본 오픈소스 개발 도구·AI 도구를 한국어 한 줄 설명, 설치 명령, 라이선스, 심화 글과 함께 정리한 표. data/tools.json 제공.

Debian 12 LXC 샌드박스에서 설치·실행해 본 기록을 바탕으로 만든 표입니다. 각 행의 **확인** 칸에 실제로 실행했는지, 문서로만 확인했는지를 적었습니다. **공식 자료** 칸은 도구의 공식 사이트·GitHub, **심화 글**은 설치 과정·첫 화면·실제 출력을 적은 사용기입니다. 기계 판독용 데이터는 [`data/tools.json`](data/tools.json).

갱신 2026-10-19 · 도구 32개(✅ 실행 16 · ◐ 일부 실행 6 · 📄 문서 확인 10) · 라이선스 [CC BY 4.0](LICENSE)

## 선정 기준·확인 방법

- **넣는 기준**: 최근 공개·갱신된 개발·AI 도구 중 ① 공식 사이트나 저장소가 있고 ② 설치 방법(또는 웹·API 접근 방법)이 공개돼 있으며 ③ 사용기 글을 공개한 것. 보관(archived)된 저장소, 공개 전·삭제된 글은 넣지 않습니다.
- **확인 칸**: ✅ 실행 = 샌드박스에서 설치부터 첫 실행까지 돌려 봄(괄호는 성공한 단계 수) · ◐ 일부 실행 = 설치나 일부 명령만 돌려 봄 · 📄 문서 확인 = 실행하지 않고 공식 문서·발표 자료로만 확인(macOS 전용·유료 구독 도구 포함).
- **실행 환경**: Debian 12 LXC(x86-64). 웹 도구는 브라우저로 페이지를 열어 확인. macOS·Windows 전용 기능, GPU 추론 성능, 유료 플랜 기능은 검증 범위 밖입니다.
- **값의 출처**: 라이선스·별 수·언어는 GitHub API, 설치 명령은 공식 README·문서 기준입니다. 자동 추출이 틀린 값은 사람이 공식 페이지를 보고 고칩니다.
- 설치 명령은 확인 시점의 버전 기준이라 바뀔 수 있습니다. 쓰기 전에 **공식 자료** 칸의 문서를 함께 보세요.

## 전체 표

| 도구 | 무엇 | 설치 한 줄 | 라이선스 | 확인 | 공식 자료 | 심화 글 |
|---|---|---|---|---|---|---|
| [A Walkable History of Art](https://artmuseum.artfrompixels.com/) | 미술사 연표에서 화가를 골라 3D 가상 갤러리로 들어가는 웹사이트 | 설치 없음 — 브라우저에서 바로 | 해당 없음(웹 서비스) | ◐ 일부 실행 | [공식](https://artmuseum.artfrompixels.com/) | [A Walkable History of Art: 3D 미술사 갤러리, 누구에게 맞나](https://review.kimwon.com/a-walkable-history-of-art-%eb%af%b8%ec%88%a0%ec%82%ac/) |
| [agent-gc](https://github.com/williamjeong2/agent-gc) | AI 코딩 에이전트가 남긴 worktree와 빌드 산출물을 정리하는 Rust TUI | `npm install -g agent-gc` | MIT | ✅ 실행 | [GitHub](https://github.com/williamjeong2/agent-gc) | [agent-gc 사용법, AI 에이전트가 남긴 용량 되찾기](https://review.kimwon.com/agent-gc-%ec%82%ac%ec%9a%a9%eb%b2%95/) |
| [Bastardica](https://bastardica.mitpit.com/) | 브라우저에서 글꼴 두 개를 섞어 새 폰트 파일을 만드는 웹 도구 | 설치 없음 — 브라우저에서 바로 | 해당 없음(웹 서비스) | ✅ 실행 | [공식](https://bastardica.mitpit.com/) | [Bastardica 사용법, 글꼴 두 개를 섞어 새 폰트로](https://review.kimwon.com/bastardica-%ec%82%ac%ec%9a%a9%eb%b2%95/) |
| [Blumify for Claude](https://blumify.io/developers#mcp) | 유튜브·팟캐스트 링크를 스크립트와 요약으로 바꿔 주는 Claude 플러그인 | `/plugin install blumify@blumify` | MIT | ✅ 실행 | [공식](https://blumify.io/developers#mcp) · [GitHub](https://github.com/Sketchjar/blumify-claude-plugin) | [Blumify 사용법: Claude용 유튜브·팟캐스트 요약 플러그인, 설치부터 질문까지](https://review.kimwon.com/blumify-%ec%82%ac%ec%9a%a9%eb%b2%95/) |
| [Book of Shapes](https://bookofshapes.com/) | 값을 조절해 SVG로 내려받는 생성형 패턴 모음 웹 사이트 | 설치 없음 — 브라우저에서 바로 | 해당 없음(웹 서비스) | ◐ 일부 실행 | [공식](https://bookofshapes.com/) | [Book of Shapes, 무엇이고 누구에게 맞나](https://review.kimwon.com/bookofshapes-svg-%ed%8c%a8%ed%84%b4/) |
| [bzip3](https://github.com/iczelia/bzip3) | bzip2를 잇는 블록 정렬 기반 고압축률 명령줄 압축기 | `brew install bzip3` | LGPL-3.0 | ◐ 일부 실행 | [GitHub](https://github.com/iczelia/bzip3) | [bzip3, 무엇이고 누구에게 맞나](https://review.kimwon.com/bzip3-what-it-is-and-who-its-for/) |
| [Carrier-Explode](https://carrierexplode.com) | 아이폰·픽셀·갤럭시 펌웨어의 통신사 설정을 해독해 비교하는 사이트 | 설치 없음 — 웹사이트에서 조회(공개 API 제공) | MIT | ✅ 실행 | [공식](https://carrierexplode.com) · [GitHub](https://github.com/AlecDusheck/carrier-explode) | [Carrier-Explode 사용법: 아이폰·갤럭시 통신사 설정 비교 사이트, 조회부터 API까지](https://review.kimwon.com/carrier-explode-%ec%82%ac%ec%9a%a9%eb%b2%95/) |
| [Cloudflare Python Workers](https://github.com/cloudflare/python-workers-examples) | Cloudflare 엣지에서 Python 코드를 실행하는 서버리스 런타임 | `uv tool install workers-py` | Apache-2.0 | ◐ 일부 실행 | [GitHub](https://github.com/cloudflare/python-workers-examples) | [Cloudflare Python Workers가 달라진 점](https://review.kimwon.com/cloudflare-python-workers-%ec%86%8c%ea%b0%9c/) |
| [Cloudflare Quick Tunnels](https://developers.cloudflare.com/cloudflare-one/networks/connectors/cloudflare-tunnel/do-more-with-tunnels/trycloudflare/) | 계정 없이 로컬 서버에 공개 HTTPS 주소를 붙이는 cloudflared 기능 | `brew install cloudflared` | Apache-2.0 | ✅ 실행 | [공식](https://developers.cloudflare.com/cloudflare-one/networks/connectors/cloudflare-tunnel/do-more-with-tunnels/trycloudflare/) · [GitHub](https://github.com/cloudflare/cloudflared) | [Quick Tunnels 사용법, 로컬을 공개 URL로](https://review.kimwon.com/cloudflare-quick-tunnels-%ec%82%ac%ec%9a%a9%eb%b2%95/) |
| [dbt Charts](https://docs.dbtcharts.com/) | SQL과 YAML 파일 하나로 대시보드를 정의하는 dbt Labs 도구 | `uv tool install dbt-charts` | Apache-2.0 | ✅ 실행 | [공식](https://docs.dbtcharts.com/) · [GitHub](https://github.com/dbt-labs/dbt-charts) | [dbt Charts 사용법: 설치부터 첫 보드까지](https://review.kimwon.com/dbt-charts-%ec%82%ac%ec%9a%a9%eb%b2%95/) |
| [fnprint](https://github.com/1rhino2/fnprint) | 심볼 없는 x86-64 ELF 함수를 동작 기반으로 식별하는 도구 | `git clone https://github.com/1rhino2/fnprint && cd fnprint && cargo build --release` | MIT | 📄 문서 확인 | [GitHub](https://github.com/1rhino2/fnprint) | [fnprint, 동작으로 함수를 찾아내는 도구](https://review.kimwon.com/fnprint-%eb%b0%94%ec%9d%b4%eb%84%88%eb%a6%ac-%eb%b6%84%ec%84%9d/) |
| [FOSS Alternatives](https://beko2210.github.io/european-alternatives.eu-free-open-source/) | 유료 소프트웨어를 대신할 오픈소스 도구 600여 개를 모은 디렉터리 | — | MIT | ✅ 실행 | [공식](https://beko2210.github.io/european-alternatives.eu-free-open-source/) · [GitHub](https://github.com/BEKO2210/european-alternatives.eu-free-open-source) | [European Alternatives 사용법: 오픈소스 대체 앱 사전, 설치부터 빌드까지](https://review.kimwon.com/european-alternatives-%ec%82%ac%ec%9a%a9%eb%b2%95/) |
| [Gemini 3.8 Flash TTS](https://ai.google.dev/gemini-api/docs/speech-generation) | 프롬프트로 목소리를 설계하고 연기를 지시하는 구글 TTS 모델 | 설치 없음 — Gemini API로 호출 | 해당 없음(Google API) | 📄 문서 확인 | [공식](https://ai.google.dev/gemini-api/docs/speech-generation) | [Gemini 3.8 Flash TTS, 무엇이고 누구에게 맞나](https://review.kimwon.com/gemini-38-flash-tts-%ec%9d%8c%ec%84%b1%ed%95%a9%ec%84%b1/) |
| [Globestudio](https://globestudio.app) | 점 지도와 3D 지구본을 만들어 이미지·영상으로 내보내는 오픈소스 웹 도구 | `git clone https://github.com/alevizio/globestudio && cd globestudio && npm install` | MIT | ✅ 실행 | [공식](https://globestudio.app) · [GitHub](https://github.com/alevizio/globestudio) | [Globestudio 사용법, 점 지도와 3D 지구본을 무료로](https://review.kimwon.com/globestudio-%ec%82%ac%ec%9a%a9%eb%b2%95/) |
| [Google Home MCP](https://developers.home.google.com/mcp/home) | AI 에이전트가 Google Home 기기를 읽고 제어하게 하는 공식 MCP 서버 | 설치 없음 — 원격 MCP 서버(Home Premium Advanced 구독) | 해당 없음(Google 서비스) | 📄 문서 확인 | [공식](https://developers.home.google.com/mcp/home) | [Google Home MCP, 무엇이고 누구에게 맞나](https://review.kimwon.com/google-home-mcp-%ec%8a%a4%eb%a7%88%ed%8a%b8%ed%99%88-ai/) |
| [HN Watch](https://github.com/sourabhbgp/hn-watch) | Claude 에이전트로 해커뉴스를 감시해 관심 글을 골라 주는 macOS 앱 | `git clone https://github.com/sourabhbgp/hn-watch && cd hn-watch && npm install` | MIT | 📄 문서 확인 | [GitHub](https://github.com/sourabhbgp/hn-watch) | [HN Watch, 해커뉴스를 대신 지켜보는 맥 앱](https://review.kimwon.com/hn-watch-%ed%95%b4%ec%bb%a4%eb%89%b4%ec%8a%a4-%ec%95%8c%eb%a6%bc/) |
| [Ledge](https://ledge.sh/) | 마크다운 노트 속 코드 블록을 그 자리에서 실행하는 노트 앱 | 공식 사이트 설치 파일(macOS·Linux·Windows·모바일) | Apache-2.0 | 📄 문서 확인 | [공식](https://ledge.sh/) · [GitHub](https://github.com/ledgesh/ledge) | [Ledge, 실행되는 마크다운 노트는 누구에게 맞나](https://review.kimwon.com/ledge-%eb%a7%88%ed%81%ac%eb%8b%a4%ec%9a%b4-%eb%85%b8%ed%8a%b8-%ec%bd%94%eb%93%9c%ec%8b%a4%ed%96%89/) |
| [llmspeed](https://llmspeed.dev) | 하드웨어 구매 전 로컬 LLM 답변 속도를 체험하는 웹 시뮬레이터 | `npm install` | MIT | ✅ 실행 | [공식](https://llmspeed.dev) · [GitHub](https://github.com/albinstman/llmspeed) | [llmspeed 사용법: GPU 사기 전 로컬 LLM 속도 체험, 설치부터 빌드까지](https://review.kimwon.com/llmspeed-%ec%82%ac%ec%9a%a9%eb%b2%95/) |
| [Lofi Cities](https://loficities.com) | 픽셀아트 도시 야경과 실시간 합성 로파이 음악을 트는 무료 웹 앱 | 설치 없음 — 브라우저에서 바로 | 해당 없음(웹 서비스) | ✅ 실행 | [공식](https://loficities.com) | [Lofi Cities 사용법, 설치 없이 켜는 작업용 로파이](https://review.kimwon.com/lofi-cities-%ec%82%ac%ec%9a%a9%eb%b2%95/) |
| [MCPJam](https://www.mcpjam.com/) | MCP 서버·앱을 채팅하며 검사·디버깅하는 테스트 도구 | `npm i -g @mcpjam/cli` | Apache-2.0(일부 별도) | ✅ 실행 | [공식](https://www.mcpjam.com/) · [GitHub](https://github.com/MCPJam/inspector) | [MCPJam 사용법: 설치부터 첫 명령까지](https://review.kimwon.com/mcpjam-%ec%82%ac%ec%9a%a9%eb%b2%95/) |
| [Nanolathe](https://nanolathe.gg/) | Total Annihilation 원본 데이터를 읽어 실행하는 Go 기반 오픈소스 RTS 엔진 | — | MIT | 📄 문서 확인 | [공식](https://nanolathe.gg/) · [GitHub](https://github.com/nanolathe-gg/nanolathe) | [Nanolathe 살펴보기: 토탈 어나이얼레이션을 되살린 오픈소스 RTS 엔진](https://review.kimwon.com/nanolathe-%ed%86%a0%ed%83%88%ec%96%b4%eb%82%98%ec%9d%b4%ec%96%bc%eb%a0%88%ec%9d%b4%ec%85%98-%ec%97%94%ec%a7%84/) |
| [NVIDIA Personal AI Router](https://github.com/NVIDIA/Personal-AI-Router) | 집 안 여러 컴퓨터에 로컬 AI 추론 요청을 나눠 보내는 라우터 | 릴리스 페이지 설치 파일(exe·deb·dmg) | Apache-2.0 | 📄 문서 확인 | [GitHub](https://github.com/NVIDIA/Personal-AI-Router) | [PC 여러 대로 AI 돌리는 NVIDIA PAIR](https://review.kimwon.com/personal-ai-router-%eb%a1%9c%ec%bb%ac-ai-%eb%9d%bc%ec%9a%b0%ed%84%b0/) |
| [omnibin](https://github.com/kitamura-felipe/omnibin) | 의료 AI 모델 평가 결과를 신뢰구간 포함 PDF 리포트로 만드는 파이썬 패키지 | `pip install omnibin` | MIT | ◐ 일부 실행 | [GitHub](https://github.com/kitamura-felipe/omnibin) | [omnibin, 의료 AI 평가 리포트를 자동으로](https://review.kimwon.com/omnibin-%eb%aa%a8%eb%8d%b8-%ed%8f%89%ea%b0%80-%eb%a6%ac%ed%8f%ac%ed%8a%b8/) |
| [Pass Designer](https://developer.apple.com/pass-designer) | Apple Wallet 패스 템플릿을 보면서 편집하는 Apple의 Mac 앱 | Apple Developer 사이트에서 내려받기(macOS 27+) | 해당 없음(Apple 무료 앱) | 📄 문서 확인 | [공식](https://developer.apple.com/pass-designer) | [Apple Pass Designer, 무엇이고 누구에게 맞나](https://review.kimwon.com/pass-designer-%ec%95%a0%ed%94%8c%ec%9b%94%eb%a0%9b%ed%8c%a8%ec%8a%a4/) |
| [Pirate Face](https://pirateface.co) | 공개 AI 모델을 검증된 토렌트로 보존·배포하는 웹 서비스 | 설치 없음 — 브라우저에서 바로 | 해당 없음(웹 서비스) | ✅ 실행 | [공식](https://pirateface.co) | [Pirate Face 사용법, AI 모델을 토렌트로 보존](https://review.kimwon.com/pirateface-%ec%82%ac%ec%9a%a9%eb%b2%95/) |
| [PS2 Web Recomp](https://github.com/snuri00/ps2-web-recomp) | PS2 게임을 WebAssembly로 정적 리컴파일해 브라우저에서 실행하는 도구 | `git clone https://github.com/snuri00/ps2-web-recomp` | MIT | 📄 문서 확인 | [GitHub](https://github.com/snuri00/ps2-web-recomp) | [PS2 Web Recomp: 에뮬레이터 없이 브라우저에서 PS2 게임 돌리기](https://review.kimwon.com/ps2-web-recomp-%eb%b8%8c%eb%9d%bc%ec%9a%b0%ec%a0%80-%ea%b2%8c%ec%9e%84/) |
| [Quake-SRP](https://github.com/terrapapagalli1516/quake-srp) | 1996년작 Quake를 safe Rust로 포팅해 브라우저에서 돌리는 엔진 | 설치 없음 — 브라우저 플레이 페이지(quake-srp.pages.dev), 소스는 git clone | GPL-2.0 | ✅ 실행 | [GitHub](https://github.com/terrapapagalli1516/quake-srp) | [Quake-SRP 사용법: 브라우저에서 도는 러스트판 퀘이크, 설치부터 소스 검증까지](https://review.kimwon.com/quake-srp-%ec%82%ac%ec%9a%a9%eb%b2%95/) |
| [skills](https://skills.sh) | GitHub 저장소의 에이전트 스킬을 코딩 에이전트에 설치·관리하는 CLI | `npx skills add <owner/repo>` | MIT | ✅ 실행 | [공식](https://skills.sh) · [GitHub](https://github.com/vercel-labs/skills) | [skills 사용법: 설치부터 첫 스킬 적용까지](https://review.kimwon.com/skills-cli-%ec%82%ac%ec%9a%a9%eb%b2%95/) |
| [SymvaCAS](https://kirinonakar.github.io/symvacas/) | SymPy 기반 CAS·그래프·통계·파이썬을 합친 오픈소스 계산기 앱 | `.venv/bin/python -m pip install -q sympy==1.14.0` | MIT | ◐ 일부 실행 | [공식](https://kirinonakar.github.io/symvacas/) · [GitHub](https://github.com/kirinonakar/symvacas) | [SymvaCAS 살펴보기: SymPy로 도는 무료 계산기](https://review.kimwon.com/symvacas-%ea%b3%b5%ed%95%99%ec%9a%a9-%ea%b3%84%ec%82%b0%ea%b8%b0/) |
| [Tcl/Tk](https://www.tcl-lang.org/) | 스크립트 언어 Tcl과 GUI 툴킷 Tk를 묶은 조합 | `brew install tcl-tk` | TCL | 📄 문서 확인 | [공식](https://www.tcl-lang.org/) | [Tcl/Tk 9.1, 무엇이 달라졌고 누구에게 맞나](https://review.kimwon.com/tcltk-91-%ec%83%88%ea%b8%b0%eb%8a%a5/) |
| [trynix](https://trynix.dev) | 브라우저 탭에서 nixpkgs 패키지를 설치 없이 바로 실행하는 웹 도구 | 설치 없음 — 브라우저에서 바로 | MIT | ✅ 실행 | [공식](https://trynix.dev) · [GitHub](https://github.com/fzakaria/trynix) | [trynix 사용법, 브라우저 탭에서 패키지 바로 실행](https://review.kimwon.com/trynix-%ec%82%ac%ec%9a%a9%eb%b2%95/) |
| [unslop](https://github.com/theclaymethod/unslop) | AI 글투를 줄 단위로 찾아내는 파이썬 글쓰기 검사 도구 | `git clone https://github.com/theclaymethod/unslop` | MIT(README 표기) | ✅ 실행 | [GitHub](https://github.com/theclaymethod/unslop) | [unslop 사용법: 설치부터 첫 검사까지](https://review.kimwon.com/unslop-%ec%82%ac%ec%9a%a9%eb%b2%95/) |

## CLI·터미널

- **agent-gc** — AI 코딩 에이전트가 남긴 worktree와 빌드 산출물을 정리하는 Rust TUI (Rust · ★ 3 · [GitHub](https://github.com/williamjeong2/agent-gc))  
  `npm install -g agent-gc`  
  심화 글: [agent-gc 사용법, AI 에이전트가 남긴 용량 되찾기](https://review.kimwon.com/agent-gc-%ec%82%ac%ec%9a%a9%eb%b2%95/) · 2026-10-07
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
- **PS2 Web Recomp** — PS2 게임을 WebAssembly로 정적 리컴파일해 브라우저에서 실행하는 도구 (C++ · ★ 429 · [GitHub](https://github.com/snuri00/ps2-web-recomp))  
  `git clone https://github.com/snuri00/ps2-web-recomp`  
  심화 글: [PS2 Web Recomp: 에뮬레이터 없이 브라우저에서 PS2 게임 돌리기](https://review.kimwon.com/ps2-web-recomp-%eb%b8%8c%eb%9d%bc%ec%9a%b0%ec%a0%80-%ea%b2%8c%ec%9e%84/) · 2026-10-13
- **Tcl/Tk** — 스크립트 언어 Tcl과 GUI 툴킷 Tk를 묶은 조합  
  `brew install tcl-tk`  
  심화 글: [Tcl/Tk 9.1, 무엇이 달라졌고 누구에게 맞나](https://review.kimwon.com/tcltk-91-%ec%83%88%ea%b8%b0%eb%8a%a5/) · 2026-09-30
- **trynix** — 브라우저 탭에서 nixpkgs 패키지를 설치 없이 바로 실행하는 웹 도구 (JavaScript · ★ 159 · [GitHub](https://github.com/fzakaria/trynix))  
  설치 없음 — 브라우저에서 바로  
  심화 글: [trynix 사용법, 브라우저 탭에서 패키지 바로 실행](https://review.kimwon.com/trynix-%ec%82%ac%ec%9a%a9%eb%b2%95/) · 2026-09-13

## AI·LLM

- **Blumify for Claude** — 유튜브·팟캐스트 링크를 스크립트와 요약으로 바꿔 주는 Claude 플러그인 (★ 0 · [GitHub](https://github.com/Sketchjar/blumify-claude-plugin))  
  `/plugin install blumify@blumify`  
  심화 글: [Blumify 사용법: Claude용 유튜브·팟캐스트 요약 플러그인, 설치부터 질문까지](https://review.kimwon.com/blumify-%ec%82%ac%ec%9a%a9%eb%b2%95/) · 2026-10-15
- **Gemini 3.8 Flash TTS** — 프롬프트로 목소리를 설계하고 연기를 지시하는 구글 TTS 모델  
  설치 없음 — Gemini API로 호출  
  심화 글: [Gemini 3.8 Flash TTS, 무엇이고 누구에게 맞나](https://review.kimwon.com/gemini-38-flash-tts-%ec%9d%8c%ec%84%b1%ed%95%a9%ec%84%b1/) · 2026-09-24
- **Google Home MCP** — AI 에이전트가 Google Home 기기를 읽고 제어하게 하는 공식 MCP 서버  
  설치 없음 — 원격 MCP 서버(Home Premium Advanced 구독)  
  심화 글: [Google Home MCP, 무엇이고 누구에게 맞나](https://review.kimwon.com/google-home-mcp-%ec%8a%a4%eb%a7%88%ed%8a%b8%ed%99%88-ai/) · 2026-09-17
- **HN Watch** — Claude 에이전트로 해커뉴스를 감시해 관심 글을 골라 주는 macOS 앱 (Rust · ★ 1 · [GitHub](https://github.com/sourabhbgp/hn-watch))  
  `git clone https://github.com/sourabhbgp/hn-watch && cd hn-watch && npm install`  
  심화 글: [HN Watch, 해커뉴스를 대신 지켜보는 맥 앱](https://review.kimwon.com/hn-watch-%ed%95%b4%ec%bb%a4%eb%89%b4%ec%8a%a4-%ec%95%8c%eb%a6%bc/) · 2026-09-29
- **llmspeed** — 하드웨어 구매 전 로컬 LLM 답변 속도를 체험하는 웹 시뮬레이터 (TypeScript · ★ 107 · [GitHub](https://github.com/albinstman/llmspeed))  
  `npm install`  
  심화 글: [llmspeed 사용법: GPU 사기 전 로컬 LLM 속도 체험, 설치부터 빌드까지](https://review.kimwon.com/llmspeed-%ec%82%ac%ec%9a%a9%eb%b2%95/) · 2026-10-18
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

- **A Walkable History of Art** — 미술사 연표에서 화가를 골라 3D 가상 갤러리로 들어가는 웹사이트  
  설치 없음 — 브라우저에서 바로  
  심화 글: [A Walkable History of Art: 3D 미술사 갤러리, 누구에게 맞나](https://review.kimwon.com/a-walkable-history-of-art-%eb%af%b8%ec%88%a0%ec%82%ac/) · 2026-10-09
- **Bastardica** — 브라우저에서 글꼴 두 개를 섞어 새 폰트 파일을 만드는 웹 도구  
  설치 없음 — 브라우저에서 바로  
  심화 글: [Bastardica 사용법, 글꼴 두 개를 섞어 새 폰트로](https://review.kimwon.com/bastardica-%ec%82%ac%ec%9a%a9%eb%b2%95/) · 2026-09-25
- **Book of Shapes** — 값을 조절해 SVG로 내려받는 생성형 패턴 모음 웹 사이트  
  설치 없음 — 브라우저에서 바로  
  심화 글: [Book of Shapes, 무엇이고 누구에게 맞나](https://review.kimwon.com/bookofshapes-svg-%ed%8c%a8%ed%84%b4/) · 2026-10-02
- **Carrier-Explode** — 아이폰·픽셀·갤럭시 펌웨어의 통신사 설정을 해독해 비교하는 사이트 (TypeScript · ★ 70 · [GitHub](https://github.com/AlecDusheck/carrier-explode))  
  설치 없음 — 웹사이트에서 조회(공개 API 제공)  
  심화 글: [Carrier-Explode 사용법: 아이폰·갤럭시 통신사 설정 비교 사이트, 조회부터 API까지](https://review.kimwon.com/carrier-explode-%ec%82%ac%ec%9a%a9%eb%b2%95/) · 2026-10-10
- **FOSS Alternatives** — 유료 소프트웨어를 대신할 오픈소스 도구 600여 개를 모은 디렉터리 (TypeScript · ★ 61 · [GitHub](https://github.com/BEKO2210/european-alternatives.eu-free-open-source))  
  심화 글: [European Alternatives 사용법: 오픈소스 대체 앱 사전, 설치부터 빌드까지](https://review.kimwon.com/european-alternatives-%ec%82%ac%ec%9a%a9%eb%b2%95/) · 2026-10-15
- **Globestudio** — 점 지도와 3D 지구본을 만들어 이미지·영상으로 내보내는 오픈소스 웹 도구 (JavaScript · ★ 12 · [GitHub](https://github.com/alevizio/globestudio))  
  `git clone https://github.com/alevizio/globestudio && cd globestudio && npm install`  
  심화 글: [Globestudio 사용법, 점 지도와 3D 지구본을 무료로](https://review.kimwon.com/globestudio-%ec%82%ac%ec%9a%a9%eb%b2%95/) · 2026-10-04
- **Lofi Cities** — 픽셀아트 도시 야경과 실시간 합성 로파이 음악을 트는 무료 웹 앱  
  설치 없음 — 브라우저에서 바로  
  심화 글: [Lofi Cities 사용법, 설치 없이 켜는 작업용 로파이](https://review.kimwon.com/lofi-cities-%ec%82%ac%ec%9a%a9%eb%b2%95/) · 2026-09-28
- **Quake-SRP** — 1996년작 Quake를 safe Rust로 포팅해 브라우저에서 돌리는 엔진 (Rust · ★ 69 · [GitHub](https://github.com/terrapapagalli1516/quake-srp))  
  설치 없음 — 브라우저 플레이 페이지(quake-srp.pages.dev), 소스는 git clone  
  심화 글: [Quake-SRP 사용법: 브라우저에서 도는 러스트판 퀘이크, 설치부터 소스 검증까지](https://review.kimwon.com/quake-srp-%ec%82%ac%ec%9a%a9%eb%b2%95/) · 2026-10-10

## 인프라·자동화

- **Cloudflare Python Workers** — Cloudflare 엣지에서 Python 코드를 실행하는 서버리스 런타임 (Python · ★ 334 · [GitHub](https://github.com/cloudflare/python-workers-examples))  
  `uv tool install workers-py`  
  심화 글: [Cloudflare Python Workers가 달라진 점](https://review.kimwon.com/cloudflare-python-workers-%ec%86%8c%ea%b0%9c/) · 2026-09-23
- **Cloudflare Quick Tunnels** — 계정 없이 로컬 서버에 공개 HTTPS 주소를 붙이는 cloudflared 기능 (Go · ★ 16,035 · [GitHub](https://github.com/cloudflare/cloudflared))  
  `brew install cloudflared`  
  심화 글: [Quick Tunnels 사용법, 로컬을 공개 URL로](https://review.kimwon.com/cloudflare-quick-tunnels-%ec%82%ac%ec%9a%a9%eb%b2%95/) · 2026-09-19

## 기타

- **Nanolathe** — Total Annihilation 원본 데이터를 읽어 실행하는 Go 기반 오픈소스 RTS 엔진 (Go · ★ 222 · [GitHub](https://github.com/nanolathe-gg/nanolathe))  
  심화 글: [Nanolathe 살펴보기: 토탈 어나이얼레이션을 되살린 오픈소스 RTS 엔진](https://review.kimwon.com/nanolathe-%ed%86%a0%ed%83%88%ec%96%b4%eb%82%98%ec%9d%b4%ec%96%bc%eb%a0%88%ec%9d%b4%ec%85%98-%ec%97%94%ec%a7%84/) · 2026-10-14
- **SymvaCAS** — SymPy 기반 CAS·그래프·통계·파이썬을 합친 오픈소스 계산기 앱 (Python · ★ 1 · [GitHub](https://github.com/kirinonakar/symvacas))  
  `.venv/bin/python -m pip install -q sympy==1.14.0`  
  심화 글: [SymvaCAS 살펴보기: SymPy로 도는 무료 계산기](https://review.kimwon.com/symvacas-%ea%b3%b5%ed%95%99%ec%9a%a9-%ea%b3%84%ec%82%b0%ea%b8%b0/) · 2026-10-08

## 출처·원칙

- 설치 명령은 공식 README 기준이며 실행 시점의 버전에 따라 달라질 수 있습니다.
- 라이선스·별 수는 GitHub API 값입니다. 오류·누락은 이슈로 알려주세요.
- 표의 문장과 데이터는 CC BY 4.0, 각 도구의 이름·로고·코드는 해당 프로젝트의 라이선스를 따릅니다.
- 블로그: [리뷰노트](https://review.kimwon.com) · 링크허브: [links.kimwon.com](https://links.kimwon.com/review/)
