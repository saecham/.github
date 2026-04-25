# 새참 (saecham)

> 농가의 협력과 휴식 — 농가가 함께 나누는 새참(snack/break)에서 따왔습니다.
> 농업인 · 컨설턴트 · 농업 사업자가 함께 쓰는 도구를 만듭니다.

## 🌾 제품

| 제품 | 레포 | 도메인 | 설명 |
|------|------|--------|------|
| **도담팜 (DodamFarm)** | [`dodam-farm`](https://github.com/saecham/dodam-farm) | [`dodam.farm`](https://dodam.farm) | 멀티페르소나 농업 경영 관리 플랫폼 (농가/컨설턴트/관리자/플랫폼) — 영농일지·출하·정산·장부·수익분석·OCR 통합 |
| **pheno-work** | [`pheno-work`](https://github.com/saecham/pheno-work) | TBD | 작물 표현형 (phenotype) R&D 도구 |

## 🛠 기술 스택

- **Backend**: FastAPI · SQLAlchemy · Python 3.12+ · PostgreSQL
- **Frontend**: Next.js 16 (App Router · Turbopack) · React · TypeScript · shadcn/ui · Tailwind CSS
- **Auth**: PIN + OAuth 2.0 (Google · Kakao · Naver) + 페르소나별 서브도메인 라우팅
- **Infra**: 멀티테넌트 · OAuthIdentity 매핑 · 승인 플로우

## 🤝 협력 모델

새참(saecham) 의 모든 제품은 **농업인-컨설턴트 협력**을 핵심 가치로 둡니다.
- 농가는 영농일지·출하·장부를 직관적으로 관리
- 컨설턴트는 담당 농가의 데이터를 분석해 보고서·권고 발행
- 관리자는 사용자·권한·결제를 운영
- 플랫폼 운영팀은 전사 통계·보안을 모니터링

## 🚀 시작

각 제품 레포의 README 를 참고하세요. `dodam-farm` 이 첫 제품이며, 다른 농업 도구도 같은 백엔드 인프라(인증·다중 테넌트·결제) 위에 점진적으로 추가됩니다.

---

> 🇰🇷 Made in Korea · 농업인의 데이터로 농업인의 가치를 만듭니다.
