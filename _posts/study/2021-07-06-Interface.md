---
title: Interface
layout: post
date: '2021-07-06 11:00:00'
categories:
- study
tags:
- Java
comments: true
published: true
---

클래스는 인터페이스를 구현하고, 클래스로부터 객체를 생성하는 과정을 거치게 된다.  
인터페이스를 사용하는 이유는 객체가 다양한 자료형(타입)을 가질 수 있기 때문이다. 
class 대신 interface 키워드를 사용하며, entends 대신 implements 키워드를 사용한다.  

public interface InterfaceA {  
	public void funA();  	
}

public interface InterfaceB {  
	public void funB();  
}

<script src="https://gist.github.com/parkhyoungmin/60fe0f2f07b03ef49663fc73fbd193d2.js"></script>
<script src="https://gist.github.com/parkhyoungmin/f87cef19a663388b419548942dd6276b.js"></script>
