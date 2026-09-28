# awesome-devtools-ko — 직접 설치해 써본 개발·AI 도구 표

직접 설치·실행해 본 오픈소스 개발 도구·AI 도구를 한국어 한 줄 설명, 설치 명령, 라이선스, 심화 글과 함께 정리한 표. data/tools.json 제공.

직접 설치해 실행한 기록(Debian 12 LXC 샌드박스)을 바탕으로 만든 표입니다. 각 행의 **심화 글**에 설치 과정·첫 화면·실제 출력이 있습니다. 기계 판독용 데이터는 [`data/tools.json`](data/tools.json).

갱신 2026-09-28 · 도구 15개 · 라이선스 [CC BY 4.0](LICENSE)

## 전체 표

| 도구 | 무엇 | 설치 한 줄 | 라이선스 | 심화 글 |
|---|---|---|---|---|
| [Bastardica](https://bastardica.mitpit.com/) | 브라우저에서 글꼴 두 개를 섞어 새 폰트 파일을 만드는 웹 도구 | — | — | [Bastardica 사용법, 글꼴 두 개를 섞어 새 폰트로](https://review.kimwon.com/bastardica-%ec%82%ac%ec%9a%a9%eb%b2%95/) |
| [bzip3](https://github.com/iczelia/bzip3) | bzip2를 잇는 블록 정렬 기반 고압축률 명령줄 압축기 | `brew install bzip3` | LGPL-3.0 | [bzip3, 무엇이고 누구에게 맞나](https://review.kimwon.com/bzip3-what-it-is-and-who-its-for/) |
| [Cloudflare Python Workers](https://github.com/cloudflare/python-workers-examples) | Cloudflare 엣지에서 Python 코드를 실행하는 서버리스 런타임 | `uv tool install workers-py` | Apache-2.0 | [Cloudflare Python Workers가 달라진 점](https://review.kimwon.com/cloudflare-python-workers-%ec%86%8c%ea%b0%9c/) |
| [Cloudflare Quick Tunnels](https://github.com/randyburden/cbda4da88bc4e6cd9e17d59ecf03dcf9) | 계정도 포트 개방도 없이, 명령 한 줄로 내 컴퓨터의 개발 서버에 공개 HTTPS 주소를 붙이는 방법. | — | — | [Quick Tunnels 사용법, 로컬을 공개 URL로](https://review.kimwon.com/cloudflare-quick-tunnels-%ec%82%ac%ec%9a%a9%eb%b2%95/) |
| dbt Charts | YAML 한 파일로 대시보드를 만드는 dbt Charts를 설치하고 첫 보드 파일까지 만들어 봤습니다. | — | — | [dbt Charts 사용법: 설치부터 첫 보드까지](https://review.kimwon.com/dbt-charts-%ec%82%ac%ec%9a%a9%eb%b2%95/) |
| [fnprint](https://github.com/1rhino2/fnprint) | 심볼 없는 x86-64 ELF 함수를 동작 기반으로 식별하는 도구 | `git clone https://github.com/1rhino2/fnprint && cd fnprint && cargo build --release` | MIT | [fnprint, 동작으로 함수를 찾아내는 도구](https://review.kimwon.com/fnprint-%eb%b0%94%ec%9d%b4%eb%84%88%eb%a6%ac-%eb%b6%84%ec%84%9d/) |
| [Gemini 3.8 Flash TTS](https://ai.google.dev/gemini-api/docs/speech-generation) | 프롬프트로 목소리를 설계하고 연기를 지시하는 구글 TTS 모델 | — | — | [Gemini 3.8 Flash TTS, 무엇이고 누구에게 맞나](https://review.kimwon.com/gemini-38-flash-tts-%ec%9d%8c%ec%84%b1%ed%95%a9%ec%84%b1/) |
| Google Home MCP | AI 에이전트가 집 안 기기를 읽고 제어하는 Google Home MCP, 준비물과 한계를 정리했습니다. | — | — | [Google Home MCP, 무엇이고 누구에게 맞나](https://review.kimwon.com/google-home-mcp-%ec%8a%a4%eb%a7%88%ed%8a%b8%ed%99%88-ai/) |
| MCPJam | MCP 서버를 클라이언트별로 테스트하는 MCPJam을 설치하고 첫 명령까지 실행하는 과정을 화면과 함께 정리 | `sudo npm i -g @mcpjam/cli` | — | [MCPJam 사용법: 설치부터 첫 명령까지](https://review.kimwon.com/mcpjam-%ec%82%ac%ec%9a%a9%eb%b2%95/) |
| NVIDIA Personal AI Router | 같은 네트워크의 컴퓨터를 묶어 로컬 추론 요청을 나눠 보내는 NVIDIA PAIR, 무엇을 해 주고 무엇은  | — | — | [PC 여러 대로 AI 돌리는 NVIDIA PAIR](https://review.kimwon.com/personal-ai-router-%eb%a1%9c%ec%bb%ac-ai-%eb%9d%bc%ec%9a%b0%ed%84%b0/) |
| [omnibin](https://github.com/felipekitamura/omnibin) | 의료 AI 모델 평가 결과를 신뢰구간 포함 PDF 리포트로 만드는 파이썬 패키지 | `pip install omnibin` | MIT | [omnibin, 의료 AI 평가 리포트를 자동으로](https://review.kimwon.com/omnibin-%eb%aa%a8%eb%8d%b8-%ed%8f%89%ea%b0%80-%eb%a6%ac%ed%8f%ac%ed%8a%b8/) |
| [Pirate Face](https://pirateface.co) | 공개 AI 모델을 검증된 토렌트로 보존·배포하는 웹 서비스 | — | — | [Pirate Face 사용법, AI 모델을 토렌트로 보존](https://review.kimwon.com/pirateface-%ec%82%ac%ec%9a%a9%eb%b2%95/) |
| [skills](https://skills.sh) | GitHub 저장소의 에이전트 스킬을 코딩 에이전트에 설치·관리하는 CLI | `npx skills add <owner/repo>` | MIT | [skills 사용법: 설치부터 첫 스킬 적용까지](https://review.kimwon.com/skills-cli-%ec%82%ac%ec%9a%a9%eb%b2%95/) |
| [trynix](https://github.com/marketplace/actions) | 브라우저 탭에서 nixpkgs 패키지를 설치 없이 바로 실행하는 웹 도구 | — | MIT | [trynix 사용법, 브라우저 탭에서 패키지 바로 실행](https://review.kimwon.com/trynix-%ec%82%ac%ec%9a%a9%eb%b2%95/) |
| [unslop](https://github.com/theclaymethod/unslop) | AI 글투를 줄 단위로 찾아내는 파이썬 글쓰기 검사 도구 | `git clone https://github.com/theclaymethod/unslop` | — | [unslop 사용법: 설치부터 첫 검사까지](https://review.kimwon.com/unslop-%ec%82%ac%ec%9a%a9%eb%b2%95/) |

## CLI·터미널

- **bzip3** — bzip2를 잇는 블록 정렬 기반 고압축률 명령줄 압축기 (C · ★ 1,495 · [GitHub](https://github.com/iczelia/bzip3))  
  `brew install bzip3`  
  심화 글: [bzip3, 무엇이고 누구에게 맞나](https://review.kimwon.com/bzip3-what-it-is-and-who-its-for/) · 2026-09-09

## 개발 도구

- **fnprint** — 심볼 없는 x86-64 ELF 함수를 동작 기반으로 식별하는 도구 (Rust · ★ 44 · [GitHub](https://github.com/1rhino2/fnprint))  
  `git clone https://github.com/1rhino2/fnprint && cd fnprint && cargo build --release`  
  심화 글: [fnprint, 동작으로 함수를 찾아내는 도구](https://review.kimwon.com/fnprint-%eb%b0%94%ec%9d%b4%eb%84%88%eb%a6%ac-%eb%b6%84%ec%84%9d/) · 2026-09-09
- **trynix** — 브라우저 탭에서 nixpkgs 패키지를 설치 없이 바로 실행하는 웹 도구 ([GitHub](https://github.com/marketplace/actions))  
  심화 글: [trynix 사용법, 브라우저 탭에서 패키지 바로 실행](https://review.kimwon.com/trynix-%ec%82%ac%ec%9a%a9%eb%b2%95/) · 2026-09-13

## AI·LLM

- **Gemini 3.8 Flash TTS** — 프롬프트로 목소리를 설계하고 연기를 지시하는 구글 TTS 모델  
  심화 글: [Gemini 3.8 Flash TTS, 무엇이고 누구에게 맞나](https://review.kimwon.com/gemini-38-flash-tts-%ec%9d%8c%ec%84%b1%ed%95%a9%ec%84%b1/) · 2026-09-24
- **omnibin** — 의료 AI 모델 평가 결과를 신뢰구간 포함 PDF 리포트로 만드는 파이썬 패키지 ([GitHub](https://github.com/felipekitamura/omnibin))  
  `pip install omnibin`  
  심화 글: [omnibin, 의료 AI 평가 리포트를 자동으로](https://review.kimwon.com/omnibin-%eb%aa%a8%eb%8d%b8-%ed%8f%89%ea%b0%80-%eb%a6%ac%ed%8f%ac%ed%8a%b8/) · 2026-09-27
- **Pirate Face** — 공개 AI 모델을 검증된 토렌트로 보존·배포하는 웹 서비스  
  심화 글: [Pirate Face 사용법, AI 모델을 토렌트로 보존](https://review.kimwon.com/pirateface-%ec%82%ac%ec%9a%a9%eb%b2%95/) · 2026-09-21
- **skills** — GitHub 저장소의 에이전트 스킬을 코딩 에이전트에 설치·관리하는 CLI  
  `npx skills add <owner/repo>`  
  심화 글: [skills 사용법: 설치부터 첫 스킬 적용까지](https://review.kimwon.com/skills-cli-%ec%82%ac%ec%9a%a9%eb%b2%95/) · 2026-09-11
- **unslop** — AI 글투를 줄 단위로 찾아내는 파이썬 글쓰기 검사 도구 (Python · ★ 411 · [GitHub](https://github.com/theclaymethod/unslop))  
  `git clone https://github.com/theclaymethod/unslop`  
  심화 글: [unslop 사용법: 설치부터 첫 검사까지](https://review.kimwon.com/unslop-%ec%82%ac%ec%9a%a9%eb%b2%95/) · 2026-09-12

## 웹·앱

- **Bastardica** — 브라우저에서 글꼴 두 개를 섞어 새 폰트 파일을 만드는 웹 도구  
  심화 글: [Bastardica 사용법, 글꼴 두 개를 섞어 새 폰트로](https://review.kimwon.com/bastardica-%ec%82%ac%ec%9a%a9%eb%b2%95/) · 2026-09-25

## 인프라·자동화

- **Cloudflare Python Workers** — Cloudflare 엣지에서 Python 코드를 실행하는 서버리스 런타임 (Python · ★ 334 · [GitHub](https://github.com/cloudflare/python-workers-examples))  
  `uv tool install workers-py`  
  심화 글: [Cloudflare Python Workers가 달라진 점](https://review.kimwon.com/cloudflare-python-workers-%ec%86%8c%ea%b0%9c/) · 2026-09-23

## 기타

- **Cloudflare Quick Tunnels** — 계정도 포트 개방도 없이, 명령 한 줄로 내 컴퓨터의 개발 서버에 공개 HTTPS 주소를 붙이는 방법. ([GitHub](https://github.com/randyburden/cbda4da88bc4e6cd9e17d59ecf03dcf9))  
  심화 글: [Quick Tunnels 사용법, 로컬을 공개 URL로](https://review.kimwon.com/cloudflare-quick-tunnels-%ec%82%ac%ec%9a%a9%eb%b2%95/) · 2026-09-19
- **dbt Charts** — YAML 한 파일로 대시보드를 만드는 dbt Charts를 설치하고 첫 보드 파일까지 만들어 봤습니다.  
  심화 글: [dbt Charts 사용법: 설치부터 첫 보드까지](https://review.kimwon.com/dbt-charts-%ec%82%ac%ec%9a%a9%eb%b2%95/) · 2026-09-16
- **Google Home MCP** — AI 에이전트가 집 안 기기를 읽고 제어하는 Google Home MCP, 준비물과 한계를 정리했습니다.  
  심화 글: [Google Home MCP, 무엇이고 누구에게 맞나](https://review.kimwon.com/google-home-mcp-%ec%8a%a4%eb%a7%88%ed%8a%b8%ed%99%88-ai/) · 2026-09-17
- **MCPJam** — MCP 서버를 클라이언트별로 테스트하는 MCPJam을 설치하고 첫 명령까지 실행하는 과정을 화면과 함께 정리  
  `sudo npm i -g @mcpjam/cli`  
  심화 글: [MCPJam 사용법: 설치부터 첫 명령까지](https://review.kimwon.com/mcpjam-%ec%82%ac%ec%9a%a9%eb%b2%95/) · 2026-09-18
- **NVIDIA Personal AI Router** — 같은 네트워크의 컴퓨터를 묶어 로컬 추론 요청을 나눠 보내는 NVIDIA PAIR, 무엇을 해 주고 무엇은   
  심화 글: [PC 여러 대로 AI 돌리는 NVIDIA PAIR](https://review.kimwon.com/personal-ai-router-%eb%a1%9c%ec%bb%ac-ai-%eb%9d%bc%ec%9a%b0%ed%84%b0/) · 2026-09-14

## 출처·원칙

- 설치 명령은 공식 README 기준이며 실행 시점의 버전에 따라 달라질 수 있습니다.
- 라이선스·별 수는 GitHub API 값입니다. 오류·누락은 이슈로 알려주세요.
- 표의 문장과 데이터는 CC BY 4.0, 각 도구의 이름·로고·코드는 해당 프로젝트의 라이선스를 따릅니다.
- 블로그: [리뷰노트](https://review.kimwon.com) · 링크허브: [links.kimwon.com](https://links.kimwon.com/review/)
