# fa06-1st-
- KPMG Future Academy 6기 1조 1차 프로젝트 기획안입니다.

-------------------
# 프로젝트 기획서

## 1. 프로젝트 개요
- **프로젝트 기간**: 2025-08-11 ~ 2024-08-18
- **팀 명**: 얼마고 (Eolma-Go)
- **참여 인원**: 송유선, 유병욱, 임은아

## 2. 프로젝트 일정
| 작업 항목                  | 시작 날짜   | 종료 날짜   | 기간(일) |
|---------------------------|------------|------------|---------|
| 프로젝트 기획 | 2025-08-11| 2025-08-12| 2       |
| 기능 정의 및 시나리오 작성| 2025-08-11| 2025-08-13 | 2       |
| 자료 조사 및 벤치마킹       | 2025-08-12 | 2025-08-14 | 2     |
| 요구사항 도출 및 WBS 작성   | 2025-08-13 | 2025-08-14 | 1       |
| 기획서 및 발표 자료 제작             | 2025-08-14 | 2025-08-18 | 4      |
| 최종 피드백 및 프로젝트 발표  | 2025-08-17 | 2025-08-18 | 1       |
<img width="514" height="265" alt="image" src="https://github.com/user-attachments/assets/ad197367-f1c6-44b6-8315-57e4cb0c5c89" />



## 3. 프로젝트 주제
**[AI 기반 재래시장 내 품목 적정가 예측 서비스]**
- 목표: **AX/DX를 통한 전통시장 시세 및 종합 정보 플랫폼 구축**

## 4. 문제 정의 및 목적
- 전통 시장에 대한 소비자들의 신뢰도를 회복할 수 있을까?
- 외국인들의 정보 비대칭 문제를 해결할 수 없을까?
- 분산된 전통 시장에 대한 정보를 한 번에 찾아볼 수 없을까?

### 1) 가격 신뢰도 문제 해결
- **문제**: 바가지 요금에 대한 불신, 가격 표준 정보 접근성 낮음.
- **해결방안**
    - 정부 데이터(농수산물 시세, 크롤링) + 유저 제보 가격 데이터를 결합해 평균가·적정가 제시.

### 2) 부대시설·편의 정보 부족 해결
- **문제**: 화장실, 휴게 공간, ATM, 주차장 등 편의 시설 정보 부재로 불편.
- **해결방안**
    - **데이터 분석**
        - 시장 내 상점·편의 시설 위치 데이터 구축.
        - 위치기반 분석으로 방문객 동선과 편의시설 접근성 매핑.
    - **기술적 구현**
        - GPS 기반 전통시장 특화 지도에 부대시설 표시.
        - 실시간 길찾기, 혼잡도 안내 기능 추가.

### 3) 정보 비대칭 해소
- **문제**: 외국인·2030 세대가 시장 정보를 사전에 확인하기 어려움.
- **해결방안**
    - **UI 기획**
        - 시세 정보, 리뷰, 편의시설, 이벤트, 인기 메뉴 등을 통합한 모바일 UI 설계.
        - 다국어 지원(한국어·영어·중국어·일본어)로 외국인 접근성 강화.
    - **추가 기능**
        - 위치 기반 점포 검색, 리뷰 작성, 가격 제보 API 개발.
        - SNS 공유 기능을 통해 바이럴 마케팅 유도.
    
### 4) 전통시장 활성화
- **문제**: 젊은 층·외국인 방문 증가세를 지속·확대해야 함.
- **해결방안**
    - **유튜브·인스타그램 인플루언서 마케팅**
        - 전통시장 체험 콘텐츠 제작, QR 코드와 서비스 연계 홍보.
    - **관광객 주요 동선 광고**
        - 관광객 유동 인구가 집중된 공항·지하철·환전소 등에서 서비스 홍보 → 전통시장 방문 유도
  
## 5. 핵심 타겟 및 주요 기능
<img width="7260" height="3476" alt="1차 프로젝트 (4)" src="https://github.com/user-attachments/assets/7553320c-19da-4bc7-91d9-7131832e8a77" />


-> 데이터 기반 시계열 예측을 통한 **품목 적정가 산정** 사용자 참여 오픈소스 생태계


