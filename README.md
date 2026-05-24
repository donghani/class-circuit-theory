# ⚡ 회로이론 (Circuit Theory)
> **경희대학교 전자공학과 김동한 교수님 강의 자료실**  
> 본 저장소는 전기/전자공학의 가장 근본이 되는 **회로이론(Circuit Theory)** 과목의 강의자료(PDF)와 학습 교안 패키지를 체계적으로 아카이빙하는 공간입니다.

---

## 📢 과목 및 강사 정보 (Course Information)

| 구분 | 정보 및 링크 |
| :--- | :--- |
| **👨‍🏫 담당 교수** | **김동한 교수** (전자공학과, 전자정보대학 609호, 내선 3831) |
| **✉️ 이메일** | [donghani@khu.ac.kr](mailto:donghani@khu.ac.kr) |
| **⏱️ 상담 시간** | 매주 수업 종료 후 1시간 |
| **📖 주교재** | **회로이론 12판** (J. David Irwin, R. Mark Nelms 저) |
| **🔗 강의 영상** | [YouTube 채널 (경희대 김동한)](https://www.youtube.com/channel/UCT_h-5YhlC0t9LEdVckdrXQ) |
| **💻 실습 포털** | [경희대학교 e-Campus](https://e-campus.khu.ac.kr) |

---

## 📚 주차별 강의 자료 (Lecture Slides)

아래 강의 자료(PDF)는 본 저장소의 루트 디렉토리에 포함되어 있어 즉시 다운로드하거나 확인할 수 있습니다.

### 🔵 **Part 1. 회로 분석의 기초 (Basic Concepts & Laws)**
* **[Chapter 1. 기본 개념](./Chapter1%20%EA%B8%B0%EB%B3%B8%EA%B0%9C%EB%85%90.pdf):** 전하(Charge), 전류(Current), 전압(Voltage), 에너지 및 전력(Power)의 물리적 정의
* **[Chapter 2-1. 옴의 법칙](./Chapter2-1%20%EC%98%B5%EC%9D%98_%EB%B2%95%EC%B9%99.pdf):** 저항(Resistance)의 특성 및 전압/전류의 선형적 비례 관계
* **[Chapter 2-2. 키르히호프 법칙](./Chapter2-2%20%ED%82%A4%EB%A5%B4%ED%9E%88%ED%98%B8%ED%94%84%20%EB%B2%95%EC%B9%99.pdf):** 회로 해석의 뼈대인 키르히호프 전류 법칙(KCL) 및 전압 법칙(KVL)
* **[Chapter 2-3. Single Loop](./Chapter2-3%20Single%20Loop.pdf):** 단일 루프 회로 분석 및 전압 분배 법칙(Voltage Division)
* **[Chapter 2-4. Single Node Pair](./Chapter2-4%20Single%20Node%20Pair.pdf):** 단일 마디 쌍 회로 분석 및 전류 분배 법칙(Current Division)
* **[Chapter 2-5, 2-6, 2-7. 직병렬 및 Delta-Wye](./Chapter2-5,%202-6%202-7%20SER_Delta-Wye.pdf):** 저항의 직병렬 합성, 델타-와이($\Delta\text{-Y}$) 상호 변환 기법
* **[Chapter 2-8. 종속 전원 회로](./Chapter2-8%20Circuits%20with%20Dependent%20Sources.pdf):** 전압/전류 제어 전원(Dependent Sources)을 포함한 능동 회로 해석

### 🟢 **Part 2. 핵심 회로 해석 기법 (Circuit Analysis Techniques)**
* **[Chapter 3-1. 마디 해석법 (Node Analysis)](./Chapter3-1%20Node%20Analysis.pdf):** KCL을 바탕으로 미지 마디 전압을 설정하여 연립방정식을 세우는 체계적 기법
* **[Chapter 3-2. 망로 해석법 (Loop Analysis)](./Chapter3-2%20Loop%20Analysis.pdf):** KVL을 바탕으로 독립 루프 전류를 설정하여 회로를 구하는 기법
* **[Chapter 3-3, 3-4. 선형성 및 중첩의 원리](./Chapter3-3,%203-4%20Linearity%20%26%20Superposition.pdf):** 선형 회로의 특성을 이용해 여러 전원이 섞인 회로를 개별 해석 후 합산하는 기법
* **[Chapter 3-5, 3-6. 테브난 & 노턴 및 최대 전력 전달](./Chapter3-5,%203-6%20Thevenin%20%26%20Norton%20and%20Maximum%20Power%20Transfer.pdf):** 복잡한 회로망을 단 하나의 등가 전원과 등가 저항으로 축소하는 핵심 정리 및 최대 부하 전력 전송 조건
* **[Chapter 3-7, 3-8, 3-9. 회로망 정리](./Chapter3-7,%203-8,%203-9%20Reciprocity,%20Compensation%20and%20Millman's%20Theorem.pdf):** 가역 정리(Reciprocity), 보상 정리(Compensation), 밀만의 정리(Millman's Theorem) 유도와 적용
* **[Chapter 3-10. 실무 적용 예시](./Chapter3-10%20Application%20Examples.pdf) / [Chapter 3-11. 설계 예시](./Chapter3-11%20Design%20Examples.pdf):** 이론적 회로망 정리를 활용한 전자기기 전원 회로 해석 및 저전력 설계 응용

### 🟡 **Part 3. 과도 상태 및 동적 회로 (Storage Elements & Transient Response)**
* **[Chapter 5. 커패시터와 인덕터](./Chapter5%20capacitance%20and%20Inductance.pdf):** 에너지를 저장하는 리액티브 소자인 커패시터($C$)와 인덕터($L$)의 전압-전류 관계식 및 직병렬 합성
* **[Chapter 6-1. 1차 과도 회로 개론](./Chapter6-1%20Intro%20First%20Order%20Diff%20Equation.pdf) ([업데이트판](./Chapter6-1%20Intro%20First%20Order%20Diff%20Equation-updated.pdf)):** 미분방정식을 이용한 1차 회로(RC, RL)의 고유 응답 및 스텝(Step) 과도 응답 해석
* **[Chapter 6-2. 스텝-바이-스텝 펄스 응답](./Chapter6-2%20Step%20by%20Step%20Pulse.pdf):** 펄스파 입력에 따른 과도 상태 구하기 기법
* **[Chapter 6-3. 2차 과도 회로](./Chapter6-3%20Second%20order%20Circuits.pdf):** 2차 미분방정식을 따르는 RLC 회로의 제동 상태(과제동, 임계제동, 부족제동) 분류 및 응답식 유도
* **[Chapter 6-4. 설계 및 응용](./Chapter6-4%20Desgin%20and%20Applications.pdf):** 과도 회로 특성을 적용한 발진 제어 및 필터링 설계 실무

### 🟣 **Part 4. 교류 정현파 해석 (AC Sinusoidal Steady-State)**
* **[Chapter 7. 정현파 정상 상태 분석](./Chapter7%20Sinusoidal%20Steady%20Analysis.pdf):** 오일러 공식을 통한 정현파의 페이저(Phasor) 변환, 임피던스($Z$)와 어드미턴스($Y$), 주파수 도메인 교류 해석
* **[Chapter 8. 교류 전력 분석](./Chapter8%20Steady-State%20Power%20Analysis.pdf):** 순시 전력, 평균 전력(Real Power), 무효 전력(Reactive Power), 피상 전력 및 복소 전력(Complex Power) 계산과 역률(Power Factor) 보정 기술

---

## 🚀 빠른 시작 가이드 (Quick Start)

### 1. 로컬 저장소 내려받기 (Sparse Checkout 적용)
본 저장소에는 고화질의 대용량 강의자료 PDF들이 보관되어 있어, 필요한 강의 자료 및 홈페이지 설정 파일만 가볍게 내려받아 사용하고 싶다면 아래 순서대로 터미널에서 **Git Sparse-Checkout** 기능을 적용해 보세요.

```powershell
# 저장소 구조만 가볍게 클론
git clone --filter=blob:none --sparse https://github.com/donghani/class-circuit-theory.git
cd class-circuit-theory

# 핵심 마크다운 문서 및 홈페이지, 이미지 자원만 체크아웃
git sparse-checkout set README.md index.html index.md concept1.png textbook_cover.jpg
```
