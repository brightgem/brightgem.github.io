> 책 소개 및 선택 이유

- [자바 코딩의 기술](https://play.google.com/store/books/details?id=lAP1DwAAQBAJ&pcampaignid=books_web_aboutlink)

<img src="http://image.yes24.com/goods/91236635/800x0" width="30%" height="30%"></img>

- 자바 코드 작성 표준에 대한 학습 위함
- 내 코드에 대한 리뷰
- JMachine (JBOX) 소스 코드 복잡도 증가
   
> 주요 내용

1장. 우선 정리부터 <불필요한 코드 정리 / 가독성 높이기 위한 코드 작성>
 - 1.1 쓸모없는 비교 피하기
 - 1.2 부정 피하기
 - 1.3 불 표현식을 직접 반환 : 
[잘못된 코드](https://github.com/gilbutITbook/007025/blob/master/src/general/return_boolean_expression_directly/problem/Astronaut.java) / 
[올바른 코드](https://github.com/gilbutITbook/007025/blob/master/src/general/return_boolean_expression_directly/solution/Astronaut.java)
 - 1.4 불 표현식 간소화
 - 1.5 조건문에서 NullPointerException 피하기
 - 1.6 스위치 실패 피하기
 - 1.7 항상 괄호 사용하기
 - 1.8 코드 대칭 이루기 : 
 [잘못된 코드](https://github.com/gilbutITbook/007025/blob/master/src/general/ensure_code_symmetry/problem/BoardComputer.java) / 
 [올바른 코드](https://github.com/gilbutITbook/007025/blob/master/src/general/ensure_code_symmetry/solution/BoardComputer.java)

2장. 코드 스타일 레벨 업 <1장의 연장선>
 - 2.1 매직 넘버를 상수로 대체
 - 2.2 정수 상수 대신 열거형
 - 2.3 For 루프 대신 For-Each : 인덱스 변수를 사용해야 하는 경우가 아니라면 For문 지양
 - 2.4 순회하며 컬렉션 수정하지 않기
 - 2.5 순회하며 계산 집약적 연산하지 않기 : 
 [잘못된 코드](https://github.com/gilbutITbook/007025/blob/master/src/general/compile_regex_once/problem/Inventory.java) / 
 [올바른 코드](https://github.com/gilbutITbook/007025/blob/master/src/general/compile_regex_once/solution/Inventory.java)
 - 2.6 새 줄로 그루핑
 - 2.7 이어붙이기 대신 서식화
 - 2.8 직접 만들지 말고 자바 API 사용하기

3장. 슬기롭게 주석 사용하기 <주석의 올바른 사용법>
 - 3.1 지나치게 많은 주석 없애기 : 과도한 주석은 불필요 / 설명이 필요한 부분에 주석 추가
 - 3.2 주석 처리된 코드 제거 : 주석 처리되어 있는 코드는 대부분 앞으로 사용되지 않을 코드 -> 정리 필요
 - 3.3 주석을 상수로 대체
 - 3.4 주석을 유틸리티 메서드로 대체
 - 3.5 구현 결정 설명하기
 - 3.6 예제로 설명하기
 - 3.7 패키지를 JavaDoc으로 구조화하기 : JavaDoc을 활용해 잘 문서화된 주석 필요
 - 3.8 클래스와 인터페이스를 JavaDoc으로 구조화하기
 - 3.9 메서드를 JavaDoc으로 구조화하기
 - 3.10 생성자를 JavaDoc으로 구조화하기

4장. 올바르게 명명하기 <명명은 가독성을 높이는 중요한 요소>
 - 4.1 자바 명명 규칙 사용하기 : 
 [잘못된 코드](https://github.com/gilbutITbook/007025/blob/master/src/naming/use_java_naming_conventions/problem/Problem.java) / 
 [올바른 코드](https://github.com/gilbutITbook/007025/blob/master/src/naming/use_java_naming_conventions/solution/Solution.java)
 - 4.2 프레임워크에는 Getter/Setter 규칙 적용
 - 4.3 한 글자로 명명하지 않기
 - 4.4 축약 쓰지 않기
 - 4.5 무의미한 용어 쓰지 않기
 - 4.6 도메인 용어 사용하기

5장. 문제 발생에 대비하기 <올바른 예외처리/자원클로즈 방법 설명>
 - 5.1 빠른 실패
 - 5.2 항상 가장 구체적인 예외 잡기 : 
 [잘못된 코드](https://github.com/gilbutITbook/007025/blob/master/src/error_handling/always_catch_most_specific_exception/problem/Transmission.java) / 
 [올바른 코드](https://github.com/gilbutITbook/007025/blob/master/src/error_handling/always_catch_most_specific_exception/solution/Transmission.java)
 - 5.3 메시지로 원인 설명
 - 5.4 원인 사슬 깨지 않기
 - 5.5 변수로 원인 노출
 - 5.6 타입 변환 전에 항상 타입 검증하기
 - 5.7 항상 자원 닫기 : 
 [잘못된 코드](https://github.com/gilbutITbook/007025/blob/master/src/error_handling/always_close_resources/problem/Logbook.java) / 
 [올바른 코드](https://github.com/gilbutITbook/007025/blob/master/src/error_handling/always_close_resources/solution/Logbook.java) (try-with-resources 구문 사용)
 - 5.8 항상 다수 자원 닫기
 - 5.9 빈 catch 블록 설명하기
   
> 현재까지 소감

1. 설명이 이해하기 쉽고 가독성 좋게 잘 쓰여진 책인 것 같다.
 
2. 중급 자바 개발자가 되기 위한 과정에 읽어보면 좋은 책인 것 같다.

3. 실제 개발 업무에 반영하기 위한 고민 필요
