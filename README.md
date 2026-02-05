# 💫 K-NOVA: Korean Neologism Observatory and Visual Analytics 🔭
- 📂 Side Project
- 🏆 [KNBD: Korean Neologisms Benchmark Dataset](https://github.com/Jees-an/Korean-neologisms-benchmark-dataset)

## 1. 개요

![K-NOVA](img/K-NOVA.png)

'NOVA'는 새롭게 나타나는 별을 말합니다.
**언어의 새로운 형태와 의미** 역시 특정 시점에 출현하여 빠르게 확산되거나 소멸된다는 점에서 천문학의 신성(新星) 현상과 닮아 있습니다.
이에 **한국어 신어 관측 시스템**의 이름을 'K-NOVA(Korean Neologism Obsevatory and Visual Analytics)'로 명명하게 되었습니다.

---

## 2. 한국어 신어 수집 현황
- Latest Update: 2026.02.05.

| 수집 기간 | 장르 | 신어 후보 항목 수 | 최종 신어 수 |
|------|----------|---|---|
| 2025.01.01.~2025.12.31. | 문어 | | |
| 2025.01.01.~2025.12.31. | 웹 언어 | | |
| | **합계** | | |

---

## 3. 한국어 신어 수집 및 분석의 과정

![신어 수집·분석 파이프라인](img/Korean_Neologism_Extractor.png)

| 모듈 | 기능 |
|------|---------|
| [모듈 1] | 대규모 말뭉치 수집 |
| [모듈 2] | 신어 후보군 추출 |
| [모듈 3] | 신어 후보군 정제 |
| [모듈 4] | LLM 보조 신어 판별 |
| [모듈 5] | LLM 보조 신어 집필 |
| [모듈 6] | 사용 양상 관측(빈도, 분포, 사용 화자 수 등) |

---

## 4. 참고문헌

- 안진산(2026), 『실시간 신어 추출 파이프라인의 설계와 검증』, (*forthcoming*).
- 안진산(2026), 『거대언어모델을 활용한 신어 집필의 가능성과 쟁점 -<신어 2023>의 신어 목록을 중심으로-』, (*forthcoming*).
- [남길임·안진산·이수진(2025), 「말뭉치, LLMs, 인간 전문가의 협업을 통한 한국어 신어의 탐지 -<신어 2023>의 신어 목록을 중심으로-」, 『한국어학』 108호.](https://www.kci.go.kr/kciportal/ci/sereArticleSearch/ciSereArtiView.kci?sereArticleSearchBean.artiId=ART003232209)

---

## 🧑‍🏫 주요 기여자

- **안진산**
  경북대학교 국어국문학과 외래교수 | 언어정보연구센터 연구원
  📧 san@knu.ac.kr