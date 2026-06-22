# 📚 Prompt Engineering for Accounting & Audit

**회계·감사 실무 특화 프롬프트 라이브러리**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow?style=flat)](https://opensource.org/licenses/MIT)
[![Domain](https://img.shields.io/badge/Domain-Accounting%20%26%20Audit-blue?style=flat)](https://github.com/HyunSu1313/prompt-engineering-accounting/blob/main)
[![Tool](https://img.shields.io/badge/Tool-AI%20Assisted-purple?style=flat)](https://github.com/HyunSu1313/prompt-engineering-accounting/blob/main)

---

## 📌 프로젝트 개요

회계사(KICPA) 및 감사 실무자가 AI를 업무에 효과적으로 활용하기 위한 **검증된 프롬프트 템플릿 모음**입니다.

단순한 질문이 아닌, **출력 형식·기준서 근거·실무 문구까지 즉시 활용 가능한 형태**로 설계되었습니다.

---

## 🗂️ 카테고리 구성

| # | 카테고리 | 주요 활용 |
|---|---|---|
| 01 | [레퍼런스 검색용](./01_reference_search.md) | 회계기준서 해석, 내부회계 가이드라인·개념체계, 엑셀·ERP, 논리·계산 검증 |
| 02 | [커뮤니케이션용](./02_communication.md) | 조서 문장화, 이메일, 클라이언트 인터뷰·요청 문장 |

> 위 템플릿이 실제로 효과가 있는지 검증한 자료는 [평가 및 검증](#-평가-및-검증) 섹션에 별도로 정리했습니다.

---

## 📊 평가 및 검증

프롬프트의 실무 적용 가능성을 검증하기 위해, 일반 질문 방식과 템플릿 적용 방식을 비교한 평가 기준 및 케이스 스터디를 별도로 정리했습니다.

- [evaluation.md](./evaluation.md): 프롬프트 평가 기준(근거 정확성, 출력 일관성, 실무 활용성, 할루시네이션 통제, 커뮤니케이션 품질) 및 테스트 케이스 요약
- [case_studies/](./case_studies/): 실제 업무 상황 기반 입력→출력→검토 결과 상세 사례

---

## 💡 설계 원칙

**1. 출력 형식 고정**
"설명해줘" 대신 원하는 출력 구조를 프롬프트에 명시합니다.
→ 매번 다른 형태의 답변 없이 일관된 결과물 획득

**2. 실무 즉시 활용**
감사조서 문구, 검토멘트, 메일 문장 등 복붙해서 바로 쓸 수 있는 형태로 출력합니다.

**3. 근거 기반 + 할루시네이션 방지**
조항·문단 번호까지 요청하고, 원문 인용 시 정확한 일치 여부를 확인합니다.
→ 확인되지 않는 내용은 "직접 확인 필요"로 명시 (추정 출력 방지)

**4. 회사 컨텍스트 옵션 (필요시 기재)**
상장 여부 · 규모(대형/중소기업) · 업종 · 회계처리기준(K-IFRS/일반기업회계기준)을 필요시 입력합니다.
→ 답변 기준이 달라지는 경우에만 영향을 미치며, 미기재 시 일반적인 기준으로 답변

**5. 검증 우선**
AI 출력을 그대로 사용하지 않고, 실무에서 직접 검증한 결과만 라이브러리에 포함합니다.

---

## 🚀 사용 방법

1. 필요한 카테고리 파일을 열어 템플릿 확인
2. `[질문]` 또는 `[상황]` 부분에 실제 내용 입력 (필요시 회사 컨텍스트 기재)
3. 사용 중인 AI(Claude, Copilot 등)에 프롬프트 전체 붙여넣기
4. 출력 결과 검토 후 실무 활용

---

## 🔭 향후 계획

- [ ] 각 카테고리 예시 케이스 추가
- [ ] RCM 자동화 툴(별도 프로젝트)과의 연계 사례 정리
- [ ] SoX 특화 프롬프트 옵션 추가

---

> 본 프로젝트는 개인 학습 및 포트폴리오 목적으로 작성된 자료이며, 소속 조직의 공식 입장이나 산출물이 아닙니다.

---

## 👤 개발자

**정현수** | KICPA | EY한영 Risk Consulting (P&C)

📫 mosjeong1@gmail.com
🔗 [GitHub](https://github.com/HyunSu1313)
