---
title: RegExpression
layout: post
date: '2021-08-01 22:00:00'
categories:
- study
tags:
- Java
comments: true
published: true
---

# 정규식
- ^x : 문자열이 x로 시작합니다.
- x$ : 문자열이 x로 끝납니다.
- .x : 임의의 한 문자를 표현합니다.
- x+ : x가 1번이상 반복합니다.
- x? : x가 존재하거나 존재하지 않습니다.
- x* : x가 0번이상 반복합니다.
- x|y : x 또는 y를 찾습니다.
- (x) : ()안의 내용을 캡쳐하며, 그룹화 합니다.
- (x)(?:y) : y부분은 그룹에서 배제됩니다.
- x{n} : x를 n번 반복한 문자를 찾습니다.
- x{n,} : x를 n번이상 반복한 문자를 찾습니다.
- x{n,m} : x를 n번이상 m번이하 반복한 문자를 찾습니다.
- \[xy\] : x,y중 하나를 찾습니다.
- \[^xy\] : x,y를 제외하고 문자 하나를 찾습니다.
- \[x-z\] : x-z 사이의 문자중 하나를 찾습니다.
- \^ : ^를 식에 문자 자체로 포함합니다.
- \b : 문자와 공백사이의 문자를 찾습니다.
- \B : 문자와 공백사이가 아닌 값을 찾습니다.
- \d : 숫자를 찾습니다.
- \D : 숫자가 아닌 값을 찾습니다.
<script src="https://gist.github.com/parkhyoungmin/c07c1c30cd025e40b08958e52953380c.js"></script>


