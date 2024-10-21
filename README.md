# java-calculator-precourse

## 문자열 덧셈 계산기

### 기능 요구 사항
- 입력한 문자열에서 숫자를 추출하여 더하는 계산기를 구현한다.
- 쉼표(,) 또는 콜론(:)을 구분자로 가지는 문자열을 전달하는 경우 구분자를 기준으로 분리한 각 숫자의 합을 반환한다.
  - 예: "" => 0, "1,2" => 3, "1,2,3" => 6, "1,2:3" => 6
- 앞의 기본 구분자(쉼표, 콜론) 외에 커스텀 구분자를 지정할 수 있다. 커스텀 구분자는 문자열 앞부분의 "//"와 "\n" 사이에 위치하는 문자를 커스텀 구분자로 사용한다.
  - 예를 들어 "//;\n1;2;3"과 같이 값을 입력할 경우 커스텀 구분자는 세미콜론(;)이며, 결과 값은 6이 반환되어야 한다.
- 사용자가 잘못된 값을 입력할 경우 IllegalArgumentException을 발생시킨 후 애플리케이션은 종료되어야 한다.

### 기능 목록

#### 1. 입력 처리

- 사용자가 입력한 문자열을 입력 받고, 잘못된 값을 입력할 경우 IllegalArgumentException을 발생시킨 후 애플리케이션은 종료되어야 한다.

#### 2. 문자열 처리 1

- 기본 구분자(쉼표, 콜론)로 구분해서 문자열 처리

#### 3. 문자열 처리 2

- "//문자\n"가 앞에 들어온 문자열을 통해서 커스텀 구분자 확인

#### 4. 문자열 처리 4

- 커스텀 구분자와 기본 구분자를 통한 문자열 처리

#### 5. 계산 시스템 구현

- 구분자를 통해 정리된 문자열을 계산하는 로직 구현