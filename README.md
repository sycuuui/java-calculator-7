# 과제1 - 문자열 덧셈 계산기
## 구현 기능 목록
<hr>

### 입력
- 구분자와 양수로 구성된 문자열 입력

### 계산기
- 구분자 기준으로 문자열 분리하여 문자열 배열 생성
- 쉼표(,) 또는 콜론(:) 구분자 등록
- 문자열 앞부분의 "//"와 "\n" 사이에 위치하는 문자를 커스텀 구분자로 등록
  - "//"와 "\n"이 있고 문자열 앞부분이 "//" 아닌 경우 IllegalArgumentException을 발생시킨 후 애플리케이션은 종료
- 문자열 배열에 있는 양수 더하기 계산
    - 양수가 아닌 값이 있을 경우 IllegalArgumentException을 발생시킨 후 애플리케이션은 종료

### 출력
- 계산한 결과 출력