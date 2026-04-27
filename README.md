목표:
en_us.snbt를 기반으로 ko_kr.snbt를 만들어줘.

작업 파일:
- 원본: en_us.snbt
- 결과: ko_kr.snbt

번역 규칙:
1. SNBT 구조, 키 이름, quest ID, chapter ID, 줄 순서를 절대 변경하지 마.
2. 왼쪽 키는 그대로 두고, 오른쪽 문자열 값만 한국어로 번역해.
3. 예:
   quest.xxxxx.title: "Getting Started"
   →
   quest.xxxxx.title: "&5시작하기"

4. quest_desc 배열도 배열 구조는 유지하고 문자열만 번역해.
5. 새 quest, 새 chapter, 임의 ID를 만들지 마.
6. 원문에 없는 내용을 과하게 추가하지 마.
7. 단, 분위기용 문장은 설명 맨 앞이나 끝에 한 줄 정도만 자연스럽게 추가 가능.
8. 색 코드 스타일:
   - 제목: &5 또는 &d
   - 일반 설명: &7
   - 행동/목표: &e
   - 아이템/중요 요소: &6
   - 장소/상태: &b

문체:
- 게임형 가이드 문체
- 짧고 읽기 쉽게
- 너무 소설처럼 길게 쓰지 말 것
- “~하세요”보다 “~하면 됩니다”, “~을 획득합니다” 느낌 선호

검수 조건:
1. en_us.snbt와 ko_kr.snbt의 키 개수가 같아야 함.
2. quest.xxx.title / quest.xxx.quest_subtitle / quest.xxx.quest_desc 키가 누락되면 안 됨.
3. SNBT 문법이 깨지면 안 됨.
4. 작업 후 변경 요약과 누락 여부를 알려줘.

먼저 Getting Started 챕터만 번역해서 ko_kr_getting_started.snbt로 만들어줘.
그다음 내가 확인하면 다음 챕터로 넘어갈게.
