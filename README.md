# LuaJIT Almanac

This project is a modest attempt into putting together a bit of LuaJIT history
and current related information together in order to help people interested
in the subject to understand the when's, why's and how's of the project.

**Note:** *pull requests* are extremely helpful and needed. I (the author) did not
participate in 99%+ of the history of LuaJIT. So, what I compile here
by myself are information gathered by a bystander.

## What Is Lua

[Lua](https://en.wikipedia.org/wiki/Lua_(programming_language)) is a [programming language](https://en.wikipedia.org/wiki/Programming_language) developed in [Brazil](https://en.wikipedia.org/wiki/Brazil), created by [Roberto Ierusalimschy](https://en.wikipedia.org/wiki/Roberto_Ierusalimschy), sponsored by the [PUC Rio University](https://en.wikipedia.org/wiki/Pontifical_Catholic_University_of_Rio_de_Janeiro).

As a programming language, Lua is well known for its minimalistic design, readability and powerful features. Despite created with the purpose of being the most portable programming language, having as only dependency to be built a ANSI C compiler, its use has expanded outside its niches into web development, data analysis, gaming and others.

With the increased usage and expansion, shortcomings as lower library availability and performance became more visible. Projects like [LuaRocks](https://luarocks.org/) and "awesome" repositories in github have been tackling these issues with good results.

Concerns on performance have been addressed in recent versions of Lua, mostly with improvements on the garbage collector strategy. Outside of the main language repository, we have [Pallene](https://github.com/pallene-lang/pallene) as a approach into solving performance issues with Lua in a predictable way.

The most widespread and used, to date, approach to improve Lua code performance right now is the [LuaJIT project](http://luajit.org/), which supports Lua 5.1 code (with some caveats). Whenever someone says Lua is the fastest scripting language to date, they do so because of LuaJIT **and its forks**.

## What Is A JIT

## What Is LuaJIT

## Why Does It Matter?

## A Bit Of History

## Is LuaJIT Dead?

# Forks

* [RaptorJIR](https://github.com/raptorjit/raptorjit)
* [LuaJIT2](https://github.com/openresty/luajit2)
* [LuaVela](https://github.com/iponweb/luavela)
* [MoonJIT](https://github.com/moonjit/moonjit)

## Why Fork

## Why Not Fork

## What To Know If You Want To Fork

# Benchmarks

- http://luajit.org/performance.html
- https://github.com/kostya/benchmarks
- https://eklausmeier.wordpress.com/2016/04/05/performance-comparison-c-vs-lua-vs-luajit-vs-java/

# Projects That Depend on LuaJIT

# Links

- [LjTools](https://github.com/rochus-keller/LjTools) - parser, browser, assembler and test VM for LuaJIT 2.0 bytecode