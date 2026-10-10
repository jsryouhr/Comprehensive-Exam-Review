# 최종 수정본 변경 기록 (2026-10-10)

- **기준:** 처음 업로드한 원고(`Yoon_Comprehensive_Exam_Lapinski_REVISED.docx`) 대비 전체를 수정 표시했다(작성자 Claude).
- **결과물:** `..._FINAL_tracked.docx`, `..._FINAL_clean.docx`, 각 PDF. 원고 파일은 저장소에 두지 않는다(CLAUDE.md).
- **최종 문안:** `exam/final-texts.json`.

## 사용자 결정 (2026-10-10)
- 아이디어 3은 약 70단어로 축약.
- 원본 대비 전체 수정 표시.
- 선택 발전안 두 가지:
  - Chung & Rimal (2016)의 학문 대비 문장(Part 2 기여 문단).
  - "TNSB에서 커뮤니케이션 제외" 절(Part 1 TNSB 문단).
- Yoon et al. (2024)은 목록 밖 표시 없이 인용한다.

## 분량과 검증
- 단어 수:
  - 서론 133, Part 1 1,403, Part 2 1,278, 각주 145.
  - 원본은 Part 1 997, Part 2 1,655였다.
- LibreOffice 렌더링: 본문이 11쪽에서 끝나 내용 10쪽 제한을 지킨다. 11쪽 하단에 약 두 줄 여유가 있다.
- XSD 검증 통과. 수정 표시를 모두 수락하면 수락본과 같고, 모두 거부하면 원본 텍스트와 같다.
- 새 문장은 45단어를 넘지 않는다(원문 그대로 둔 Sherif 문장은 예외).
- 금지어와 결과 동사는 없다.
- 본문 인용과 참고문헌이 서로 일치한다.

## Part 1 변경
- **이전 v2 수정(Q1–Q11):** 논지 문장, 문화 문단 재구성, SNA 각주 등. `part1-v2-changes.md` 참조.
- **원문 대조 수정(batch5):**
  - Rimal & Real (2003) 문장을 고쳐 TNSB 조절변인을 2005로 귀속.
  - 손씻기 문장을 둘로 나누고 attitudes 삭제.
  - "Syntheses have since confirmed" 문장을 Rhodes et al. (2020) 문장으로 교체.
  - 그다음 문장을 "Thus,"로 시작.
  - 문화 A 문단에 Kalny et al.의 미국 중심 표본이라는 단서 추가.
- **선택 발전안:** "Communication, central to the 2003 model, was not among the constructs of the TNSB …" 문장 추가. 근거는 Lapinski & Rimal (2005, p. 133).
- **각주 1:** Perkins & Berkowitz 절을 삭제했다(SNA 각주와 중복). SNA 각주에는 "outside the assigned readings"를 명시했다.
- **분량 때문에 줄인 것:**
  - Kalny et al. 후속 두 문장을 한 문장으로 압축.
  - Rimal & Lapinski (2015)의 "dynamic … shaped by human action" 절 삭제.
  - Shulman et al. (2017) 문장을 Part 1에서 빼고 Part 2 공백 단락에만 남김.
  - 티베트 인터뷰 문장의 "herding decisions were constrained…" 절 삭제.
  - 각주 1의 Deutsch & Gerard "face-to-face or anonymously" 절 삭제.
  - "Commonly, nationality serves as a proxy for culture" 삭제.
  - "In this essay" → "In the present essay"(서론과 용어 통일).

## Part 2 변경 (`part2-revision-notes.md` Q1–Q20 판정 반영)
- **도입:**
  - 조건문 "To the extent that the critique presumes …"로 바꿨다.
  - Lapinski & Rimal (2005, p. 137)의 "a central assumption about the role of communication"을 근거로 넣었다.
  - 네 차원을 한 문장으로 열거했다. Lapinski & Rimal (2005, p. 127)의 "conduit" 근거 문장은 분량 때문에 뺐다.
