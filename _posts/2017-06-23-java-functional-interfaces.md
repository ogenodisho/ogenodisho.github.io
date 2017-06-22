---
layout: post
title: "Java 8 Functional Interfaces"
date: 2017-06-23
categories: [Dev]
tags: [java]
comments: true
---

| Inputs  | Outputs | Name     |
| :-----: | :-----: | :------: |
| True    |  False  | Consumer |
| False   |  True   | Supplier |
| True    |  True   | Function |

A `Function` is parameterized with the types of its inputs and outputs. If these types are the same - you can refer to the `Function` as an `Operator` of that single type.

A `Function` that returns a boolean is called a `Predicate`.

`Unary` and `Binary` refers to the number of relevant arguments. E.g., `BiOperator` is an `Operator` that takes 2 inputs.
