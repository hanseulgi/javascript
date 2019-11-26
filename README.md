

# javascript 스터디
### 주제 하나씩 정해서 스터디 진행
#### 자바스크립트를 깨우치다 (책 읽고 개인 공부)

### git
git clone https://github.com/hanseulgi/javascript.git

### 진행
- 인원 : 한슬기, 김소연, 민승기 
- 시간 : 오후 7시 ~ 9시
- 일자 : 매주 월요일
- 장소 : <a href="http://naver.me/Fh8xRCe4" target="_blank">홍대 슈퍼스타트</a>









### 자바스크립트를 깨우치다 목차 

--------------------------------------
chapter 1 자바스크립트 객체
- 객체 만들기 1
- 자바스크립트 생성자는 객체 인스턴스를 생성하고 반환한다 8
- 자바스크립트 네이티브 / 내장 객체 생성자 10
- 사용자 정의 객체 생성자 함수 12
- new 연산자를 사용한 생성자 인스턴스 생성 14
- 리터럴을 사용한 값 생성하기 17
- 원시값(=단순값) 19
- 원시값 null, undifinde, "string", 10, true, false는 객체가 아니다 21
- 원시값은 어떻게 저장·복사되는가 22
- 원시값은 값 자체를 비교한다 24
- 문자열, 숫자, 불리언 원시값을 객체처럼 사용하면 객체처럼 동작한다 25
- 복합 객체(=합성 객체) 26
- 복합 객체는 어떻게 저장·복사되는가 28
- 복합 객체는 참조를 비교한다 29
- 복합 객체는 동적 속성을 포함한다 30
- typeof 연산자 31
- 동적 속성 덕분에 객체 수정이 가능하다 33
- 생성자 인스턴스에는 자신의 생성사 함수를 가리키는 속성이 있다 34
- 객체가 특정 생성사 함수의 인스턴스인지 확인하기 37
- 생성자를 통해 만든 인스턴스에 인스턴스 속성 추가하기 39
- "자바스크립트 객체"와 "Object() 객체"의 의미 41
--------------------------------------
chapter 2 객체와 속성 다루기
- 복합 객체는 자바스크립트 자료형의 대부분을 속성으로 포함할 수 있다 43
- 복합 객체에 다른 객체 포함하기 45
- 점 표기법과 각괄호 표기법을 사용한 객체 속성 접근 46
- 객체 속성 삭제하기 50
- 객체 속성의 참조를 찾는 법 51
- hasOwnProperty를 사용해 프로토타입 체인에서 상속받은 속성인지 확인하기 55
- in 연산자를 사용해 객체가 주어진 속성을 포함하는지 확인하기 56
- for in 루프를 사용해 객체의 속성 탐색하기 57
- 호스트 객체 vs 네이티브 객체 58
- Underscore.js를 사용한 객체 확장 60
--------------------------------------
chapter 3 Object()
- Object() 객체 사용 63
- Object() 매개 변수 64
- Object()의 속성과 메소드 65
- Object() 객체 인스턴스의 속성과 메소드 66
- "객체 리터럴"을 사용한 Object() 객체 생성 66
- 모든 객체는 Object.prototype을 상속받는다 69
--------------------------------------
chapter 4 Function()
- Function() 객체 사용 71
- Function() 매개 변수 72
- Function()의 속성과 메소드 73
- Function() 객체 인스턴스의 속성과 메소드 73
- 함수는 항상 값을 반환한다 74
- 함수는 1급 클래스다(문법은 물론 값으로도) 75
- 함수에 매개변수 전달하기 77
- this와 arguments 78
- arguments.callee 속성 79
- 함수 인스턴스의 length속성과 arguments.length 80
- 함수 매개변수 재정의 81
- 함수 완료 전에 반환하기(실행종료) 82
- 함수를 정의하는 세가지 방법 82
- 함수를 호출하는 네가지 패턴 83
- 익명 함수 85
- 자기 호출 표현식 86
- 자기 호출 익명 함수 86
- 함수는 중첩될 수 있다 87
- 함수에 함수 전달하기 / 함수에서 함수 반환하기 88
- 함수가 정의되기 전에 함수를 호출하기(함수 호이스팅) 89
- 함수는 자신을 호출할 수 있다(재귀 호출) 90
--------------------------------------
chapter 5 머리/전역 객체
- 머리 객체의 사용 93
- 머리 객체에 포함된 전역 함수 94
- 머리 객체 vs 전역 속성, 전역변수 95
- 머리 객체 참조하기 97
- 머리 객체는 생략 될 수 있다 98
--------------------------------------
chapter 6 this 키워드
- this의 사용 99
- this의 값은 어떻게 정해지는가 101
- 중첩된 함수의 this는 머리 객체를 참조한다 103
- call() 또는 apply()를 사용한 this값 설정 105
- 사용자 정의 생성자 함수 내에서 this 키워드 사용하기 107
- 프로토타입 메소드 안의 this는 생성자 인스턴스를 참조한다 109
--------------------------------------
chapter 7 스코프와 클로저
- 자바스크립트의 스코프 111
- 자바스크립트에는 블록 스코프가 없다 113
- 함수 내에서 변수 선언시 var를 사용해 스코프 문제 피하기 113
- 스코프 체인(문법적 스코프) 115
- 스코프 체인을 검색할 때는 가장 처음 발견한 값을 반환한다 116
- 스코프는 함수를 정의할 때 결정된다 117
- 스코프 체인이 클로저를 만든다 119
--------------------------------------
chapter 8 함수의 프로토타입
- 프로토타입 체인 121
- prototype 속성이 왜 중요한가 123
- 모든 Function() 인스턴스에는 prototype 속성이 있다 123
- prototype 속성은 Object() 객체다 124
- 생성자 함수를 통해 만든 인스턴스는 생성자 함수의 prototype 속성과 연결되어 있다 125
- 프로토타입 체인의 끝은 Object.prototype이다 127
- 프로토타입 체인은 체인에서 제일 먼저 찾은 속성을 반환한다 128
- prototype 속성을 새 객체로 대체하면 기본 constructor 속성이 삭제된다 129
- 프로토타입에서 상속한 속성은 가장 최근의 값을 사용한다 131
- prototype 속성을 새 객체로 대체하면 이전에 만든 인스턴스는 갱신되지 않는다 132
- 사용자 정의 생성자도 네이티브 생성자처럼 프로토타입을 상속할 수 있다 134
- 상속 체인 만들기 135
--------------------------------------
chapter 9 Array()
- Array() 객체의 사용 137
- Array() 매개변수 138
- Array() 속성과 메소드 139
- Array 객체 인스턴스의 속성과 메소드 139
- 배열 만들기 140
- 배열에 값을 추가하고 갱신하기 141
- 크기와 색인 143
- 미리 설정한 크기로 배열 만들기 143
- 배열의 크기를 설정하면 값을 추가하거나 제거할 수 있다 144
- 다른 배열을 포함한 배열(다중 배열) 145
- 배열을 앞뒤로 훑기 146
--------------------------------------
chapter 10 String()
- String() 객체의 사용 149
- String() 매개변수 150
- String() 속성과 메소드 151
- String 객체 인스턴스의 속성과 메소드 151
--------------------------------------
chapter 11 Number()
- Number() 객체의 사용 153
- 정수와 실수 154
- Number() 매개변수 154
- Number() 속성 155
- Number() 객체 인스턴스의 속성과 메소드 156
--------------------------------------
chapter 12 Boolean()
- Boolean() 객체의 사용 157
- Boolean() 매개변수 158
- Boolean() 속성과 메소드 159
- Boolean 객체 인스턴스의 속성과 메소드 159
- false 복합 객체는 true로 반환된다 160
- 일부 값은 false이고, 그 외는 true다 160
--------------------------------------
chapter 13 원시 문자열, 숫자, 불리언값 다루기
- 원시/리터럴 값은 속성에 접근할 때 객체로 변환된다 163
- 문자열 163
- 숫자 164
- 불리언 165
- 평소에는 원시 문자열, 숫자, 불리언값을 사용하라 166
--------------------------------------
chapter 14 Null
- null 값 사용 167
- typeof null == "object" 168
--------------------------------------
chapter 15 UNDEFINED
- undefined 값 169
- 자바스크립트 ECMAScript 3 이상에서 undefined는 전역 변수로 선언된다 170
--------------------------------------
chapter 16 Math 함수
- 내장 Math 함수 171
- Math 객체의 속성과 메소드 171
- Math는 생성자 함수가 아니다 173
- Math는 변경할 수 없는 상수를 포함한다 173
--------------------------------------
부록 A 복습
- 복습을 해봅시다 
--------------------------------------
부록 B 마치며
- 어떤 생각이 드는가? 


