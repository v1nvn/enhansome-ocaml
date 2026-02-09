# Awesome OCaml

<img src="colour-logo.png" width="70%" />

> ***Everything you'll ever need on the road to mastering OCaml.***

A curated list of references to awesome OCaml tools, frameworks, libraries, and articles. Additionally, there is a collection of freely available [**books**](https://github.com/rizo/awesome-ocaml/tree/master/books) ⭐ 3,045 | 🐛 4 | 📅 2025-11-05, [**papers**](https://github.com/rizo/awesome-ocaml/tree/master/papers) ⭐ 3,045 | 🐛 4 | 📅 2025-11-05, and [**presentations**](https://github.com/rizo/awesome-ocaml/tree/master/presentations) ⭐ 3,045 | 🐛 4 | 📅 2025-11-05.

If you're looking for comprehensive community-driven content about OCaml, visit 📚[OCamlverse](https://ocamlverse.github.io/)!

For a quick introduction to the modern OCaml development workflow, consult the [**Up and Running with OCaml**](https://ocaml.org/learn/tutorials/up_and_running.html) tutorial.

Your favorite package is not listed? Fork and [create a Pull Request](https://github.com/rizo/awesome-ocaml/edit/master/README.md) ⭐ 3,045 | 🐛 4 | 📅 2025-11-05 to add it!

## Contents

* [Community](#community)
* [Algorithms and Data Structures](#algorithms-and-data-structures)
* [Application Libraries](#application-libraries)
* [Benchmarking](#benchmarking)
* [Blogs](#blogs)
* [Books](#books)
* [Videos](#videos)
* [Code Analysis and Linters](#code-analysis-and-linters)
* [Compilers and Compiler Tools](#compilers-and-compiler-tools)
* [Concurrency](#concurrency)
* [Databases](#databases)
* [Datetime](#datetime)
* [Developer Tools](#developer-tools)
* [Exercises and Short Examples](#exercises-and-short-examples)
* [Formal Software Verification](#formal-software-verification)
* [General](#general)
* [Graphics](#graphics)
* [Internationalization](#internationalization)
* [User Interface](#user-interface)
* [Language-related](#language-related)
* [Large Source Code Examples](#large-source-code-examples)
* [Logging](#logging)
* [Machine Learning](#machine-learning)
* [Messaging](#messaging)
* [Metaprogramming](#metaprogramming)
* [Metrics](#metrics)
* [Mobile Applications](#mobile-applications)
* [Networking](#networking)
* [Online Courses](#online-courses)
* [Package Management](#package-management)
* [Parallelism](#parallelism)
* [Project Starter Templates](#project-starter-templates)
* [Printers helpers](#printers-helpers)
* [Questions](#questions)
* [Regular Expressions](#regular-expressions)
* [Science and Technical Computing](#science-and-technical-computing)
* [Security and Cryptography](#security-and-cryptography)
* [Semantic Technology](#semantic-technology)
* [Serialization](#serialization)
* [System Programming](#system-programming)
* [Testing](#testing)
* [Utilities](#utilities)
* [Web Development](#web-development)

***

## Community

* [Official OCaml Website](https://ocaml.org/)
* [OCaml Discourse Web Forum](https://discuss.ocaml.org/)
* [OCaml Discord Chat](https://discord.gg/ZBgYuvR)
* [Official OCaml Mailing List](https://inbox.ocaml.org/caml-list/)
* [OCaml Planet](https://ocaml.org/community/planet/)
* [OCaml SubReddit](https://www.reddit.com/r/ocaml/)

## Algorithms and Data Structures

* [ODiff](https://github.com/dmtrKovalenko/odiff) ⭐ 2,793 | 🐛 14 | 🌐 Zig | 📅 2025-12-22 – Library of [YIQ NTSC transmission image difference alghoritm](http://www.progmat.uaem.mx:8080/artVol2Num2/Articulo3Vol2Num2.pdf) implemented in OCaml and ReasonML.
* [OCamlgraph](https://github.com/backtracking/ocamlgraph) ⭐ 244 | 🐛 21 | 🌐 OCaml | 📅 2025-10-28 – A generic graph library for OCaml.
* [Decompress](https://github.com/mirage/decompress) ⭐ 118 | 🐛 9 | 🌐 OCaml | 📅 2025-01-08 - A pure OCaml implementation of Zlib.
* [ods](https://github.com/owainlewis/ods) ⭐ 54 | 🐛 1 | 🌐 OCaml | 📅 2026-01-13 – A large collection of data structures and algorithms for OCaml.
* [Ke](https://github.com/mirage/ke) ⭐ 51 | 🐛 0 | 🌐 HTML | 📅 2024-02-26 - Fast implementation of queue (FIFO) in OCaml.
* [combine](https://github.com/backtracking/combine) ⭐ 35 | 🐛 3 | 🌐 OCaml | 📅 2025-05-27 – OCaml library for combinatorics <https://www.lri.fr/~filliatr/combine/>.
* [ORaft](https://github.com/komamitsu/oraft) ⭐ 31 | 🐛 3 | 🌐 OCaml | 📅 2023-08-18 - Library of [Raft consensus algorithm](https://raft.github.io/raft.pdf) implemented in OCaml
* [Duff](https://github.com/mirage/duff) ⭐ 20 | 🐛 0 | 🌐 OCaml | 📅 2024-11-26 - Implementation of Rabin's fingerprint and delta compression by P. MacDonald in OCaml (same as [libXdiff](http://www.xmailserver.org/xdiff-lib.html)
* [Comparing a Machine Learning Algorithm Implemented in F# and OCaml](https://philtomson.github.io/blog/2014-05-29-comparing-a-machine-learning-algorithm-implemented-in-f-sharp-and-ocaml/)

## Application Libraries

* [Core](https://github.com/janestreet/core) ⭐ 1,201 | 🐛 13 | 🌐 OCaml | 📅 2026-01-15 – Jane Street Capital's full-fledged standard library overlay. A portable subset of Core is also available: [Core\_kernel](https://github.com/janestreet/core_kernel) ⭐ 219 | 🐛 8 | 🌐 OCaml | 📅 2026-01-15.
* [Base](https://github.com/janestreet/base) ⭐ 1,007 | 🐛 21 | 🌐 OCaml | 📅 2026-01-15 - Jane Street Capital's dependency-free, quick-compiling, fully-portable across any environment that can run OCaml code standard library.
* [Batteries Included](https://github.com/ocaml-batteries-team/batteries-included) ⭐ 520 | 🐛 90 | 🌐 OCaml | 📅 2025-10-07 – A community-maintained foundation library for your OCaml projects.
* [ocaml-containers](https://github.com/c-cube/ocaml-containers) ⭐ 516 | 🐛 26 | 🌐 OCaml | 📅 2026-02-08 – A lightweight, modular standard library extension, string library, and interfaces to various libraries (bigarrays, Unix, etc.) BSD license.
* [Cmdliner](https://github.com/dbuenzli/cmdliner) ⭐ 329 | 🐛 15 | 🌐 OCaml | 📅 2026-01-21 – Declarative definition of command line interfaces for OCaml.
* [ocaml-rpc](https://github.com/mirage/ocaml-rpc) ⭐ 98 | 🐛 12 | 🌐 OCaml | 📅 2025-12-11 – Light library to deal with RPCs in OCaml.
* [easy-format](https://github.com/mjambon/easy-format) ⭐ 43 | 🐛 10 | 🌐 OCaml | 📅 2022-06-04 – Pretty-printing library for OCaml.
* [Minicli](https://github.com/UnixJunkie/minicli) ⭐ 31 | 🐛 2 | 🌐 OCaml | 📅 2020-10-07 – Minimalist library for command-line parsing.
* [React](http://erratique.ch/software/react) – React is an OCaml module for functional reactive programming (FRP). It provides support for programs with time-varying values, declarative events, and signals.

## Benchmarking

* [core\_bench](https://github.com/janestreet/core_bench) ⭐ 56 | 🐛 12 | 🌐 OCaml | 📅 2026-01-15 – Micro-benchmarking library for OCaml by Jane Street.
    - [Getting Started with Core\_bench](https://github.com/janestreet/core_bench/wiki/Getting-Started-with-Core_bench) ⭐ 56 | 🐛 12 | 🌐 OCaml | 📅 2026-01-15
* [benchmark](https://github.com/Chris00/ocaml-benchmark) ⭐ 32 | 🐛 4 | 🌐 OCaml | 📅 2025-01-31 – Benchmarking functions for measuring the run-time of functions using latency or throughput.

## Blogs

* [Gagallium](http://gallium.inria.fr/blog/)
* [Type OCaml – Many things about OCaml](http://typeocaml.com/)
* [OCaml Platform](https://opam.ocaml.org/blog/)
* [Drup's Thingies](https://drup.github.io/)
* [Thomas Letan’s articles about OCaml](https://soap.coffee/~lthms/tags/ocaml.html)

## Books

* [More OCaml: Algorithms, Methods, and Diversions](https://www.amazon.com/More-OCaml-Algorithms-Methods-Diversions/dp/0957671113/) – In More OCaml, John Whitington takes a meandering tour of functional programming with OCaml, introducing various language features and describing some classic algorithms. The book ends with a large-scale example dealing with the production of PDF files. There are questions for each chapter, along with worked-out answers and hints.
* [How to Think Like a (Functional) Programmer](http://www.greenteapress.com/thinkocaml/index.html) by Allen Downey and Nicholas Monje – How to Think Like a Computer Scientist is an introductory programming textbook based on the OCaml language. It is a modified version of Think Python by Allen Downey. It is intended for newcomers to programming and also those who know some programming but want to learn programming in the function-oriented paradigm, or those who simply want to learn OCaml.
* [OCaml from the Very Beginning](http://ocaml-book.com/) by J. Whitington - OCaml from the Very Beginning will appeal both to new programmers and experienced programmers eager to explore functional languages such as OCaml.
* [Pearls of Functional Algorithm Design](https://www.amazon.co.uk/Pearls-Functional-Algorithm-Design-Richard/dp/0521513383) by Richard Bird - It summarizes 30 hard algorithmic problems in the function programming world. Although it is for Haskell, the algorithm problems are very interesting, and trying to solve them in OCaml also helps the thinking of functional programming. Partial solutions in OCaml are [here](https://github.com/MassD/pearls) ⭐ 28 | 🐛 0 | 🌐 OCaml | 📅 2015-01-16.
* [Real World OCaml](https://realworldocaml.org/) by Y. Minsky, A. Madhavapeddy, and J. Hickey - Functional Programming for the masses.
* [Unix System Programming in OCaml](https://ocaml.github.io/ocamlunix/) by X. Leroy and D. Rémy – Introduction to Unix Systems Programming, with an emphasis on communications between processes.
* [Using, Understanding, and Unraveling OCaml](https://caml.inria.fr/pub/docs/u3-ocaml) – This book describes both the OCaml language and the theoretical grounds behind its powerful type system.
* [Purely Functional Data Structures](https://www.amazon.co.uk/Purely-Functional-Structures-Chris-Okasaki/dp/0521631246/ref=sr_1_1?ie=UTF8\&qid=1406279836\&sr=8-1\&keywords=functional+data+structures) - This is the first or only book focus on various data structures in FP world. A must-read one.
* [OCaml for Scientists](http://www.ffconsultancy.com/products/ocaml_for_scientists/) - by Jon Harrop.
* [OCaml Programming: Correct + Efficient + Beautiful](https://cs3110.github.io/textbook) - Textbook on Functional Programming and Data Structures in OCaml - by Michael R. Clarkson et al.

## Videos

 - [OCaml Programming: Correct + Efficient + Beautiful](https://www.youtube.com/playlist?list=PLre5AT9JnKShBOPeuiD9b-I4XROIJhkIU) - List of 200 bite-sized videos recorded by Michael R. Clarkson. It can be watched independently of the textbook titled the same and listed above in the [Books section](#books).

## Code Analysis and Linters

* [flow](https://github.com/facebook/flow) ⭐ 22,216 | 🐛 618 | 🌐 OCaml | 📅 2026-02-08 - flow is a static type checker for JavaScript.
* [Infer](https://github.com/facebook/infer) ⭐ 15,517 | 🐛 407 | 🌐 OCaml | 📅 2026-02-07 - Infer is a static analyzer for Java, C and Objective-C
* [SLAyer](https://github.com/Microsoft/SLAyer) ⚠️ Archived - SLAyer is an automatic formal verification tool that uses separation logic to verify memory safety of C programs.
* [coq-of-ocaml](https://github.com/formal-land/coq-of-ocaml) ⭐ 270 | 🐛 18 | 🌐 OCaml | 📅 2024-08-05 - Translator from OCaml to Coq to formally verify OCaml code.
* [pfff](https://github.com/returntocorp/pfff) ⚠️ Archived – pfff is a set of tools and APIs to perform some static analysis, dynamic analysis, code visualizations, code navigations, or style-preserving source-to-source transformations such as refactorings on source code.
* [Camelot](https://github.com/upenn-cis1xx/camelot) ⭐ 45 | 🐛 8 | 🌐 OCaml | 📅 2025-09-12 - Camelot is a modular and fully configurable OCaml linter and stylechecker.
* [MemCAD](https://github.com/Antique-team/memcad) ⭐ 27 | 🐛 0 | 📅 2021-10-15 - MemCAD is an abstract interpreter for shape analysis. MemCAD can verify C programs manipulating complex data structures.
* [Mascot](http://mascot.x9c.fr/) - Mascot is a style-checker for OCaml sources.
* [Frama-C](http://frama-c.com) - Frama-C is a static analysis and formal proof framework for C and C++.
* [MOPSA](https://gitlab.com/mopsa/mopsa-analyzer) - MOPSA is a generic framework for building sound static analyzers based on the theory of abstract interpretation.

## Program analysis

* [BAP](https://github.com/BinaryAnalysisPlatform/bap) ⭐ 2,212 | 🐛 42 | 🌐 OCaml | 📅 2025-04-30 - BAP is a reverse engineering and program analysis platform that targets binary programs.
* [BinCat](https://github.com/airbus-seclab/bincat) ⭐ 1,847 | 🐛 18 | 🌐 OCaml | 📅 2025-02-25 - BinCat is a binary code static analysis toolkit.
* [cwe\_checker](https://github.com/fkie-cad/cwe_checker) ⭐ 1,317 | 🐛 27 | 🌐 Rust | 📅 2025-04-10 - cwe\_checker finds vulnerable patterns in binary executables.
* [Owi](https://github.com/OCamlPro/owi) ⭐ 280 | 🐛 143 | 🌐 OCaml | 📅 2026-02-04 - Owi is a toolchain for working with WebAssembly (Wasm) in OCaml, featuring a powerful, parallel symbolic execution engine for Wasm. It also provides frontends for compiling and analyzing C and Rust programs.
* [Smt.ml](https://github.com/formalsec/smtml) ⭐ 59 | 🐛 43 | 🌐 OCaml | 📅 2026-02-06 - Smt.ml is a frontend OCaml library that interfaces with multiple SMT solvers, enabling seamless integration of solvers like Z3, cvc5, Colibri2, Bitwuzla, and Alt-Ergo within OCaml programs.

## Compilers and Compiler Tools

* **Parser and Lexer Generators**:
  * [Angstrom](https://github.com/inhabitedtype/angstrom) ⭐ 698 | 🐛 13 | 🌐 OCaml | 📅 2024-09-12 - Parser combinators built for speed and memory efficiency
  * [Sedlex](https://github.com/ocaml-community/sedlex) ⭐ 263 | 🐛 20 | 🌐 OCaml | 📅 2025-11-24 is a modern, encoding-agnostic (read: Unicode-supporting) lexer generator (the ppx-based successor to [ulex](http://www.cduce.org/download.html#side).)
  * [Opal](https://github.com/pyrocat101/opal) ⭐ 152 | 🐛 3 | 🌐 OCaml | 📅 2023-07-24 – Self-contained monadic parser combinators for OCaml.
  * [Menhir](http://gallium.inria.fr/~fpottier/menhir/) – Menhir is a LR(1) parser generator for OCaml.
    * See [ocaml-parsing](https://github.com/smolkaj/ocaml-parsing) ⭐ 127 | 🐛 0 | 🌐 OCaml | 📅 2024-05-06 for a clearer example of using Menhir and Sedlex to produce a useful parser,
    * ... and [Obelisk](https://github.com/Lelio-Brun/Obelisk) ⭐ 61 | 🐛 0 | 🌐 OCaml | 📅 2025-11-29, a neat project to produce readable LaTeX, HTML, or plain-text EBNF-style documentation for your grammar.
  * [ocamllex/ocamlyacc](http://caml.inria.fr/pub/docs/manual-ocaml-4.01/lexyacc.html) – lex and yacc implementation for OCaml.

* **Languages and Compilers**:
  * [Rhine](https://github.com/artagnon/rhine-ml) ⚠️ Archived – A Lisp on LLVM written in OCaml.

  * [Mazeppa](https://github.com/mazeppa-dev/mazeppa) ⭐ 466 | 🐛 1 | 🌐 OCaml | 📅 2025-12-05 - A modern supercompiler for call-by-value functional languages.

  * [Quick C-- Target Language](http://www.cminusminus.org/) - It is now a dead project. [Github Repo](https://github.com/nrnrnr/qc--) ⚠️ Archived. [Alternative website](http://www.cs.tufts.edu/~nr/c--/qc--.html).

  * [Liquid ML](https://github.com/benfaerber/liquid-ml) ⭐ 49 | 🐛 0 | 🌐 OCaml | 📅 2025-11-26 - Shopify's Liquid Templating language for OCaml.

  * [Caramel](https://caramel.run/) - Caramel is a functional language for building type-safe, scalable, and maintainable applications.

  * [cDuce](http://www.cduce.org/) - cDuce is a modern XML-oriented functional language with innovative features.

  * [Compcert C Compiler](http://compcert.inria.fr/) - It is a C Compiler supporting most of the ISO C90 and C99 / ANSI C  features.

  * [Eff Programming Language](http://www.eff-lang.org/) - Eff is a functional language with handlers of not only exceptions, but also of other computational effects such as state or I/O.

  * [Hack Programming Language](https://hacklang.org/)

  * [Haxe Programming Language](https://haxe.org/)

  * [Neko Programming Language](https://nekovm.org/) - Originally the compiler was written in OCaml.

  * [Mezzo Programming Language](https://protz.github.io/mezzo/) - Mezzo is a programming language in the ML tradition, which places strong emphasis on the control of aliasing and access to mutable memory.

  * [OCaml-Java](http://www.ocamljava.org/) - OCaml to Java bytecode compiler.

  * [Opa Programming Language](http://opalang.org/)

  * [Rust Programming Language](https://www.rust-lang.org/) - Originally written in OCaml before bootstrapping.

  * [tis-interpreter](https://github.com/TrustInSoft/tis-interpreter) - An interpreter for finding subtle bugs in programs written in standard C

  * [Reason](http://facebook.github.io/reason/) - Friendly syntax & toolchain for OCaml by Facebook.

  * [RaML](http://raml.co/index.html) - Resource Aware ML (RaML) is a tool that automatically and statically computes resource-use bounds for OCaml programs.

* **Articles**:
  * [Kaleidoscope: Implementing a Language with LLVM in Objective Caml¶](http://llvm.org/docs/tutorial/OCamlLangImpl1.html)

## Concurrency

Before OCaml 5.0, there were two libraries for concurrent programming: *Lwt* and *Async*. They provide very similar functionality but make radically different decisions with regards to error handling and internal implementation details (see the links below for more details). [Real World OCaml](https://realworldocaml.org/) uses Async, but a version of the [code examples translated to Lwt](https://github.com/dkim/rwo-lwt) ⭐ 106 | 🐛 0 | 🌐 OCaml | 📅 2017-06-04 is also available.

With the introduction of [Effect Handlers](https://ocaml.org/manual/effects.html) in OCaml 5.0, a bunch of other libraries have been created for concurrent programming, replacing the monadic approaches of LWT and Async with direct-style ones.

* **Libraries**:
  * [Eio](https://github.com/ocaml-multicore/eio) ⭐ 673 | 🐛 73 | 🌐 OCaml | 📅 2025-11-04 — effects-based direct-style IO for multicore OCaml.
  * [Miou](https://github.com/robur-coop/miou) ⭐ 131 | 🐛 14 | 🌐 OCaml | 📅 2026-01-27 — a simple scheduler for OCaml 5.
  * [Lwt](http://ocsigen.org/lwt/) — A cooperative threads library for OCaml.
  * [Async](https://opensource.janestreet.com/async/) — A monadic concurrence library to go with the Core library.
* **Articles**:
  * [The blog post that introduced Async](https://blog.janestreet.com/announcing-async/)
  * [A user gives up on Async](http://rgrinberg.com/posts/abandoning-async/)
  * [Cooperative Concurrency in OCaml: A Core.Std.Async Example](http://philtomson.github.io/blog/2014/07/09/core-dot-async-example/).

## Databases

* **New Implementations**
  * [Irmin](https://github.com/mirage/irmin) ⭐ 1,923 | 🐛 141 | 🌐 OCaml | 📅 2026-02-07 — A distributed database that follows the same design principles as Git.
  * [RunOrg](https://github.com/RunOrg/RunOrg) ⭐ 12 | 🐛 6 | 🌐 OCaml | 📅 2015-03-22 - It is a WIP database server written in OCaml.
  * [dokeysto](https://github.com/UnixJunkie/dokeysto) ⭐ 10 | 🐛 1 | 🌐 OCaml | 📅 2025-09-22 - dumb OCaml key-value store, string keys and string
    values. Optional on-the-fly LZ4 compression of values or tokyocabinet backend.
  * [Obigstore](http://obigstore.forge.ocamlcore.org/) — A database with BigTable-like data model atop LevelDB.
* **Overlays**
  * [Caqti](https://github.com/paurkedal/ocaml-caqti) ⭐ 348 | 🐛 6 | 🌐 OCaml | 📅 2026-01-02 - Cooperative-threaded access to relational data
  * [Caqti setence preparation, ppx\_rapper](https://github.com/roddyyaga/ppx_rapper) ⭐ 153 | 🐛 18 | 🌐 OCaml | 📅 2025-09-01
  * [Sequoia](https://github.com/andrenth/sequoia) ⭐ 130 | 🐛 10 | 🌐 OCaml | 📅 2022-12-23 - Sequoia is a type-safe query builder for MySQL/MariaDB and PostgreSQL
  * [ORM](https://github.com/mirage/orm) ⭐ 61 | 🐛 4 | 🌐 OCaml | 📅 2018-11-15 — ORM for SQLite.
  * [Macaque](https://github.com/ocsigen/macaque) ⭐ 38 | 🐛 12 | 🌐 OCaml | 📅 2019-11-18 — Macaque is a library for safe and flexible database queries using comprehensions on top of PG'OCaml.
* **Bindings**
  * [SQLite3](https://github.com/mmottl/sqlite3-ocaml) ⭐ 129 | 🐛 3 | 🌐 OCaml | 📅 2025-11-28 — OCaml bindings to the SQLite3 database.
  * [pgx](https://github.com/arenadotio/pgx) ⭐ 128 | 🐛 19 | 🌐 OCaml | 📅 2022-10-26 – A pure OCaml PostgreSQL client library.
  * [ocaml-redis](https://github.com/0xffea/ocaml-redis) ⭐ 82 | 🐛 3 | 🌐 OCaml | 📅 2025-05-21 – Redis bindings for OCaml.
  * [mariadb](https://github.com/ocaml-community/ocaml-mariadb) ⭐ 57 | 🐛 3 | 🌐 OCaml | 📅 2026-01-19 - Bindings to MariaDB/MySQL, supporting the nonblocking API
  * [PG'OCaml](http://pgocaml.forge.ocamlcore.org/) — A type-safe interface to PostgreSQL in pure OCaml.
    * [ppx\_pgsql](https://github.com/tizoc/ppx_pgsql) ⭐ 55 | 🐛 5 | 🌐 OCaml | 📅 2020-09-04 – A syntax extension for embedded SQL queries using PG'OCaml.
  * [mysql\_protocol](https://github.com/slegrand45/mysql_protocol) ⭐ 14 | 🐛 0 | 🌐 OCaml | 📅 2022-04-12 – Implementation of MySQL Protocol with the Bitstring library.
  * [Dbm](https://forge.ocamlcore.org/projects/camldbm/) — A binding to the NDBM/GDBM Unix "databases".
  * [Mongo.ml](https://massd.github.io/mongo/) – An OCaml driver for Mongodb
  * [PostgreSQL-OCaml](https://mmottl.github.io/postgresql-ocaml/) — An interface to PostgreSQL through the C API (`libpq`).
  * [Sqlite3EZ](https://mlin.github.io/ocaml-sqlite3EZ/) — Thin wrapper for SQLite3 with a simplified interface.
* **Articles**:
  * [Implementing the Binary Memcached Protocol with Ocaml and Bitstring](https://andreas.github.io/2014/08/22/implementing-the-binary-memcached-protocol-with-ocaml-and-bitstring/)
  * [Interfacing OCaml and PostgreSQL with Caqti](https://medium.com/@bobbypriambodo/interfacing-ocaml-and-postgresql-with-caqti-a92515bdaa11)
  * [Finally, Type-Safe, Extensible and Efficient Language Integrated Query](https://www.cs.tsukuba.ac.jp/~kam/papers/pepm2016a.pdf) by Oleg and Co.
    The proposed approach is to describe SQL queries in type-safe manner and optimize them (using term rewriting or normalization-by evaluation) before sending to database engine. It potentially could optimize O(n^2) queries to O(n) ones.

## Datetime

* [ISO8601](https://github.com/sagotch/ISO8601.ml) ⭐ 28 | 🐛 9 | 🌐 OCaml | 📅 2024-02-08
* [odate](https://github.com/hhugo/odate) ⭐ 22 | 🐛 1 | 🌐 OCaml | 📅 2024-04-12
* [calendar](http://calendar.forge.ocamlcore.org/)
* [ptime](http://erratique.ch/software/ptime)

## Developer Tools

* **Editor Integration**:
  * [merlin](https://github.com/ocaml/merlin) ⭐ 1,657 | 🐛 299 | 🌐 OCaml | 📅 2026-02-02 – Context sensitive completion for OCaml in Vim and Emacs.
  * [ocaml-lsp](https://github.com/ocaml/ocaml-lsp) ⭐ 879 | 🐛 162 | 🌐 OCaml | 📅 2026-02-08 - An LSP language server for OCaml that integrates with any editor that understands LSP like [VSCode](https://github.com/microsoft/vscode) ⭐ 181,528 | 🐛 13,581 | 🌐 TypeScript | 📅 2026-02-09, Vim and Emacs.
  * [tuareg](https://github.com/ocaml/tuareg) ⭐ 388 | 🐛 38 | 🌐 Emacs Lisp | 📅 2025-09-10 - OCaml mode for Emacs that can run the toplevel and the debugger within Emacs.
  * [OCaml Debugger](https://github.com/hackwaly/ocamlearlybird) ⭐ 228 | 🐛 24 | 🌐 OCaml | 📅 2025-12-02 – extension that provides OCaml Debugger for [VSCode](https://github.com/microsoft/vscode) ⭐ 181,528 | 🐛 13,581 | 🌐 TypeScript | 📅 2026-02-09
  * [vscode-ocaml](https://github.com/hackwaly/vscode-ocaml) ⚠️ Archived – extension that provides OCaml language support for [VSCode](https://github.com/microsoft/vscode) ⭐ 181,528 | 🐛 13,581 | 🌐 TypeScript | 📅 2026-02-09
  * [merlin-eldoc](https://github.com/Khady/merlin-eldoc) ⭐ 45 | 🐛 5 | 🌐 Emacs Lisp | 📅 2023-02-13 – Emacs package to provide merlin's features through eldoc.
  * [ocp-indent](http://www.typerex.org/ocp-indent.html) – Indentation tool for OCaml, to be used from editors like Emacs and Vim.
    * [Vim plugin](https://github.com/def-lkb/ocp-indent-vim) ⭐ 29 | 🐛 1 | 🌐 Python | 📅 2018-03-23.
  * [Sublime better ocaml](https://github.com/whitequark/sublime-better-ocaml) ⭐ 23 | 🐛 2 | 📅 2018-02-08 – Better OCaml mode for Sublime Text.
    * [Sublime text package](https://github.com/def-lkb/sublime-text-merlin) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2017-06-23
  * [ocp-index](http://www.typerex.org/ocp-index.html) – Easy access to the interface information of installed OCaml libraries. Provides standalone tools like `ocp-browser` and `ocp-grep`.
    * [ocp-index-top](https://github.com/reynir/ocp-index-top) ⭐ 20 | 🐛 9 | 🌐 OCaml | 📅 2025-01-16 – Toplevel directive for looking up documentation using ocp-index.
    * [ocp-browser](http://www.typerex.org/ocp-index.html#ocp-browser) – Small ncurses-based API and documentation browser.
    * [Sublime text package](https://sublime.wbond.net/packages/OCaml%20Autocompletion)
  * [opam-switch-mode](https://github.com/ProofGeneral/opam-switch-mode) ⭐ 9 | 🐛 1 | 🌐 Emacs Lisp | 📅 2023-08-02 - Minor mode for Emacs that extends Tuareg and Merlin with menus to change or reset the opam switch in the ambient Emacs session.

* [utop](https://github.com/ocaml-community/utop) ⭐ 906 | 🐛 117 | 🌐 OCaml | 📅 2025-08-12 – Universal toplevel for OCaml with support for multiline edition, history, real-time and context-sensitive completion, colors, and more.

* [ocamlformat](https://github.com/ocaml-ppx/ocamlformat) ⭐ 699 | 🐛 132 | 🌐 OCaml | 📅 2025-12-08 - A command-line tool to format OCaml code.

* **Foreign Function Interface**:
  * [ctypes](https://github.com/ocamllabs/ocaml-ctypes) ⭐ 402 | 🐛 105 | 🌐 OCaml | 📅 2025-11-06 – Library for binding to C libraries using pure OCaml.
  * [ocaml-main-program-in-c](https://github.com/johnwhitington/ocaml-main-program-in-c) ⭐ 17 | 🐛 0 | 🌐 Shell | 📅 2017-10-03 – Example build system for making mixed C/Ocaml binaries where the main program is in C.
  * [Py.ml](https://github.com/thierry-martinez/pyml) ⭐ 0 | 🐛 0 | 📅 2025-08-29 - OCaml bindings for Python.
  * [Modular foreign function bindings](http://openmirage.org/blog/modular-foreign-function-bindings)

* [learn-ocaml](https://github.com/ocaml-sf/learn-ocaml) ⭐ 322 | 🐛 126 | 🌐 JavaScript | 📅 2025-12-06. Web app (written in OCaml) underlying the learn-ocaml-corpus. Can be customized to serve lectures (with Markdown slides), playgrounds (with a toplevel prelude), and interactive exercises (with OCaml tests). MIT License.

* **Code coverage**:
  * [Bisect\_ppx](https://github.com/aantron/bisect_ppx) ⭐ 314 | 🐛 24 | 🌐 OCaml | 📅 2025-10-12

* [Jupyter](https://github.com/akabe/ocaml-jupyter) ⭐ 306 | 🐛 12 | 🌐 Jupyter Notebook | 📅 2026-02-08 – An OCaml kernel for the Jupyter notebook.

* [OCaml Yeoman Generator](https://github.com/mabrasil/generator-ocaml) ⭐ 22 | 🐛 3 | 🌐 JavaScript | 📅 2018-06-29 – Yeoman generator to scaffold OCaml modules.

* [ghim](https://github.com/samoht/ghim) ⭐ 19 | 🐛 0 | 🌐 OCaml | 📅 2014-05-07 – A command-line tool to manage Github Issues.

* [learn-ocaml.el](https://github.com/pfitaxel/learn-ocaml.el) ⭐ 8 | 🐛 4 | 🌐 Emacs Lisp | 📅 2021-10-14. Minor mode for Emacs that can display exercise topics and grade exercise solutions, after logging to a Learn-OCaml instance. MIT License.

* [puml2xml](https://github.com/khalidbelk/puml2xml) ⭐ 5 | 🐛 0 | 🌐 OCaml | 📅 2025-02-17 – A PlantUML (**.puml**) to XML (**.xmi**) converter.

* [Try OCaml](https://try.ocamlpro.com/) – Try OCaml in your web browser.

* [BetterOCaml](https://betterocaml.ml) – An efficient, intuitive, and cross-platform web IDE with your OCaml code interpreted and running in your browser!

* [codingground](https://www.tutorialspoint.com/compile_ocaml_online.php) – Compile and execute OCaml code online.

* [OCaml: Learn & Code iOS app](https://apps.apple.com/app/ocaml-learn-code/id1547506826) - Learn and execute OCaml code from your iPhone/iPad/Mac.

* [ocamlbrowser](http://caml.inria.fr/pub/docs/manual-ocaml/browser.html) – A source and compiled interface browser, written using LablTk. Included in the standard distribution for ocaml <= 4.01 and with labltk for ocaml >= 4.02.

## Exercises and Short Examples

* [OCaml at Exercism](http://exercism.io/languages/ocaml) – Exercism is your place to engage in thoughtful conversations about code. Explore simplicity, idiomatic language features, and expressive, readable code. [Solutions](https://github.com/exercism/xocaml) ⭐ 104 | 🐛 11 | 🌐 OCaml | 📅 2026-02-01.
* [99 problems](https://ocaml.org/learn/tutorials/99problems.html). 99% of the solutions are [here](https://github.com/MassD/99) ⭐ 56 | 🐛 0 | 🌐 OCaml | 📅 2022-08-01.
* [learn-ocaml-corpus](https://ocaml-sf.org/learn-ocaml-public/#activity=exercises). Corpus of beginner-to-advanced online exercises (including those from the OCaml MOOC) with automatic grading tests.
* [Rosetta Code](http://rosettacode.org/wiki/Category:OCaml)
* [Programming Language Examples Alike Cookbook](http://pleac.sourceforge.net/pleac_ocaml/index.html) - The OCaml section of the book is a free reference for solving common programming problems using OCaml.

## Formal Software Verification

* [Coq](https://coq.inria.fr/) – Coq is a formal proof management system. It provides a formal language to write mathematical definitions, executable algorithms, and theorems, together with an environment for semi-interactive development of machine-checked proofs.
* [Why3](http://why3.lri.fr/) – Why3 is a platform for deductive program verification. It provides a rich language for specification and programming, called WhyML, and relies on external theorem provers, both automated and interactive, to discharge verification conditions.
* [Alt-Ergo](http://alt-ergo.lri.fr/) – Alt-Ergo is an open-source SMT solver dedicated to the proof of mathematical formulas generated in the context of program verification.

## General

* [camlPDF](https://github.com/johnwhitington/camlpdf) ⭐ 220 | 🐛 7 | 🌐 OCaml | 📅 2026-01-30 – OCaml library for reading, writing and modifying PDF files.
* [slacko](https://github.com/Leonidas-from-XIV/slacko) ⭐ 86 | 🐛 8 | 🌐 OCaml | 📅 2024-01-26 – A neat interface for Slack in OCaml.
* [Functional Programming with OCaml](https://haifengl.wordpress.com/2014/06/17/ocaml-introduction/)
* [Python to OCaml: retrospective](http://roscidus.com/blog/blog/2014/06/06/python-to-ocaml-retrospective/)
* [OCaml for the Masses](http://queue.acm.org/detail.cfm?id=2038036)
* [Why We Use OCaml](https://espertech.wordpress.com/2014/07/15/why-we-use-ocaml)
* [Xen – OCaml Coding Considerations](http://wiki.xen.org/wiki/OCaml_Coding_Considerations)
* [Monads are a class of hard drugs](http://lambda-diode.com/programming/monads-are-a-class-of-hard-drugs)
* [Beginner's guide to OCaml](http://blog.nullspace.io/beginners-guide-to-ocaml-beginners-guides.html)
* [Why OCaml, why now?](http://spyder.wordpress.com/2014/03/16/why-ocaml-why-now/)
* [A blog about game development in OCaml](http://cranialburnout.blogspot.ca/)
* [(Functional) Alternatives to inheritance](http://ocamltutorials.blogspot.se/2013/06/alternatives-to-subtyping.html)
* [Learn X in Y minutes](https://learnxinyminutes.com/docs/ocaml/) - Where X=OCaml.

## Graphics

* **2D**
  * [Vg](https://github.com/dbuenzli/vg) ⭐ 99 | 🐛 5 | 🌐 OCaml | 📅 2025-07-29 – Declarative 2D vector graphics for OCaml.
  * [cairo2](https://github.com/Chris00/ocaml-cairo) ⭐ 56 | 🐛 11 | 🌐 OCaml | 📅 2024-11-08 — Binding to Cairo, a 2D Vector Graphics Library. Integrates well with lablgtk.
  * [archimedes](http://archimedes.forge.ocamlcore.org/) — 2D plotting library.
* **3D**
  * [glMLite](https://github.com/fccm/glMLite) ⭐ 19 | 🐛 2 | 🌐 OCaml | 📅 2022-06-30 — OpenGL bindings for OCaml. Provides an (experimental) functional API. ([homepage](http://decapode314.free.fr/ocaml/GL/))
  * [lablgl](https://forge.ocamlcore.org/projects/lablgl/) — Interface to OpenGL. Integrates well with lablgtk.
  * [tgls](http://erratique.ch/software/tgls) — Thin bindings OpenGL 3.{2,3},4.{0,1,2,3,4} and OpenGL ES {2,3}.

## Internationalization

* [Camomile](https://github.com/yoriyuki/Camomile/) ⭐ 124 | 🐛 22 | 🌐 OCaml | 📅 2024-04-01 — A Unicode library for OCaml.
* [ocaml-m17n](https://github.com/whitequark/ocaml-m17n) ⭐ 49 | 🐛 1 | 🌐 OCaml | 📅 2019-05-09 — Multilingualization for OCaml source code. Allows using Unicode identifiers in OCaml source code.
* [Uutf](https://github.com/dbuenzli/uutf) ⭐ 36 | 🐛 1 | 🌐 OCaml | 📅 2025-07-29 — Non-blocking streaming Unicode codec for OCaml.
* [Uunf](https://github.com/dbuenzli/uunf) ⭐ 25 | 🐛 0 | 🌐 OCaml | 📅 2026-01-02 — Unicode text normalization for OCaml.
* [Uuseg](https://github.com/dbuenzli/uuseg) ⭐ 25 | 🐛 2 | 🌐 OCaml | 📅 2026-01-02 — Unicode text segmentation for OCaml.
* [Uucp](https://github.com/dbuenzli/uucp) ⭐ 24 | 🐛 3 | 🌐 OCaml | 📅 2026-01-02 — Unicode character properties for OCaml.
* [Uucd](https://github.com/dbuenzli/uucd) ⭐ 17 | 🐛 0 | 🌐 OCaml | 📅 2026-01-02 — Unicode character database decoder for OCaml.

## User Interface

* [Notty](https://github.com/pqwy/notty) ⭐ 374 | 🐛 22 | 🌐 OCaml | 📅 2024-04-06 - Notty is a declarative terminal library for OCaml, structured around the notion of composable images.
* [Lambda-Term](https://github.com/ocaml-community/lambda-term) ⭐ 224 | 🐛 21 | 🌐 OCaml | 📅 2026-01-14 – Lambda-Term is a cross-platform library for manipulating the terminal. It provides an abstraction for keys, mouse events, and colors, as well as a set of widgets to write curses-like applications.
* [lablqml](https://github.com/Kakadu/lablqml) ⭐ 167 | 🐛 14 | 🌐 OCaml | 📅 2024-02-03 – QML Qt5 bindings for OCaml.
* [ocaml-linenoise](https://github.com/ocaml-community/ocaml-linenoise) ⭐ 54 | 🐛 5 | 🌐 C | 📅 2024-07-29 - Self-contained OCaml bindings to linenoise; easy high-level readline functionality in OCaml.
* [lablgtk](https://garrigue.github.io/lablgtk/) — GTK2 and GTK3 bindings for OCaml with various higher-level facilities to define GUIs.
* [labltk](https://forge.ocamlcore.org/projects/labltk/) — Interface to the Tcl/Tk GUI framework. In the standard distribution for ocaml <= 4.01.
* [TSDL](http://erratique.ch/software/tsdl) – Tsdl is an OCaml module providing thin bindings to the cross-platform SDL library.

## Language-related

* [Higher-Rank Polymorphism in OCaml](http://devmusings.legiasoft.com/blog/2008/05/23/higher-rank_polymorphism_in_ocaml)
* [mikmatch](https://github.com/mjambon/mikmatch) ⭐ 23 | 🐛 2 | 🌐 OCaml | 📅 2023-10-23 – OCaml pattern-matching extended with regexps
* [Inlined records in constructors](https://www.lexifi.com/ocaml/inlined-records-constructors/)
* [Algebraic Data Types](https://espertech.wordpress.com/2014/07/30/algebraic-data-types/)
* [XEN – OCaml Best Practices for Developers](http://wiki.xen.org/wiki/OCaml_Best_Practices_for_Developers)
* [OCaml Style Guide (by Jane Street)](https://opensource.janestreet.com/standards/) - See also: [\[1\]](https://www.seas.upenn.edu/~cis500/cis500-f06/resources/programming_style.html), [\[2\]](http://www.cs.cornell.edu/Courses/cs312/2001sp/style.html), [\[3\]](https://www.seas.upenn.edu/~cis120/20fa/ocaml_style/).
* [A safe but strange way of modifying OCaml compiler](https://camlspotter.blogspot.com/2012/09/a-safe-but-strange-way-of-modifying.html)
* [Fiddling with the OCaml Type System](https://technotroph.wordpress.com/2013/10/25/fiddling-with-the-ocaml-type-system/)

## Large Source Code Examples

* [Oni2](https://github.com/onivim/oni2) ⭐ 7,867 | 🐛 553 | 🌐 Reason | 📅 2022-08-17 - Native, lightweight modal code editor.
* [coq](https://github.com/coq/coq) ⭐ 5,348 | 🐛 2,595 | 🌐 OCaml | 📅 2026-02-07 - formal proof management system
* [mirage](https://github.com/mirage/mirage) ⭐ 2,833 | 🐛 58 | 🌐 OCaml | 📅 2026-01-27 -  library operating system that constructs unikernels for secure, high-performance network applications across a variety of cloud computing and mobile platforms
* [Liquidsoap](https://github.com/savonet/liquidsoap) ⭐ 1,615 | 🐛 289 | 🌐 OCaml | 📅 2026-02-09 - a swiss-army knife for multimedia streaming, notably used for netradios and webtvs
* [Base](https://github.com/janestreet/base) ⭐ 1,007 | 🐛 21 | 🌐 OCaml | 📅 2026-01-15 - Standard library for OCaml
* [libguestfs](https://github.com/libguestfs/libguestfs) ⭐ 703 | 🐛 46 | 🌐 C | 📅 2026-02-05 - library and tools for accessing and modifying virtual machine disk images
* [cil](https://github.com/cil-project/cil) ⭐ 393 | 🐛 32 | 🌐 OCaml | 📅 2023-09-14 - C Intermediate Language
* [xen-api](https://github.com/xapi-project/xen-api) ⭐ 358 | 🐛 102 | 🌐 OCaml | 📅 2026-02-06 - management stack that configures and controls Xen-enabled hosts and resource pools, and co-ordinates resources within the pool.
* [MLDonkey](https://github.com/ygrek/mldonkey) ⭐ 328 | 🐛 54 | 🌐 OCaml | 📅 2025-01-28 - cross-platform multi-network peer-to-peer daemon
* [pfff](https://github.com/returntocorp/pfff) ⚠️ Archived - an OCaml API to write static analysis, dynamic analysis, code visualizations, code navigations, or style-preserving source-to-source transformations such as refactorings on source code.
* [frama-c](https://git.frama-c.com/pub/frama-c) - platform dedicated to the analysis of source code written in C
* [Tezos](https://gitlab.com/tezos/tezos) - a self-upgradable Proof of Stake blockchain
* [WHY3](https://gitlab.inria.fr/why3/why3) - platform for deductive program verification

## Logging

* [dolog](https://github.com/UnixJunkie/dolog) ⭐ 37 | 🐛 2 | 🌐 OCaml | 📅 2023-09-14 – A dumb OCaml logger.
* [Volt](https://github.com/codinuum/volt) ⭐ 8 | 🐛 0 | 🌐 OCaml | 📅 2023-09-14 – A variant of the Bolt OCaml logging tool.
* [Logs](http://erratique.ch/software/logs) - Logs provides a logging infrastructure for OCaml.

## Machine Learning

* **Libraries**
  * [PyTorch bindings](https://github.com/LaurentMazare/ocaml-torch) ⭐ 435 | 🐛 11 | 🌐 OCaml | 📅 2024-10-17 - OCaml bindings for PyTorch.
  * [Ocaml-sklearn](https://github.com/lehy/ocaml-sklearn) ⭐ 36 | 🐛 1 | 🌐 Python | 📅 2020-12-09 scikit-learn for OCaml.
  * [Object detection convolutional neural network with OCaml (based on Owl)](https://github.com/owlbarn/owl_mask_rcnn) ⭐ 19 | 🐛 1 | 🌐 OCaml | 📅 2020-01-30.
  * [Ocaml-NN](https://github.com/ck090/ocaml-nn/tree/main) ⭐ 6 | 🐛 0 | 🌐 OCaml | 📅 2023-12-25 - Fully functional monadic implementation of a Neural Network (FCNNs) in OCaml
  * [Owl](https://ocaml.xyz/) - Scientific library with neural networks, algorithmic differentiation and ONNX support.
* **Articles**
  * [Deep Learning with OCaml (PyTorch bindings)](https://blog.janestreet.com/deep-learning-experiments-in-ocaml/).
  * [Transfer Learning with OCaml (PyTorch bindings)](https://blog.janestreet.com/of-pythons-and-camels/).
  * [Reinforcement Learning with OCaml (PyTorch bindings)](https://blog.janestreet.com/playing-atari-games-with-ocaml-and-deep-rl/).

## Messaging

* [capnp-ocaml](https://github.com/capnproto/capnp-ocaml) ⭐ 103 | 🐛 9 | 🌐 OCaml | 📅 2023-07-19 – OCaml code generator plugin for the Cap'n Proto serialization framework.
* [ocaml-zmq](https://github.com/issuu/ocaml-zmq) ⚠️ Archived – ZeroMQ bindings for OCaml with Async and Lwt wrappers.
* [Kafka](https://github.com/didier-wenzek/ocaml-kafka) ⭐ 71 | 🐛 6 | 🌐 OCaml | 📅 2024-07-08 – OCaml bindings for Apache Kafka.
* [AMQP](https://github.com/andersfugmann/amqp-client) ⭐ 65 | 🐛 0 | 🌐 OCaml | 📅 2024-06-01 – AMQP client library for Async and Lwt.
* [onanomsg](https://github.com/rgrinberg/onanomsg) ⭐ 38 | 🐛 7 | 🌐 OCaml | 📅 2020-10-28 – nanomsg bindings for OCaml.
* [MPI](https://github.com/xavierleroy/ocamlmpi) ⭐ 27 | 🐛 4 | 🌐 OCaml | 📅 2025-01-17 – Message Passing Interface bindings for OCaml.
* [MQTT](https://github.com/j0sh/ocaml-mqtt) ⭐ 19 | 🐛 2 | 🌐 OCaml | 📅 2020-11-25 – OCaml implementation of the MQTT pubsub protocol.

## Metaprogramming

* **Articles**:
  * [A Guide to Extension Points in OCaml](http://whitequark.org/blog/2014/04/16/a-guide-to-extension-points-in-ocaml/)
  * [Extension Points, or how OCaml is becoming more like Lisp](https://blogs.janestreet.com/extension-points-or-how-ocaml-is-becoming-more-like-lisp)
  * [Syntax extensions without Camlp4: let's do it!](https://www.lexifi.com/ocaml/syntax-extensions-without-camlp4-lets-do-it/)
  * [Reading Camlp4 – Ambassador to the Computers](https://ambassadortothecomputers.blogspot.com/p/reading-camlp4.html)
* **Syntax Extensions**:
  * [ppx\_deriving\_yojson](https://github.com/whitequark/ppx_deriving_yojson) ⭐ 166 | 🐛 33 | 🌐 OCaml | 📅 2025-08-11 – A Yojson codec generator for OCaml.
  * [ppx\_import](https://github.com/ocaml-ppx/ppx_import) ⭐ 92 | 🐛 17 | 🌐 OCaml | 📅 2025-10-13 – Import is a syntax extension that allows to pull in types or signatures from other compiled interface files.
  * [ppx\_string\_interpolate](https://github.com/sheijk/ppx_string_interpolate) ⭐ 21 | 🐛 0 | 🌐 OCaml | 📅 2020-05-21 – A simple ppx filter to support string interpolation like `[%str "value of foo is $(foo)"]`.
  * [ppx\_monad](https://github.com/rizo/ppx_monad) ⭐ 7 | 🐛 1 | 🌐 OCaml | 📅 2017-03-07 – Monad syntax extension for OCaml.
* **Tools and Language Extensions**:
  * [MetaOCaml](http://okmij.org/ftp/ML/MetaOCaml.html) – an OCaml dialect for multi-stage programming.
  * [Fan](http://bobzhang.github.io/fan/) – Fan is a compile-time metaprogramming system for OCaml, originally inspired from Camlp4. It's a combination of OCaml and Lispy Macros. It shares the same concrete syntax with OCaml.
  * [camlp5](https://camlp5.github.io/) - Camlp5 is a preprocessor-pretty-printer of OCaml.
  * [camlp4](http://caml.inria.fr/pub/docs/manual-camlp4/manual002.html) - Camlp4 is part of the standard OCaml distribution and is different from Camlp5.

## Metrics

* [prometheus](https://github.com/mirage/prometheus) ⭐ 54 | 🐛 8 | 🌐 OCaml | 📅 2025-12-08 – OCaml client library for Prometheus monitoring.

## Mobile Applications

* **Articles**:
  * [OCaml on iOS 7 Released](http://psellos.com/2014/08/2014.08.ocamlxarm-402.html)
  * [OCaml + Cordova = more secured, typed and hybrid mobile applications](https://dannywillems.github.io/2016/07/14/ocaml-cordova-secured-typed-hybrid-mobile-applications.html)
* **Bindings**:
  * [Cordova plugins](https://github.com/dannywillems/ocaml-cordova-plugin-list) ⭐ 26 | 🐛 1 | 📅 2016-10-21 – List of bindings to Cordova plugins. Get access to native device components like accelerometer, SMS, geolocation, etc in OCaml.

## Networking

* **HTTP Tools**:
  * [ocaml-cohttp](https://github.com/mirage/ocaml-cohttp) ⭐ 770 | 🐛 106 | 🌐 OCaml | 📅 2026-01-15 – Very lightweight HTTP server using Lwt or Async.
  * [httpaf](https://github.com/inhabitedtype/httpaf) ⭐ 535 | 🐛 26 | 🌐 OCaml | 📅 2024-05-27 – A high performance, memory efficient, and scalable web server written in OCaml.
  * [piaf](https://github.com/anmonteiro/piaf) ⭐ 210 | 🐛 16 | 🌐 OCaml | 📅 2025-10-01 - Client/server library for HTTP/1.X / HTTP/2 written entirely in OCaml.
  * [ocurl](https://github.com/ygrek/ocurl) ⭐ 60 | 🐛 8 | 🌐 C | 📅 2025-11-29 – OCaml bindings to libcurl.
* [ocaml-dns](https://github.com/mirage/ocaml-dns) ⭐ 110 | 🐛 20 | 🌐 OCaml | 📅 2025-11-30 – A pure OCaml implementation of the DNS protocol.
* [charrua-unix](https://github.com/haesbaert/charrua-unix) ⚠️ Archived - charrua-unix is a Unix DHCP daemon based on [charrua-core](https://github.com/haesbaert/charrua-core) ⭐ 60 | 🐛 3 | 🌐 OCaml | 📅 2026-01-27.
* [fluent-logger](https://github.com/fluent/fluent-logger-ocaml) ⭐ 8 | 🐛 0 | 🌐 OCaml | 📅 2014-08-30 – Fluentd logger for OCaml.

## Online Courses

* [OCaml MOOC: Introduction to Functional Programming in OCaml](https://www.fun-mooc.fr/en/courses/introduction-functional-programming-ocaml/) - Videos available in [this playlist](https://www.youtube.com/playlist?list=PLTBEN441uEY36t5CCrJkdTSv588d3nWN5) of the [OCaml Software Foundation](https://ocaml-sf.org/) YouTube channel.
* [Cornell University – Data Structures and Functional Programming](http://www.cs.cornell.edu/Courses/cs3110/2014fa/course_info.php).
* [Princeton University - Functional programming in OCaml](http://www.cs.princeton.edu/~dpw/courses/cos326-12/).
* [University of Illinois](https://courses.engr.illinois.edu/cs421/fa2014/) - Course that uses OCaml to teach functional programming and programming language design

## Package Management

* **Build Tools**:
  * [dune](https://github.com/ocaml/dune) ⭐ 1,837 | 🐛 1,049 | 🌐 OCaml | 📅 2026-02-08 – A composable and opinionated build system for OCaml (former jbuilder)
  * [ocaml-makefile](https://github.com/mmottl/ocaml-makefile) ⭐ 80 | 🐛 0 | 🌐 OCaml | 📅 2025-07-21 — Easy to use Makefile for small to medium-sized OCaml-projects.
  * [topkg](https://github.com/dbuenzli/topkg) ⭐ 70 | 🐛 0 | 🌐 OCaml | 📅 2025-11-11 — OPAM-aware packaging system using ocamlbuild.
  * [obuild](https://github.com/ocaml-obuild/obuild) ⭐ 55 | 🐛 36 | 🌐 OCaml | 📅 2026-02-01 – Simple package build system for ocaml.
  * [Bazel](https://github.com/jin/rules_ocaml) ⭐ 39 | 🐛 3 | 🌐 Starlark | 📅 2021-04-22 - OCaml rules for [Bazel](https://bazel.build/), Google's multi-language and platform build tool.
  * [Oasis](http://oasis.forge.ocamlcore.org/) - A tool to integrate a configure, build and install system in your OCaml project. It helps to create standard entry points in your build system and allows external tools to analyse your project easily.
    * [oasis2opam](https://github.com/ocaml/oasis2opam) ⭐ 27 | 🐛 7 | 🌐 OCaml | 📅 2017-10-28 — Tool to convert OASIS metadata to OPAM package descriptions.

* **Distribution**:
  * [esy](https://github.com/esy/esy) ⭐ 855 | 🐛 331 | 🌐 Reason | 📅 2026-02-07 - package.json workflow for native development with Reason/OCaml.
  * [Diskuv OCaml](https://github.com/diskuv/dkml-installer-ocaml#readme) ⚠️ Archived - Diskuv OCaml distribution for Windows.
  * [makorel](https://github.com/sagotch/makorel) ⚠️ Archived – Release OPAM packages easily.
  * [OPAM](http://opam.ocamlpro.com/) – A flexible Git-friendly package manager with multiple compiler support.
  * [ocamlfind](http://projects.camlcity.org/projects/findlib.html) — Local OCaml library manager. Used by most of the OCaml ecosystem.
  * [OCaml for Windows](https://fdopen.github.io/opam-repository-mingw) - opam repository and experimental build for Windows (deprecated since 2021).

## Parallelism

(*Note: Sorted from the easier to use to the more flexible.*)

* **Articles**:
  * [Parallel programming in multicore OCaml](https://github.com/ocaml-multicore/parallel-programming-in-multicore-ocaml) ⭐ 293 | 🐛 6 | 🌐 OCaml | 📅 2024-03-12
  * [Awesome multicore OCaml](https://github.com/ocaml-multicore/awesome-multicore-ocaml) ⭐ 159 | 🐛 2 | 📅 2023-08-30. A compilation of resources
  * [What is the state of OCaml's parallelization abilities?](https://stackoverflow.com/questions/6588500/what-is-the-state-of-ocamls-parallelization-abilities)
  * [Parallelism programming](https://v2.ocaml.org/releases/5.0/htmlman/parallelism.html) from the officiel OCaml manual

* **Libraries**:
  * [SPOC](https://github.com/mathiasbourgoin/SPOC) ⭐ 140 | 🐛 9 | 🌐 HTML | 📅 2026-01-22 - Libraries and syntax extensions to offload intensive computations to parallel accelerators (multicore CPUs, GPUs and other accelerators compatible with GPGPU frameworks).
  * [Parany](https://github.com/UnixJunkie/parany) ⭐ 54 | 🐛 1 | 🌐 OCaml | 📅 2023-10-05 – Parallelize computation over independent items, even if there is an infinite number of them.
  * [Rpc.Parallel](https://github.com/janestreet/rpc_parallel) ⭐ 50 | 🐛 2 | 🌐 OCaml | 📅 2026-01-15 — A library for spawning processes on a cluster of machines, and passing typed messages between them.
  * [Nproc](https://github.com/MyLifeLabs/nproc) ⭐ 30 | 🐛 4 | 🌐 OCaml | 📅 2013-08-28 – Process pool implementation for OCaml.
  * [ForkWork](https://github.com/mlin/forkwork) ⭐ 17 | 🐛 4 | 🌐 OCaml | 📅 2019-09-09 — A simple library for forking child processes to perform work on multiple cores.
  * [Parmap](http://rdicosmo.github.io/parmap/) — Provides easy-to-use parallel map and fold functions.
  * [Functory](http://functory.lri.fr/About.html) — A distributed computing library which facilitates distributed execution of parallelizable computations in a seamless fashion.
  * [Ocamlnet](http://projects.camlcity.org/projects/ocamlnet.html) — An enhanced system platform library. Contains the `netmulticore` library to compute tasks on as many cores of the machine as needed.
  * [Sklml](http://sklml.inria.fr) – Functional parallel skeleton compiler and programming system for OCaml programs.

## Printers helpers

* [**dyn** ](https://github.com/ocaml/dune/blob/4b95cd3d1b3a62e69a9a9db2bc4af2f9fd2e56d8/otherlibs/dyn/dyn.mli) ⭐ 1,837 | 🐛 1,049 | 🌐 OCaml | 📅 2026-02-08 in Dune. It appears to also be fully manual.
* [**ppx\_deriving** ](https://github.com/ocaml-ppx/ppx_deriving#usage) ⭐ 507 | 🐛 47 | 🌐 OCaml | 📅 2025-07-17’s `[@@deriving show]`.
* Reason's native [**Console.log**](https://github.com/reasonml/reason-native/tree/master/src/console#consoleloganything) ⭐ 460 | 🐛 50 | 🌐 Reason | 📅 2024-05-07
* [**refl** ](https://github.com/thierry-martinez/refl#basic-usage) ⭐ 53 | 🐛 0 | 🌐 OCaml | 📅 2022-11-16, a ppx\_deriving-like.
* [**lrt** ](https://github.com/LexiFi/lrt#getting-started) ⭐ 35 | 🐛 0 | 🌐 OCaml | 📅 2020-11-02, another ppx\_deriving-like.
* [**Inspect**](https://github.com/krohrer/caml-inspect#readme) ⭐ 32 | 🐛 2 | 🌐 OCaml | 📅 2016-08-02
* [**Genprint** ](https://github.com/progman1/genprintlib#readme) ⭐ 31 | 🐛 0 | 🌐 OCaml | 📅 2020-07-06
* [**Dum**](https://github.com/mjambon/dum#readme) ⭐ 30 | 🐛 1 | 🌐 OCaml | 📅 2022-06-07
* [**typerep** ](https://github.com/janestreet/typerep) ⭐ 27 | 🐛 2 | 🌐 OCaml | 📅 2026-01-15, probably a ppx\_deriving-like with ppx\_typerep\_conv.
* [**cmon** ](https://github.com/let-def/cmon#documentation) ⭐ 25 | 🐛 0 | 🌐 OCaml | 📅 2022-04-01, fully manual.
* [**tpf** ](https://github.com/pqwy/tpf#readme) ⭐ 23 | 🐛 0 | 🌐 OCaml | 📅 2020-04-14, again a ppx\_deriving-like.
* [**OCaml@p** ](https://github.com/tsubame-sp/ocaml_at_p#readme) ⭐ 10 | 🐛 0 | 🌐 OCaml | 📅 2017-02-17
* [**repr**](https://mirage.github.io/repr/repr/Repr/index.html#val-pp_json), which appears to have the user build the type representation manually from combinators in addition to also having the user pass it where needed.
* [**data-encoding**](https://gitlab.com/nomadic-labs/data-encoding/-/blob/master/src/tutorial.md#how-to-build-an-encoding), also fully manual.

## Project Starter Templates

* [spin](https://github.com/tmattio/spin) ⭐ 299 | 🐛 14 | 🌐 OCaml | 📅 2024-10-07 - Reason and Ocaml project generator
* [drom](https://github.com/OCamlPro/drom/) ⭐ 198 | 🐛 50 | 🌐 OCaml | 📅 2025-10-27 - The drom tool is a wrapper over opam/dune in an attempt to provide a cargo-like user experience.
* [modern-ocaml](https://github.com/Khady/modern-ocaml) ⭐ 92 | 🐛 0 | 🌐 OCaml | 📅 2026-01-02 - Template for an ocaml project with modern tooling

## Questions

* [OCaml polymorphism example other than template function?](https://stackoverflow.com/questions/14440531/ocaml-polymorphism-example-other-than-template-function)
* [OCaml - polymorphic print and type losing](https://stackoverflow.com/questions/7442449/ocaml-polymorphic-print-and-type-losing)

# Science and Technical Computing

* [owl](https://github.com/owlbarn/owl) ⭐ 1,323 | 🐛 44 | 🌐 OCaml | 📅 2025-09-23 - OCaml numerical library: dense and sparse matrix, linear algebra, regressions, maths and stats functions.
* [tensorflow-ocaml](https://github.com/LaurentMazare/tensorflow-ocaml) ⭐ 287 | 🐛 5 | 🌐 OCaml | 📅 2019-07-06 – OCaml bindings for TensorFlow.
* [biocaml](https://github.com/biocaml/biocaml) ⭐ 123 | 🐛 35 | 🌐 OCaml | 📅 2025-11-26 – OCaml Bioinformatics Library <http://biocaml.org>.
* [oml](https://github.com/hammerlab/oml) ⭐ 119 | 🐛 24 | 🌐 OCaml | 📅 2018-02-01 - OCaml library for general numerical work.
* [slap](https://github.com/akabe/slap) ⭐ 90 | 🐛 3 | 🌐 OCaml | 📅 2020-07-10 - A linear algebra library in OCaml with type-based static size checking for matrix operations.
* [bistro](https://github.com/pveber/bistro) ⭐ 48 | 🐛 19 | 🌐 OCaml | 📅 2025-10-20 – OCaml library for building bioinformatics pipelines.
* [ocephes](https://github.com/rleonid/ocephes) ⭐ 12 | 🐛 2 | 🌐 C | 📅 2016-06-09 - Bindings to frequently used `C` special functions library.
* [onumerical](https://github.com/cheshire/onumerical) ⭐ 8 | 🐛 0 | 🌐 OCaml | 📅 2014-04-04 – Numerical library for OCaml.
* [lacaml](https://mmottl.github.io/lacaml/) - OCaml bindings for BLAS/LAPACK (high-performance linear algebra Fortran libraries).
* [obandit](http://freux.fr/oss/obandit.html) - OCaml library for multi-armed bandits.
* [WHIZARD](https://whizard.hepforge.org/) - A system designed for the efficient calculation of multi-particle scattering cross sections and simulated event samples.

## Regular Expressions

* [Re](https://github.com/ocaml/ocaml-re) ⭐ 252 | 🐛 22 | 🌐 OCaml | 📅 2025-11-24 – a pure OCaml regular expressions library with combinators, supporting several formats (glob, posix, str, etc.).
* [Tyre](https://github.com/Drup/tyre) ⭐ 181 | 🐛 8 | 🌐 OCaml | 📅 2025-12-08 - Tyre is a set of combinators to build type-safe regular expressions, allowing automatic extraction and modification of matched groups.
* [ocaml-pcre](https://github.com/mmottl/pcre-ocaml) ⭐ 35 | 🐛 0 | 🌐 OCaml | 📅 2025-12-20 – bindings to the PCRE library (perl-compatible regular expressions)
* [Humane-re](https://github.com/rgrinberg/humane-re) ⭐ 26 | 🐛 1 | 🌐 OCaml | 📅 2019-09-17 – Humane-re attempts to provide an easy interface for 90% of your regex needs. Courtesy of ocaml-re.

## Security and Cryptography

* [ocaml-tls](https://github.com/mirleft/ocaml-tls) ⭐ 316 | 🐛 5 | 🌐 OCaml | 📅 2025-09-26 – TLS in pure OCaml.
* [nocrypto](https://github.com/mirleft/ocaml-nocrypto) ⭐ 111 | 🐛 43 | 🌐 OCaml | 📅 2020-04-17 – A small cryptographic library behind the ocaml-tls project. It is built to be straightforward to use, adhere to functional programming principles, and able to run in a Xen-based unikernel.
* [cryptokit](https://github.com/xavierleroy/cryptokit) ⭐ 105 | 🐛 5 | 🌐 C | 📅 2026-01-01 – The Cryptokit library for OCaml provides a variety of cryptographic primitives that can be used to implement cryptographic protocols in security-sensitive applications.
* [Digestif](https://github.com/mirage/digestif) ⭐ 93 | 🐛 7 | 🌐 OCaml | 📅 2025-05-21 - Hash algorithms (like SHA\* or BLAKE2\*) in OCaml and C.
* [nocoiner](https://github.com/marcoonroad/nocoiner) ⭐ 11 | 🐛 3 | 🌐 OCaml | 📅 2023-04-12 - A Commitment scheme library for Multi-party computations such as online auctions and gambling.

> Note: The differences between `nocrypto` and `cryptokit` cryptographic libraries are described in the following blog post: [OCaml-TLS: building the nocrypto library core](https://mirage.io/blog/introducing-nocrypto).

## Semantic Technology

* [OCaml-RDF](https://framagit.org/zoggy/ocaml-rdf) – OCaml library to manipulate RDF graphs and execute Sparql queries.

## Serialization

* [yojson](https://github.com/ocaml-community/yojson) ⭐ 360 | 🐛 20 | 🌐 OCaml | 📅 2025-08-01 — An optimized parsing and printing library for the JSON format.
* [atdgen](https://github.com/ahrefs/atd) ⭐ 338 | 🐛 89 | 🌐 OCaml | 📅 2026-01-06 — A serialization compiler for multiple languages (OCaml, Java, Python, Scala, Typescript) with a Binou or JSON format
* [sexplib](https://github.com/janestreet/sexplib) ⭐ 173 | 🐛 5 | 🌐 OCaml | 📅 2026-01-15 – A S-expression parser and printer
* [biniou](https://github.com/mjambon/biniou) ⭐ 43 | 🐛 5 | 🌐 OCaml | 📅 2022-06-17 – Extensible binary data format, like JSON but faster.
* [cbor](https://github.com/ygrek/ocaml-cbor) ⭐ 25 | 🐛 3 | 🌐 OCaml | 📅 2022-02-07 —  OCaml native [CBOR](https://cbor.io/) decoder/encoder.
* [bencode](https://github.com/rgrinberg/bencode) ⭐ 24 | 🐛 1 | 🌐 OCaml | 📅 2024-04-24 — Bencode (.torrent file format) reader/writer.
* [jsonm](http://erratique.ch/software/jsonm) — Non-blocking streaming JSON codec for OCaml.
* [xmlm](http://erratique.ch/software/xmlm) — A streaming codec to decode and encode the XML data format.

## System Programming

* [Mirage OS](https://github.com/mirage/mirage) ⭐ 2,833 | 🐛 58 | 🌐 OCaml | 📅 2026-01-27 – Mirage is a programming framework for constructing secure, high-performance network applications across a variety of cloud computing and mobile platforms.

* [ocaml-git](https://github.com/mirage/ocaml-git) ⭐ 369 | 🐛 19 | 🌐 OCaml | 📅 2025-05-14 – Pure OCaml low-level git bindings.

* **Embedded systems**
  * [OMicroB](https://github.com/stevenvar/omicrob) ⭐ 154 | 🐛 8 | 🌐 OCaml | 📅 2025-10-16 - A virtual machine designed to run OCaml bytecode on AVR (Arduino for instance) micro-controlers.
  * [ocaml-esp32](https://github.com/sadiqj/ocaml-esp32) ⚠️ Archived - A compiler for ESP32 SoC.
  * [OCaPIC](http://www.algo-prog.info/ocapic/web/index.php?id=OCAPIC:OCAPIC) - An OCaml virtual machine for PIC18 micro-controlers.

* [ocaml-vchan](https://github.com/mirage/ocaml-vchan) ⭐ 45 | 🐛 7 | 🌐 OCaml | 📅 2025-03-06 – Pure OCaml implementation of the "vchan" shared-memory communication protocol.

* [ocaml-fat](https://github.com/mirage/ocaml-fat) ⭐ 25 | 🐛 7 | 🌐 OCaml | 📅 2025-05-31 – Read and write FAT-format filesystems from OCaml.

## Testing

* [Alcotest](https://github.com/mirage/alcotest) ⭐ 503 | 🐛 50 | 🌐 OCaml | 📅 2025-12-18 – A lightweight and colourful test framework.
* [QCheck](https://github.com/c-cube/qcheck) ⭐ 392 | 🐛 49 | 🌐 OCaml | 📅 2026-01-31 — QCheck is a property testing library inspired from Haskell's QuickCheck
* [expect-test](https://github.com/janestreet/ppx_expect) ⭐ 183 | 🐛 16 | 🌐 OCaml | 📅 2026-01-15 — A framework for writing tests in OCaml, similar to [Cram](https://bitheap.org/cram/), developed by [JaneStreet](https://blog.janestreet.com/testing-with-expectations/).
* [iTeML](https://github.com/vincent-hugot/iTeML) ⭐ 67 | 🐛 6 | 🌐 OCaml | 📅 2021-04-05 (formerly known as [qtest](http://batteries.vhugot.com/qtest/))  — supports inline pragma's to generate tests.
* [TestSimple](https://github.com/hcarty/ocaml-testsimple) ⭐ 13 | 🐛 0 | 🌐 OCaml | 📅 2015-02-28 - A lightweight unit testing framework compatible with the [Test Anything Protocol](https://testanything.org/).
* [OUnit](http://ounit.forge.ocamlcore.org/) – OUnit is a unit test framework for OCaml. It allows one to easily create unit-tests for OCaml code. It is based on HUnit, a unit testing framework for Haskell.
* [Kaputt](http://kaputt.x9c.fr/) —  comprehensive testing framework.
* [Pa\_test](https://ocaml.janestreet.com/ocaml-core/111.28.00/doc/pa_test) —  General inline testing macro's.

## Utilities

* [ocaml-cuid](https://github.com/marcoonroad/ocaml-cuid) ⭐ 18 | 🐛 2 | 🌐 OCaml | 📅 2022-05-07 - Collision-resistant IDs for server scalability & database performance.
* [Validate](https://github.com/Axot017/validate) ⭐ 17 | 🐛 0 | 🌐 OCaml | 📅 2024-02-02 - PPX deriver designed to streamline the process of validating records.
* [sqids-ocaml](https://github.com/sqids/sqids-ocaml) ⭐ 13 | 🐛 0 | 🌐 OCaml | 📅 2024-02-10 - Official OCaml port of Sqids. Generate short unique IDs from numbers.
* [Uuidm](https://erratique.ch/software/uuidm) - Uuidm is an OCaml module implementing 128-bit universally unique identifiers version 3, 5 (name based with MD5, SHA-1 hashing) and 4 (random based) according to RFC 4122.

## Web Development

* **Frameworks**:
  * [Opium](https://github.com/rgrinberg/opium) ⭐ 784 | 🐛 33 | 🌐 OCaml | 📅 2026-01-06 – Sinatra like web toolkit for OCaml.
  * [incr\_dom](https://github.com/janestreet/incr_dom) ⭐ 393 | 🐛 6 | 🌐 OCaml | 📅 2026-01-15 - A library for building dynamic webapps, using Js\_of\_ocaml
  * [webmachine](https://github.com/inhabitedtype/ocaml-webmachine) ⭐ 222 | 🐛 13 | 🌐 OCaml | 📅 2021-10-19 – A REST toolkit for OCaml. OCaml webmachine is a layer on top of cohttp that implements a state-machine-based HTTP request processor. It's particularly well-suited for writing RESTful APIs. As the name suggests, this is an OCaml port of the webmachine project.
  * [ocaml-vdom](https://github.com/LexiFi/ocaml-vdom) ⭐ 206 | 🐛 3 | 🌐 OCaml | 📅 2025-02-06 - Elm architecture and (V)DOM for OCaml
  * [Ocsigen Eliom](http://ocsigen.org/eliom/) – Eliom is a full-featured multi-tier framework, for developing multi-platform Web and mobile apps as 100% OCaml distributed applications. It can also be used for more traditional Web or mobile apps: Web sites, single page applications, REST API, etc.
  * [Dream](https://aantron.github.io/dream/) - Tidy Web framework for OCaml and ReasonML
  * [fmlib\_browser](https://hbr.github.io/fmlib/odoc/fmlib_browser/doc_overview.html) - a library which helps to write web applications which run in the browser in a pure functional style.

* **Tools**:
  * [Lambda Soup](https://github.com/aantron/lambda-soup) ⭐ 405 | 🐛 11 | 🌐 OCaml | 📅 2024-11-18 - Functional HTML scraping and manipulation with CSS selectors, à la Python's Beautiful Soup.
  * [gen\_js\_api](https://github.com/LexiFi/gen_js_api) ⭐ 180 | 🐛 15 | 🌐 OCaml | 📅 2025-11-26 - gen\_js\_api aims at simplifying the creation of OCaml bindings for Javascript libraries.
  * [Markup.ml](https://github.com/aantron/markup.ml) ⭐ 149 | 🐛 21 | 🌐 OCaml | 📅 2024-10-06 - Error-recovering streaming HTML5 and XML parsers, serializers.
  * [routes](https://github.com/anuragsoni/routes) ⭐ 148 | 🐛 0 | 🌐 OCaml | 📅 2024-09-18 - Typed routes for OCaml/ReasonML web applications.
  * [jingoo](https://github.com/tategakibunko/jingoo) ⭐ 138 | 🐛 5 | 🌐 OCaml | 📅 2026-02-06 – OCaml template engine almost compatible with jinja2.
  * [COW](https://github.com/mirage/ocaml-cow) ⭐ 109 | 🐛 4 | 🌐 OCaml | 📅 2023-12-07 – Caml on the Web (COW) is a set of parsers and syntax extensions to let you manipulate HTML, CSS, XML, JSON and Markdown directly from OCaml code.
  * [ocaml-uri](https://github.com/mirage/ocaml-uri) ⭐ 97 | 🐛 29 | 🌐 OCaml | 📅 2025-11-24 – RFC3986 URI parsing library.
  * [ocaml-mustache](https://github.com/rgrinberg/ocaml-mustache) ⭐ 86 | 🐛 3 | 🌐 OCaml | 📅 2024-05-31 – mustache.js logic-less templates in OCaml.
  * [dispatch](https://github.com/inhabitedtype/ocaml-dispatch) ⭐ 45 | 🐛 1 | 🌐 OCaml | 📅 2022-09-26 – Path-based dispatching for client- and server-side applications.
  * [Goji](https://github.com/klakplok/goji) ⭐ 44 | 🐛 2 | 🌐 OCaml | 📅 2014-07-26 – An OCaml bindings generator for JavaScript libraries.
  * [Syndic](https://github.com/Cumulus/Syndic) ⭐ 36 | 🐛 10 | 🌐 OCaml | 📅 2025-06-19 – RSS and Atom feed parsing
  * [js\_of\_ocaml](http://ocsigen.org/js_of_ocaml) – Js\_of\_ocaml is a compiler of OCaml bytecode to Javascript. It makes it possible to run Ocaml programs in a Web browser.
    * [commonjs\_of\_ocaml](https://github.com/AngryLawyer/commonjs_of_ocaml) ⭐ 12 | 🐛 0 | 🌐 OCaml | 📅 2016-05-19 - Easily import and export CommonJS modules from a js\_of\_ocaml project.
  * [atdjs](https://github.com/barko/atdjs) ⚠️ Archived – atd code generator (serialization) for OCaml/js\_of\_ocaml.
  * [Ocamlnet](http://projects.camlcity.org/projects/ocamlnet.html)
    has many relevant web libraries —
    [Nethtml](http://projects.camlcity.org/projects/dl/ocamlnet-4.0.4/doc/html-main/Nethtml.html)
    html parser,
    [Netasn1](http://projects.camlcity.org/projects/dl/ocamlnet-4.0.4/doc/html-main/Netasn1.html)
    for ASN.1 parsing,
    [Netencoding](http://projects.camlcity.org/projects/dl/ocamlnet-4.0.4/doc/html-main/Netencoding.html)
    for Base64, Quoted Printable, URL encoding and HTML escaping,
    [Netmime](http://projects.camlcity.org/projects/dl/ocamlnet-4.0.4/doc/html-main/Netmime.html)
    for MIME processing, etc. See the [list of
    modules](http://projects.camlcity.org/projects/dl/ocamlnet-4.0.4/doc/html-main/index.html)
    in Ocamlnet's manual.
  * [tyxml](http://ocsigen.org/tyxml) — Library to build valid (according to the W3C spec) Html and Svg trees.
  * [ReScript](https://rescript-lang.org/) - ReScript is a robustly typed language that compiles to efficient and human-readable JavaScript.

* **Open Source Projects**:
  * [Cumulus](https://github.com/Cumulus/Cumulus) ⭐ 51 | 🐛 28 | 🌐 OCaml | 📅 2015-05-04 – Hacker news like website with the OCaml framework Ocsigen

***

*Inspired by awesome projects line. Discover [more awesomeness](https://github.com/bayandin/awesome-awesomeness) ⭐ 33,203 | 🐛 43 | 🌐 Ruby | 📅 2024-06-02 :sparkles:.*
