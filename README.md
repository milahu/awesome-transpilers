# Awesome Transpilers

## By Target Language


### Golang

* [c2go](https://github.com/elliotchance/c2go) A tool for transpiling C to Go.
* [Grumpy](https://github.com/google/grumpy) Grumpy is a Python to Go source code transcompiler and runtime.

### Java

* [VOC](https://github.com/beeware/voc) A transpiler that converts Python code into Java bytecode.

### JavaScript

* [Shift.JS](https://github.com/shift-js/shift-js) Swift to JavaScript transpiler.
* [ElixirScript](https://github.com/elixirscript/elixirscript) Converts Elixir to JavaScript.
* [GopherJS](https://github.com/gopherjs/gopherjs) A compiler from Go to JavaScript for running Go code in a browser.
* [Dart2js](https://dart.dev/tools/dart2js) Use the dart2js tool to compile Dart code to deployable JavaScript.

## Transpilers

### TypeScript Compiler

- https://github.com/microsoft/TypeScript - 90K stars
- https://www.typescriptlang.org/
- https://github.com/kidonng/typescript - A tiny redistribution of TypeScript (10x smaller, 4MB versus 40MB)
- criticism: https://gist.github.com/amcdnl/b52e9dd11850eeb8de8f#file-hate-typescript-md
- alternative: JavaScript with jsdoc type annotations
   - https://www.typescriptlang.org/docs/handbook/jsdoc-supported-types.html
   - https://github.com/futurGH/ts-to-jsdoc
- written in: TypeScript
- compiles from: TypeScript
- compiles to: JavaScript
- last commit: 2023

### Babel

- https://github.com/babel/babel - 40K stars
- compile new versions of JavaScript (ES2020) to old versions of JavaScript (ES2015)
- written in: TypeScript, JavaScript
- compiles from: JavaScript
- compiles to: JavaScript
- last commit: 2023

### Nim

- https://github.com/nim-lang/Nim - 15K stars
- https://nim-lang.org/
- written in: Nim (self-hosted)
- compiles from: Nim
- compiles to: C, C++, JavaScript

### ClojureScript

- https://github.com/clojure/clojurescript - 9K stars
- https://clojurescript.org/
- written in: Clojure
- compiles from: Clojure
- compiles to: JavaScript

### jscodeshift

- https://github.com/facebook/jscodeshift - 8K stars
- toolkit for running codemods over multiple JavaScript or TypeScript files
- codemods = refactoring
- written in: JavaScript
- compiles from: JavaScript
- compiles to: JavaScript
- last commit: 2023

### c2rust

- https://github.com/immunant/c2rust - 3K stars
- Migrate C code to Rust
- written in: Rust
- compiles from: C, C++
- compiles to: Rust

### andrei-markeev/ts2c

- https://github.com/andrei-markeev/ts2c - 1K stars
- [live demo](https://andrei-markeev.github.io/ts2c/)
- written in: C
- compiles from: TypeScript, JavaScript
- compiles to: C
- last commit: 2022

### OneLang

- https://github.com/onelang/OneLang - 1K stars
- written in: TypeScript
- compiles from: TypeScript, C#, Ruby
- compiles to: C++, C#, Go, Java, JS, Perl, PHP, Python, Ruby, Swift, TypeScript
- last commit: 2021

### cheerp

- https://leaningtech.com/cheerp/
- https://leaningtech.com/cheerp-2-6-compiling-c-to-webassembly-and-javascript/
- https://github.com/leaningtech/cheerp-meta - 800 stars
- https://github.com/leaningtech/cheerp-compiler - 200 stars
- license: open source, with dual licence (GPLv2 & commercial), some plugins are closed source (WebAssembly memory profiler, Filesystem emulation)
- based on: LLVM
- written in: C++
- compiles from: C, C++, Java, x86, Adobe Flash
- compiles to: WASM

### Haxe

- https://github.com/HaxeFoundation/haxe - 5K stars
- written in: OCaml
- compiles from: Haxe
- compiles to: AS2, AS3, C++, C#, Java, JS, Lua, Neko, PHP, Python	

### QQuick/Transcrypt

- https://github.com/QQuick/Transcrypt - 3K stars
- written in: Python
- compiles from: Python
- compiles to: JavaScript
- last commit: 2022

### Js2Py

- https://github.com/PiotrDabkowski/Js2Py - 2K stars
- https://pypi.org/project/Js2Py/
- written in: Python
- compiles from: JavaScript (ECMAScript 5.1)
- compiles to: Python
- last commit: 2022
- functions: `js2py.translate_js`, `js2py.translate_file`

### Fennel

- https://github.com/bakpakin/Fennel - 2K stars
- https://fennel-lang.org/
- docs:
   - https://technomancy.us/192 - self-hosting, bootstrapping
      - via: https://www.reddit.com/r/Clojure/comments/qwchlm/comment/hl4raup/
- written in: Lua, Fennel (Lisp)
- compiles from: Fennel (Lisp)
- compiles to: Lua
- last commit: 2023

### Cito

- https://github.com/pfusik/cito - 1.5K stars
- one to many
- written in: C#
- compiles from: Cito
- compiles to: C, C++, C#, Java, JavaScript, Python, Swift, TypeScript, OpenCL C

### TypeScriptToLua

- https://github.com/TypeScriptToLua/TypeScriptToLua - 1.5K stars
- written in: TypeScript
- compiles from: TypeScript
- compiles to: Lua

### jingweno/godzilla

- https://github.com/jingweno/godzilla - 1.5K stars
- written in: Go
- compiles from: JavaScript
- compiles to: Go
- last commit: 2017

### cincheo/jsweet

- https://github.com/cincheo/jsweet - 1.3K stars
- A Java to JavaScript transpiler
- written in: Java
- compiles from: Java
- compiles to: JavaScript
- last commit: 2022

### google/j2cl

- https://github.com/google/j2cl - 1K stars
- written in: Java
- compiles from: Java
- compiles to: JavaScript, Closure JavaScript
- last commit: 2022

### Pebaz/nimporter

- https://github.com/Pebaz/nimporter - 700 stars
- written in: Python
- compiles from: Nim
- compiles to: Python
- last commit: 2022

### pseudo-lang

- https://github.com/pseudo-lang/pseudo - 700 stars
- one to many
- generate readable code
- help with automated translation for cases like algorithm generation, parser generation, refactoring, porting codebases
- written in: Python
- compiles from: Pseudo
- compiles to: Python, JavaScript, Go, C#, C++, Ruby
- last commit: 2021

### LingDong-/wax

- https://github.com/LingDong-/wax - 600 stars
- A tiny programming language
- written in: C
- compiles from: Wax
- compiles to: C, C++, Java, TypeScript, Python, C#, Swift, Lua, WebAssembly 
- last commit: 2022

### TypeScript2Cxx

- https://github.com/ASDAlexander77/TypeScript2Cxx - 500 stars
- https://news.ycombinator.com/item?id=22746170
- compiles from: TypeScript
- compiles to: C++
- last commit: 2021

### putout

- https://github.com/coderaiser/putout - 500 stars
- live demo: https://putout.cloudcmd.io/
- codemods = refactoring
- written in: JavaScript
- compiles from: JavaScript
- compiles to: JavaScript
- last commit: 2023

### jsxx

- https://github.com/surma/jsxx - 150 stars
- compiles from: JavaScript
- compiles to: C++
- last commit: 2022

### StaticScript

- https://github.com/ovr/StaticScript - 600 stars
- compiles from: TypeScript
- compiles to: LLVMIR (more compiler than transpiler)
- last commit: 2020

### ts-llvm

- https://github.com/emlai/ts-llvm - 300 stars
- compiles from: TypeScript
- compiles to: LLVMIR (more compiler than transpiler)
- last commit: 2019

### muta-minits

- https://github.com/nervosnetwork/muta-minits - 150 stars
- compiles from: TypeScript
- compiles to: LLVMIR (more compiler than transpiler)
- last commit: 2019

### transpyle

- https://github.com/mbdevpl/transpyle - 100 stars
- https://pypi.org/project/transpyle/
- written in: Python
- compiles:
   - [C to Python AST](https://pypi.org/project/transpyle/#c-to-python-ast)
   - [Python AST to C](https://pypi.org/project/transpyle/#python-ast-to-c)
   - [C++ to Python AST](https://pypi.org/project/transpyle/#c-to-python-ast-1)
   - [Python AST to C++](https://pypi.org/project/transpyle/#python-ast-to-c-1)
   - [Cython to Python AST](https://pypi.org/project/transpyle/#cython-to-python-ast)
   - [Python AST to Cython](https://pypi.org/project/transpyle/#python-ast-to-cython)
   - [Fortran to Python AST](https://pypi.org/project/transpyle/#fortran-to-python-ast)
   - [Python AST to Fortran](https://pypi.org/project/transpyle/#python-ast-to-fortran)
   - [OpenCL to Python AST](https://pypi.org/project/transpyle/#opencl-to-python-ast)
   - [Python AST to OpenCL](https://pypi.org/project/transpyle/#python-ast-to-opencl)
   - [Python to Python AST](https://pypi.org/project/transpyle/#python-to-python-ast)
   - [Python AST to Python](https://pypi.org/project/transpyle/#python-ast-to-python)

### speedy.js

- https://github.com/MichaReiser/speedy.js - 350 stars
- compiles from: JavaScript
- compiles to: WebAssembly (more compiler than transpiler)
- last commit: 2017

### futurGH/ts-to-jsdoc

- https://github.com/futurGH/ts-to-jsdoc - 60 stars
- compiles from: TypeScript
- compiles to: JavaScript (with JSDoc type annotations)
- last commit: 2023

### sebbekarlsson/typescript

- https://github.com/sebbekarlsson/typescript - 15 stars
- compiles from: TypeScript
- compiles to: C
- last commit: 2019

### sebbekarlsson/tscc

- https://github.com/sebbekarlsson/tscc - 15 stars
- compiles from: TypeScript
- compiles to: C
- last commit: 2019

### andrejusk/typescript-compiler

- https://github.com/andrejusk/typescript-compiler - 15 stars
- compiles from: TypeScript
- compiles to: C
- last commit: 2018

### yakir22/ts2cpp

- https://github.com/yakir22/ts2cpp - 10 stars
- compiles from: TypeScript
- compiles to: C++
- last commit: 2018

### duncanhorn/ts2cpp

- https://github.com/duncanhorn/ts2cpp - 5 stars
- compiles from: TypeScript interface definitions (\*.d.ts)
- compiles to: C++
- last commit: 2019

### quadramadery/js2py

- https://github.com/quadramadery/js2py - 10 stars
- written in: JavaScript
- based on: espree-parser
- compiles from: JavaScript
- compiles to: Python
- last commit: 2019
- status: early draft

### tython

- https://github.com/NCPlayz/tython - 5 stars
- written in: Python
- based on: lark-parser
- compiles from: TypeScript
- compiles to: Python
- last commit: 2020
- status: early draft

### 7HR4IZ3/es62py

- https://github.com/7HR4IZ3/es62py - 0 stars
- written in: Python
- based on: esprima-parser, js2py library
- compiles from: JavaScript (ECMA 6)
- compiles to: Python
- last commit: 2023
- status: early draft

### prometeo

- https://github.com/zanellia/prometeo - 500 stars
- written in: Python
- compiles from: Python
- compiles to: C
- last commit: 2022

### py2many

- https://github.com/py2many/py2many - 500 stars
- based on: https://github.com/konchunas/pyrs - 400 stars, Python to Rust transpiler
- one to many
- written in: Python
- compiles from: Python
- compiles to: Rust, C++, (Julia, Kotlin, Nim, Dart, Go)
- last commit: 2022

### pyo3

- https://github.com/PyO3/pyo3 - 7K stars
- Rust bindings for the Python interpreter
- no transpiler
- use cases: write native Python modules in Rust, embed Python in a Rust binary

### ts2nim

- https://github.com/bung87/ts2nim - 50 stars
- written in: TypeScript
- compiles from: TypeScript
- compiles to: Nim
- last commit: 2021

### clojurec

- https://github.com/schani/clojurec - 1K stars
- based on: [ClojureScript 0e0aa7f](https://github.com/clojure/clojurescript/tree/0e0aa7fdd379649bf87f8fff5c6a64e37fe616a4)
- written in: Clojure
- compiles from: Clojure
- compiles to: C
- last commit: 2018

### hissp

- https://github.com/gilch/hissp - 300 stars
- https://www.reddit.com/r/Clojure/comments/toyzq2/comment/i280x1f/
- written in: Python
- compiles from: Lisp
- compiles to: Python
- last commit: 2023

### kalai

- https://github.com/kalai-transpiler/kalai - 200 stars
- via: https://elangocheran.com/2020/03/18/why-clojure-lisp-is-good-for-writing-transpilers/
   - via: https://www.reddit.com/r/Clojure/comments/qwchlm/why_clojure_lisp_is_good_for_writing_transpilers/
- written in: Clojure
- compiles from: Clojure
- compiles to: Rust, C++, Java, ...
- last commit: 2023

### Cerberus X Trans

- https://www.cerberus-x.com/cxDocs/Tools_Trans.html
- https://github.com/cerberusxdev/cerberus - 200 stars
- https://github.com/cerberusxdev/cerberus/tree/develop/src/transcc/builders
- game development language with multiple target platforms (desktop, mobile, web)
- written in: C, Cerberus X
- compiles from: Cerberus X
- compiles to: C++, Objective-C, C#, Java, HTML
- last commit: 2023

### roman01la/javascript-to-clojurescript

- https://github.com/roman01la/javascript-to-clojurescript - 100 stars
- written in: JavaScript
- compiles from: JavaScript
- compiles to: ClojureScript, Clojure
- last commit: 2023

### basilisp

- https://github.com/basilisp-lang/basilisp - 50 stars
- https://www.reddit.com/r/Clojure/comments/toyzq2/comment/i281k15/
- written in: Python, Clojure
- compiles from: Clojure, Lisp
- compiles to: Python
- last commit: 2022

### Kotlift

- https://github.com/studoverse/Kotlift - 400 stars, archived
- deprecated in favor of [Kotlin Multiplatform Mobile](https://kotlinlang.org/lp/mobile/)
- written in: Kotlin, Swift
- compiles from: Kotlin
- compiles to: Swift
- last commit: 2023

### andreikop/cpp2python

- https://github.com/andreikop/cpp2python - 150 stars
- written in: Python
- compiles from: C++
- compiles to: Python
- last commit: 2019

### seasnake

- https://github.com/pybee/seasnake - 150 stars - archived
- written in: Python
- compiles from: C++
- compiles to: Python
- last commit: 2016

### Progsbase

TODO what exactly is this? a transpiler service?

- https://www.progsbase.com/
- "Job Payments: You can create programming jobs using the progsbase client. Create payments here to reward developers who implement a solution to your job."
- closed source
- Free Community Plan: convert TypeScript, Java, C, C++, JavaScript, C#, PHP, Python, Visual Basic, Swift, LibreOffice Basic, Ruby, Visual Basic
- written in: Java, Progsbase
- compiles from: Java
- compiles to: Java, C, C++, JavaScript, C#, R, PHP, Python, Visual Basic
- since: 2018

### jtransc

- https://github.com/jtransc/jtransc - 500 stars - archived
- written in: Java
- compiles from: Java, Kotlin
- compiles to: JavaScript, C++, D, C#, PHP, AS3, Dart, Haxe

### specs-feup/clava

- https://github.com/specs-feup/clava - 50 stars
- applies analysis and transformations written in LARA scripts (which is based on JavaScript)
- based on: Clang
- written in: Java
- languages: C, C++, CUDA, OpenCL
- last commit: 2022

### RapidFingers/Craxe

- https://github.com/RapidFingers/Craxe - 40 stars
- written in: Haxe
- compiles from: Haxe
- compiles to: Nim
- last commit: 2019

### Ranger

https://github.com/terotests/Ranger - 5 stars

- written in: JavaScript
- self hosting
- compiles from: Ranger?
- compiles to: JavaScript, Java, Go, Swift, PHP, C++, C#, Scala
- last commit: 2018

### cxx2cs

https://sourceforge.net/projects/cxx2cs/

- compiles from: C++
- compiles to: C#
- last commit: 2015

### J2CL

https://github.com/google/j2cl - 1K stars

- Java to Closure JavaScript transpiler
- optimizes with Closure Compiler https://github.com/google/closure-compiler
- compiles from: Java
- compiles to: JavaScript
- last commit: 2022
- successor of: GWT

### GWT

- https://github.com/gwtproject/gwt - 1.5K stars
- aka: Google Web Toolkit
- written in: Java
- compiles from: Java
- compiles to: JavaScript
- last commit: 2022

### SequalsK

- paper: SequalsK—A Bidirectional Swift-Kotlin-Transpiler (2021)
   - https://dijkstra.iem.thm.de/Schultes-SequalsK-Preprint.pdf
   - https://ieeexplore.ieee.org/document/9460946 (paywall)
- paper: Evaluating swift-to-kotlin and kotlin-to-swift transpilers (2022)
   - https://dl.acm.org/doi/10.1145/3524613.3527811 (paywall)
- live demo: https://transpile.iem.thm.de/ (broken)
- talk: https://www.youtube.com/watch?v=eHUCWAf9aHI
- closed source
- bidirectional transpiler
- languages: Swift, Kotlin

### python scripts to python modules

- status: concept, project idea
- written in: Python
- compiles from: Python scripts
- compiles to: Python modules
- simlar to: [2to3](https://docs.python.org/3/library/2to3.html) in Python 3.11
- [Python Setuptools: quick way to add scripts without "main" function as "console_scripts" entry points](https://stackoverflow.com/questions/59591969/python-setuptools-quick-way-to-add-scripts-without-main-function-as-console)
- [Convert python script in module](https://stackoverflow.com/questions/63917528/convert-python-script-in-module)
- [chromium-depot-tools.nix](https://github.com/milahu/nur-packages/blob/master/pkgs/build-support/chromium-depot-tools/chromium-depot-tools.nix)

### lezer-parser-import-tree-sitter-scanner

- https://github.com/milahu/lezer-parser-import-tree-sitter-scanner
- Helps import tree-sitter grammars and scanners.
- A grammar transpiler, and a domain-specific C++ to JavaScript transpiler.
- Import ANTLR grammars to lezer-parser
- written in: JavaScript
- compiles from: C++, tree-sitter grammars, ANTLR grammars
- compiles to: JavaScript, lezer-parser grammars

## Transpiler Frameworks

can be used for all languages

- program transformation systems https://en.wikipedia.org/wiki/List_of_program_transformation_systems

### comby

- https://github.com/comby-tools/comby - 2K stars
- A code rewrite tool for structural search and replace that supports about every language
- written in: OCaml
- languages: C, Java, Go, Swift, Rust, PHP, TypeScript, JavaScript, ...
- features: refactoring

### JetBrains MPS

- https://github.com/JetBrains/MPS - 1.5K stars
- https://www.jetbrains.com/mps/
- metaprogramming language, Metaprogramming System
- Create your own domain-specific language
- written in: Java
- license: APL2

### rose compiler

- https://github.com/rose-compiler/rose - 500 stars
- languages: C (C89 and C98), C++ (C++98 and C++11), UPC, Fortran (77/95/2003), OpenMP, Java, Python, PHP
- use cases: static analysis, program optimization, program transformation

### jarble/transpiler

- https://github.com/jarble/transpiler - 400 stars
- translates a small subset of several programming languages into several others
- translate several metasyntax notations, such as EBNF and ABNF
- experimental "proof-of-concept," so it can only translate relatively simple programs
- A major goal of this project is to translate TypeScript and JavaScript to other languages that compile to C or native code. For example, it's possible to translate a subset of TypeScript to Zig
- written in: JavaScript
- languages: JavaScript, Prolog, C, C#, PHP, Python, Lua, Perl, Haskell, Fortran, Java, OCaml, GLSL, ...

### Rascal

- https://github.com/usethesource/rascal - 300 stars
- https://www.rascal-mpl.org/docs/WhyRascal/UseCases/SourceToSource
- metaprogramming language
- written in: Java
- compiles from: any
- compiles to: any

### true-grue/raddsl

- https://github.com/true-grue/raddsl - 100 stars
- Tools for rapid prototyping of DSL compilers
- features: parse, transform
- written in: Python
- last commit: 2021

### LangTrans

- https://github.com/LangTrans/LangTrans - 20 stars
- Customize programming languages
- written in: Python
- features: parse, transform
- syntactic preprocessor
- customize the syntax of any programming language
- based on: regex
- last commit: 2022

### codeworker

- http://codeworker.free.fr/
- CodeWorker can be trained to parse almost any language
- last version: 2010

### SemanticDesigns DMS Toolkit

- https://www.semanticdesigns.com/Products/DMS/DMSToolkit.html
- Software Reengineering Toolkit
- closed source
- languages: C++, Java, COBOL, SQL, HTML, Verilog, ...
- written in: PARLANSE = parallel language. As an example, the attribute evaluation process is automatically parallelized, and can often provide a linear speedup on an N-way SMP system.

## Code generators

- https://github.com/topics/code-generator
- https://github.com/yellicode/core - build your own code generation templates with TypeScript
  - https://github.com/yellicode/typescript-extension
  - Model driven: Generate code from any JSON document, or create your code models using our free, cross-platform modeling tool, Yellicode Modeler. Extend models with language- or framework specific meta data and use Yellicode's type-safe APIs to transform your models into code.

## Partial evaluators

aka: partial evaluation, code optimizers, code optimization, dead code elimination, tree shaking, code compression, code minification

### JavaScript

- https://github.com/terser/terser - 8K stars - JavaScript parser, mangler and compressor toolkit for ES6+
- https://github.com/google/closure-compiler - 7K stars - JavaScript checker and optimizer. written in Java
  - https://github.com/google/closure-compiler-npm/tree/master/packages/google-closure-compiler-js - javascript version of the google closure-compiler. deprecated. last commit 2020
- https://github.com/facebookarchive/prepack - 15K stars - last commit 2021. archived. outdated. [does not work with javscript ESM modules](https://github.com/facebookarchive/prepack/issues/2629)
- https://github.com/mindedsecurity/JStillery - 1K stars - last commit 2019 - JavaScript Deobfuscation via Partial Evaluation
- https://github.com/SumeyyeSuslu/SPEjs - 5 stars - last commit 2018 - Symbolic Partial Evaluator for JavaScript. Sümeyye Süslü, Christoph Csallner, 2018
  - based on [Z3 SMT solver](https://github.com/Z3Prover/z3)
  - paper https://ranger.uta.edu/~csallner/papers/S%C3%BCsl%C3%BC18SPEjs.pdf

### SVG

- https://github.com/svg/svgo - 20K stars - tool for optimizing SVG files. written in JavaScript

### CSS

- https://github.com/linkedin/opticss - 1K stars - A CSS Optimizer

## Machine Learning

- https://www.altamira.ai/open-source-gpt-alternative-solutions/
- https://www.ankursnewsletter.com/p/openais-gpt-3-vs-open-source-alternatives
  - GPT-J and GPT-Neo are the most popular open source alternatives to GPT-3 today
- GPT = Generative Pretrained Transformer
- LLM = large language model
- The Pile = 800 GB of English texts - https://pile.eleuther.ai/
- The Stack = 6TB of source code, covering 358 programming languages
  - https://huggingface.co/datasets/bigcode/the-stack
  - rust: https://huggingface.co/mrm8488/bloom-560m-finetuned-the-stack-rust
- HumanEval benchmark: https://github.com/openai/human-eval

### TransCoder by Facebook

- https://github.com/facebookresearch/TransCoder - 1.5K stars
   - deprecated in favor of CodeGen
- https://github.com/facebookresearch/CodeGen - 500 stars
- based on: tree-sitter parsers
- tags: ai, machine learning, generic, metaprogramming language, Metaprogramming System, transpiler framework
- Create your own domain-specific language
- generic transpiler, can be trained to translate all languages
- written in: Python
- license: MIT, Creative Commons Attribution-NonCommercial 4.0, Creative Commons Attribution-ShareAlike 2.0
- languages: C++, Java, Python, ... any

### OPT by Facebook

- https://github.com/facebookresearch/metaseq/tree/main/projects/OPT
- blog post: https://ai.facebook.com/blog/democratizing-access-to-large-scale-language-models-with-opt-175b/
- license: open source (models, inference code, training code)
- parameters: 175B

### InCoder by Facebook

- https://huggingface.co/facebook/incoder-6B
- parameters: 6B

### CodeGen by Salesforce

- https://blog.salesforceairesearch.com/codegen/
- parameters: 16B
- trained on: The Pile, BigQuery (C, C++, Go, Java, JavaScript, Python)
- architecture: autoregressive language models for program synthesis

### CodeT5 by Salesforce

- https://github.com/salesforce/CodeT5
- architecture: encoder-decoder
- parameters: 770M (?)
- release: 2020-07-06

### PolyCoder

- https://github.com/VHellendoorn/Code-LMs
- tags: ai, machine learning
- paper https://arxiv.org/pdf/2202.13169.pdf
- This model was not trained to solve programming problems and may not perform well on a benchmark such as [HumanEval](https://github.com/openai/human-eval).
- Whitespace is very important to the model, since no preprocessing was done on the input files.
- parameters: 2.7B
- release: 2020-10
- trained on: 12 programming languages (C, C#, C++, Go, Java, JavaScript, PHP, Python, Ruby, Rust, Scala, TypeScript)
- architecture: GPT-2

### GPT-3 by OpenAI

- license: closed source (OINO = open in name only)
- parameters: 175B
- architecture: auto-regressive model for next token prediction
- release: 2020-06-11
- price: 0.06 USD / 1K tokens - https://openai.com/api/pricing/

### CodeParrot

- https://huggingface.co/codeparrot
- CodeParrot is a GPT-2 model trained to generate Python code
- parameters: 1.5B
- architecture: GPT-2
- Code generation with: CodeParrot (1.5B), InCoder (6B) and CodeGen (6B)
- trained on: GitHub Code (32 programming languages), ...

### GPT-Neo

- trained on: The Pile
- parameters: 2.7B

### GPT-J by EleutherAI

- live demo: https://6b.eleuther.ai/
  - EleutherAI also developed a simple user interface for GPT-J. This interface allows users to increase the level of creativity of the model by using a parameter known as “temperature.”
- model: https://github.com/kingoflolz/mesh-transformer-jax/#gpt-j-6b
- license: open source (models, inference code, training code)
- parameters: 6B
- trained on: The Pile
- autoregressive model for text generation

### GPT-NeoX by EleutherAI

- https://github.com/EleutherAI/gpt-neox/
- parameters: 20B
- release: 2022-02

### AlexaTM by Amazon

- https://github.com/amazon-science/alexa-teacher-models
- encoder-decoder architecture
- trained on: causal-language-modeling (CLM), denoising tasks
- parameters: 20B
- release: 2022-11-18

### Codex

- tags: ai, machine learning
- license: closed source
- free trial: 18 USD credit
- parameters: 12B

### Jurassic-1 language model by AI21 labs

- https://www.ai21.com/studio
- license: closed source
- free trial: 90 USD credit

### Megatron-Turing NLG by NVIDIA and Microsoft

- https://developer.nvidia.com/megatron-turing-natural-language-generation
- license: closed source
- parameters: 530B

### BLOOM

- decoder-only architecture
- https://huggingface.co/docs/transformers/model_doc/bloom
- license: closed source
- 13 programming languages
- trained on: 46 natural languages, 13 programming languages
- parameters: 176B
- architecture: auto-regressive model for next token prediction (similar to GPT3)

## Online Transpilers

### javainuse.com

- [Online Tool To Convert XML To JSON And JSON To XML](https://www.javainuse.com/xmljson)
- [Online JSON to Java POJO Class Converter](https://www.javainuse.com/pojo)
- [JSON to NDJSON Online Converter Tool](https://www.javainuse.com/ndjson)
- [JSON to YAML Converter Tool](https://www.javainuse.com/jsontoyaml)
- [YAML to JSON Converter Tool](https://www.javainuse.com/yamltojson)
- [YAML to POJO Converter Tool](https://www.javainuse.com/yamltopojo)
- [XML to POJO Converter Tool](https://www.javainuse.com/xmltopojo)
- [Online Bash Shell Scripts to Windows Batch Files Converter Tool](https://www.javainuse.com/bash)
- [Online JSON to Typescript Converter Tool](https://www.javainuse.com/json2type)
- [Online tool to convert Properties File to YAML format](https://www.javainuse.com/app2yaml)
- [Online tool to convert Kubernetes YAML to Terraform HCL format](https://www.javainuse.com/yaml2tcf)
- [Online tool to convert SQL to Mongo format](https://www.javainuse.com/sql2mongo)
- [Online tool to convert JSON to Kotlin format](https://www.javainuse.com/json2kot)
- [Online tool to convert JavaScript to Python format](https://www.javainuse.com/js2py)
- [Online tool to convert Python to JavaScript format](https://www.javainuse.com/py2js)
- [Online tool to convert Python to C++ format](https://www.javainuse.com/py2cpp)
- [Online tool to convert Java to Python format](https://www.javainuse.com/java2py)
- [Online tool to convert Javascript to Typescript format](https://www.javainuse.com/js2ts)
- [Online tool to convert Java to Javascript format](https://www.javainuse.com/java2js)
- [Online tool to convert Java to Golang format](https://www.javainuse.com/java2go)
- [Online tool to convert Kotlin to Java format](https://www.javainuse.com/kot2java)
- [Online tool to convert Java to Kotlin format](https://www.javainuse.com/java2kot)
- [Online tool to convert Java to C# format](https://www.javainuse.com/java2csharp)
- [Online Tool to Convert Java to C++](https://www.javainuse.com/java2cpp)
- [Online Tool to Convert C Code to Python](https://www.javainuse.com/c2py)
- [Online Tool to Convert C Code to C++](https://www.javainuse.com/c2cpp)
- [Online Tool to Convert Python Code to R](https://www.javainuse.com/py2r)
- [Online Tool to Convert JavaScript Code to JQuery](https://www.javainuse.com/js2jq)
- [Online Tool to Convert Scala Code to Java](https://www.javainuse.com/sc2ja)
- [Online Tool to Convert Java Code to Scala](https://www.javainuse.com/ja2sc)
- [Online Tool to Convert C# Code to Java](https://www.javainuse.com/csharp2java)
- [Online Tool to Convert PHP Code to Python](https://www.javainuse.com/php2py)
- [Online Tool to Convert C# Code to Python](https://www.javainuse.com/csharp2py)
- [Online Tool to Convert C++ Code to Java](https://www.javainuse.com/cpp2java)
- [Online Tool to Convert Python Code to Java](https://www.javainuse.com/py2java)
- [Online Tool to Convert Python Code to CSharp](https://www.javainuse.com/py2csharp)

## GitHub topics

- https://github.com/topics/transpiler
- https://github.com/topics/source-to-source
- https://github.com/topics/program-transformation
- https://github.com/topics/metaprogramming
- https://github.com/topics/term-rewriting
- https://github.com/topics/refactoring-tools
- https://github.com/topics/static-analysis

## See also

- https://github.com/transpiler/awesome-transpiler
- https://github.com/JohnDeved/awesome-typescript-compilers
- https://github.com/aalhour/awesome-compilers
- https://github.com/onelang/OneLang/wiki/OneLang-vs.-Haxe-vs.-Progsbase-comparison
- https://en.wikipedia.org/wiki/Source-to-source_compiler
- https://devopedia.org/transpiler
- https://aterik.github.io/Transpiler.and.similar.List/List/
- https://github.com/milahu/awesome-component-converters - html components: react, svelte, solidjs, vue, angular, ...
- https://cdn.intechopen.com/pdfs/14395/InTech-Automatic_generation_of_programs.pdf - Automatic Generation of Programs. by: Ondřej Popelka and Jiří Štastný
- https://arxiv.org/pdf/2202.07612.pdf - CodeGen-Test: An Automatic Code Generation Model Integrating Program Test Information. by: ZHONG Maosheng, LIU Gen, LI Hongwei, KUANG Jiangling, ZENG Jinshan, WANG Mingwen
- https://www.assemblyscript.org/ - similar to TypeScript (JavaScript), compiles to WebAsssembly, alternative to JS2C/TS2C transpilers
- https://stackoverflow.com/questions/6498850/programming-languages-that-compile-into-c-c-source
- https://softwareengineering.stackexchange.com/questions/143722/is-there-a-language-that-transpiles-to-c-with-better-syntax
- https://github.com/dbohdan/compilers-targeting-c
- https://medium.com/@ZombieCodeKill/the-a-z-of-javascript-transpilers-2d3d556fa627 - The A-Z of JavaScript Transpilers
- https://github.com/jashkenas/coffeescript/wiki/List-of-languages-that-compile-to-JS - List of languages that compile to JavaScript
- https://github.com/milahu/awesome-bidirectional-transforms - bidirectional transpilers, lenses