- **차원 1:** Rimal & Real (2003) 직접인용에 따옴표와 쪽수를 붙였다. 매개 채널 문장에서 근거 없는 비교("received more attention")를 삭제했다.
- **차원 2:**
  - 해석을 정의하는 첫 문장을 넣었다.
  - "routinely asked"를 삭제했다.
  - Lapinski et al. (2013)은 믿을 만함 결과로 다시 썼다.
  - Rimal & Lapinski (2015) 인용 오용을 바로잡았다.
- **차원 3:**
  - "distinctive contribution of the TNSB tradition"과 cue to action 문장을 삭제했다.
  - TNSB 조절변인, Lapinski & Rimal (2005, p. 141)의 사적성 논리, 2013 상호작용 비일치 결과를 넣었다.
  - Real & Rimal (2007)을 Chung & Rimal (2016) 재인용으로 넣었다.
- **차원 4:** 이론화와 검증의 구분을 정리했다. 근거는 Lapinski & Rimal (2005)과 Rimal & Lapinski (2015)이고, TNSB가 전달 방식을 명세하지 않는다는 점을 덧붙였다. 각주 4는 Geber et al. (2019)과 Rimal & Yilma (2022) 두 편으로 축약했다.
- **기여:**
  - Chung & Rimal (2016) 학문 대비 문장을 추가했다.
  - 행동 속성 예시(privacy, ambiguity)를 넣었다.
  - 셋째 항목을 "수신자의 메시지 지각을 자료로 다룸"으로 바꿨다. 근거는 Lapinski et al. (2013, p. 23)이다. Schultz et al. (2007)은 에너지 사용 사례로 유지했다.
  - 넷째 항목(번역·불변성 절차)을 "문화를 커뮤니케이션의 특성으로 다룸"으로 교체했다(Liu & Lapinski, 2025).
- **공백:**
  - 조작 점검 중복 절을 삭제했다.
  - 변화 항목에 Rimal & Lapinski (2015) 근거를 넣었다.
  - 문화 항목에 Shulman et al. (2017) 근거를 넣고 "proposed more often than tested directly"로 바꿨다.
- **아이디어 1:**
  - 오리엔테이션에서 시작한다(Rimal & Real, 2005).
  - 층 단위 음주 평균을 집단 규범으로 쓴다(Rimal & Lapinski, 2015).
  - RI-CLPM(Hamaker et al., 2015)을 쓰고 각주 5로 목록 밖임을 표시했다.
  - 대화 → 집단–지각 규범 연결 가설을 넣었다. 승인 대화 → 명령적 규범 가설은 분량 때문에 뺐다.
- **아이디어 2:**
  - 출처 요인의 근거로 Chung & Rimal (2016)의 사회적 거리를 넣었다.
  - 개방형 문항 다음에 평정 문항을 두는 측정 순서를 넣었다.
  - 방향 예측: 같은 집단 성원의 제재일 때 효과가 더 크다.
  - 문화 확장의 근거를 Liu & Lapinski (2025)로 바꿨다(Hall 대체). 번역·불변성 절은 분량 때문에 뺐다.
- **아이디어 3:** 약 70단어로 축약했다. 일방향 피드백의 한계(Lapinski & Rimal, 2005), 정적 보고서 vs LLM 챗봇, 대화 로그 코딩을 담았다. 관계형 조건, AI 출처 질문, Costello et al.과 Neighbors et al.은 뺐다.
- **결론:** 두 문장으로 축약했다.
- **참고문헌:** Real & Rimal (2007)과 Geber & Hefner (2019)를 삭제하고 Hamaker et al. (2015)를 추가했다.

## 남은 확인 사항
- Rhodes et al. (2020)의 "shift perceived norms reliably … small and heterogeneous"는 원문 미확인이다(저자 원문 주장 유지).
- Real & Rimal (2007)의 결과는 Chung & Rimal (2016)을 통한 2차 확인이다.
- Word에서 열어 11쪽 끝을 다시 확인할 것. 글꼴 대체에 따라 한두 줄 달라질 수 있다.
