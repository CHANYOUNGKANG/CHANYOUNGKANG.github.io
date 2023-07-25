---
layout: post
title: '1주차 항해일지 2023 - 07- 24 '
subtitle: 'JVM, 변수, 타입'
cover-img: /assets/img/앙몬드2.jpg
thumbnail-img: /assets/img/앙몬드2.png
share-img: /assets/img/1주차 타이틀.jpg
tags:
  - books
  - test
published: true
---

**[수업 목표]**

1. Java 프로그램을 만들때 사용하는 Java 언어에 대해서 이해합니다.
2. Java 의 실행환경인 JVM 에 대해서 이해합니다.
3. Java 의 데이터인 변수와 상수에 대해서 이해합니다.
4. Java 의 변수를 담는 저장공간의 종류에 대해서 이해하고 사용법을 익힙니다.
5. Java 의 저장공간 종류(변수 타입)간에 변환에 대해서 이해하고 사용법을 익힙니다.

- 첫 개발언어라는 의미에서 A Programming Language 의 약자
- 발표년대 : 1960’
- 핵심기능 : 입/출력, 문맥
- 프로그램을 만들기위해 기본적으로 필요한 기능 입/출력💻, 문맥💌 기능만 구현가능한 언어
- [B 언어](https://ko.wikipedia.org/wiki/B_(%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%B0%8D_%EC%96%B8%EC%96%B4))
    - Bell 사에서 개발해서 B 언어
    - 발표년대 : 1960’
    - 핵심기능 : A언어 기능 + 기계식 데이터 타입🔢, 연산기능🧮, 메서드🎁
    - A언어 기능에  데이터를 담을 수 있는 타입이 생기고, 데이터🔢를 연산🧮하고 묶어서 관리할 수 있는 메서드🎁(포장지) 구현이 가능한 언어
- [C 언어](https://ko.wikipedia.org/wiki/C_(%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%B0%8D_%EC%96%B8%EC%96%B4))
    - B언어에 비해 더 좋은 언어라는 의미로 알파벳 B 다음인 알파벳 C를 따서 C언어
    - 발표년대 : 1970’
    - 핵심기능 : B언어 기능 + 자료형 데이터 타입🔢(변하는 것), 자료구조🗳️(분류통)
    - B언어 기능에 다양한 데이터 타입🔢을 정의하고 자료구조🗳️에 담을 수 있는 언어
    
    - [Java 언어](https://ko.wikipedia.org/wiki/%EC%9E%90%EB%B0%94_(%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%B0%8D_%EC%96%B8%EC%96%B4))
    
    ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/a01529db-5a8b-4923-a3f9-34f5f3c7705c/Untitled.png)
    
    - 어디서나 마시는 커피처럼 어디서나 동작 가능한, 자바 커피에서 이름을 따서 만든 Java 언어
    - 발표년대 : 1990’
    - 핵심기능 : C언어 기능 + 공통 실행환경🗺️(놀이터), 클래스🗑️(바구니 틀), 객체🪣(바구니)
    - C언어 기능에 여러 기기에서 실행가능하도록 도와주는 공통 실행환경🗺️, 그리고 데이터🔢와 메서드🎁를 담는 클래스🗑️(바구니 틀)를 통해 객체🪣(바구니)를 만들 수 있는 언어