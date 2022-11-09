---
title: "@DataJpaTest with TestContainer"
date: 2022-07-18 11:21:00 +0900
tags: [java, testcontainer, jpa]
categories: [Java, SpringBoot]
---

## What is TestContainers?

일반적으로 Springboot 에서 DB 를 테스트해야할 경우는 H2 를 많이 사용한다. 하지만 PostgreSQL 의 Upsert 문처럼 DB 마다 약간씩 다른 문법들을 완벽하게 지원하지는 못하고 있기 때문에 사용하는 DB 가 in-memory 를 지원하지 않는다면 결국 로컬에 DB 를 설치하거나 container 를 직접 구성하여 테스트해야하는 경우가 생긴다.

`TestContainer` 는 프로그래밍 언어를 사용하여 Docker container 를 구성할 수 있도록 함으로써, 통일된 테스트 환경을 만들어주는 라이브러리이다.

이 글에서는 Spring data JPA 를 사용하는 환경을 가정하고 TestContainer 를 사용하여 DB 를 어떻게 테스트할 수 있을지 알아본다.

## Example

## Conclusion
