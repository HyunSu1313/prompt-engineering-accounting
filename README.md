# 📚 Prompt Engineering for Accounting & Audit

**회계·감사 실무 특화 프롬프트 라이브러리**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow?style=flat)](https://opensource.org/licenses/MIT)
[![Domain](https://img.shields.io/badge/Domain-Accounting%20%26%20Audit-blue?style=flat)]()
[![Tool](https://img.shields.io/badge/Tool-Claude%20AI-purple?style=flat)]()

---

## 📌 프로젝트 개요

회계사(KICPA) 및 감사 실무자가 AI를 업무에 효과적으로 활용하기 위한 **검증된 프롬프트 템플릿 모음**입니다.

단순한 질문이 아닌, **출력 형식·기준서 근거·실무 문구까지 즉시 활용 가능한 형태**로 설계되었습니다.

---

## 🗂️ 카테고리 구성

| # | 카테고리 | 주요 활용 |
|---|---|---|
| 01 | [회계처리 · 기준서 해석](./01_accounting_standards.md) | 분개, 기준서 조항, 질의회신, 조서 문구 |
| 02 | [문장 검토 · 실무 표현](./02_writing_review.md) | 검토멘트, 조서 문구, 메일, 문의 문장 |
| 03 | [내부통제 · 통제 중요성](./03_internal_controls.md) | 권한분리, 전산권한, COSO, 내부회계, SoX |
| 04 | [ERP · 엑셀 문제해결](./04_erp_excel.md) | 함수 오류, ERP 처리 방식, 효율화 |
| 05 | [논리 · 계산 검증](./05_logic_verification.md) | 계산 검증, 해석 검증, 논리 흐름 점검 |

---

## 💡 설계 원칙

**1. 출력 형식 고정**
"설명해줘" 대신 원하는 출력 구조를 프롬프트에 명시합니다.
→ 매번 다른 형태의 답변 없이 일관된 결과물 획득

**2. 실무 즉시 활용**
감사조서 문구, 검토멘트, 메일 문장 등 복붙해서 바로 쓸 수 있는 형태로 출력합니다.

**3. 근거 기반**
회계처리 관련 프롬프트는 기준서 조항·링크·질의회신 사례번호까지 요청합니다.
→ 불확실한 정보는 "확인된 사례 없음"으로 명시 (추정 출력 방지)

**4. 검증 우선**
AI 출력을 그대로 사용하지 않고, 실무에서 직접 검증한 결과만 라이브러리에 포함합니다.

---

## 🚀 사용 방법

1. 필요한 카테고리 파일을 열어 템플릿 확인
2. `[질문]` 또는 `[상황]` 부분에 실제 내용 입력
3. Claude에 프롬프트 전체 붙여넣기
4. 출력 결과 검토 후 실무 활용

---

## 🔭 향후 계획

- [ ] 각 카테고리 예시 케이스 추가
- [ ] RCM 자동화 툴과 연동
- [ ] 일반기업회계기준(K-GAAP) 버전 추가
- [ ] SoX 특화 프롬프트 추가

---

## 👤 개발자

**정현수** | KICPA | EY한영 Risk Consulting (P&C)

📫 mosjeong1@gmail.com  
🔗 [GitHub](https://github.com/HyunSu1313)
