---
title: "My Opinion about Rust and Golang"
thumbnailImagePosition: right
thumbnailImage: https://source.unsplash.com/5KvPQc1Uklk/200x200
coverImage: https://source.unsplash.com/5KvPQc1Uklk/1200x600
metaAlignment: center
coverMeta: out
coverCaption: "Beautiful fireworks by Ryan Wong"
date: 2017-11-25
categories:
- opinion
tags:
- development
- programming
- analyst
- golang
- rustlang
- rust
draft: false
---
You know i am really interested with two compiled language which is Rust-lang and Golang from this mid-year of 2017. 
I think i am are ready to move into more capability which is available on these languages with pretty efficient, fast on managing it's memory and cpu process.

Node.js is cool but instead using a node program to handle some various cpu-intensive or very large memory consumptions around my application. 
I tend to use a right tool for a right job.

Golang has a mature design and has a lot of users with their own library and packages. This means good for Golang community and environment. 
I was diving into the code and see how much Golang successfuly handles the concurrencies and the easy-way of writing code and be productive with it.
But we all know because Golang is built on Google company, with a purpose to handle their services depending on their bussiness, it seems not very well on introducing Golang as this language has some of limitations.

Golang in a few terms seems to be not very good in programming language design, people often seems Golang is not providing some solutions who needed for community. 
Some of the cons was listed on here [https://github.com/ksimka/go-is-not-good](https://github.com/ksimka/go-is-not-good). Even though the language is not giving all the developer wants, 
the community still growing bigger and Golang being a top 10 language at 2016 (tiobe index).

The short story cons of Golang is it didn't provide a generics function, no exception, too opinionated and has no standard modules repository or package manager (you can think this like `npm` on Node.js). 
The community often use thir own package manager and still using `github.com` as a path for importing libraries they need. I see this is not a best practice in terms of stability and community power.

In some way, there is Rust. Rust-lang invented by Mozzila team, servo was a big project that running under new firefox browser ([Firefox Quantum](https://blog.rust-lang.org/2017/11/14/Fearless-Concurrency-In-Firefox-Quantum.html)), and going more popularity and spreading. Rust comes with a memory-safe guaranteed and has more-more efficient and reliable depending it's own ecosystem. 
It has package management called `cargo`, you can think it's like `npm` for node (again).
Rust itself has no garbage collector, instead using ownership concept like borrowing and slices. Maybe this concept is hard at first because it affects the way you're thinking about how you write the code, but it has a big advantage that Rust provide including memory-safety and efficiency, so you got the real efficiency.

Rust also has a smart and very descriptive compiler, that really helps you out of trouble. Intead telling you a "wrong code program" message, rust giving you an understandable context with descriptive content, It is benefits you more when you in a learning process, and because developer spent more time in debugging this could be a good process because once you finish with your code it means your code valid in a long term of running on production.

Comparing Rust-lang with Golang is like we comparing Apple with Orange, they have a different purpose, style and ecosystem. Rust in other way is a system programming with order to replacing C++ language with a modern tools. Golang still the easiest option if you want a highly productive and ready-to-build an application with more benefit in concurrency and cpu-intensive rather than using node. 
But like i said before, use the right tool for the job. It helps you so much in the future, preventing you from doing a repetitive actions that messing your time and team.

Cheers.


