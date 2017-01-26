---
layout: post_page
title: What Is Enterprise Code? - Reactive Manifesto
date: 2017-01-26
tags: Programming
---
The podcast discussion at [Software Engineering Daily regarding reactive microservices](https://softwareengineeringdaily.com/2017/01/24/reactive-microservices-development-with-markus-eisele/) should help define "Enterprise Code" to our customers in terms of the [Reactive Manifesto](http://www.reactivemanifesto.org/). I often use "Enterprise" with customers and management as poorly defined techno-jargon exemplifying [Josh Bernoff's "weasel words."](http://withoutbullshit.com/blog/garden-poisonous-weasel-words) "This is the best _enterprise level_ platform you can get your hands on."

Why are these coding practices important? The Reactive Manifesto reminds us to design frameworks that are *flexible, loosely-coupled, and scalable*. The consequent responsiveness leads to resiliency to failure and elasticy for change, creating an "Enterprise" level system in my book. A recent architectural challenge led to decoupling data access methods from middle tier business object code. The results leave a more scalable and testable code base.

Negatively, an overzealous architect can overdo abstraction, leaving a difficult coding environment. Inserting the right mix of Reactive Manifesto ideas for the scope of the project becomes an art form. Code generation and automation ease this implementation to encourage widespread practice.

<img src="https://i-msdn.sec.s-msft.com/dynimg/IC340233.png"/>
