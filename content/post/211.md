---
title: 'Read it or Throw it #211'
date: 2019-05-18T10:10:00.002-07:00
draft: false
---

1. [GitHub Package Registry: Your packages, at home with their code](https://github.com/features/package-registry)

This is a big deal since GitHub continues to expand its services after the [GitHub Actions](https://developer.github.com/actions/).

  

That's one of the reasons that [private repositories are free](https://techcrunch.com/2019/01/07/github-free-users-now-get-unlimited-private-repositories/) since GitHub wants to attract customers and make them pay for the ecosystem services

  

  

2. [Announcing WAPM: The WebAssembly Package Manager (Wasmer)](https://medium.com/wasmer/announcing-wapm-the-webassembly-package-manager-18d52fae0eea)

This also a big deal since Web Assembly is the future universal bytecode not only of the internet

but probably of Desktop-apps / smartphones apps/god knows

  

Even though Web Assembly is still considered in an early stage, it's spec (see next item), browsers adoption, out of the browser Runtimes is getting a lot of momentum. 

  

  

3. [Standardizing WASI: A system interface to run WebAssembly outside the web (Mozilla)](https://hacks.mozilla.org/2019/03/standardizing-wasi-a-webassembly-system-interface/)

Continuing the previous item, Mozilla announced WASI, a specification for running web assembly programs outside of the browser.

  

Imagine having a C++/Rust/Go/another language that is being compiled to Web-Assembly

(LLVM already supports that).

  

Then the Runtimes hosting the WebAssembly file will come out of the box with implementation

for the system-calls interface. 

  

It means that we could not only run our programs but also switch between WASM runtimes as long as they implement the WASI interface.

  

  

4. [Announcing Lucet: Fastly’s native WebAssembly compiler and runtime](https://www.fastly.com/blog/announcing-lucet-fastly-native-webassembly-compiler-runtime)

One day after Mozilla announcing the WASI standard Fastly announces its WASM runtime that implements WASI. (they have been working closely with Mozilla for months before going public). 

  

The future of CDNs is executing code on the edge, and what could be more suitable for the mission then running a WASM file on the edge? 

  

We'll be able to develop our code in a lot of programming languages and run execute WASM files.

  

Current Serverless seems like old tech already ![😛](https://mail.google.com/mail/e/1f61b)

  

  

5. [Ruby 3 progress update: types will be part of Ruby 3 stdlib source! ](https://twitter.com/darkdimius/status/1119115657776209920)

Stripe owns a very big Ruby codebase and they internally developed type-checking extensions in order to increase the code quality. (like TypeScript did for Java-Script). 

  

This project will become an official part of Ruby 3 

  

This is very cool, I love that Ruby is getting better doesn't stand still.  
I also think it'll hurt badly the [Crystal Programming Language](https://crystal-lang.org/) adoption

  

  

6. [My Key Learnings after 30,000 LOC in Rust (Dotan Nahum)](https://medium.com/@jondot/my-key-learnings-after-30-000-loc-in-rust-a553e6403c19)

A fantastic article about what it feels like getting into Rust when coming from any other programming language.

It talks about overcoming obstacles and frustration, learning new thinking paradigms and the benefits of knowing Rust

  

  

7. [awesome](https://github.com/sindresorhus/awesome) 

There are many _awesome-XXXX_ repositories in Github,  
but this one is a list of all the_ awesome-XXXX_

  

  

8. [sourcegraph - Search, navigate, and review code](https://sourcegraph.com/)

Recently I've started using this tool a lot (I was aware of it but never gave it a serious chance).

  

I find it much better than reading code via GitHub. 

(most of the times, I don't want to clone locally code and read it on my computer)

  

  

9. [Is Mastery More Like a Wedge or a Knife? (Scott H Young)](https://www.scotthyoung.com/blog/2019/05/08/wedge-and-knife/)

I'm a long-time reader of Scott-H-Young blog and I appreciate much his work. 

This article worth your read

  

  

10. [IPFS - Simply Explained (YouTube)](https://www.youtube.com/watch?v=5Uj6uR3fp-U)

Less than 10 minutes short video explaining what's IPFS for dummies.

You can think about it like Bittorent next generation.

  

  

  

A complex system that works is invariably found to have evolved from a simple system that worked. A complex system designed from scratch never works and cannot be patched up to make it work. You have to start over, beginning with a working simple system. 

John Gall