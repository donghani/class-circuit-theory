# 🌐 경희대학교 회로이론 강의자료실 (Class Circuit Theory)

Welcome! 본 사이트는 경희대학교 전자공학과 김동한 교수님의 **회로이론(Circuit Theory)** 과목 강의자료실입니다.
교재(회로이론 12판, J. David Irwin & R. Mark Nelms 저)와 연계된 주차별 교안(PDF) 파일들을 손쉽게 둘러보고 내려받으실 수 있습니다.

---

## 👨‍🏫 강사 및 교과 정보 (Course Overview)

* **강사:** 전자공학과 김동한 교수 (전자정보대학 609호)
* **연락처:** donghani@khu.ac.kr | 내선번호 3831
* **상담시간:** 수업 후 1시간
* **주교재:** **회로이론 12판** (J. David Irwin, R. Mark Nelms 저)
* **보조자료:** [유튜브 강의 채널 (경희대 김동한)](https://www.youtube.com/channel/UCT_h-5YhlC0t9LEdVckdrXQ)
* **강의 업로드:** [경희대학교 e-Campus](https://e-campus.khu.ac.kr) 및 본 GitHub 저장소

---

## 📚 주차별 이론 강의 교안 (Lecture Slides)

원하시는 단원의 링크를 클릭하여 PDF 강의 자료를 간편하게 저장할 수 있습니다.

### 🔵 Part 1. 회로 해석의 기초 (Basic Concepts & Laws)
* 📖 [**Chapter 1. 기본 개념**](./Chapter1%20%EA%B8%B0%EB%B3%B8%EA%B0%9C%EB%85%90.pdf)
  * 전하, 전류, 전압, 에너지 및 전력의 정의
* 📖 [**Chapter 2-1. 옴의 법칙**](./Chapter2-1%20%EC%98%B5%EC%9D%98_%EB%B2%95%EC%B9%99.pdf)
  * 저항기 기호, 수동소자 규약(PSC) 및 V-I 특성
* 📖 [**Chapter 2-2. 키르히호프 법칙**](./Chapter2-2%20%ED%82%A4%EB%A5%B4%ED%9E%88%ED%98%B8%ED%94%84%20%EB%B2%95%EC%B9%99.pdf)
  * 회로 마디(Node), 루프(Loop), 가지(Branch) 정의와 KCL, KVL 법칙
* 📖 [**Chapter 2-3. Single Loop**](./Chapter2-3%20Single%20Loop.pdf) & [**Chapter 2-4. Single Node Pair**](./Chapter2-4%20Single%20Node%20Pair.pdf)
  * 전압/전류 배분 법칙을 이용한 고속 직렬/병렬 분압 계산
* 📖 [**Chapter 2-5, 2-6, 2-7. 직병렬 및 Delta-Wye**](./Chapter2-5,%202-6%202-7%20SER_Delta-Wye.pdf)
  * 브릿지 회로 간소화를 위한 델타-와이 상호 등가 변환 기술
* 📖 [**Chapter 2-8. 종속 전원 회로**](./Chapter2-8%20Circuits%20with%20Dependent%20Sources.pdf)
  * 종속 전원이 존재할 때의 루프 방정식 세우기 요령

### 🟢 Part 2. 핵심 회로 해석 기법 (Circuit Analysis Techniques)
* 📖 [**Chapter 3-1. 마디 해석법 (Nodal Analysis)**](./Chapter3-1%20Node%20Analysis.pdf)
  * 기준 마디 설정 및 KCL을 활용한 미지 노드 전압 연립방정식 유도
* 📖 [**Chapter 3-2. 망로 해석법 (Mesh/Loop Analysis)**](./Chapter3-2%20Loop%20Analysis.pdf)
  * 독립 루프 전류를 활용한 KVL 식 조립법
* 📖 [**Chapter 3-3, 3-4. 선형성 및 중첩의 원리**](./Chapter3-3,%203-4%20Linearity%20%26%20Superposition.pdf)
  * 독립 전원을 각각 개별적으로 ON 하여 대수 합을 연산하는 중첩 적용
* 📖 [**Chapter 3-5, 3-6. 테브난 & 노턴 및 최대 전력 전달**](./Chapter3-5,%203-6%20Thevenin%20%26%20Norton%20and%20Maximum%20Power%20Transfer.pdf)
  * 임의의 복잡 선형 회로를 등가 전압원 $V_{oc}$ 및 직렬 저항 $R_{Th}$로 변경하고 최대 부하 매칭 조건 연산
* 📖 [**Chapter 3-7, 3-8, 3-9. 회로망 정리**](./Chapter3-7,%203-8,%203-9%20Reciprocity,%20Compensation%20and%20Millman's%20Theorem.pdf)
  * 쌍대성 및 가역, 보상, 밀만의 획기적 전위 계산 법칙
* 📖 [**Chapter 3-10. 실무 적용 예시**](./Chapter3-10%20Application%20Examples.pdf) & [**Chapter 3-11. 설계 예시**](./Chapter3-11%20Design%20Examples.pdf)
  * 소자의 오차율 분석 및 배터리 전원 분배 설계 문제 해결

### 🟡 Part 3. 과도 상태 및 동적 회로 (Storage Elements & Transient Response)
* 📖 [**Chapter 5. 커패시터와 인덕터**](./Chapter5%20capacitance%20and%20Inductance.pdf)
  * 전계를 이용해 전하를 축적하는 $C$와 자계를 이용해 자속을 생성하는 $L$의 충방전 공식
* 📖 [**Chapter 6-1. 1차 과도 회로 개론**](./Chapter6-1%20Intro%20First%20Order%20Diff%20Equation.pdf) & [**업데이트판**](./Chapter6-1%20Intro%20First%20Order%20Diff%20Equation-updated.pdf)
  * 1차 상미분방정식을 이용한 RC/RL 회로의 응답 시정수($\tau=RC$, $\tau=L/R$) 특성 분석
* 📖 [**Chapter 6-2. 스텝-바이-스텝 펄스 응답**](./Chapter6-2%20Step%20by%20Step%20Pulse.pdf)
  * 시간 간격에 따른 시스템 연속성 조건 설정 및 시각 변화 과도응답
* 📖 [**Chapter 6-3. 2차 과도 회로**](./Chapter6-3%20Second%20order%20Circuits.pdf)
  * 감쇄 상수($\alpha$)와 고유 진동 주파수($\omega_0$) 비교를 통한 부족/과/임계 제동 수식
* 📖 [**Chapter 6-4. 설계 및 응용**](./Chapter6-4%20Desgin%20and%20Applications.pdf)
  * 과도 스위칭 시 발생하는 고전압 차단 및 정밀 지연 회로 타이머

### 🟣 Part 4. 교류 정현파 해석 (AC Sinusoidal Steady-State)
* 📖 [**Chapter 7. 정현파 정상 상태 분석**](./Chapter7%20Sinusoidal%20Steady%20Analysis.pdf)
  * 시간 도메인 회로를 주파수(페이저) 영역으로 매핑하여 복소수 대수식으로 치환하는 임피던스 해석법
* 📖 [**Chapter 8. 교류 전력 분석**](./Chapter8%20Steady-State%20Power%20Analysis.pdf)
  * 교류 소모 실효 전압과 복소 전력($S=P+jQ$)의 특성 및 역률 개선용 진상 커패시터 결합 설계
