---
title: Git, Github
layout: post
date: '2021-06-20 16:00:00'
categories:
- study
tags:
- IT_Knowledge
comments: true
published: true
---

Git : 버젼관리를 위한 SW
* 소스코드를 여러 개발 PC와 저장소에 분산해서 저장

Github : Git으로 저장돼서 원격전송된 내역들이 저장되는 공간을 제공하는 서비스
* 무료 오픈소스는 모든 사람들이 볼 수 있고 다운 가능

commit : Git에 변경 내용을 저장

$ git commit -m "작업내용"

merge: 각자 작업물(브랜치)을 병합

※ 브랜치란? 여러 작업을 동시에 작업하기위해 독립적으로 작업을 진행하기위한 개념

$ git merge "브랜치명"

push: Github에 파일을 추가하거나 변경 내용을 저장하는 작업

pull:Github에서 파일을 다운 후 병합하는 작업
