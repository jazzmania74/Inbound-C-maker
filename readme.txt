================================================================
  AI기반 인바운드 콘텐츠 마케팅 아이디어 생성기
  나눔경영컨설팅
================================================================

[프로젝트 개요]
회사명, 제품/서비스, 고객 페르소나를 입력하면 AI(Claude)가
6개 채널별 콘텐츠 마케팅 전략 및 실행 아이디어를 자동 생성하는 웹앱입니다.
인바운드 마케팅 전략 수립에 필요한 채널별 콘텐츠 기획을
체계적으로 도출할 수 있습니다.

[인바운드 콘텐츠 마케팅 개념]
인바운드 마케팅은 고객이 자발적으로 브랜드를 찾아오게 만드는 전략입니다.
블로그, 웨비나, SEO, AEO, eBook, 유튜브 등 다양한 채널을 통해
유용한 콘텐츠를 제공하여 잠재 고객을 유입하고 전환시킵니다.

[주요 기능]

■ 6개 채널별 콘텐츠 전략 생성:
  - 블로그: Thought Leadership & SEO 유입
  - 웨비나: 리드 생성 & 전문성 강화
  - SEO: 검색 엔진 최적화 전략
  - AEO: AI 엔진 최적화 전략 (ChatGPT/Perplexity 노출)
  - eBook: 리드 마그넷 & 깊은 인사이트
  - 유튜브: 영상 콘텐츠 마케팅

■ 각 채널별 결과 구조:
  - Purpose: 채널의 핵심 목적 및 활용 방식 (1~2문장)
  - Ideas: 3개 실행 아이디어 (제목 + 구체적 실행 방법)
  - 총 18개 아이디어 생성 (6채널 × 3개)

■ 공통 기능:
  - 6개 색상별 채널 카드 (인디고/그린/앰버/핑크/바이올렛/레드)
  - 결과 저장: PDF / HTML 다운로드 / 텍스트 복사
  - 분석 진행 상태 표시 (5단계 프로그레스 바)
  - API 키 로컬 저장 (localStorage)
  - 현재 연도 자동 반영 (최신 트렌드 기반)
  - JSON 파싱 실패 시 복구 로직 (잘린 JSON 보완)
  - XSS 방지 (escapeHtml)
  - 반응형 디자인 (모바일 3단계 breakpoint: 900/768/600px)
  - 인쇄 최적화 (CSS @media print, 색상 보존)

[파일 구성]
- Inbound C-maker.html : 메인 웹앱 (단일 HTML 파일)
- readme.txt             : 프로젝트 설명 (이 파일)
- .gitignore              : Git 추적 제외 설정

[사용 방법]
1. 웹앱을 열고 Anthropic API 키를 입력
2. 회사명 입력 (예: 세이프티아이)
3. 제품/서비스 입력 (예: 스마트 안전관리 SaaS 플랫폼)
4. 고객 Persona 입력 (예: 제조업 안전환경실 대리~과장급, 30~40대)
5. "AI 콘텐츠 아이디어 생성하기" 버튼 클릭
6. AI가 6개 채널별 전략 및 18개 실행 아이디어를 자동 생성
7. 결과를 PDF/HTML/텍스트로 저장 가능

[기술 스택]
- 프론트엔드: HTML5, CSS3, Vanilla JavaScript (단일 파일)
- AI: Anthropic Claude Haiku 4.5 API (브라우저 직접 호출)
- 프롬프트: System Prompt + User Prompt 분리 구조
- 폰트: Pretendard (JSDelivr CDN)
- 백엔드: 없음 (GitHub Pages 배포용)

[개발 환경 및 배포]
- 소스 코드: Google Drive (009.Inbound C-maker/)
- Git 저장소: Google Drive 폴더에서 직접 Git 관리
- GitHub: jazzmania74/Inbound-C-maker (main 브랜치)
- 배포 URL: https://jazzmania74.github.io/Inbound-C-maker/Inbound%20C-maker.html
- 수정 후 배포: git add → git commit → git push origin main → GitHub Pages 자동 반영

[주의사항]
- Anthropic API 키가 필요합니다 (사용자가 직접 입력)
- API 키는 브라우저의 localStorage에만 저장되며 서버로 전송되지 않습니다
- API 호출 비용은 Anthropic 계정에 청구됩니다

================================================================
