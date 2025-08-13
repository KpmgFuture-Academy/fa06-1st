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
| 문제 정의 | 2025-08-11| 2025-08-12| 2       |
| 기능 정의 및 시나리오 작성| 2025-08-11| 2025-08-13 | 2       |
| 자료 조사 및 벤치마킹       | 2025-08-12 | 2025-08-14 | 2     |
| 요구사항 도출 및 WBS 작성   | 2025-08-13 | 2025-08-14 | 1       |
| 기획서 및 발표 자료 제작             | 2025-08-14 | 2025-08-18 | 4      |
| 최종 피드백 및 프로젝트 발표  | 2025-08-17 | 2025-08-18 | 1       |
<img width="2961" height="1712" alt="1차 프로젝트 (1)" src="https://github.com/user-attachments/assets/a0fce72f-1ec2-4cc8-b105-70a74bb536e8" />


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
<img width="7572" height="3476" alt="1차 프로젝트" src="https://github.com/user-attachments/assets/142ab81c-b10c-4819-be25-6308e81a2973" />
-> 데이터 기반 시계열 예측을 통한 **품목 적정가 산정** 사용자 참여 오픈소스 생태계


# 작업 분할 구조 (WBS)
- 2차 프로젝트 수행을 위한 WBS 작성

## 1. 단계별 작업 구성
### 1. 기획
1.1. 문제 정의
1.2. 데이터 요구사항 정의

### 2. 데이터 수집 및 준비
2.1. 데이터 소스 조사  
2.2. 데이터 수집 및 저장  
2.3. 데이터 전처리

### 3. 데이터 분석 및 모델링
3.1. 데이터 탐색 및 시각화  
3.2. 모델 선택 및 학습  
3.3. 성능 평가  

### 4. 결과 도출 및 보고
4.1. 결과 요약  
4.2. 보고서 작성  
4.3. 최종 발표

  ------------------------------

# 요구사항 정의서

## 1. 기능 요구사항
- [ ] 데이터 수집 기능: [수집 대상 및 방식]
- [ ] 데이터 전처리 기능: [결측치 처리, 이상치 제거 등]
- [ ] 분석 기능: [사용할 알고리즘 또는 분석 기법]
- [ ] 시각화 기능: [대시보드, 차트, 그래프]

## 2. 비기능 요구사항
- [ ] 시스템 안정성: 데이터 처리 시 오류 발생 최소화
- [ ] 성능: 데이터 처리 및 분석 시간 최소화
- [ ] 확장성: 새로운 데이터 추가 및 확장 가능

----------------------------

# 프로젝트 설계서

## 1. 시스템 아키텍처
- **구성 요소**:
  - 데이터 수집 모듈
  - 데이터 전처리 모듈
  - 데이터 분석 및 시각화 모듈

## 2. 데이터 설계
- **데이터 흐름**: 원천 데이터 → 전처리 → 분석 → 결과
- **주요 데이터 속성**:
  - 속성 이름: [예: user_id, timestamp, value]
  - 데이터 유형: [정형, 반정형, 비정형]

## 3. 기술 스택
- **데이터 수집**: Python, Selenium, API 활용
- **분석**: Pandas, NumPy, Scikit-learn
- **시각화**: Matplotlib, Seaborn, Plotly

## 4. 예상 문제 및 해결 방안
- **문제**: 데이터 불균형  
  **해결 방안**: SMOTE 기법 활용

  <!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>프로젝트 WBS 시각화</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@400;500;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Noto Sans KR', sans-serif;
        }
        /* 커스텀 스크롤바 (선택 사항) */
        ::-webkit-scrollbar {
            width: 8px;
        }
        ::-webkit-scrollbar-track {
            background: #2d3748;
        }
        ::-webkit-scrollbar-thumb {
            background: #4a5568;
            border-radius: 10px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #718096;
        }
    </style>
