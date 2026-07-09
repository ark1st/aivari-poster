# AIVARI Agent — 포스터 발표 컨닝페이퍼

내일 포스터 발표용 이중언어(영어/한국어) 컨닝페이퍼 & 텔레프롬프터.
**ICML 2026 Workshop (GenBio)** — *AIVARI Agent: An Evidence-Grounded Agentic LLM for Variant Reportability and Interpretation*.

## 쓰는 법

`index.html`을 브라우저로 열기만 하면 됩니다. 인터넷 없이도 동작합니다.

- **학습 모드** — 오전에 전체 대본·숫자·Q&A를 스크롤하며 연습
- **발표 모드** — 실전용. 카드 하나씩, 큰 글씨(A−/A+ 조절), 방향키/스페이스로 넘김
- **🆘 급할 때** (우측 하단) — 질문을 못 알아들었을 때 읽을 문장
- **Q&A 검색** — 질문이 들어오면 키워드로 즉시 찾기
- **🌙 라이트/다크** — 발표장 조명에 맞춰 전환

## 핵심 숫자

| Metric | 값 | 의미 |
|---|---|---|
| Group Sensitivity | 0.905 | reportable case를 잡아내는 능력 |
| Group NPV | 0.933 | 전부 negative일 때 신뢰도 |
| Row Precision | 0.351 | 올린 후보 중 진짜 비율 (검토 부담) |

300 cases · 6,460 hypotheses · base model = Gemini 3 Flash · 235-case 공통 subset에서 hybrid pipeline 대비 +34pp Sensitivity, +40pp NPV.

## 한 문장 요약

> At a high level, this is a decision-support tool to reduce missed reportable findings.
> (놓칠 수 있는 reportable finding을 줄이기 위한 의사결정 보조 도구입니다.)
