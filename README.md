# awesome-devtools-ko — 직접 설치해 써본 개발·AI 도구 표

직접 설치·실행해 본 오픈소스 개발 도구·AI 도구를 한국어 한 줄 설명, 설치 명령, 라이선스, 심화 글과 함께 정리한 표. data/tools.json 제공.

직접 설치해 실행한 기록(Debian 12 LXC 샌드박스)을 바탕으로 만든 표입니다. 각 행의 **심화 글**에 설치 과정·첫 화면·실제 출력이 있습니다. 기계 판독용 데이터는 [`data/tools.json`](data/tools.json).

갱신 2026-09-21 · 도구 10개 · 라이선스 [CC BY 4.0](LICENSE)

## 전체 표

| 도구 | 무엇 | 설치 한 줄 | 라이선스 | 심화 글 |
|---|---|---|---|---|
| [bzip3](https://github.com/iczelia/bzip3) | bzip2를 잇는 블록 정렬 기반 고압축률 명령줄 압축기 | `brew install bzip3` | LGPL-3.0 | [bzip3, 무엇이고 누구에게 맞나](https://review.kimwon.com/bzip3-what-it-is-and-who-its-for/) |
| [Cloudflare Quick Tunnels](https://github.com/randyburden/cbda4da88bc4e6cd9e17d59ecf03dcf9) | 계정도 포트 개방도 없이, 명령 한 줄로 내 컴퓨터의 개발 서버에 공개 HTTPS 주소를 붙이는 방법. | — | — | [Quick Tunnels 사용법, 로컬을 공개 URL로](https://review.kimwon.com/cloudflare-quick-tunnels-%ec%82%ac%ec%9a%a9%eb%b2%95/) |
| dbt Charts | YAML 한 파일로 대시보드를 만드는 dbt Charts를 설치하고 첫 보드 파일까지 만들어 봤습니다. | — | — | [dbt Charts 사용법: 설치부터 첫 보드까지](https://review.kimwon.com/dbt-charts-%ec%82%ac%ec%9a%a9%eb%b2%95/) |
| [fnprint](https://github.com/1rhino2/fnprint) | 심볼 없는 x86-64 ELF 함수를 동작 기반으로 식별하는 도구 | `git clone https://github.com/1rhino2/fnprint && cd fnprint && cargo build --release` | MIT | [fnprint, 동작으로 함수를 찾아내는 도구](https://review.kimwon.com/fnprint-%eb%b0%94%ec%9d%b4%eb%84%88%eb%a6%ac-%eb%b6%84%ec%84%9d/) |
| Google Home MCP | AI 에이전트가 집 안 기기를 읽고 제어하는 Google Home MCP, 준비물과 한계를 정리했습니다. | — | — | [Google Home MCP, 무엇이고 누구에게 맞나](https://review.kimwon.com/google-home-mcp-%ec%8a%a4%eb%a7%88%ed%8a%b8%ed%99%88-ai/) |
| MCPJam | MCP 서버를 클라이언트별로 테스트하는 MCPJam을 설치하고 첫 명령까지 실행하는 과정을 화면과 함께 정리 | `sudo npm i -g @mcpjam/cli` | — | [MCPJam 사용법: 설치부터 첫 명령까지](https://review.kimwon.com/mcpjam-%ec%82%ac%ec%9a%a9%eb%b2%95/) |
| NVIDIA Personal AI Router | 같은 네트워크의 컴퓨터를 묶어 로컬 추론 요청을 나눠 보내는 NVIDIA PAIR, 무엇을 해 주고 무엇은  | — | — | [PC 여러 대로 AI 돌리는 NVIDIA PAIR](https://review.kimwon.com/personal-ai-router-%eb%a1%9c%ec%bb%ac-ai-%eb%9d%bc%ec%9a%b0%ed%84%b0/) |
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

- **skills** — GitHub 저장소의 에이전트 스킬을 코딩 에이전트에 설치·관리하는 CLI  
  `npx skills add <owner/repo>`  
  심화 글: [skills 사용법: 설치부터 첫 스킬 적용까지](https://review.kimwon.com/skills-cli-%ec%82%ac%ec%9a%a9%eb%b2%95/) · 2026-09-11
- **unslop** — AI 글투를 줄 단위로 찾아내는 파이썬 글쓰기 검사 도구 (Python · ★ 411 · [GitHub](https://github.com/theclaymethod/unslop))  
  `git clone https://github.com/theclaymethod/unslop`  
  심화 글: [unslop 사용법: 설치부터 첫 검사까지](https://review.kimwon.com/unslop-%ec%82%ac%ec%9a%a9%eb%b2%95/) · 2026-09-12

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
