# 김승민 | 경험을 설계하고 코드로 구현합니다.
[![Email](https://img.shields.io/badge/me@kimseungmin.dev-007EC6?style=flat-square)](mailto:me@kimseungmin.dev)

서울예술대학교에서 영화와 모션그래픽으로 사용자의 감정선을 설계하는 법을 배웠으며, 이제는 프론트엔드를 통해 그 경험을 현실로 구현합니다. 코드와 디자인의 경계에서 기술적 한계를 창의적으로 돌파하며, 기억에 남는 서비스를 만드는 데 가치를 둡니다.

---

### A. 문제 해결 중심 프로젝트

단순한 기능 구현을 넘어, 복잡한 문제를 해결하고 비즈니스 가치를 창출한 핵심 프로젝트들입니다.

| 프로젝트 | 문제 | 해결 | 결과 |
| :--- | :--- | :--- | :--- |
| **[어디가냥 (팀장)](https://github.com/KingsMinn/Meowhere-Deploy)** | 모바일 환경의 심각한 3D 렌더링 성능 저하 (5MB+) 및 파편화된 UX (3-step 탐색) | Blender를 통한 3D 모델 80% 경량화 및 Three.js 최적화, GNB/BNB 필터 통합 설계 | **렌더링 성능 80% 개선**, **핵심 정보 탐색 1단계로 단축** |
| **[FANDON-K](https://github.com/KingsMinn/Fandom-K)** | 과도한 Scroll 이벤트로 인한 랜딩페이지 애니메이션 성능 저하 (4.45초) | `Framer Motion`의 `useScroll`, `useTransform`을 활용한 60fps 렌더링 최적화 | **애니메이션 처리 속도 9.47배 향상** (0.47초), 부드러운 UX 확보 |
| **[WIKIED (팀장)](https://github.com/KingsMinn/Wikied-Distribution)** | 팀원의 실수로 인한 Git 히스토리 유실 긴급 상황 발생 | `git reset`의 위험성을 인지하고 `git revert`를 통한 안전한 복구 전략 제시 및 실행 | **30분 내 코드 손실 없이 100% 복구**, 팀 Git 가이드라인 제작으로 재발 방지 |

---

### B. 목적 기반 기술 스택

최고의 사용자 경험을 만들기 위해, 목적에 맞는 도구를 전략적으로 선택하고 사용합니다.

| 분류 | 기술 |
| :--- | :--- |
| **확장 가능한 UI 구축** | `JavaScript`, `TypeScript`, `React`, `Next.js` |
| **몰입형 인터랙션 구현** | `Three.js`, `React Three Fiber`, `Framer Motion`, `Matter.js`, `Lottie` |
| **상태 관리 및 스타일링** | `Zustand`, `Context API`, `Tailwind CSS`, `Styled Components` |
| **디자인 및 프로토타이핑** | `Figma`, `Blender`, `AfterEffects`, `Photoshop` |
| **팀워크 및 배포** | `Git`, `Vercel`, `NextAuth.js` |

---

### C. 리더십과 프로세스 개선

좋은 코드는 좋은 협업 문화에서 나온다고 믿습니다. 팀 전체의 생산성과 안정성을 높이기 위해 다음과 같은 노력을 했습니다.

-   **AI 코드리뷰 도입**: `Gemini Code Assist`를 활용하여 단순 피드백 과정을 자동화하고, 팀이 핵심 로직 리뷰에 집중할 수 있는 환경을 조성했습니다.
-   **협업 가이드라인 제작**: Git 히스토리 충돌 해결 경험을 바탕으로, 팀 내 재발 방지를 위한 명확한 Git 가이드라인을 작성하고 배포하여 협업 안정성을 강화했습니다.
-   **디자인 시스템 구축**: Figma 컴포넌트 구조 재설계, Z-Index 가이드 및 모션 가이드 정의를 통해 디자인-개발 워크플로우를 최적화하고 서비스 전체의 UI 일관성을 확보했습니다.
