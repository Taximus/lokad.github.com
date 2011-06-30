---
layout: post
title: Chapter 01 - Core Development Concepts
---

# Core Development Principles

There are certain development concepts that are essential to Lokad.CQRS, understanding it properly and successfully delivering software. These concepts will be briefly mentioned in this chapter just to ensure that we are on the same page regarding the terminology and application scenarios.

Please, feel free to skim through this chapter, if the concepts are already familiar to you.

## Inversion of Control

_Inversion of Control (IoC)_ is an approach in software development that favors removing sealed dependencies between classes in order to make code more simple and flexible. We push control of dependency creation outside of the class, while making this dependency explicit.

Usage of Inversion of Control generally allows creating applications that are more flexible, unit-testable, simple and maintainable in the long run.

Often control over the dependency creation is delegated to specialized application blocks called Inversion of Control Containers. IoC containers are really good in determining dependencies that are needed to create a specific class and injecting them automatically. This process is often called Dependency Injection.

[Continue reading...](http://abdullin.com/wiki/inversion-of-control-ioc.html)