# 작업 분할 구조 (WBS)
- 1차 프로젝트 수행을 위한 WBS 작성
[Uploading gantt.html…]()<YPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>프로젝트 WBS 간트 차트 시각화</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@400;500;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Noto Sans KR', sans-serif;
            background-color: #f8fafc; /* bg-gray-50 */
            color: #1e293b; /* text-slate-800 */
        }
        /* 커스텀 스크롤바 */
        ::-webkit-scrollbar {
            width: 8px;
            height: 8px;
        }
        ::-webkit-scrollbar-track {
            background: #e2e8f0;
        }
        ::-webkit-scrollbar-thumb {
            background: #94a3b8;
            border-radius: 10px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #64748b;
        }
        /* 그리드 라인 스타일 */
        .gantt-grid-bg {
            background-size: calc(100% / 8) 100%; /* 8일 기준 */
            background-image: linear-gradient(to right, #e2e8f0 1px, transparent 1px);
        }
        .task-bar-popup {
            opacity: 0;
            visibility: hidden;
            transition: opacity 0.2s ease, visibility 0.2s ease, transform 0.2s ease;
            position: absolute;
            bottom: 105%;
            left: 50%;
            transform: translateX(-50%) translateY(5px);
            min-width: 250px;
            z-index: 20;
        }
        .task-bar:hover .task-bar-popup {
            opacity: 1;
            visibility: visible;
            transform: translateX(-50%) translateY(0);
        }
    </style>
</head>
<body class="p-4 sm:p-6 md:p-10">

    <div class="max-w-screen-xl mx-auto">
        <header class="mb-10 text-center">
            <h1 class="text-3xl sm:text-4xl font-bold text-slate-800">전통시장 활성화 서비스 프로젝트 WBS</h1>
            <p class="text-slate-500 mt-2">날짜 기반 타임라인으로 시각화한 프로젝트 작업 구조입니다.</p>
        </header>

        <!-- 간트 차트 컨테이너 -->
        <div class="bg-white rounded-xl shadow-lg overflow-hidden border border-slate-200">
            <div id="gantt-chart-container" class="overflow-x-auto">
                <!-- WBS 데이터가 동적으로 채워질 영역 -->
                <div id="wbs-chart"></div>
            </div>
        </div>
    </div>

    <script>
        // --- 데이터 영역 ---
        const wbsData = [
            {
                phase: "1. 프로젝트 기획",
                tasks: [
                    { mid: "1.1 문제 정의", details: ["전통시장 문제 도출", "타겟 고객 페인포인트 분석"], output: "프로젝트 기획서", startDate: "2025-08-11", endDate: "2025-08-12" },
                    { mid: "1.2 목표 및 범위 설정", details: ["서비스 목적·기대효과 명확화", "기능 범위 정의"], output: "프로젝트 기획서", startDate: "2025-08-11", endDate: "2025-08-12" },
                    { mid: "1.3 일정 계획", details: ["Gantt 차트 작성", "주요 마일스톤 설정"], output: "프로젝트 일정표", startDate: "2025-08-11", endDate: "2025-08-12" }
                ]
            },
            {
                phase: "2. 기능 정의 및 시나리오",
                tasks: [
                    { mid: "2.1 핵심 기능 도출", details: ["GPS, 시세 조회, 리뷰, 다국어 등"], output: "프로젝트 기획서", startDate: "2025-08-11", endDate: "2025-08-13" },
                    { mid: "2.2 사용자 페르소나 시나리오", details: ["사용자 유형별 시나리오 작성"], output: "프로젝트 기획서", startDate: "2025-08-11", endDate: "2025-08-13" }
                ]
            },
            {
                phase: "3. 자료 조사 및 벤치마킹",
                tasks: [
                    { mid: "3.1 데이터 조사", details: ["농수산물 시세 데이터", "전통시장 시설 정보"], output: "데이터 수집 리포트", startDate: "2025-08-12", endDate: "2025-08-14" },
                    { mid: "3.2 경쟁 서비스 분석", details: ["유사 앱, 지도 서비스 분석"], output: "프로젝트 기획서", startDate: "2025-08-12", endDate: "2025-08-13" }
                ]
            },
            {
                phase: "4. 요구사항 및 WBS",
                tasks: [
                    { mid: "4.1 기능 요구사항", details: ["사용자·시스템·성능 요구사항 정리"], output: "요구사항 정의서", startDate: "2025-08-13", endDate: "2025-08-14" },
                    { mid: "4.2 비기능 요구사항", details: ["보안, 데이터 정확도, 응답 속도 등"], output: "요구사항 정의서", startDate: "2025-08-13", endDate: "2025-08-14" }
                ]
            },
            {
                phase: "5. UI/UX 설계",
                tasks: [
                    { mid: "5.1 화면 기획", details: ["주요 화면 설계"], output: "와이어프레임", startDate: "2025-08-13", endDate: "2025-08-14" },
                    { mid: "5.2 UX 플로우", details: ["서비스 흐름 제시"], output: "프로젝트 설계서", startDate: "2025-08-13", endDate: "2025-08-14" }
                ]
            },
            {
                phase: "6. 기술 설계",
                tasks: [
                    { mid: "6.1 데이터 처리 구조", details: ["데이터 결합 구조 설계"], output: "프로젝트 설계서", startDate: "2025-08-14", endDate: "2025-08-15" },
                    { mid: "6.2 API 설계", details: ["Open API, 지도 플랫폼, 번역 API"], output: "프로젝트 기획서", startDate: "2025-08-14", endDate: "2025-08-15" }
                ]
            },
            {
                phase: "7. 마케팅 및 홍보",
                tasks: [
                    { mid: "7.1 오프라인 홍보", details: ["배너 홍보"], output: "홍보물 디자인", startDate: "2025-08-15", endDate: "2025-08-18" },
                    { mid: "7.2 온라인 홍보", details: ["인플루언서 마케팅", "SNS 공유 기능"], output: "프로젝트 기획서", startDate: "2025-08-15", endDate: "2025-08-18" }
                ]
            },
            {
                phase: "8. 최종 피드백 및 발표",
                tasks: [
                    { mid: "8.1 중간 점검", details: ["중간 결과 공유, 피드백 수렴"], output: "기획서 반영", startDate: "2025-08-13", endDate: "2025-08-18" },
                    { mid: "8.2 최종 발표", details: ["서비스 개념 및 기획 발표"], output: "최종 발표 장표", startDate: "2025-08-17", endDate: "2025-08-18" }
                ]
            }
        ];

        // --- 렌더링 로직 ---
        const chartContainer = document.getElementById('wbs-chart');
        const projectStartDate = new Date("2025-08-11");
        const projectEndDate = new Date("2025-08-18");

        const dateDiffInDays = (a, b) => {
            const _MS_PER_DAY = 1000 * 60 * 60 * 24;
            const utc1 = Date.UTC(a.getFullYear(), a.getMonth(), a.getDate());
            const utc2 = Date.UTC(b.getFullYear(), b.getMonth(), b.getDate());
            return Math.floor((utc2 - utc1) / _MS_PER_DAY);
        };

        const totalDays = dateDiffInDays(projectStartDate, projectEndDate) + 1;
        
        const colors = [
            '#34d399', '#22d3ee', '#60a5fa', '#a78bfa',
            '#f472b6', '#fb923c', '#facc15', '#a3e635'
        ];

        let chartHTML = '';

        // 1. 타임라인 헤더 생성
        let dateHeaderHTML = '';
        for (let i = 0; i < totalDays; i++) {
            const currentDate = new Date(projectStartDate);
            currentDate.setDate(projectStartDate.getDate() + i);
            const day = ['일', '월', '화', '수', '목', '금', '토'][currentDate.getDay()];
            dateHeaderHTML += `<div class="text-center p-2 text-sm font-medium text-slate-500">
                <div class="text-xs">${day}</div>
                <div>${currentDate.getDate()}</div>
            </div>`;
        }
        
        chartHTML += `
            <div class="min-w-[1000px]">
                <!-- Header Row -->
                <div class="sticky top-0 bg-white/70 backdrop-blur-sm z-10 grid" style="grid-template-columns: minmax(200px, 25%) 1fr;">
                    <div class="p-2 font-bold text-slate-700 text-center border-r border-b border-slate-200 flex items-center justify-center">작업</div>
                    <div class="grid border-b border-slate-200" style="grid-template-columns: repeat(${totalDays}, 1fr);">
                        ${dateHeaderHTML}
                    </div>
                </div>

                <!-- Data Rows -->
        `;

        // 2. WBS 데이터 기반 행 생성
        wbsData.forEach((phase, phaseIndex) => {
            chartHTML += `
                <div class="grid" style="grid-template-columns: minmax(200px, 25%) 1fr;">
                    <div class="col-span-full bg-slate-100 font-bold p-2 text-slate-600 border-b border-t border-slate-200">
                        ${phase.phase}
                    </div>
                </div>
            `;
            
            phase.tasks.forEach(task => {
                const taskStartDate = new Date(task.startDate);
                const taskEndDate = new Date(task.endDate);
                const startDay = dateDiffInDays(projectStartDate, taskStartDate); // 0-indexed
                const duration = dateDiffInDays(taskStartDate, taskEndDate) + 1;
                const taskBarColor = colors[phaseIndex % colors.length];

                chartHTML += `
                    <div class="grid border-b border-slate-200" style="grid-template-columns: minmax(200px, 25%) 1fr;">
                        <!-- Task Name Column -->
                        <div class="p-3 text-sm border-r border-slate-200 truncate flex items-center min-h-[50px]">${task.mid}</div>
                        
                        <!-- Timeline Column which is a grid itself -->
                        <div class="relative grid gantt-grid-bg" style="grid-template-columns: repeat(${totalDays}, 1fr);">
                            <!-- Task Bar positioned on the timeline grid -->
                            <div class="task-bar relative p-1 h-full" style="grid-column: ${startDay + 1} / span ${duration};">
                                <div class="relative w-full h-full rounded-md flex items-center justify-start px-3 text-white font-semibold text-sm shadow-md" style="background-color: ${taskBarColor};">
                                    <span class="truncate">${task.mid}</span>
                                </div>
                                <!-- Hover Popup -->
                                <div class="task-bar-popup bg-slate-800 text-white p-3 rounded-lg shadow-xl w-max">
                                     <h4 class="font-bold text-base">${task.mid}</h4>
                                     <p class="text-xs text-slate-400 mb-2">${task.startDate} ~ ${task.endDate}</p>
                                     <ul class="list-disc list-inside text-sm text-slate-300 space-y-1">
                                         ${task.details.map(detail => `<li>${detail}</li>`).join('')}
                                     </ul>
                                     <div class="mt-2 text-right">
                                         <span class="inline-block bg-white/20 text-white text-xs font-semibold px-2 py-1 rounded-full">
                                            산출물: ${task.output}
                                         </span>
                                     </div>
                                </div>
                            </div>
                        </div>
                    </div>
                `;
            });
        });
        
        chartHTML += `</div>`;

        chartContainer.innerHTML = chartHTML;
    </script>
</body>
</html>




  ------------------------------

# 요구사항 정의서

## **전통시장 종합 가이드라인 플랫폼 - “얼마고” 요구사항 정의서**

### **1. 기능 요구사항**

### **핵심 서비스 기능**

- **GPS 기반 정보 제공:** 앱 접속 시 사용자의 현재 위치를 기반으로 주변 전통시장 정보, 시장 내 메인 점포 위치, 길찾기 등 노출 / 지도 플랫폼과 연계된 기능을 제공
- **시세 조회:** Open API를 통해 수집된 데이터를 바탕으로, 메인 화면을 통해 특정 시장 조회 시 시장별/품목별 시세 정보를 조회하고 비교할 수 있는 기능을 제공 -> 직접 검색과 터치 방식으로 기능 이원화
- **리뷰 기능:** 더콜, 후후를 벤치마킹해 사용자가 직접 자신이 경험한 해당 점포의 가격을 적시, 넘어서 사용자가 특정 시장이나 점포에 대한 경험을 텍스트와 사진 등으로 공유하고, 다른 사람의 리뷰를 조회할 수 있는 기능을 제공
- **다국어 지원:** 번역 API를 활용하여 외국인 관광객 등 다양한 사용자를 위해 한국어 외 영어, 중국어, 일본어 등의 언어를 지원해 접근성 제고

### **데이터 관련 기능**

- **데이터 수집:** 농수산물 시세 데이터 및 전통시장 시설 정보(주차장, 화장실 등)를 공공데이터 Open API와 데이터 크롤링, 사용자 생성 데이터를 통해 주기적으로 수집
- **데이터 처리:** 수집된 다양한 데이터를 서비스 목적에 맞게 결합하고 가공하여 설계 (pandas 라이브러리 활용)

### **사용자 편의 기능**

- **SNS 공유:** 서비스 내의 유용한 정보(예: 특정 상품의 최저가 정보, 추천 시장 등)를 사용자의 소셜 미디어(SNS) 계정으로 공유할 수 있는 기능을 제공
- **직관적인 UI/UX:** 사용자 페르소나 및 시나리오를 바탕으로 와이어프레임과 UX 플로우를 설계하여 누구나 쉽게 서비스를 이용할 수 있도록 함

### **2. 비기능 요구사항**

- **성능 (Performance):** 사용자의 검색 요청이나 페이지 이동 시 3초 이내에 응답하여 빠른 서비스 이용 경험을 제공 (응답 속도)
- **데이터 정확성 (Data Accuracy):** 제공되는 모든 정보, 특히 변동성이 큰 품목의 시세 데이터는 잦은 업데이트와 정확성을 유지해야 함
- **보안 (Security):** 사용자 정보(리뷰 작성자 등)를 안전하게 보호하고, 외부 공격으로부터 시스템을 보호할 수 있는 기본적인 보안 체계를 갖추어야 함
- **시스템 안정성 (System Stability):** 서비스 이용 중 데이터 처리 오류나 시스템 다운이 최소화되어야 하며, 장애 발생 시 신속하게 복구할 수 있어야 함
- **확장성 (Scalability):** 향후 결제 시스템 연동, 배달 서비스 추가 등 새로운 기능을 도입하거나 더 많은 종류의 데이터를 추가할 때 유연하게 확장할 수 있는 구조로 설계되어야 함
- **사용성 (Usability):** IT 기기 사용에 익숙하지 않은 사용자를 포함하여, 다양한 사용자 유형이 별도의 학습 없이 직관적으로 서비스를 이용할 수 있어야 함(UI 관련)

----------------------------

# 프로젝트 설계서

## **전통시장 종합 가이드라인 플랫폼 “얼마고” - 프로젝트 설계서**

### **1. 시스템 아키텍처**

- **데이터 수집 워크패키지**
    - **역할:** 서비스에 필요한 모든 원천 데이터를 수집하는 역할을 담당
    - **세부 기능:**
        - **API 연동:** 정부 및 공공기관에서 제공하는 농수산물 가격 정보, 전통시장 기본 정보(위치, 시설 등) Open API를 주기적으로 호출하여 데이터 수집
        - **웹 크롤링:** API로 제공되지 않는 특정 시장의 가격 정보나 이벤트 정보를 얻기 위해, 웹 크롤러(Python, Selenium/BeautifulSoup)를 이용해 대상 웹사이트의 데이터 수집
        - **사용자 생성 데이터 수집:** 사용자가 앱을 통해 직접 입력하는 리뷰, 사진, 가격 정보를 오픈 소스로 수집
- **데이터 전처리 워크패키지**
    - **역할:** 수집된 다양한 형태의 Raw 데이터를 정제하고 결합하여 서비스에 즉시 사용 가능한 형태로 가공
    - **세부 기능:**
        - **데이터 정제(Cleansing):** 수집된 데이터의 결측치, 이상치, 중복 값을 식별하고 처리합니다.
        - **데이터 통합(Integration):** API, 크롤링, 사용자 입력 등 각기 다른 출처의 데이터를 `market_id`, `product_id` 등을 기준으로 통합 (Pandas 라이브러리 활용)
        - **데이터 변환(Transformation):** 통합된 데이터를 분석 및 서비스 제공에 적합한 구조로 변환해 자체 데이터베이스에 저장

### **2. 데이터 설계**

- **데이터 흐름**
    - **원천 데이터 → 전처리 → 데이터베이스 → 서버 → 클라이언트**
        1. **[원천 데이터]** 공공 API, 웹사이트, 사용자 입력을 통해 정형/반정형/비정형 데이터를 수집
        2. **[전처리]** 수집된 데이터를 Pandas 등을 활용해 정제 및 통합하여 분석 가능한 형태로 가공
        3. **[데이터베이스]** 가공된 데이터를 PostgreSQL 같은 구조화된 데이터베이스에 저장
        4. **[서버]** 클라이언트의 요청에 따라 데이터베이스의 정보를 조회/가공
        5. **[클라이언트]** 서버로부터 받은 데이터를 지도, 차트, 리스트 형태로 사용자에게 시각화하여 보여줌
- **주요 데이터 속성**

| 속성 이름 (예시) | 데이터 유형 | 설명 |
| --- | --- | --- |
| `market_id`, `market_name`, `address`, `gps_coordinates`, `facility_info` | 정형 | 시장의 고유 ID, 이름, 주소, GPS 좌표, 편의시설 정보 |
| `product_id`, `product_name`, `category` | 정형 | 품목의 고유 ID, 이름, 카테고리 (농산물, 수산물 등) |
| `price_id`, `market_id`, `product_id`, `price_value`, `timestamp` | 정형 | 특정 시장/품목의 가격 정보 및 기준 시각 |
| `user_id`, `nickname`, `auth_info` | 정형 | 사용자의 고유 ID, 닉네임, 인증 정보 |
| `review_id`, `user_id`, `content_text`, `photo_url`, `reported_price` | 반정형 | 리뷰의 고유 ID, 작성자, 텍스트, 사진 경로, 사용자가 제보한 가격 |

### **3. 기술 스택(초안)**

| 구분 | 기술 | 목적 |
| --- | --- | --- |
| **프론트엔드 (Client)** | React Native, Expo | iOS/Android 크로스플랫폼 앱 개발 |
|  | Google Maps API / Naver Maps API | GPS 기반 정보 제공 및 길찾기 기능 구현 |
| **백엔드 (Server)** | Python, Django / Flask | 안정적인 API 서버 및 비즈니스 로직 개발 |
| **데이터 수집** | Python, Selenium, BeautifulSoup, Requests | 웹 크롤링 및 API 연동 |
| **데이터 처리/분석** | Pandas, NumPy | 수집된 데이터의 효율적인 정제, 통합, 가공 |
| **데이터베이스** | PostgreSQL (+PostGIS) | 데이터의 안정적 저장 및 효율적인 위치 기반 쿼리 처리 |
| **인프라/배포** | AWS / GCP, Docker | 확장성 있고 유연한 서비스 배포 및 운영 |

### **4. 예상 문제 및 해결 방안**

- **문제 1: 데이터의 부정확성 및 실시간성 부재**
    - **상세:** 공공 API의 업데이트 지연, 크롤링 오류, 악의적인 사용자 제보 등으로 인해 시세 정보가 실제와 다를 수 있음 → 서비스 신뢰도에 치명적
    - **해결 방안:**
        - **교차 검증:** 여러 출처(API, 크롤링, 사용자 제보)의 데이터를 비교하여 이상치를 고빈도로 탐지하고 필터링
        - **신뢰도 시스템:** 정확한 가격 정보를 자주 제보하는 사용자의 글에 추천/비추천 제도를 도입해 특정 가격의 가중치를 조정하는 신뢰도 모델 도입
- **문제 2: 저품질 및 악성 리뷰/가격 정보**
    - **상세:** 광고성, 비방성, 허위 리뷰나 가격 정보가 등록되어 서비스의 유용성을 저해할 수 있음
    - **해결 방안:**
        - **리뷰 모니터링:** 부적절한 단어를 감지하는 필터를 적용하고, 사용자 신고(flagging) 기능을 도입하여 커뮤니티가 자정작용을 할 수 있도록 유도합니다.


