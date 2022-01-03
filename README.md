# Let's Get IT 자바스크립트 프로그래밍 책을 공부하는 폴더

## 2장 기본 문법
### 2-2 자료형
- NaN : Not a Number의 줄임말이고 타입은 숫자임

- NaN 과의 비교연산에서 **NaN != NaN 경우에만 true** 이고 이외엔 전부 false임

- 대부분의 값은 **boolean 값으로 형 변환 했을때 true** 가 되지만 특정 경우에는 false가 됨
  - !!false
  - !!'' or !!""
  - !!0
  - !!NaN
  - !!undefined
  - !!null

- 문자열, 숫자, boolean 자료형 이외에 네 가지(undefined, null, object symbol)의 자료형이 더 있음
  - undefined와 null자료형은 빈 값을 표현한다는 공통점이 있음
    - undefined는 기본값이라는 의미가 있고, null은 아무런 역할이 없으나 일부 개발자가 의도적으로 사용하는 경우가 있다는 차이점이 있음
  - undefined는 반환할 결과값이 없음을 의미함
  - null은 object 타입이라는 특징이 있어 null인지 확인할때 ===으로 비교해야함

