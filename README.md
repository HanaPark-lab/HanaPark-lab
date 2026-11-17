<!-- GitHub Profile README -->
<a id="top"></a>

<div align="center">

<img src="header.svg" width="100%" alt="박하나 Hana Park · Model Evaluation · Vision AI · Bio × AI · Seaweed Ph.D."/>

<br/>

[![About](https://img.shields.io/badge/About_Me-1E4E63?style=for-the-badge)](#-about-me)
[![Impact](https://img.shields.io/badge/Impact-2E7D7A?style=for-the-badge)](#-impact-at-a-glance)
[![Projects](https://img.shields.io/badge/Projects-3E9C7C?style=for-the-badge)](#-projects)
[![Stack](https://img.shields.io/badge/Tech_Stack-3B6274?style=for-the-badge)](#-tech-stack)
[![Contact](https://img.shields.io/badge/Contact-C49A5A?style=for-the-badge)](#-contact)

</div>

<br/>

## 🌊 About Me

> **모델의 점수보다 오류의 방향을 먼저 봅니다. 불량을 통과시키는 오류, 병든 잎을 정상으로 보는 오류부터 줄입니다.**

<table>
<tr>
<td width="33%" valign="top">

**🧪 Evaluation & Failure Analysis**

데이터 Split → 성능 평가 → **실패 사례를 직접 보고 원인 확인** → 다음 버전까지, ‘**이 숫자를 믿어도 되는가**’부터 확인합니다.

</td>
<td width="33%" valign="top">

**🔍 Vision AI · Model to Service**

OpenCV Rule 검사, **YOLO11** 객체 검출, **ResNet-18** Fine-tuning을 거쳐 **FastAPI · Celery · Docker**로 서빙했습니다.

</td>
<td width="33%" valign="top">

**🌿 Bio × AI**

해조류(김) 박사 · 김 육상양식 **연구소장** 출신. 수조 사진 **분할 AI**와 **수질 대시보드** 과제를 기획 · 관리하며 생물과 데이터를 이어 왔습니다.

</td>
</tr>
</table>

<br/>

## 📊 Impact at a Glance

<img src="impact.svg" width="100%" alt="김 이미지 분할 학습 데이터 191→463장 · 김 최대 성장률 4.72 mm/day · 조각김치 이물검출 Val mAP50-95 0.345→0.446 · 병뚜껑 검사 54%→90%"/>

<sub>※ 모든 수치는 실제 실행 기록값입니다. 조각김치 이물검출은 6인 팀 공동 성과이며, 저는 Split · 평가 · 실패 분석을 맡았습니다. 연구소 성과는 공개 가능한 범위만 적었습니다.</sub>

<div align="right"><a href="#top"><sub><b>↑ 맨 위로</b></sub></a></div>

<br/>

## 🏢 Career — 김 육상양식 R&amp;D 연구소장

<sub>주식회사 두번째바다 (에어로포닉스 기반 김 육상양식, TIPS 선정 기업) · 2025.06 ~ 2026.06 · R&amp;D팀 3명 · 공주대 생명과학 박사(SCI(E) 주저자 1편 · 공저자 5편)<br/>🔒 사내 프로젝트라 코드 · 데이터 · 사진은 공개하지 않고, 설명과 공개 가능한 수치만 적었습니다.</sub>

<img src="company-01.svg" width="100%" alt="LAB 01 수중 김 이미지 분할 · 성장 예측 (과제 기획 · 방향 설정): 학습 이미지 191장에서 463장으로 확장"/>

<table>
<tr><td width="96" nowrap><b>기간</b></td><td>2025.08 ~ 2025.12 · 모델 개발은 AI 담당자, 나는 <b>과제 기획 · 방향 설정</b></td></tr>
<tr><td width="96" nowrap><b>문제</b></td><td>김 길이를 자로 재면 엽체가 뜯기고, 탁도 · 수조 왜곡으로 오차가 크며, 여러 단의 배드를 사람이 다 확인할 수 없었습니다.</td></tr>
<tr><td width="96" nowrap><b>내 역할</b></td><td>김 연구자 관점에서 <b>무엇을 재야 하는지</b> 과제를 정하고, 개발 흐름과 결과 보고를 검토해 <b>다음 개선 방향</b>을 제시<br/>AI 담당자와 <b>AI 학회</b>에 함께 참석해 모델 발전 방향 논의</td></tr>
<tr><td width="96" nowrap><b>팀 수행</b></td><td>CVAT · Labelme 라벨링 + SAM 보조 · <b>DeepLabV3+</b>로 배경 · 김 · 기준 마커 3클래스 분할 · 라벨 부족을 <b>Pseudo-label 준지도학습</b>으로 보완<br/>기준 마커(1.5 cm)로 <b>김 길이를 cm로 자동 계산</b> → 로지스틱 · 곰페르츠 곡선 → <b>Flask 웹</b>에서 30일 성장 곡선 표시</td></tr>
<tr><td width="96" nowrap><b>결과</b></td><td>학습 데이터 <b>191장 → 463장</b> 확장으로 이미지 중앙 편중 문제 해소 · 길이 · 면적 자동 추출</td></tr>
<tr><td width="96" nowrap><b>팀 기술</b></td><td><code>PyTorch</code> <code>DeepLabV3+</code> <code>SAM</code> <code>CVAT</code> <code>Labelme</code> <code>Flask</code></td></tr>
</table>

<div align="right"><a href="#top"><sub><b>↑ 맨 위로</b></sub></a></div>

<br/>

<img src="company-02.svg" width="100%" alt="LAB 02 실시간 수질 · 영상 대시보드 (과제 기획 · 관리): 센서로 10초마다 수온 · 염도 · pH · TDS 기록, 카메라 7대 영상"/>

<table>
<tr><td width="96" nowrap><b>기간</b></td><td>2025.09 ~ 2025.12 · 개발은 팀, 나는 <b>과제 기획 · 관리</b></td></tr>
<tr><td width="96" nowrap><b>문제</b></td><td>수질을 사람이 하루 몇 번 손으로 재서 기록해, 밤사이 변화나 이상 징후를 놓쳤습니다.</td></tr>
<tr><td width="96" nowrap><b>내 역할</b></td><td>현장에서 <b>어떤 수질 값을 얼마나 자주</b> 기록해야 하는지 정하고, 진행 상황과 코드를 함께 보며 기능 · 우선순위 조율</td></tr>
<tr><td width="96" nowrap><b>팀 수행</b></td><td><b>RS-485 (Modbus)</b> EC · pH 센서를 Python으로 읽어 <b>10초 간격</b> 수집 · 날짜별 로그 자동 저장<br/><b>Flask API</b>로 현재값 · 24시간 추이 · 로그 다운로드 제공 · <b>ESP32-CAM 7대</b> 실시간 영상을 한 웹 화면에 묶음</td></tr>
<tr><td width="96" nowrap><b>결과</b></td><td>실증 기간 수질을 연속 기록해 아래 오염원 상관분석(r = 0.55)의 데이터로 사용</td></tr>
<tr><td width="96" nowrap><b>팀 기술</b></td><td><code>Python</code> <code>RS-485 Modbus</code> <code>Flask</code> <code>ESP32-CAM</code></td></tr>
</table>


#### 🧫 그 밖의 연구 성과

<table>
<tr><th width="150">과제</th><th width="130">핵심 숫자</th><th>한 일</th></tr>
<tr><td><b>김 배양 조건 확립</b></td><td align="center"><b>4.72 mm/day</b></td><td>조건별 실험 설계 · 상대성장률(SGR) 지표 도입 · 해수 3.6톤 실증 저성장 원인 6가지 규명</td></tr>
<tr><td><b>오염원 원인 규명</b></td><td align="center"><b>r = 0.55</b></td><td>센서 pH와 오염도 상관분석(N = 828) → pH를 오염 조기 지표로 활용</td></tr>
<tr><td><b>배지 원가 절감</b></td><td align="center"><b>−80%</b></td><td>성분별 단가 분석으로 고가 성분 대체 · 월 배지 비용 80% 이상 절감 가능성 확인</td></tr>
</table>

<div align="right"><a href="#top"><sub><b>↑ 맨 위로</b></sub></a></div>


<br/>

## 🚀 Projects

<sub>KH정보교육원 [비솔] Vision AI &amp; Vertical AI 융합 전문가 과정 · 2조 Evaluation 담당 · 2026.10 ~</sub>

<img src="project-01.svg" width="100%" alt="01 조각김치 라벨링 프로그램: Golden Test 5가지 검사로 좌표 오차 1e-6 미만을 증명했습니다. 900장 정답 데이터 구축"/>

<table>
<tr><td width="96" nowrap><b>기간</b></td><td>2026.10 · 6인 팀 · 내 역할 <b>좌표 · 검증 (Coord)</b></td></tr>
<tr><td width="96" nowrap><b>수행</b></td><td>Class · BBox 기준서, 박스를 항상 <b>원본 픽셀 좌표로 저장</b>해 Zoom · Pan 오차 누적 방지 · 임시 폴더에서 돌리는 <b>Golden Test 5가지</b>(YOLO TXT 왕복 · Zoom/Pan 왕복 &lt; 1e-6 · RAW 보호 등)</td></tr>
<tr><td width="96" nowrap><b>기술</b></td><td><code>Python</code> <code>GUI</code> <code>YOLO TXT I/O</code></td></tr>
</table>

<div align="right"><a href="#top"><sub><b>↑ 맨 위로</b></sub></a></div>

<br/>

<img src="project-02.svg" width="100%" alt="02 조각김치 이물검출: 같은 촬영 묶음이 섞인 누수를 막고, Test는 한 번만 보며 YOLO 성능을 정직하게 쟀습니다."/>

<table>
<tr><td width="96" nowrap><b>기간</b></td><td>2026.10.15 ~ 10.21 · 6인 팀 · 내 역할 <b>Evaluation / Failure</b></td></tr>
<tr><td width="96" nowrap><b>핵심 성과 (팀)</b></td><td>Val mAP50-95 <b>0.345 → 0.446 (+29%)</b> · Frozen Test 75장 <b>0.412</b> (1회 평가) · 위험 이물(플라스틱 · 돌 · 금속) Precision <b>.977</b></td></tr>
<tr><td width="96" nowrap><b>문제</b></td><td>같은 이물 세트(T17_V 조각 등)가 <b>Train과 평가 데이터에 동시에</b> 들어가 성능이 부풀려져 있었습니다.</td></tr>
<tr><td width="96" nowrap><b>내 역할</b></td><td>900장을 <b>촬영 묶음 단위로 다시 Split</b> (609 / 66 / 75 / 150) → 누수 제거로 Baseline Recall .781 → .444 (부풀림 제거)<br/>Test는 <code>allow_test</code> 없으면 막히도록 <b>코드로 1회만 허용</b> · Final 모델은 Val만으로 선택</td></tr>
<tr><td width="96" nowrap><b>실패 분석</b></td><td>Baseline 놓침(FN) 82개 중 <b>73%가 작은 이물</b> → 이미지 크기 키우는 실험의 근거 · Test에서는 branch를 insect · leaf로 헷갈린 오검출이 Precision 하락 원인</td></tr>
<tr><td width="96" nowrap><b>기술</b></td><td><code>Python</code> <code>YOLO11</code> <code>Ultralytics</code> <code>mAP · P/R</code> <code>Confusion Matrix</code></td></tr>
</table>

<div align="right"><a href="#top"><sub><b>↑ 맨 위로</b></sub></a></div>

<br/>

<img src="project-03.svg" width="100%" alt="03 병뚜껑 유무 검사: 정확도보다 불량을 통과시키는 오류를 먼저 줄여, 새 사진 90% · 위험 오류 0건을 만들었습니다."/>

<table>
<tr><td width="96" nowrap><b>기간</b></td><td>2026.11.01 ~ 11.02 · 개인 · 사진 42장 (test 24 · holdout 8 · final 10)</td></tr>
<tr><td width="96" nowrap><b>결과</b></td><td>새 사진 정확도 <b>54% → 90%</b> (v1 test → v3 final) · 불량을 통과시키는 <b>NG→OK 3건 → 0건</b></td></tr>
<tr><td width="96" nowrap><b>문제</b></td><td>수업 방식(v1)은 '어두운 픽셀 양'을 재서, <b>검은 뚜껑과 어두운 사진</b>에서 틀렸습니다.</td></tr>
<tr><td width="96" nowrap><b>수행</b></td><td>버전마다 <b>실패 사진을 직접 보고 원인 확인</b> → 색과 무관한 엣지 방향 특징(세로 줄무늬 vs 가로 나사산) · 병 실루엣 기반 <b>자동 ROI</b><br/>어둡거나 기울어진 사진은 통과시키지 않고 <b>RETAKE(다시 찍기)</b>로 판정 · 폰 카메라 실시간 모드(v4~v5)</td></tr>
<tr><td width="96" nowrap><b>기술</b></td><td><code>Python</code> <code>OpenCV</code> <code>CLAHE</code> <code>Sobel</code> <code>Otsu</code> <code>Git</code></td></tr>
</table>

<div align="right"><a href="#top"><sub><b>↑ 맨 위로</b></sub></a></div>

<br/>

<img src="project-04.svg" width="100%" alt="04 이어팁 유무 검사: 전처리 26가지 비교 후 ROI 재설계로 판정 margin 0에서 0.23"/>

<table>
<tr><td width="96" nowrap><b>기간</b></td><td>2026.10.26 · 개인 · Mini Challenge</td></tr>
<tr><td width="96" nowrap><b>수행</b></td><td>전처리 26가지 비교(param sweep) → 차이 최대 +0.003 · 본체 가장자리를 일부러 포함한 <b>ROI 재설계</b>로 팁 유무 분리 · 가장 단순한 Gaussian 5×5 선택</td></tr>
<tr><td width="96" nowrap><b>기술</b></td><td><code>OpenCV</code> <code>Otsu</code> <code>ROI</code></td></tr>
</table>

<a href="https://github.com/HanaPark-lab/eartip-inspection"><img src="https://img.shields.io/badge/Repository-16323F?style=flat-square&logo=github" alt="repository"/></a>

<div align="right"><a href="#top"><sub><b>↑ 맨 위로</b></sub></a></div>

<br/>

<img src="project-05.svg" width="100%" alt="05 콩잎 병해 분류 + 비동기 서빙: ResNet-18을 Fine-tuning하고, 자신 없는 판정은 보류하는 안전장치와 함께 서비스로 띄웠습니다."/>

<table>
<tr><td width="96" nowrap><b>기간</b></td><td>2026.11.04 ~ 11.05 · 개인</td></tr>
<tr><td width="96" nowrap><b>결과</b></td><td>Val <b>0.7669 → 1.0</b> (Head-only → Full + 증강) · Test 128장 <b>0.9453</b> (1회) · 병 → 정상 오류 <b>0건</b><br/>멀리 찍은 사진(0.4배) 정확도 <b>0.384 → 0.895</b></td></tr>
<tr><td width="96" nowrap><b>판단</b></td><td>Test가 2.35%p 낮아도 E6를 서빙 모델로 선택 — 틀린 7장이 모두 점수 &lt; 0.9라 <b>보류(R1)로 걸러지기</b> 때문 · Grad-CAM으로 근거가 잎의 병반에 모이는지 확인 · 콩잎이 아닌 사진은 <b>특징 거리로 경고</b></td></tr>
<tr><td width="96" nowrap><b>서비스</b></td><td>FastAPI → Redis 캐시 → Celery 워커 → PostgreSQL 이력, <b>Docker Compose</b> · 동기 27.8ms / 캐시 HIT 3.1ms · pytest 6 passed</td></tr>
<tr><td width="96" nowrap><b>기술</b></td><td><code>PyTorch</code> <code>Hugging Face</code> <code>ResNet-18</code> <code>Grad-CAM</code> <code>FastAPI</code> <code>Celery</code> <code>Redis</code> <code>PostgreSQL</code> <code>Docker</code></td></tr>
</table>

<div align="right"><a href="#top"><sub><b>↑ 맨 위로</b></sub></a></div>

<br/>

<img src="project-06.svg" width="100%" alt="06 바른품 돌봄 동작 코치: OK/NG 기준과 3D 모캡 촬영 계획, 172컷 촬영 콘티"/>

<table>
<tr><td width="96" nowrap><b>기간</b></td><td>2026.11.08 ~ 진행 중 · 6인 팀 · 내 역할 <b>현장 사진 · 기획 문서</b></td></tr>
<tr><td width="96" nowrap><b>수행</b></td><td>10가지 돌봄 · 응급 동작(영아 CPR, 수유 → 트림 등) 촬영 콘티 · Take 규칙 · OK / NG 기준 · 현장 체크리스트</td></tr>
<tr><td width="96" nowrap><b>기술</b></td><td><code>VICON</code> <code>YOLO Pose (예정)</code></td></tr>
</table>

<div align="right"><a href="#top"><sub><b>↑ 맨 위로</b></sub></a></div>

<br/>

### 🧪 Other Projects

<sub>[어디서 진행한 프로젝트인지: 예) 박사과정 연구실 / 개인 / 공모전]</sub>

<img src="project-07.svg" width="100%" alt="07 김 감염률 측정기"/>

<table>
<tr><td width="96" nowrap><b>기간</b></td><td>[YYYY.MM ~ YYYY.MM] · [개인 / N인 팀] · 내 역할 <b>[역할]</b></td></tr>
<tr><td width="96" nowrap><b>문제</b></td><td>[어떤 문제를 풀려고 만들었는지]</td></tr>
<tr><td width="96" nowrap><b>수행</b></td><td>[무엇을 어떻게 만들었는지]</td></tr>
<tr><td width="96" nowrap><b>결과</b></td><td>[숫자로 보여줄 결과]</td></tr>
<tr><td width="96" nowrap><b>기술</b></td><td><code>[기술]</code></td></tr>
</table>

<div align="right"><a href="#top"><sub><b>↑ 맨 위로</b></sub></a></div>

<br/>

<img src="project-08.svg" width="100%" alt="08 바다마중 앱 개발"/>

<table>
<tr><td width="96" nowrap><b>기간</b></td><td>[YYYY.MM ~ YYYY.MM] · [개인 / N인 팀] · 내 역할 <b>[역할]</b></td></tr>
<tr><td width="96" nowrap><b>문제</b></td><td>[어떤 문제를 풀려고 만들었는지]</td></tr>
<tr><td width="96" nowrap><b>수행</b></td><td>[무엇을 어떻게 만들었는지]</td></tr>
<tr><td width="96" nowrap><b>결과</b></td><td>[숫자로 보여줄 결과]</td></tr>
<tr><td width="96" nowrap><b>기술</b></td><td><code>[기술]</code></td></tr>
</table>

<div align="right"><a href="#top"><sub><b>↑ 맨 위로</b></sub></a></div>

<br/>

## 🎯 What I Do

| 영역 | 해 본 것 |
| :--- | :--- |
| **🌿 Bio Research** | 해조류(김) 배양 · 생장 · 병해 연구, 배양 조건 실험 설계와 3.6톤 규모 실증, 배지 비용 분석 |
| **📡 Field Data** | 센서 · 영상 수집 시스템 기획 · 관리(수질 10초 기록, 카메라 7대), pH · 오염도 상관분석 |
| **📏 Data · Evaluation** | 촬영 묶음 단위 Split, Test 1회 평가 규칙, Class별 P/R · 실패 유형(FN · FP · CLASS · BBOX) 분석 |
| **👁️ Machine Vision** | OpenCV Rule 검사 (CLAHE · Sobel · Otsu), 자동 ROI, RETAKE 판정 |
| **🤖 Deep Learning** | 객체 검출 (YOLO11), 분류 Fine-tuning (ResNet-18), Grad-CAM |
| **⚙️ Model Serving** | FastAPI · Redis 캐시 · Celery 비동기 작업 · PostgreSQL 기록 · Docker Compose |
| **🧍 3D · Pose** | VICON 모캡 촬영 기획, 동작별 OK / NG 기준 설계 |
| **📝 R&amp;D · Documentation** | 국책과제 제안 · KPI 관리, 라벨 기준서, 실패 분석 보고서, README |

<div align="right"><a href="#top"><sub><b>↑ 맨 위로</b></sub></a></div>

<br/>

## 🔄 How I Work

<p align="center"><img src="how-i-work.svg" width="100%" alt="End-to-End Project Flow: DEFINE 기준 → SPLIT 데이터 → BUILD 모델 → EVALUATE 평가 → SHIP 서빙, 실패 사례를 다음 기준에 반영"/></p>

<sub>모델을 만들기 전에 <b>무엇을 OK / NG로 볼지</b>와 <b>데이터를 어떻게 나눌지</b>부터 정하고, 평가 후에는 <b>틀린 사진을 직접 보며</b> 찾은 원인을 다음 버전의 기준에 반영합니다.</sub>

| 원칙 | 실제로 한 것 |
| :--- | :--- |
| **🧩 같은 촬영 묶음은 쪼개지 않는다** | 누수를 막으려 Split을 묶음 단위로 다시 짬 (02) |
| **🔒 Test는 한 번만 본다** | Val로 고르고 Test는 1회, 코드로 막음 (`allow_test`, 덮어쓰기 금지) |
| **📸 기준을 정한 사진으로 성능을 말하지 않는다** | 매번 새 사진(holdout · final)으로 보고 (03, 04) |
| **⚠️ 위험한 오류부터 줄인다** | 불량을 통과시키는 NG→OK, 병을 정상으로 보는 오류를 먼저 셈 (03, 05) |

<div align="right"><a href="#top"><sub><b>↑ 맨 위로</b></sub></a></div>

<br/>

## 🛠 Tech Stack

<div align="center">

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black) ![YOLO11](https://img.shields.io/badge/YOLO11-111F68?style=flat-square&logo=yolo&logoColor=white) ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Celery](https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
<br/>
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white) ![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white)

<sub>AI · Vision · Serving &nbsp;&nbsp;|&nbsp;&nbsp; Language · Deploy · Collaboration</sub>

</div>

<br/>

| 분야 | 기술 |
| :--- | :--- |
| 🤖 **AI · Vision** | `PyTorch` `Hugging Face Transformers` `YOLO11 (Ultralytics)` `ResNet-18` `Grad-CAM` |
| 🏷️ **Labeling** | `Python GUI` |
| 👁️ **Machine Vision** | `OpenCV` `CLAHE` `Sobel` `Otsu` `Morphology` `GrabCut` `HSV` |
| ⚙️ **Backend · Serving** | `FastAPI` `Celery` `Redis` `PostgreSQL` |
| 📏 **Data · Evaluation** | `IoU · Dice` `mAP · P/R` `Confusion Matrix` `상관분석` `pHash · md5` `Excel` |
| 💻 **Language** | `Python` |
| ☁️ **Deploy · Test** | `Docker` `Docker Compose` `pytest` |
| 🧍 **3D · Pose** | `VICON` `YOLO Pose (예정)` |
| 🤝 **Collaboration** | `Git` `GitHub` |

<br/>

## 📚 Now Learning

- 🎓 KH정보교육원 Vision AI &amp; Vertical AI 융합 전문가 과정 (2026.10 ~)
- 📜 **ADsP** (데이터분석 준전문가) · 🐧 **리눅스마스터** 준비 중
- 🎯 다음 목표: 06 촬영 데이터로 동작 분류 · 03 실시간 재시연 · 02 병해 데이터 보강

<div align="right"><a href="#top"><sub><b>↑ 맨 위로</b></sub></a></div>

<br/>

## 📫 Contact

<div align="center">

[![Email](https://img.shields.io/badge/Email-1E4E63?style=flat-square&logo=gmail&logoColor=white)](mailto:gksk9063@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/HanaPark-lab)

</div>
