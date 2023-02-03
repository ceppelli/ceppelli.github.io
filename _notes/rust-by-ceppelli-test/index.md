---
layout: post
title:  "Rust By Ceppelli"
description: "Chapter 001 - STM"
image: /notes/rust-by-ceppelli-test/rust-logo-blk.svg
date:   2023-01-31 00:00:00 +0100
updated: 2022-01-31
tags: [lang, rust]
permalink: /notes/rust-by-ceppelli-test/
published: false
---

![The Rust Logo](rust-logo-blk.svg)

This is the first chapter of my **Rust By Ceppelli MdBook**.
In this chapter I'm trying to evaluate different STM implementations looking for the right balance between flexibility, correctness and performance.

Here the link to the [`Chapter 001 - STM`](https://rust-by.ceppelli.com/ch001-00-stm-introduction.html)


```rust,editable,edition2018,ace_editor,ace_hidpi,ace-tm,hljs
// Type your code here, or load an example.
pub fn square(num: i32) -> i32 {
    num * num
}

// If you use `main()`, declare it as `pub` to see it in the output:
pub fn main() { 
    let number = square(2);
    print!("{}", number);
}
```






```rust,pg
// rust,editable,edition2018,ace_editor,ace_hidpi,hljs,ace-tomorrow-night,ace_dark
// Type your code here, or load an example.
pub fn square(num: i32) -> i32 {
    num * num
}

// If you use `main()`, declare it as `pub` to see it in the output:
pub fn main() { 
    let number = square(2);
    print!("{}", number);
}
```


{% include rust-pg.html %}


