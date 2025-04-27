# 영어 단어 학습 앱  https://royssama.github.io/study-english/templates/

영어 단어를 학습하고 퀴즈를 통해 복습할 수 있는 웹 애플리케이션입니다.

## 주요 기능

- JSON 형식으로 단어 등록
- 랜덤 순서로 문제 출제
- 정답/오답 즉시 피드백
- 결과 통계 및 다시 풀기 기능
- 정답지 확인 기능

## 사용 방법

1. JSON 형식으로 단어를 입력합니다:
```json
[
  {
    "english": "time",
    "definition": "This is what you look at when you want to know what hour it is.",
    "korean": "시간"
  },
  {
    "english": "watch",
    "definition": "You wear this on your wrist to keep track of the time.",
    "korean": "시계"
  }
]
```

2. "단어 등록" 버튼을 클릭합니다.
3. 퀴즈가 시작되면 정의를 보고 영어 단어와 한글 뜻을 입력합니다.
4. 정답 확인 버튼을 클릭하거나 엔터 키를 눌러 답을 확인합니다.
5. 모든 문제를 풀면 결과가 표시됩니다.

## 기술 스택

- HTML5
- CSS3
- JavaScript (Vanilla JS)
- Bootstrap 5
- Font Awesome

## 설치 및 실행

1. 저장소를 클론합니다:
```bash
git clone [repository-url]
```

2. `index.html` 파일을 웹 브라우저에서 엽니다.

## 라이선스

MIT License 