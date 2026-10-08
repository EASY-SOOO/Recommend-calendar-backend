- 회원, 관심 분야, 기업 규모 필터, 채용공고, 자격증, 추천, 캘린더 API 16개 동작 확인
- 모든 API 공통 응답 형식: { success, data, error }
- docs/API.md: API 목록 + 요청·응답 예시 (2~3단계 CBT·일정 생성 API는 계획만 적어둠)
- README.md: 프로젝트 구조, 실행 방법

▶ 실행 방법
JDK 17 설치 후 압축 풀고 ./gradlew bootRun (윈도우는 .\gradlew bootRun)
→ http://localhost:8080/swagger-ui.html 에서 바로 API 테스트 가능해요. DB 설치 없이 내장 DB + 샘플 데이터로 돌아감

보내주신 고용24 API 응답 필드(coNm, regionNm, certCd 등)에 맞춰 작성했고, ERD부분은 임의로 채워넣음, 기업명은 전부 '(샘플)' 가상 기업이고, 합격률·시험일도 샘플값
