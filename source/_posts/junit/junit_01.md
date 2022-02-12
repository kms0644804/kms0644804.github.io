---
layout: post
title: "1. 첫 번째 JUnit 테스트"
date: 2021-08-20
categories: JUnit
tags: [dev, test, kotlin, java]
toc: true
author:
- Kangmin
---

- https://github.com/boring-km/JunitPractice

## 1.1 단위 테스트를 작성하는 이유
- 단위 테스트를 반영한 사람과 아닌 사람이 문제를 발견하거나 검증하는 데 소요하는 시간에서 단위 테스트를 작성한 사람이 훨씬 간편하고 빠르게 찾아내는 것을 확인함.

## 1.2 JUnit의 기본: 첫 번째 테스트 통과
## 1.3 테스트 준비, 실행, 단언
- src/main/kotlin/chapter01

## 1.4 테스트가 정말로 뭔가를 테스트하는가?
- 의도치 않게 생각했던 것을 실제로 검증하지 않는 나쁘고 노력이 많이 들어가는 테스트를 작성할 수도 있다.
- 테스트에서 먼저 실패하고 그 코드를 통과시키기 위한 TDD의 자세를 따라가자

## 1.5 결론
- ScoreCollection 코드 분석해보고 스스로 질문 던져보기
    - 코드가 정상적으로 동작하는지 확신하려고 추가적인 테스트를 작성할 필요가 있는가?
    - 내가 클래스에서 결함이나 한계점을 드러낼 수 있는 테스트를 작성할 수 있을까?