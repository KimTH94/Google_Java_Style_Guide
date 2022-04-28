# Google_Java_Style_Guide
Google Java Style Guide 번역본

## 목록 
### 1. 소개
  #### 1.1 용어 노트
  #### 1.2 가이드 노트

### 2. 소스 파일의 기본
#### 2.1 파일 이름
#### 2.2 인코딩: UTF-8
#### 2.3 특수문자

### 3. 소스 파일 구조
#### 3.1 라이센스 또는 저작권 정보(저작권 정보가 있으면)
#### 3.2 `Package` 설명
#### 3.3 `Import` 설명
#### 3.4 `Class` 선언

### 4. 포맷
#### 4.1 괄호
#### 4.2
#### 4.3
#### 4.4
#### 4.5
#### 4.6
#### 4.7
#### 4.8

### 5. 네이밍
#### 5.1 모든 식별자에 공통적인 규칙
#### 5.2 식별자 유형별 규칙
- 5.2.1 `Package` 이름
#### 5.3

### 6. 프로그래밍 실습
#### 6.1
#### 6.2
#### 6.3
#### 6.4

### 7. Java Doc
#### 7.1
#### 7.2
#### 7.3


## 1. 소개
이 문서는 Java™ 프로그래밍 언어의 소스 코드에 대한 Google 코딩 표준의 완전한 정의 역할을 합니다.
Java 소스 파일은 여기에 있는 규칙을 준수하는 경우에만 Google 스타일에 있는 것으로 설명됩니다.
다른 프로그래밍 스타일 가이드와 마찬가지로 다루는 문제는 형식의 미학적 문제뿐만 아니라 다른 유형의 규칙이나 코딩 표준에도 적용됩니다. 그러나 이 문서는 주로 우리가 보편적으로 따르는 엄격하고 빠른 규칙 에 중점을 두고 있으며 명확하게 시행할 수 없는 조언 은 제공 하지 않습니다(인간이든 도구든).
### 1.1 용어 노트
### 1.2 가이드 노트
이 문서의 예저 코드는 표준이 아닙니다.
즉, 예제는 Google 스타일이지만, 코드를 표현하는 

## 3. 소스 파일 구조
### 3.1 라이센스 또는 저작권 정보(저작권 정보가 있으면)
### 3.2 `Package` 설명
패키지 선언 시 줄 바꿈되지 않습니다.
열제한(#### 목차 4.4 : 100)은 패지키 선언 시 적용되지 않습니다.
``` java
package kr.co.companyname.projectname.platformname.business.str.service; // 가능
package kr.co.companyName.projectName.business.str.
        service; // 불가능
```
### 3.3 `Import` 설명
### 3.4 `Class` 선언

## 5. 네이밍
### 5.1 모든 식별자에 공통적인 규칙
식별자는 ASCII 문자와 숫자만 사용하며, 아래에 언급된 경우 `_`을 사용하기도 합니다.  
따라서 유효한 식별자 이름은  **\w+ 정규식**(한 개 이상의 알파벳 또는 숫자)과 일치합니다.  
Google Style에서는 특수 접두사나 접미사가 사용되지 않습니다.
``` java
String name_;   // ❌
String mName;   // ❌
String s_name;  // ❌
String kName;   // ❌
```  
### 5.2 식별자 유형별 규칙
#### 5.2.1 `Package` 이름
Package 이름은 모두 소문자이며, 연속 된 단어는 소문자로 연결됩니다.(`_` 불가능)
``` java
package com.example.deepspace;   // ⭕️
package com.example.deep_space;  // ❌
package com.example.deepSpace;   // ❌
```
#### 5.2.2 `Class` 이름
Class 이름은 [UpperCamelCase](https://velog.io/@thehill_hannam/Case-Naming-Convention-%EC%A0%95%EB%A6%AC#uppercamelcase)
#### 5.3
---
## 참고
[Google Java Style Guide 원본](https://google.github.io/styleguide/javaguide.html#s7-javadoc)
- 다른 번역본
    - [JunHoPark93](https://github.com/JunHoPark93/google-java-styleguide)
    - [newwisdom's log](https://newwisdom.tistory.com/m/96)
