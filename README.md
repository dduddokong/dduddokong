### Hi, I'm Do-hyun Lee 👋

Economics student at **Seoul National University** (minors in Industrial Engineering and Statistics), working toward an actuarial career.
I build insurance and risk models in Python and test them against public disclosures and real data.

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-2E7D32)
![R](https://img.shields.io/badge/R-276DC3?logo=r&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?logo=postgresql&logoColor=white)
![Excel VBA](https://img.shields.io/badge/Excel%20VBA-217346?logo=microsoftexcel&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude%20Code-D97757?logo=anthropic&logoColor=white)

**Exams:** Korean Actuary Exam Parts 1 and 2 (Actuarial Mathematics, Pension Mathematics, Actuarial Modeling) · SOA Exam P
**Activities:** Head of Projects, SNU Actuarial Society · DB Insurance Study Group
**Contact:** dlehgus58@gmail.com

---

#### Featured projects

| | Project | Result | Stack |
|:-:|---|---|---|
| 🛡️ | **[ORSA Reverse Stress Test](https://github.com/dduddokong/orsa-reverse-stress-test)**<br/><sub>K-ICS capital model of four stylised Korean non-life insurers, built from public disclosures · DB Insurance & Finance Contest · team of 2</sub> | Diversification effects match four insurers' disclosures exactly; +100bp rate shock within **3%** of the disclosed figure | NumPy · SciPy · pytest |
| 💳 | **[KCB Credit Target Prediction](https://github.com/dduddokong/kcb-credit-target-prediction)**<br/><sub>Default-target prediction on 162k loan applications × 558 variables · SNU course · team of 3</sub> | Linked records without a customer ID (LSH + Fellegi–Sunter, 99.96% label agreement); AUROC **0.809 → 0.860**; **1st of 5 teams** | LightGBM · XGBoost · CatBoost |
| 🌌 | **[Galaxy SFR Hurdle Model](https://github.com/dduddokong/galaxy-sfr-hurdle-model)**<br/><sub>Two-part model for a zero-inflated, heavy-tailed target, built like frequency × severity · SNU DataHub competition · solo</sub> | RMSE **−24.2%** vs. baseline (9.525 → 7.218); spatial-block CV, 21 pre-registered analyses | scikit-learn · pandas |
| 🚗 | **[AVs & Auto Insurance Premiums](https://github.com/dduddokong/av-insurance-premiums)**<br/><sub>Frequency × severity view of autonomous-vehicle safety data · Liner Scholar Research Competition · sole author</sub> | 68% fewer crashes per mile can still mean **1.4–1.9×** the crashes per vehicle-year; run with a multi-agent research workflow | Python · Claude Code · Codex |
| 🌡️ | **[Heat-Wave Parametric Insurance](https://github.com/dduddokong/heatwave-parametric-insurance)** *(in progress)*<br/><sub>Basis risk in Jeju's heat-wave income cover and contract design under correlated heat risk · SNU Actuarial Society</sub> | Mean inter-regional heat-day correlation of **0.84** (ERA5, preliminary); TVaR capital loading by Monte Carlo | NumPy |

---

<details>
<summary><b>한국어 소개</b></summary>
<br/>

서울대학교 경제학부(산업공학·통계학 부전공) 이도현입니다. 보험·리스크 모형을 Python으로 직접 만들고, 공시 자료와 실제 데이터로 검증합니다.

| 프로젝트 | 한 줄 요약 |
|---|---|
| ORSA 역스트레스 테스트 | 공시 자료로 손해보험사 4곳(가상화)의 K-ICS 자본 모형을 재구성 (제17회 DB 보험금융 공모전) |
| KCB 신용 타깃 예측 | ID가 없는 대출 데이터에서 확률적 레코드 연결을 하고, 앙상블로 AUROC 0.860 달성 |
| 은하 별생성률 허들 모형 | 0이 많고 꼬리가 두꺼운 타깃을 빈도-심도 구조로 풀어 RMSE 24.2% 개선 |
| 자율주행차와 자동차보험료 | 빈도×심도 요율 산정 틀로 분석, 멀티에이전트 연구 워크플로를 직접 구축 |
| 폭염 지수형 보험 (진행 중) | 제주 폭염소득보험의 베이시스 리스크와 공간 상관 아래의 계약 설계 |

보험계리사 시험 1·2차(보험수학, 연금수리, 계리모형), SOA Exam P에 합격했습니다.
</details>
