# 개인 이력서 – REPORT

| 항목 | 내용 |
|---|---|
| 활동명 | 천사지기 |
| 배포 URL | https://angelrita.smu.ai.kr/ |
| 작성일 | 2026-10-17 |

---

## 1. 인수 검수표

> - 완성된 이력서를 **직접 확인**하고 결과를 적습니다.

> - 확인 방법은 과제 공지의 **수용 기준 번호(①, ②, …)마다** 무엇을 어떻게 확인했는지 적습니다.

> - 수용 기준 중 하나라도 충족하지 못하면 **Fail**입니다. 어떤 기준을 못 맞췄는지 번호로 적습니다. 예: `Fail (②)`

> - **Fail을 정직하게 적은 것은 감점하지 않습니다. Pass라고 적었는데 실제로 안 되면 감점합니다.**

> - 근거는 캡처 이미지 경로로 적습니다.

| ID | 확인 방법 | 결과 | 근거 |
|---|---|---|---|
| F-01 | ① 활동명 확인. ② 현재 소속 표시 확인. ③ 관심 분야를 담은 한 줄 소개 및 50자 이내 표시 확인. ④ 창 너비 1280px에서 스크롤 없이 첫 화면에 보임 확인.  | Pass |[1280px 확인](images/Check_F01.png) |
| F-02 | ① header에 Github 프로필 링크 표시 ② 클릭 후 프로필 이동 확인  . ③ 홈페이지 소스에서 이메일·전화번호 등 별도 연락처 유무 확인 | Pass | [header 깃허브](images/Check_F02_1.png) [깃허브 이동코드](images/Check_F02_2.png) [소스 내 연락처 x(1)](images/Check_F02_3.png) [소스 내 연락처 x(2)](images/Check_F02_4.png) |
| F-03 | ① 실적 수 4개 이상 및 2개의 고교 시절 실적 ② 실적마다 시기, 분류, 내용, 역할 표시 ③ 분류 허용 범위 내 표시 ④ 최신 실적이 위에 오도록 시기 역순 정렬 완료 ⑤ 표(table)로 표시 확인 | Pass | [실적표 1](images/Check_F03_1.png) [실적표 2](images/Check_F03_2.png) |
| F-04 | ① 시간표와 나열된 교과목의 일치 확인. ② 각 과목의 전공/교양 표시 확인. ③ 본 과목의 #weekly 링크 확인. | Pass | [시간표](images/Check_F04_1.png) [캡쳐](images/Check_F04_2.png) [주소 옆 #weekly 확인](images/Check_F04_3.png) [#weekly 연결](images/Check_F04_4.png) |
| F-05 | ① 1~15주차 표시 확인. ② 2·3·5·6·7주차가 doc02·03·05·06·07.html에 연결되는지 소스 확인. ③ 나머지 주차의 문구와 링크 유무 확인. ④ 실습과 예정의 CSS 색상 구분 확인. | Pass | [캡쳐 및 색상 구분](images/Check_F05_1.png) [2주차](images/Check_F05_2.png) [3주차](images/Check_F05_3.png) [5주차](images/Check_F05_4.png) [6주차](images/Check_F05_5.png) [7주차](images/Check_F05_6.png) [예정 주차 링크 없음](images/Check_F05_7.png) |
| F-06 | ① footer의 최종 수정일 형식과 time 요소 확인. ② 최신 배포 저장소 커밋의 한국 날짜와 비교 확인. | Pass | [깃허브 내 커밋 날짜](images/Check_F06_1.png) [footer 내 요소 확인](images/Check_F06_2.png) |
| Q-HTML | W3C HTML 검사기로 배포URL 검사. 오류 0 확인. | Pass | [HTML 검사기 확인](images/Check_Q-HTML.png) |
| Q-CSS | W3C CSS 검사기(https://jigsaw.w3.org/css-validator/)로 검사. 오류 0 확인.  인라인 스타일 없음 확인. 표현용 태그 없음. 창 크기 변경 확인. | Pass | [CSS 검사기 확인](images/Check_Q-CSS_1.png) [코드 내 인라인 style 없음 (1)](images/Check_Q-CSS_2.png) [코드 내 인라인 style 없음 (2)](images/Check_Q-CSS_3.png) [창크기 변경 1](images/Check_Q-CSS_4.png) [창크기 변경 2](images/Check_Q-CSS_5.png)  [창크기 변경 3](images/Check_Q-CSS_6.png) [창크기 변경 4](images/Check_Q-CSS_7.png) [창크기 변경 5](images/Check_Q-CSS_8.png) [창크기 변경 6](images/Check_Q-CSS_9.png) [외부 css 1](images/Check_Q-CSS_10.png) [외부 css 2](images/Check_Q-CSS_11.png) |
| Q-DEPLOY | 배포 URL 정상 동작 확인. 깨진 링크, 이미지, 영상 없음 확인. | Pass | [링크 이동 1](images/Check_Q-DEPLOY_1.png) [링크 이동 2](images/Check_Q-DEPLOY_2.png) [동영상](images/Check_Q-DEPLOY_3.png) [실적 내 링크들](images/Check_Q-DEPLOY_4.png) [2주차 정상동작](images/Check_F05_2.png) [3주차 정상동작](images/Check_F05_3.png) [5주차 정상동작](images/Check_F05_4.png) [6주차 정상동작](images/Check_F05_5.png) [7주차 정상동작](images/Check_F05_6.png) |

---

## 2. 완성도 분석

완성도 = 충족(Pass)한 요구사항 수 ÷ 평가 대상 요구사항 수(9) = 9 / 9 = 100%


### 요구사항과 결과가 다른 부분

없습니다.

### 다음에 다르게 할 점

현재는 단순히 CSS와 HTML5에서 구현이 가능한 정도의 웹사이트를 만들었습니다.
다음 번에는 우주의 느낌이 나거나 게임의 느낌이 나도록 JavaScript를 이용하여 홈페이지 내 이미지가 일정 스크롤이 내려가면 변하거나 header에서 footer까지 이동할 경우 header에서부터 footer까지 이어지는 하나의 로켓을 만들어 지구에서 발사된 로켓이 footer에 도착한 경우 달에 도착하고 그 로켓을 누를 시 다시 페이지 처음으로 올라가는 형식을 구현하고 싶습니다.

---

## 3. 추가 요구사항 제안 (선택 – 가산점)

### 요구사항 정의

| ID | 요구사항 | 제안 이유 | 수용 기준 |
|---|---|---|---|
| A-01 | 페이지 내 이동 편의 | 긴 페이지에서 이동을 쉽게 하기 위해. | ① 맨 위로 버튼이 화면 오른쪽 아래에 고정되고 클릭 시 상단으로 이동한다. ② F-01 위치 내에 홈페이지 정보 칸을 배치해 클릭시 각 정보별로 이동한다. ③ 수강 과목 내 본 과목의 버튼의 어디를 눌러도 실습 부분으로 이동한다. |
| A-02 | 실적의 결과물을 확인 | 설명만으로 알기 어려운 게임·웹사이트·모델링 결과물을 직접 제시하기 위해. | ① 우주센터 실적 클릭 시 itch.io 게임 페이지가 열린다. ② 디지털인문학 실적 클릭 시 해당 웹사이트가 열린다. ③ 모델링 실적 클릭 시 WebM 영상이 열리고 재생된다. |
| A-03 | 실적 내 구분을 추가 | 실적이 많아졌을 때 구분을 위해. | ① 모든 실적을 볼 수 있는 전체 버튼이 있고 현재 실적을 숫자로 보여준다. ② 옆으로 나열된 버튼은 현재 실적 표에 있는 분류로 분류마다 몇개의 실적이 있는지 확인할 수 있도록 한다. ③ 분류 버튼을 클릭 시 그 분류에 들어있는 실적만 보이도록 한다. |
| A-04 | 진행도 및 일정 구분, 클릭 표시 | 완료한 주차와 휴식·시험 일정을 한눈에 확인, 버튼의 가시성을 위해. | ① 총 15개 칸을 표시한다. ② OT 1개·실습 5개·추석 휴식 1개를 포함해 진행도를 7/15로 표시한다. ③ OT는 START, 추석은 SAVEPOINT로 구분한다. ④ 실습을 확인할 수 있는 주차의 칸은 기본 발광과 hover·키보드 초점 강조가 있고 손 모양 커서를 표시한다. |


### 검수

| ID | 확인 방법 | 결과 | 근거 |
|---|---|---|---|
| A-01 | ① 오른쪽 아래 맨 위로 버튼 확인. 끝까지 내린 후 맨 위로 버튼 클릭 시 맨 위로 링크 확인. ② F-01 구역 내 주차 버튼 3개 확인. 주차 버튼 3개 클릭 시 각 주차 위치로 이동 확인. ③ 본 과목 버튼 내 css 스타일 ::after 확인. | Pass | [오른쪽아래 맨위로 버튼](images/Check_A01_1.png) [fixed 고정](images/Check_A01_2.png) [맨위로 이동 #top 확인](images/Check_A01_3.png) [id=top 이동링크 확인](images/Check_A01_4.png) [F01 위치 주차버튼 확인](images/Check_F02_1.png) [이동 링크 확인](images/Check_A01_5.png) [실적으로 이동](images/Check_A01_6.png) [수강과목으로 이동](images/Check_A01_7.png) [주차로 이동](images/Check_F04_4.png) [본 과목 :after 확인](images/Check_A01_8.png) | 
| A-02 | ①~③ 소스의 목적지 및 로컬 WebM 존재 확인. 클릭 시 itch.io 이동, 웹사이트, 영상 재생 확인.  | Pass | [itch.io 이동](images/Check_Q-DEPLOY_1.png) [웹사이트 이동](images/Check_Q-DEPLOY_2.png) [동영상 재생](images/Check_Q-DEPLOY_3.png)  [소스 내 링크 확인](images/Check_Q-DEPLOY_4.png) |
| A-03 | ①~② 실적 표 위 6개의 버튼 및 이름, 갯수 확인. ③ 분류 버튼 클릭 시 분류에 맞는 실적 분리 확인. | Pass | [6개의 분류 버튼](images/Check_F03_1.png) [프로젝트](images/Check_A03_1.png) [활동](images/Check_A03_2.png) [교육](images/Check_A03_3.png) [수상](images/Check_A03_4.png) [자격](images/Check_A03_5.png) |
| A-04 | ①~② 15개 칸 표시, 1주차 OT, 실습 , 추석 휴식 포함 진행도 표시 확인. ③ 구분된 OT와 추석 위 단어 확인. ④ 마우스 커서를 올릴 시 hover효과, Tab키 시 초점 강조 표시 확인. | Pass | [1~15주차 칸 표시 / 진행도 표시 / 실습, 휴강 구분 표시](images/Check_F05_1.png) [초점 강조 및 hover 효과 확인](images/Check_A04.png) |
