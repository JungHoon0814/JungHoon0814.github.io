---
layout: post
title: "TypeScript?"
subtitle: "코딩애플님의 TypeScript 10분정리보고 재정리"
category: study
tags: typescript.
---

<!--more-->

* this unordered seed list will be replaced by the toc
{:toc}

## TypeScript란? 
--- 
  TypeScript = JavaScript + Type 문법  
  "JavaScript의 Superset"같은 것  
  크기가 큰 프로젝트의 경우에서는 TypeScript를 더 많이 쓰기도 한다

## JavaScript와 TypeScript의 차이
--- 
  JavaScript는 Dynamic Typing 가능  
    Ex) 7 - '2' ===> 원래는 숫자 - 숫자 여야하지만 JavaScript는 알아서 바꿔준다  
    즉 연산이 가능하다. 하지만 프로젝트의 사이즈가 커지면 커질수록 단점이 된다

   그에 반해 TypeScript는 타입을 명확히 엄격하게 검사하기 때문에 Dynamic Typing을 할 수 없다. 그래서 명확한 타입, 명시된 타입을 넣어주어야 하기에 큰 프로젝트에서 유리하다 

   또한 JavaScript는 에러 메세지 조차 추상적이고 추적이 어렵다. 하지만 TypeScript는 에러 메세지 퀄리티가 좋음.  

   > 즉 TypeScript는 하나의 언어라기 보다는 코드에디터 부가기능으로 볼 수도 있다.

### 추가..
---
- TypeScript를 설치시 Node.js는 최신버전!  
- tsconfig.json  
  - typescript --> javascript컴파일 시 옵션조절 가능
- 간단한 변수타입이 지정가능
- 타입전에 ?  
  - 지정한 속성이 옵션이에요
- 다양한 타입을 받고싶을 때?  
  - Union type   
- 여러 타입을 한번에 중첩해서 쓰고싶은 경우
  - 타입도 변수 선언 가능
- 함수에도 타입 지정이 가능  