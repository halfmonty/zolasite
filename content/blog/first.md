+++
title = "My First Post"
date = 2022-12-13
[taxonomies]
categories=["blog"]
tags=["blog", "meta"]
[extra]
toc=true
+++

# Introductions

Hi, I'm Half Monty. What is a Half Monty? Well, something not quite a full-monty, I suppose. Why the pseudonym? I work for a pretty well known fortune 500 company and while I don't anticipate saying anything controversial, we live in a time where even accidents or misunderstandings can years later cause an outrage and uproar and for people to come after you and your job because of something you said. I value my job and I want to protect future me from dumb me today.

## Who Am I?

I'm a guy who's just trying to learn how to be better at what I do. I'm a true professional full stack developer and it's fun and terrible all at the same time. That means I write solutions and implement every part of the process, from architecture, to designing data structures, building schemas and interacting with databases, writing backends, writing frontend, packaging into docker images, writing ci/cd pipelines, writing tests and unfortunately even managing infrastructure. 

## Experience

In my line of work, often time-to-market is what drives the most value. I started my career in C# .Net and have transitioned to Node.js with typescript to write many frontends and backends. I generally enjoy Node and typescript but the ecosystem is a problem in a corporate environment. Most of what my work team provides is solutions to many different problems. Unfortunately with many solutions to many problems using Node means having many things to constanty keep up with various libraries and versions and deprecations. This is no problem when you are working on a handful of tools but my team has ~100. 

## Rust

I unfortunately cannot yet make the case for adopting rust and requiring that skillup in my work team but it's been on my radar and I've been trying to skill myself up over time in my personal time. I imagine most of what I'll find myself writing here is going to be about Rust. Why? Rust works, works fast and works well. When you spend your valuable time creating a bit of Rust code, you don't then have to spend more valuable time constantly working to keep it up to date. It will always build and work with Rust's promise of backwards compatibile compilation and even deprecated libraries/crates shouldn't prevent a build from succeeding thanks to the cargo.lock file and the crate repo hanging on to old crates. 

You can actually confidently build an application or service to "completion" and avoid TLM and maintenance hell. This alone is an incredible draw for me to Rust but it's filled with so many other desireable features.

## Intentions For This Blog

This blog is very a low friction way for me to record thoughts on topics, progress I've made in various areas and a way to document things I've figured out so that I don't have to figure them out again.

I'm going to treat this much like a diary where the intended audience is future me, but written as if someone else may read it and potentially glean some value.

## This Blog

This blog is a static site generator written in Rust called Zola that takes template files and markdown files and spits out a pretty site for you. I'm currently using a theme called blow that I thought was pretty attractive and supports things like colored code examples

```rust
fn main() {
    println!("Hello, world!");
}
```

In the future I would very much like to write my own static site generator in rust or at the very least my own theme. We'll see how I get along in future posts.