</head>
<body class="bg-gray-900 text-white p-4 sm:p-6 md:p-10">

    <div class="max-w-7xl mx-auto">
        <header class="mb-10 text-center">
            <h1 class="text-3xl sm:text-4xl font-bold text-cyan-400">전통시장 활성화 서비스 프로젝트 WBS</h1>
            <p class="text-gray-400 mt-2">프로젝트 전체 구조를 단계별로 시각화한 자료입니다.</p>
        </header>

        <!-- WBS 데이터 -->
        <div id="wbs-container" class="space-y-8">
            <!-- 각 단계는 이 템플릿을 사용하여 동적으로 생성됩니다. -->
        </div>
    </div>

    <script>
        const wbsData = [
            {
                phase: "1. 프로젝트 기획",
                tasks: [
                    {
                        mid: "1.1 문제 정의",
                        details: ["전통시장 내 가격 신뢰도, 부대시설 정보 부족, 정보 비대칭 문제 도출", "타겟 고객군(2030, 장년층, 외국인)별 페인포인트 분석"],
                        output: "문제 정의서"
                    },
                    {
                        mid: "1.2 목표 및 범위 설정",
                        details: ["서비스 목적·기대효과 명확화", "서비스 기능 범위 정의"],
                        output: "프로젝트 범위 문서"
                    },
                    {
                        mid: "1.3 일정 계획",
                        details: ["Gantt 차트 작성", "주요 마일스톤 설정"],
                        output: "프로젝트 일정표"
                    }
                ]
            },
            {
                phase: "2. 기능 정의 및 시나리오 작성",
                tasks: [
                    {
                        mid: "2.1 핵심 기능 도출",
                        details: ["GPS 기반 점포 검색, 시세 조회, 리뷰/제보 기능, 다국어 지원, 부대시설 안내"],
                        output: "기능 목록서"
                    },
                    {
                        mid: "2.2 사용자 시나리오",
                        details: ["2030, 장년층, 외국인 유형별 사용 시나리오 작성"],
                        output: "사용자 시나리오 문서"
                    }
                ]
            },
            {
                phase: "3. 자료 조사 및 벤치마킹",
                tasks: [
                    {
                        mid: "3.1 공공데이터 조사",
                        details: ["농수산물·축산물 시세 데이터", "지자체 전통시장 시설 정보"],
                        output: "데이터 수집 리포트"
                    },
                    {
                        mid: "3.2 경쟁 서비스 분석",
                        details: ["유사 가격 비교 앱, 여행 정보 플랫폼, 지도 서비스 분석"],
                        output: "벤치마킹 보고서"
                    }
                ]
            },
            {
                phase: "4. 요구사항 도출 및 WBS 작성",
                tasks: [
                    {
                        mid: "4.1 기능 요구사항",
                        details: ["사용자·시스템·성능 요구사항 정리"],
                        output: "요구사항 명세서"
                    },
                    {
                        mid: "4.2 비기능 요구사항",
                        details: ["보안, 데이터 정확도, API 응답 속도 등"],
                        output: "요구사항 명세서"
                    }
                ]
            },
            {
                phase: "5. UI/UX 설계",
                tasks: [
                    {
                        mid: "5.1 화면 기획",
                        details: ["시세 검색 화면, 지도 화면, 리뷰 작성 화면 설계"],
                        output: "와이어프레임"
                    },
                    {
                        mid: "5.2 다국어 지원 설계",
                        details: ["한국어·영어·중국어·일본어 UI 구성"],
                        output: "다국어 UI 시안"
                    }
                ]
            },
            {
                phase: "6. 기술 설계",
                tasks: [
                    {
                        mid: "6.1 데이터 처리 구조",
                        details: ["공공데이터 + 유저 데이터 결합 구조 설계"],
                        output: "데이터 아키텍처 문서"
                    },
                    {
                        mid: "6.2 API 설계",
                        details: ["가격 조회 API, 부대시설 조회 API, 리뷰 제출 API"],
                        output: "API 명세서"
                    }
                ]
            },
            {
                phase: "7. 마케팅 및 홍보 전략",
                tasks: [
                    {
                        mid: "7.1 오프라인 홍보",
                        details: ["QR 코드 부착, 팜플렛 배포, 시장 입구 홍보"],
                        output: "홍보물 디자인"
                    },
                    {
                        mid: "7.2 온라인 홍보",
                        details: ["유튜브·인스타그램 인플루언서 마케팅", "SNS 공유 기능 활용"],
                        output: "온라인 캠페인 계획서"
                    }
                ]
            },
            {
                phase: "8. 최종 피드백 및 결과 발표",
                tasks: [
                    {
                        mid: "8.1 중간 점검",
                        details: ["중간 결과 발표, 피드백 수렴"],
                        output: "중간 보고서"
                    },
                    {
                        mid: "8.2 최종 발표",
                        details: ["서비스 개념 발표 및 시연"],
                        output: "최종 발표자료"
                    }
                ]
            }
        ];

        const container = document.getElementById('wbs-container');

        wbsData.forEach(item => {
            const phaseElement = document.createElement('div');
            phaseElement.className = 'flex flex-col md:flex-row items-start';

            // 1단계 (대분류)
            const phaseTitle = `
                <div class="w-full md:w-1/4 lg:w-1/5 mb-4 md:mb-0 md:pr-6">
                    <div class="sticky top-6 bg-gray-800 p-4 rounded-xl shadow-lg border border-gray-700">
                        <h2 class="text-xl font-bold text-cyan-300">${item.phase}</h2>
                    </div>
                </div>
            `;

            // 2단계, 3단계, 산출물
            const tasksContainer = document.createElement('div');
            tasksContainer.className = 'w-full md:w-3/4 lg:w-4/5 grid grid-cols-1 lg:grid-cols-2 gap-4';

            item.tasks.forEach(task => {
                const taskCard = `
                    <div class="bg-gray-800/50 backdrop-blur-sm p-5 rounded-lg border border-gray-700/50 transition-all duration-300 hover:border-cyan-400 hover:shadow-cyan-500/10 hover:shadow-lg">
                        <h3 class="font-bold text-lg text-gray-200">${task.mid}</h3>
                        <div class="mt-3 pl-4 border-l-2 border-gray-600">
                            <p class="text-sm font-semibold text-gray-400 mb-1">세부 작업:</p>
                            <ul class="list-disc list-inside text-gray-300 text-sm space-y-1">
                                ${task.details.map(detail => `<li>${detail}</li>`).join('')}
                            </ul>
                        </div>
                        <div class="mt-4 text-right">
                            <span class="inline-block bg-cyan-500/20 text-cyan-300 text-xs font-semibold px-3 py-1 rounded-full">
                                산출물: ${task.output}
                            </span>
                        </div>
                    </div>
                `;
                tasksContainer.innerHTML += taskCard;
            });

            phaseElement.innerHTML = phaseTitle;
            phaseElement.appendChild(tasksContainer);
            container.appendChild(phaseElement);
        });
    </script>
</body>
</html>

