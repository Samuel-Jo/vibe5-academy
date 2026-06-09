# 🚀 바이브코딩 5일 캠프 — 교육용 사이트

> 비전공 학생도 **5일** 만에 AI 앱 하나를 **기획 → 배포 → 검증 → 발표**까지 완주하도록 안내하는 교육 사이트.
> 코드는 AI가, 사람은 **의도·검증·방향**에 집중한다.

**🌐 라이브: https://vibe5-academy.pages.dev**

---

## 무엇인가
기존 16일 바이브코딩 로드맵을 **5일로 압축 재설계**한 커리큘럼을, 비전공 학생이 따라올 수 있게 만든 **단일 페이지 교육 사이트**입니다.

## 담긴 내용
- **왜 5일인가 + 바이브코딩 7대 원칙** (비유 중심 설명)
- **4단계 → 5일 타임라인** (Vibe Spec → 바이브 빌드 → 검증 → 완성·공유)
- **DAY별 상세**: 오늘의 목표·체크리스트(진도 저장)·산출물·도구·AI 팁
- **진도율 추적**: 26개 체크리스트, localStorage 자동 저장
- **완성 예시(worked example)**:
  - AI 클릭베이트 판별기 — 규칙 70.6% → AI 하이브리드 100% ([라이브](https://clickbait-meter.pages.dev) · [코드](https://github.com/Samuel-Jo/clickbait-meter))
  - AI 사기 메시지 방패(scam-shield) — 75%→90%→95% ([라이브](https://scam-shield-9uc.pages.dev) · [코드](https://github.com/Samuel-Jo/scam-shield))
- **산출물 6종 안내**: spec·README·build-notes·eval·CHANGELOG·final_report

## 기술
- 단일 `index.html`, 의존성 0(외부 CDN/폰트/라이브러리 없음), 순수 HTML/CSS/JS
- 다크 테마 + 단계별 강조색, 모바일 반응형, 접근성(label·aria) 고려
- 배포: Cloudflare Pages

## 5일 로드맵 요약
| DAY | 단계 | 핵심 |
|---|---|---|
| 1 | Vibe Spec | 의도(spec) 한 장 + 첫 배포 |
| 2 | 바이브 빌드 1 | 작동 V1(베이스라인) + 배포 |
| 3 | 바이브 빌드 2 | AI-네이티브 고도화(LLM·가드레일) + 배포 |
| 4 | 검증 | Eval·Pass Rate·정직한 한계 |
| 5 | 완성·공유 | 정식 배포·전후 비교·발표 |

---
바이브코딩 5일 캠프 · 비전공 학생용 교육 사이트.
