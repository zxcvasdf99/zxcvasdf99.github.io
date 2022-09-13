---
layout: post
title: 안드로이드 스튜디오 앱 개발하기 첫번째
date: 2021-08-20 23:18 +0800
tags: [jekyll theme, jekyll, tutorial]
toc:  true
---
파이어베이스 서버와 안드로이드 스튜디오를 사용해 메인화면 구현하기

### Code

파이어베이스는 Nosql 형태로 데이터가 {key:value} 형태로 구성


{% highlight js %}
// 파이어베이스와 안드로이드 스튜디오 연동을 위해 필요한 라이브러리를 호출한다
import com.google.firebase.database.DataSnapshot;
import com.google.firebase.database.DatabaseError;
import com.google.firebase.database.DatabaseReference;
import com.google.firebase.database.FirebaseDatabase;
import com.google.firebase.database.ValueEventListener;

// Create a function that takes two arguments and returns the sum of those arguments
var adder = new Function("a", "b", "return a + b");

// Call the function
adder(2, 6);
// > 8
{% endhighlight %}

You may also optionally show code snippets with line numbers. Add `linenos` to the Rouge tags.

{% highlight js linenos %}
// Example can be run directly in your JavaScript console

// Create a function that takes two arguments and returns the sum of those arguments
var adder = new Function("a", "b", "return a + b");

// Call the function
adder(2, 6);
// > 8
{% endhighlight %}

Aenean lacinia bibendum nulla sed consectetur. Etiam porta sem malesuada magna mollis euismod. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa.
