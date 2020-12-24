# Awesome Advent of Code

This is a collection of awesome resources related to the yearly
[Advent of Code] challenge.

[Advent of Code]: https://adventofcode.com/

* [The Official AoC Website](https://adventofcode.com/)
* [The AoC Subreddit](https://www.reddit.com/r/adventofcode/)
* [Project Templates](#project-templates)
* [Tools and Utilities](#tools-and-utilities)
* [Other Advent Calendars](#other-advent-calendars)
* [2018](/2018.md)
* [2019](/2019.md)
* [2020](#2020)
  * [Solutions](#solutions)
    * [Ada](#ada)
    * [Assembly](#assembly)
    * [AWK](#awk)
    * [Bash](#Bash)
    * [C](#c)
    * [C#](#c-1)
    * [C++](#c-2)
    * [Clojure](#clojure)
    * [Common Lisp](#common-lisp)
    * [Crystal](#crystal)
    * [D](#d)
    * [Dart](#dart)
    * [Elixir](#elixir)
    * [Elm](#elm)
    * [Erlang](#erlang)
    * [F#](#f)
    * [Go](#go)
    * [Groovy](#groovy)
    * [Haskell](#haskell)
    * [Haxe](#haxe)
    * [Idris](#idris)
    * [J](#J)
    * [Java](#java)
    * [JavaScript](#javascript)
    * [Julia](#julia)
    * [Kotlin](#kotlin)
    * [LDPL](#ldpl)
    * [Lua](#lua)
    * [MATLAB](#matlab)
    * [Nim](#nim)
    * [OCaml](#ocaml)
    * [PHP](#php)
    * [Perl](#perl)
    * [Pony](#pony)
    * [PowerShell](#powershell)
    * [Prolog](#prolog)
    * [Python](#python)
    * [R](#r)
    * [Racket](#racket)
    * [Raku](#raku)
    * [ReasonML](#reasonml)
    * [Red](#red)
    * [Ruby](#ruby)
    * [Rust](#rust)
    * [Smalltalk](#smalltalk)
    * [Scala](#scala)
    * [Scheme](#scheme)
    * [SpectX](#spectx)
    * [SQL](#sql)
    * [Swift](#swift)
    * [TypeScript](#typescript)
      * [Deno](#deno)
    * [Unison](#unison)
    * [VB.NET](#vbnet)
    * [Zig](#zig)
  * [Live Streams](#live-streams)

---

## Project Templates

*Templates, cookiecutters and skeletons for quickly setting up projects
in your favourite language.*

* [Reason Starter kit for Advent of Code](https://github.com/ManasJayanth/reason-aoc-starter) *(Reason and OCaml)*
* [dave-burke/advent-of-code-java-starter](https://github.com/dave-burke/advent-of-code-java-starter) *(Java)*
* [gobanos/cargo-aoc](https://github.com/gobanos/cargo-aoc) *(Rust)*
* [nickyvanurk/advent-of-code-rust-template](https://github.com/nickyvanurk/advent-of-code-rust-template) *(Rust)*
* [hughjdavey/aoc-kotlin-starter](https://github.com/hughjdavey/aoc-kotlin-starter) *(Kotlin)*
* [codemicro/adventOfCode](https://github.com/codemicro/adventOfCode/tree/master/template) *(Go, Python)*
* [kindermoumoute/adventofcode](https://github.com/kindermoumoute/adventofcode/tree/master/template) *(Go)*
* [staylorwr/elixir_aoc](https://github.com/staylorwr/elixir_aoc) *(Elixir)*
* [mhanberg/advent-of-code-elixir-starter](https://github.com/mhanberg/advent-of-code-elixir-starter) *(Elixir)*
* [AlexeSimon/adventofcode](https://github.com/AlexeSimon/adventofcode) *(Python)*
* [UncleCJ/advent-of-code](https://github.com/UncleCJ/advent-of-code) *(Jupyter Python Notebooks)*
* [sindrekjr/AdventOfCodeBase](https://github.com/sindrekjr/AdventOfCodeBase) *(C#)*
* [mhanberg/advent-of-code-clojure-starter](https://github.com/mhanberg/advent-of-code-clojure-starter) *(Clojure)*
* [caderek/aoc-starter-js](https://github.com/caderek/aoc-starter-js) *(JavaScript)*
* [caderek/aoc-starter-ts](https://github.com/caderek/aoc-starter-ts) *(TypeScript)*
* [mariotacke/template-advent-of-code](https://github.com/mariotacke/template-advent-of-code) *(JavaScript)*
* [arkadye/advent_of_code](https://github.com/arkadye/advent_of_code_framework) *(C++)*
* [eduherminio/AdventOfCode.Template](https://github.com/eduherminio/AdventOfCode.Template) *(C#)*
* [izexi/aoc-ts-template](https://github.com/izexi/aoc-ts-template) *(TypeScript)*
* [advent-of-code-template](https://github.com/ridaamirini/advent-of-code-template) *(PHP)*
* [amorriscode/advent-of-code](https://github.com/amorriscode/advent-of-code) *(JavaScript)*

## Tools and Utilities

* [Alfie](https://alfie.prodo.ai/) -- Online JS editor that helps users solve AoC problems.
* [Chrome extension](https://chrome.google.com/webstore/detail/advent-of-code-ranking/jbnlafikncgjjhdkmfhokcplgahebmjl) -- Browser extension for private leaderboard visualization
* [Firefox extension](https://addons.mozilla.org/en-US/firefox/addon/aoc-ranking/) -- Browser extension for private leaderboard visualization
* [Globals medals overview](http://www.maurits.vdschee.nl/scatterplot/medals.html) -- Alternative global leaderboard showing first, second and third places as gold, silver and bronze medals.
* [Scatterplot of first 100](http://www.maurits.vdschee.nl/scatterplot/) -- Scatterplot of the time taken to solve the parts of each puzzle by the first 100 people that solved it.
* [aocdl](https://github.com/GreenLightning/advent-of-code-downloader) -- Command-line utility that automatically downloads your personal input file while you read the puzzle description *(Go)*.
* [aocinput](https://github.com/dds/aoc2020/blob/main/cmd/aocinput/aocinput.go) -- CLI for getting inputs. Clipboard support. Polite to AoC. Nice help and options. *(Go)*
* [aoc-cli](https://github.com/keirua/aoc-cli) -- Command-line utility that helps solve problems in ruby: it downloads your personal input file, creates the sample source files and benchmarks your solutions *(Ruby)*.
* [AoCHelper](https://github.com/eduherminio/AoCHelper) -- NuGet library that simplifies puzzle solving and provides benchmarking *(.NET)*.
* [aocleaderboard](https://github.com/scarvalhojr/aocleaderboard) -- get over the 200-member limit for private leaderboards and combine multiple leaderboards in a single page with recalculated scores.
* [advent-of-code-api](https://hackage.haskell.org/package/advent-of-code-api) -- Haskell library for querying AOC prompts, inputs, and leaderboards *(Haskell)*
* [advent-of-code-ocr](https://github.com/mstksg/advent-of-code-ocr#readme) -- Command line utility and Haskell library for parsing AoC ascii art words *(Haskell)*
* [advent-of-code-ocr](https://github.com/bsoyka/advent-of-code-ocr) -- Python module for parsing AoC ascii art words *(Python)*
* [aoc-ranking](https://github.com/freedomofkeima/aoc-ranking) -- Show all non-zero score AoC participants in one, global scoreboard. *(Python)*
* [aoc-cli](https://github.com/scarvalhojr/aoc-cli) -- Read puzzle descriptions, download input, and submit answers from the comfort of your terminal. *(Rust)*

## Other Advent Calendars

*24 days of cool stuff regarding <insert-technology-here>.*

* [Raku Advent Calendar](https://raku-advent.blog/)
* [QEMU Advent Calendar](https://www.qemu-advent-calendar.org/)

## 2020

**WARNING:** All of these likely contain spoilers.

Read [CONTRIBUTING.md](/CONTRIBUTING.md) to learn how to add your own repos.

### Solutions

#### Ada

*Solutions to AoC in Ada.*

* [jwarwick/aoc_2020](https://github.com/jwarwick/aoc_2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)

#### Assembly

*Solutions to AoC in Assembly.*

* [k2l8m11n2/advent-2020](https://github.com/k2l8m11n2/advent-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--07-brightgreen)

#### AWK

*Solutions to AoC in AWK.*

* [patsie75/aoc](https://github.com/patsie75/aoc) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--12-brightgreen)
* [phillbush/aoc](https://github.com/phillbush/aoc) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--18-brightgreen)

#### Bash

*Solutions to AoC in Bash.*

* [NoMod-Programming/Advent-of-Code-2020](https://github.com/NoMod-Programming/Advent-of-Code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--08-brightgreen)

#### C

*Solutions to AoC in C.*

* [AJSKirk/aoc](https://github.com/AJSKirk/aoc) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [breakthatbass/advent_of_code2020](https://github.com/breakthatbass/advent_of_code2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [poww10s/advent-of-code-2020](https://github.com/poww10s/advent-of-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--22-brightgreen)
* [madex/advent-2020-c](https://github.com/madex/advent-2020-c) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--21-brightgreen)

#### C#

*Solutions to AoC in C#.*

* [DjolenceTipic/Advent-of-Code](https://github.com/DjolenceTipic/Advent-of-Code) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--22-brightgreen)
* [GuyInGrey/AdventOfCode2020](https://github.com/GuyInGrey/AdventOfCode2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--15-brightgreen)
* [Perska/AoC2020](https://github.com/Perska/AoC2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [RaczeQ/AdventOfCode2020](https://github.com/RaczeQ/AdventOfCode2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--18-brightgreen)
* [Raknison123/AdventOfCode2020](https://github.com/Raknison123/AdventOfCode2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--18-brightgreen)
* [andi0b/advent-of-code-2020](https://github.com/andi0b/advent-of-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--21-brightgreen)
* [eduherminio/AoC2020](https://github.com/eduherminio/AoC2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [encse/adventofcode](https://github.com/encse/adventofcode) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [fulee85/AdventOfCode2020](https://github.com/fulee85/AdventOfCode2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [grigoresc/adventofcode.2020](https://github.com/grigoresc/adventofcode.2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--21-brightgreen)
* [mddr/advent-of-code-2020](https://github.com/mddr/advent-of-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--14-brightgreen)
* [p-kostic/AdventOfCode2020](https://github.com/p-kostic/AdventOfCode2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [sindrekjr/AdventOfCode](https://github.com/sindrekjr/AdventOfCode) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [thejan14/adventofcode2020](https://github.com/thejan14/adventofcode2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--22-brightgreen)
* [viceroypenguin/adventofcode](https://github.com/viceroypenguin/adventofcode) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--21-brightgreen)

#### C++

*Solutions to AoC in C++.*

* [BuzzHari/advent_of_code](https://github.com/BuzzHari/advent_of_code) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--06-brightgreen)
* [DarthGandalf/advent-of-code](https://github.com/DarthGandalf/advent-of-code) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [Kazhuu/advent-of-code-2020](https://github.com/Kazhuu/advent-of-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--20-brightgreen)
* [Sciencentistguy/AdventOfCode](https://github.com/Sciencentistguy/AdventOfCode) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--21-brightgreen)
* [TheRealMolen/adventofcode2020](https://github.com/TheRealMolen/adventofcode2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--12-brightgreen)
* [janpipek/advent-of-code-2020](https://github.com/janpipek/advent-of-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--22-brightgreen)
* [jimmiebergmann/AdventOfCode2020](https://github.com/jimmiebergmann/AdventOfCode2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--09-brightgreen)
* [memoriesadrift/Advent-of-Code-2020-Solutions](https://github.com/memoriesadrift/Advent-of-Code-2020-Solutions) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--15-brightgreen)
* [mfarberbrodsky/adventofcode](https://github.com/mfarberbrodsky/adventofcode) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--21-brightgreen)
* [spencerk226/AdventOfCode2020](https://github.com/spencerk226/AdventOfCode2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--21-brightgreen)
* [tboschi/advent-of-code-2020](https://github.com/tboschi/advent-of-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--21-brightgreen)
* [thorstel/Advent-of-Code-2020](https://github.com/thorstel/Advent-of-Code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [tomlankhorst/advent-of-code-2020-cpp](https://github.com/tomlankhorst/advent-of-code-2020-cpp) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [yadavgaurav251/Advent-Of-Code](https://github.com/yadavgaurav251/Advent-Of-Code) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--10-brightgreen)

#### Clojure

*Solutions to AoC in Clojure.*

* [callum-oakley/advent-of-code-2020](https://github.com/callum-oakley/advent-of-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [rjray/advent-2020-clojure](https://github.com/rjray/advent-2020-clojure) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [AndreaCrotti/advent2020](https://github.com/AndreaCrotti/advent2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--15-brightgreen)
* [amandeepsp/aoc2020](https://github.com/amandeepsp/aoc2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--19-brightgreen)
* [pete23/advent-2020](https://github.com/pete23/advent-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--21-brightgreen)

#### Common Lisp

*Solutions to AoC in Common Lisp.*

* [atgreen/advent-of-code-2020](https://github.com/atgreen/advent-of-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--08-brightgreen)
* [m3m0ry/2020-aoc](https://github.com/m3m0ry/2020-aoc) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--21-brightgreen)
* [~zge/aoc20](https://git.sr.ht/~zge/aoc20)

#### Crystal

*Solutions to AoC in Crystal.*

* [jazcarate/advent-of-code-2020](https://github.com/jazcarate/advent-of-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--19-brightgreen)
* [meadsteve/advent-of-code-2020](https://github.com/meadsteve/advent-of-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--12-brightgreen)

#### D

*Solutions to AoC in D.*

#### Dart

*Solutions to AoC in Dart.*

* [julemand101/AdventOfCode2020](https://github.com/julemand101/AdventOfCode2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--22-brightgreen)
* [limonadev/aoc2020](https://github.com/limonadev/aoc2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--21-brightgreen)

#### Elixir

*Solutions to AoC in Elixir.*

* [norrbacka/aoc2020_elixir](https://github.com/norrbacka/aoc2020_elixir) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--17-brightgreen)
* [papey/aoc](https://github.com/papey/aoc) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)

#### Elm

*Solutions to AoC in Elm and Literate Elm.*

#### Erlang

*Solutions to AoC in Erlang.*

* [stuart-thackray/aoc2020erl](https://github.com/stuart-thackray/aoc2020erl) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--20-brightgreen)

#### F#

*Solutions to AoC in F#.*

* [JanDotNet/AdventOfCode](https://github.com/JanDotNet/AdventOfCode) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [ThomasGoetzmann/AdventOfCode2020](https://github.com/ThomasGoetzmann/AdventOfCode2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--11-brightgreen)
* [jilleJr/adventofcode-2020-fsharp](https://github.com/jilleJr/adventofcode-2020-fsharp) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--14-brightgreen)
* [jovaneyck/advent-of-code-2020](https://github.com/jovaneyck/advent-of-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [wimex/AdventOfCode2020](https://github.com/wimex/AdventOfCode2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--22-brightgreen)
* [sanderploegsma/advent-of-code](https://github.com/sanderploegsma/advent-of-code) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)

#### Go

*Solutions to AoC in Go.*

* [Catorpilor/adventofcode](https://github.com/Catorpilor/adventofcode) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [NoMod-Programming/Advent-of-Code-2020](https://github.com/NoMod-Programming/Advent-of-Code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--08-brightgreen)
* [alokmenghrajani/adventofcode2020](https://github.com/alokmenghrajani/adventofcode2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--21-brightgreen)
* [arxeiss/advent-of-code-2020](https://github.com/arxeiss/advent-of-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--22-brightgreen)
* [bartvanackooij/adventofcode2020](https://github.com/bartvanackooij/adventofcode2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--10-brightgreen)
* [chigley/advent2020](https://github.com/chigley/advent2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [codemicro/adventOfCode](https://github.com/codemicro/adventOfCode) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [codingdiaz/advent-of-code-2020](https://github.com/codingdiaz/advent-of-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--08-brightgreen)
* [davidporos92/aoc-2020](https://github.com/davidporos92/aoc-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--13-brightgreen)
* [dds/aoc2020](https://github.com/dds/aoc2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--21-brightgreen)
* [devries/advent_of_code_2020](https://github.com/devries/advent_of_code_2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [j4rv/advent-of-code-2020](https://github.com/j4rv/advent-of-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--20-brightgreen)
* [jkershaw2000/aoc-2020](https://github.com/jkershaw2000/aoc-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--18-brightgreen)
* [jsgv/advent-of-code-2020](https://github.com/jsgv/advent-of-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--17-brightgreen)
* [jugendhacker/adventofcode](https://github.com/jugendhacker/adventofcode) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--13-brightgreen)
* [kindermoumoute/adventofcode](https://github.com/kindermoumoute/adventofcode) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [legion47T/adventofcode2020](https://github.com/legion47T/adventofcode2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [lynerist/Advent-of-code-2020-golang](https://github.com/lynerist/Advent-of-code-2020-golang) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--17-brightgreen)
* [mbonnafon/AdventOfCode](https://github.com/mbonnafon/AdventOfCode) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--13-brightgreen)
* [mbulatova/advent-of-code-2020](https://github.com/mbulatova/advent-of-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--14-brightgreen)
* [mnml/aoc](https://github.com/mnml/aoc) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [nlowe/aoc2020](https://github.com/nlowe/aoc2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--17-brightgreen)
* [sshilin/aoc2020](https://github.com/sshilin/aoc2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [thlacroix/goadvent](https://github.com/thlacroix/goadvent) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [orfeasa/advent-of-code-2020](https://github.com/orfeasa/advent-of-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)

#### Groovy

*Solutions to AoC in Groovy.*

#### Haskell

*Solutions to AoC in Haskell.*

* [BZuilhof/AdventOfCode](https://github.com/BZuilhof/AdventOfCode) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--10-brightgreen)
* [DestyNova/advent_of_code_2020](https://github.com/DestyNova/advent_of_code_2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [Sciencentistguy/AdventOfCode](https://github.com/Sciencentistguy/AdventOfCode) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--21-brightgreen)
* [SimonBaars/AdventOfCode-Haskell](https://github.com/SimonBaars/AdventOfCode-Haskell) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--11-brightgreen)
* [anhtumai/advent_of_code_2020](https://github.com/anhtumai/advent_of_code_2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [bionikspoon/HaskellAdventOfCode2020](https://github.com/bionikspoon/HaskellAdventOfCode2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [ephemient/aoc2020](https://github.com/ephemient/aoc2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [haskelling/aoc2020](https://github.com/haskelling/aoc2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [jitwit/aoc](https://github.com/jitwit/aoc) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [mstksg/advent-of-code-2020](https://github.com/mstksg/advent-of-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [rstromlund/advent-of-code](https://gitlab.com/rstromlund/advent-of-code/-/tree/master/)
* [slotThe/aoc-2020-haskell](https://gitlab.com/slotThe/aoc-2020-haskell)

#### Haxe

*Solutions to AoC in Haxe.*

#### Idris

*Solutions to AoC in Idris.*

* [xWafl/aoc-2020-idris](https://github.com/xWafl/aoc-2020-idris) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--10-brightgreen)

#### J

*Solutions to AoC in J.*

* [jitwit/aoc](https://github.com/jitwit/aoc) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [mk12/aoc](https://github.com/mk12/aoc) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--14-brightgreen)

#### Java

*Solutions to AoC in Java.*

* [Alex1607/AdventOfCode2020](https://github.com/Alex1607/AdventOfCode2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--15-brightgreen)
* [Ernyoke/advent-of-code-2020](https://github.com/Ernyoke/advent-of-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [PulseBeat02/Advent-of-Code-2020](https://github.com/PulseBeat02/Advent-of-Code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [SimonBaars/AdventOfCode-Java](https://github.com/SimonBaars/AdventOfCode-Java) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [SizableShrimp/AdventOfCode2020](https://github.com/SizableShrimp/AdventOfCode2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [akaritakai/AdventOfCode2020](https://github.com/akaritakai/AdventOfCode2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--19-brightgreen)
* [freefal/aoc2020](https://github.com/freefal/aoc2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--18-brightgreen)
* [mattgogerly/AdventOfCode](https://github.com/mattgogerly/AdventOfCode) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--16-brightgreen)
* [mzielinski/advent-of-code-2020](https://github.com/mzielinski/advent-of-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [tmrd993/advent-of-code-solutions](https://github.com/tmrd993/advent-of-code-solutions) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [yeroc/advent-of-code](https://github.com/yeroc/advent-of-code) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--17-brightgreen)

#### JavaScript

*Solutions to AoC in JavaScript.*

* [AxemaFr/AdventOfCode-2020](https://github.com/AxemaFr/AdventOfCode-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--12-brightgreen)
* [BenHall-1/AdventOfCode](https://github.com/BenHall-1/AdventOfCode) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--05-brightgreen)
* [Butterstroke/Advent-of-Code-2020](https://github.com/Butterstroke/Advent-of-Code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--12-brightgreen)
* [CharlesMenier/AdventOfCode2020](https://github.com/CharlesMenier/AdventOfCode2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--12-brightgreen)
* [KonradLinkowski/AdventOfCode](https://github.com/KonradLinkowski/AdventOfCode) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--19-brightgreen)
* [NLDev/Advent-of-Code-2020](https://github.com/NLDev/Advent-of-Code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [adamczarnecki/advent_of_code_2020](https://github.com/adamczarnecki/advent_of_code_2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--18-brightgreen)
* [adriennetacke/advent-of-code-2020](https://github.com/adriennetacke/advent-of-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--12-brightgreen)
* [chinesedfan/adventofcode](https://github.com/chinesedfan/adventofcode) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--22-brightgreen)
* [cullylarson/advent-code-2020](https://github.com/cullylarson/advent-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--09-brightgreen)
* [falsepopsky/advent-of-code-2020-js](https://github.com/falsepopsky/advent-of-code-2020-js) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--03-brightgreen)
* [joaomlneto/advent-of-code](https://github.com/joaomlneto/advent-of-code) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [leyanlo/advent-of-code](https://github.com/leyanlo/advent-of-code) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [linyeir/adventOfCode](https://github.com/linyeir/adventOfCode) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--15-brightgreen)
* [mariotacke/advent-of-code-2020](https://github.com/mariotacke/advent-of-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--19-brightgreen)
* [mdunisch/adventOfCode2020](https://github.com/mdunisch/adventOfCode2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--10-brightgreen)
* [mtsknn/advent-of-code](https://github.com/mtsknn/advent-of-code) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--22-brightgreen)
* [neg4n/advent-of-code](https://github.com/neg4n/advent-of-code) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--03-orange)
* [ridaamirini/advent-of-code](https://github.com/ridaamirini/advent-of-code) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--21-brightgreen)
* [rorz/advent-of-code-2020-functional-js](https://github.com/rorz/advent-of-code-2020-functional-js) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--13-brightgreen)
* [ryanolsonx/aocjs](https://github.com/ryanolsonx/aocjs) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--03-brightgreen)
* [s1gr1d/aoc-2020_functional-JS](https://github.com/s1gr1d/aoc-2020_functional-JS) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--18-brightgreen)
* [sankita11/AdventOfCode-2020](https://github.com/sankita11/AdventOfCode-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--16-brightgreen)
* [shahata/adventofcode-solver](https://github.com/shahata/adventofcode-solver) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [theninthsky/advent-of-code](https://github.com/theninthsky/advent-of-code) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--17-brightgreen)
* [kopenkinda/advent-of-code-2020](https://github.com/kopenkinda/advent-of-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)

#### Julia

*Solutions to AoC in Julia.*

* [DearRude/aoc-2020](https://github.com/DearRude/aoc-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [Enforcer007/AdventOfCode2020](https://github.com/Enforcer007/AdventOfCode2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--09-brightgreen)
* [goggle/AdventOfCode2020.jl](https://github.com/goggle/AdventOfCode2020.jl) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--20-brightgreen)
* [kersulis/Advent2020.jl](https://github.com/kersulis/Advent2020.jl) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--18-brightgreen)
* [natemcintosh/aoc_2020](https://github.com/natemcintosh/aoc_2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--22-brightgreen)
* [nsirons/programming-puzzles](https://github.com/nsirons/programming-puzzles) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [pranphy/advent-of-code](https://github.com/pranphy/advent-of-code) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--12-brightgreen)
* [racinmat/advent_of_code_2020](https://github.com/racinmat/advent_of_code_2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)

#### Kotlin

*Solutions to AoC in Kotlin.*

* [Albert221/advent-of-code](https://github.com/Albert221/advent-of-code) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--07-brightgreen)
* [JuanMaCuevas/AdventOfCode2020](https://github.com/JuanMaCuevas/AdventOfCode2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--15-brightgreen)
* [agrison/advent-of-code-2020](https://github.com/agrison/advent-of-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [bence-t0th/Advent-of-Code-2020](https://github.com/bence-t0th/Advent-of-Code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--11-brightgreen)
* [crepppy/aoc2020](https://github.com/crepppy/aoc2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--08-brightgreen)
* [edgars-supe/advent-of-code](https://github.com/edgars-supe/advent-of-code) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--12-brightgreen)
* [ephemient/aoc2020](https://github.com/ephemient/aoc2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [hughjdavey/aoc-2020](https://github.com/hughjdavey/aoc-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [janbina/advent-of-code-2020](https://github.com/janbina/advent-of-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [jorispz/aoc-2020](https://github.com/jorispz/aoc-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--10-brightgreen)
* [nschwermann/AdventOfCode](https://github.com/nschwermann/AdventOfCode) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--20-brightgreen)
* [yangzii0920/advent-of-code-2020](https://github.com/yangzii0920/advent-of-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--22-brightgreen)
* [tobi6112/AdventOfCode_2020](https://github.com/tobi6112/AdventOfCode_2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--19-brightgreen)

#### LDPL

*Solutions to AoC in LDPL.*

#### Lua

*Solutions to AoC in Lua.*

* [actually-reb/aoc2020](https://github.com/actually-reb/aoc2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)

#### MATLAB

*Solutions to AoC in MATLAB (Octave).*

* [jholtom/advent-of-code-2020](https://github.com/jholtom/advent-of-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--15-brightgreen)

#### Nim

*Solutions to AoC in Nim.*

* [0xSMT/advent-of-code-2020](https://github.com/0xSMT/advent-of-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--12-brightgreen)
* [MarcosSevert/AoC2020](https://github.com/MarcosSevert/AoC2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--16-brightgreen)
* [aod/advent-of-nim](https://github.com/aod/advent-of-nim) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--11-brightgreen)
* [dimspith/AdventOfCode2020](https://github.com/dimspith/AdventOfCode2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--20-brightgreen)
* [jgesc/AdventOfCode2020](https://github.com/jgesc/AdventOfCode2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--17-brightgreen)
* [pietroppeter/adventofnim](https://github.com/pietroppeter/adventofnim) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--21-brightgreen)

#### OCaml

*Solutions to AoC in OCaml.*

* [illbexyz/advent-of-code-2020](https://github.com/illbexyz/advent-of-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--17-brightgreen)

#### PHP

*Solutions to AoC in PHP.*

* [CostingGeek/advent-of-code-2020](https://github.com/CostingGeek/advent-of-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--18-brightgreen)
* [XonneX/adventofcode2020](https://github.com/XonneX/adventofcode2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--14-brightgreen)
* [hapidjus/AdventOfCode](https://github.com/hapidjus/AdventOfCode) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--16-brightgreen)
* [ridaamirini/advent-of-code](https://github.com/ridaamirini/advent-of-code) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--21-brightgreen)
* [vuryss/aoc-php](https://github.com/vuryss/aoc-php) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--21-brightgreen)
* [xavice/advent-of-code](https://github.com/xavice/advent-of-code) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--05-brightgreen)

#### Perl

*Solutions to AoC in Perl.*

* [syaffers/p5-advent-of-code-2020]

#### Pony

*Solutions to AoC in Pony.*

#### Prolog

*Solutions to AoC in Prolog.*

* [aarroyoc/advent-of-code-2020](https://github.com/aarroyoc/advent-of-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)

#### PowerShell

*Solutions to AoC in PowerShell.*

* [rdybro/adventofcode](https://github.com/rdybro/adventofcode) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--22-brightgreen)
* [seanluce/adventofcode2020](https://github.com/seanluce/adventofcode2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--08-brightgreen)
* [sgruber94/awesome-advent-of-code2020](https://github.com/sgruber94/awesome-advent-of-code2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--06-brightgreen)
* [tomlarse/aoc2020](https://github.com/tomlarse/aoc2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--03-brightgreen)

#### Python

*Solutions to AoC in Python.*

* [0xVector/AdventOfCode2020](https://github.com/0xVector/AdventOfCode2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [Akumatic/Advent-of-Code](https://github.com/Akumatic/Advent-of-Code) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--19-brightgreen)
* [aribchowdhury/AdventOfCode2020](https://github.com/aribchowdhury/AdventOfCode2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [IanFindlay/advent-of-code](https://github.com/IanFindlay/advent-of-code) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [James-Ansley/adventofcode](https://github.com/James-Ansley/adventofcode) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--18-brightgreen)
* [Kurocon/AdventOfCode2020](https://github.com/Kurocon/AdventOfCode2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [Levivig/AdventOfCode2020](https://github.com/Levivig/AdventOfCode2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--07-brightgreen)
* [Manas02/Advent-of-code](https://github.com/Manas02/Advent-of-code) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--15-brightgreen)
* [Robin-Bakker/advent-of-code](https://github.com/Robin-Bakker/advent-of-code) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--08-brightgreen)
* [VasileiosGeladaris/AdventOfCode2020](https://github.com/VasileiosGeladaris/AdventOfCode2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--10-brightgreen)
* [agubelu/Advent-of-Code-2020](https://github.com/agubelu/Advent-of-Code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [alstn2468/Advent_of_Code_2020](https://github.com/alstn2468/Advent_of_Code_2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--14-brightgreen)
* [asiron/aoc](https://github.com/asiron/aoc) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--13-brightgreen)
* [aufbakanleitung/advent-of-code-2020](https://github.com/aufbakanleitung/advent-of-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--21-brightgreen)
* [aureliensimon/avent-of-code-2020](https://github.com/aureliensimon/avent-of-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--15-brightgreen)
* [bsoyka/aoc](https://github.com/bsoyka/aoc) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--22-brightgreen)
* [campierce/advent-of-code](https://github.com/campierce/advent-of-code) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [candemircan/adventofcode](https://github.com/candemircan/adventofcode) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--05-brightgreen)
* [codemicro/adventOfCode](https://github.com/codemicro/adventOfCode) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [d1618033/aoc](https://github.com/d1618033/aoc) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [dalealleshouse/advent_of_code](https://github.com/dalealleshouse/advent_of_code) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--19-brightgreen)
* [danwigrizer/Advent-of-Code](https://github.com/danwigrizer/Advent-of-Code) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--15-brightgreen)
* [darkarp/AdventSolutions](https://github.com/darkarp/AdventSolutions) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--10-brightgreen)
* [david-ds/adventofcode-2020](https://github.com/david-ds/adventofcode-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [eliseomartelli/Advent-of-Code-2020](https://github.com/eliseomartelli/Advent-of-Code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--04-brightgreen)
* [elvinyhlee/advent-of-code-2020-python](https://github.com/elvinyhlee/advent-of-code-2020-python) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [ephemient/aoc2020](https://github.com/ephemient/aoc2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [facufrau/Advent-of-code-2020](https://github.com/facufrau/Advent-of-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [gamma032steam/Advent-of-code-2020](https://github.com/gamma032steam/Advent-of-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--19-brightgreen)
* [gbusch/AdventOfCode/](https://github.com/gbusch/AdventOfCode/) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--09-brightgreen)
* [gui1612/advent_2020](https://github.com/gui1612/Advent-of-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--02-orange)
* [harbenml/advent-of-code-2020](https://github.com/harbenml/advent-of-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [hmludwig/aoc2020](https://github.com/hmludwig/aoc2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--16-brightgreen)
* [howtodowtle/advent_of_code](https://github.com/howtodowtle/advent_of_code) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [irobin591/advent-of-code](https://github.com/irobin591/advent-of-code) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [jayascript/adventofcode2020](https://github.com/jayascript/adventofcode2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--10-brightgreen)
* [jesperdramsch/advent-of-code](https://github.com/jesperdramsch/advent-of-code) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [jkershaw2000/aoc-2020](https://github.com/jkershaw2000/aoc-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--18-brightgreen)
* [john-sandall/advent-of-code](https://github.com/john-sandall/advent-of-code) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--01-brightgreen)
* [jon-edward/advent-of-code-2020](https://github.com/jon-edward/advent-of-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--04-brightgreen)
* [jordyjwilliams/advent_of_code](https://github.com/jordyjwilliams/advent_of_code) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--15-brightgreen)
* [JoseTomasTocino/AdventOfCode2020](https://github.com/JoseTomasTocino/AdventOfCode2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [kamaravichow/advent-of-code-2020-python](https://github.com/kamaravichow/advent-of-code-2020-python) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--06-brightgreen)
* [ktmeaton/advent-of-code-2020](https://github.com/ktmeaton/advent-of-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--22-brightgreen)
* [lukestorry/advent-of-code-2020](https://github.com/lukestorry/advent-of-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--22-brightgreen)
* [matus-pikuliak/advent_2020](https://github.com/matus-pikuliak/advent_2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [mebeim/aoc](https://github.com/mebeim/aoc) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [nagybalint/advent-of-code-2020](https://github.com/nagybalint/advent-of-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--20-brightgreen)
* [npanuhin/Advent-of-Code](https://github.com/npanuhin/Advent-of-Code) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [pauldraper/advent-of-code-2020](https://github.com/pauldraper/advent-of-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [peter-roland-toth/AoC-2020-Python](https://github.com/peter-roland-toth/AoC-2020-Python) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [phoebegoh/aoc2020](https://github.com/phoebegoh/aoc2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--11-brightgreen)
* [r0f1/adventofcode2020](https://github.com/r0f1/adventofcode2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--21-brightgreen)
* [rkc007/advent-of-code-2020](https://github.com/rkc007/advent-of-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--16-brightgreen)
* [rubennoriegamier/advent_of_code_2020](https://github.com/rubennoriegamier/advent_of_code_2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--14-brightgreen)
* [sammyrulez/adventofcode](https://github.com/sammyrulez/adventofcode) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--08-brightgreen)
* [sebadel/adventofcode2020](https://github.com/sebadel/adventofcode2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [sejaldua/advent-of-code-2020](https://github.com/sejaldua/advent-of-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--11-brightgreen)
* [silverben10/aoc](https://github.com/silverben10/aoc) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--22-brightgreen)
* [smetanin-av/advent_of_code](https://github.com/smetanin-av/advent_of_code) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--20-brightgreen)
* [tboschi/advent-of-code-2020](https://github.com/tboschi/advent-of-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--21-brightgreen)
* [terror/aoc](https://github.com/terror/aoc) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--13-brightgreen)
* [thosquey/aoc2020](https://github.com/thosquey/aoc2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--21-brightgreen)
* [tombombadilv/advent-of-code-2020](https://github.com/tombombadilv/advent-of-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--19-brightgreen)
* [wysockipiotr/aoc](https://github.com/wysockipiotr/aoc) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--18-brightgreen)
* [yeurch/advent-of-code](https://github.com/yeurch/advent-of-code) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--21-brightgreen)
* [yufengg/adventofcode](https://github.com/yufengg/adventofcode) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--21-brightgreen)
* [rosscon/rosscon_advent_of_code](https://github.com/rosscon/rosscon_advent_of_code) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--22-brightgreen)
* [terezaif/adventofcode](https://github.com/terezaif/adventofcode) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--22-brightgreen)
* [zed-b/advent-of-code](https://github.com/zed-b/advent-of-code) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--22-brightgreen)

#### R

*Solutions to AoC in R.*

* [CharnelMouse/AdventOfCode2020](https://github.com/CharnelMouse/AdventOfCode2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [JohannesFriedrich/AdventOfCode2020](https://github.com/JohannesFriedrich/AdventOfCode2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--09-brightgreen)
* [akulumbeg/adventofcode](https://github.com/akulumbeg/adventofcode) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--13-brightgreen)
* [fdlk/advent-2020](https://github.com/fdlk/advent-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [lemonad/advent-of-code](https://github.com/lemonad/advent-of-code) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--08-brightgreen)
* [nirski/aoc20](https://github.com/nirski/aoc20) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--15-brightgreen)
* [plannapus/Advent_of_Code](https://github.com/plannapus/Advent_of_Code) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [rrrlw/advent-of-code](https://github.com/rrrlw/advent-of-code) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--11-brightgreen)

#### Racket

*Solutions to AoC in Racket.*

* [Bogdanp/aoc2020](https://github.com/Bogdanp/aoc2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--19-brightgreen)
* [haskal/aoc2020](https://git.lain.faith/haskal/aoc2020)
* [jackfirth/advent-of-code](https://github.com/jackfirth/advent-of-code) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--15-brightgreen)
* [lojic/LearningRacket](https://github.com/lojic/LearningRacket) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--22-brightgreen)
* [mbutterick/aoc-racket](https://github.com/mbutterick/aoc-racket) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [samdphillips/aoc-2020](https://github.com/samdphillips/aoc-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--06-brightgreen)
* [opsound/adventofcode](https://github.com/opsound/adventofcode) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--20-brightgreen)

#### Raku

*Solutions to AoC in Raku.*

* [interlab/advent-of-code](https://github.com/interlab/advent-of-code) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--13-brightgreen)

#### ReasonML

*Solutions to AoC in ReasonML.*

* [believer/advent-of-code](https://github.com/believer/advent-of-code) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--22-brightgreen)
* [cometkim/advent-of-code-2020](https://github.com/cometkim/advent-of-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--20-brightgreen)

#### Red

*Solutions to AoC in Red.*

#### Ruby

*Solutions to AoC in Ruby.*

* [0x8b/aoc-2020-rb](https://github.com/0x8b/aoc-2020-rb) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--22-brightgreen)
* [damyvv/AoC_2020](https://github.com/damyvv/AoC_2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--22-brightgreen)
* [gogvale/AdventOfCode](https://github.com/gogvale/AdventOfCode) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--08-brightgreen)
* [ni3t/advent-2020](https://github.com/ni3t/advent-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--11-brightgreen)
* [damaldonadoc/advent-of-code-rb](https://github.com/damaldonadoc/advent-of-code-rb) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [gchan/advent-of-code-ruby](https://github.com/gchan/advent-of-code-ruby) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)

#### Rust

*Solutions to AoC in Rust.*

* [agubelu/Advent-of-Code-2020](https://github.com/agubelu/Advent-of-Code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [aniljava/aoc-2020](https://github.com/aniljava/aoc-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--09-brightgreen)
* [baszalmstra/adventofcode2020](https://github.com/baszalmstra/adventofcode2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [believer/advent-of-code](https://github.com/believer/advent-of-code) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--22-brightgreen)
* [deepakrb/aoc-2020](https://github.com/deepakrb/aoc-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--16-brightgreen)
* [drwilco/aoc](https://github.com/drwilco/aoc) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--22-brightgreen)
* [ephemient/aoc2020](https://github.com/ephemient/aoc2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [floatdrop/aoc](https://github.com/floatdrop/aoc) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--15-brightgreen)
* [forny/advent-of-code-2020](https://github.com/forny/advent-of-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [fornwall/advent-of-code](https://github.com/fornwall/advent-of-code) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--22-brightgreen)
* [hashedone/aoc2020](https://github.com/hashedone/aoc2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--10-brightgreen)
* [lukestorry/advent-of-code-2020](https://github.com/lukestorry/advent-of-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--22-brightgreen)
* [maksyms/aoc2020](https://github.com/maksyms/aoc2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--22-brightgreen)
* [mathieu/adventofcode-2020](https://lab.texthtml.net/mathieu/adventofcode-2020)
* [naamancurtis/advent_of_code](https://github.com/naamancurtis/advent_of_code) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--21-brightgreen)
* [nickyvanurk/advent-of-code](https://github.com/nickyvanurk/advent-of-code) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--22-brightgreen)
* [novoselov-ab/adventofcode-2020-rust](https://github.com/novoselov-ab/adventofcode-2020-rust) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--20-brightgreen)
* [phantomion/rust_aoc](https://github.com/phantomion/rust_aoc) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--15-brightgreen)
* [sertsedat/advent-of-code](https://github.com/sertsedat/advent-of-code) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--21-brightgreen)
* [shank/advent-of-code](https://gitlab.com/shank/advent-of-code)
* [stannislav/advent-of-code](https://github.com/stannislav/advent-of-code) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [tejasbubane/adventofcode-2020](https://github.com/tejasbubane/adventofcode-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--20-brightgreen)
* [thepants999/advent-of-code-2020](https://github.com/thepants999/advent-of-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [warycat/rustgym](https://github.com/warycat/rustgym) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [williamfhe/advent-of-code-2020](https://github.com/williamfhe/advent-of-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--19-brightgreen)
* [youngtrashbag/adventofcode](https://github.com/youngtrashbag/adventofcode) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--04-brightgreen)
* [zsacul/AdventOfCode2020](https://github.com/zsacul/AdventOfCode2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [EtherTyper/advent-of-code](https://gitlab.com/EtherTyper/advent-of-code)
* [SLMT/advent-of-code](https://github.com/SLMT/advent-of-code) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--21-brightgreen)
* [LesnyRumcajs/advent-of-rust-2020](https://github.com/LesnyRumcajs/advent-of-rust-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [tumdum/aoc2020](https://github.com/tumdum/aoc2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)

#### Smalltalk

*Solutions to AoC in Smalltalk.*

* [NoMod-Programming/Advent-of-Code-2020](https://github.com/NoMod-Programming/Advent-of-Code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--08-brightgreen)

#### Scala

*Solutions to AoC in Scala.*

* [slowens-revature/advent_of_code_2020](https://github.com/slowens-revature/advent_of_code_2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--22-brightgreen)
* [FlorianCassayre/AdventOfCode-2020](https://github.com/FlorianCassayre/AdventOfCode-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--20-brightgreen)
* [jirkavrba/advent-of-code](https://github.com/jirkavrba/advent-of-code) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--12-brightgreen)
* [niedrist/advent-of-code-2020](https://github.com/niedrist/advent-of-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--11-brightgreen)
* [sim642/adventofcode](https://github.com/sim642/adventofcode) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [Billzabob/AdventOfCode](https://github.com/Billzabob/AdventOfCode) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--17-brightgreen)

#### Scheme

*Solutions to AoC in Scheme.*

* [jitwit/aoc](https://github.com/jitwit/aoc) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)

#### SpectX

*Solutions to AoC in SpectX.*

* [spectx/aoc2020](https://github.com/spectx/aoc2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--08-brightgreen)

#### SQL

*Solutions to AoC in SQL.*

* [xocolatl/advent-of-code](https://github.com/xocolatl/advent-of-code) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--21-brightgreen)

#### Swift

*Solutions to AoC in Swift.*

* [UMPUSTEN/AoC-2020](https://github.com/UMPUSTEN/AoC-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--12-brightgreen)
* [bence-t0th/Advent-of-Code-2020](https://github.com/bence-t0th/Advent-of-Code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--11-brightgreen)
* [fguchelaar/AdventOfCode2020](https://github.com/fguchelaar/AdventOfCode2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--17-brightgreen)
* [gernb/AdventOfCode2020](https://github.com/gernb/AdventOfCode2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--20-brightgreen)
* [juanj/AdventOfCode2020](https://github.com/juanj/AdventOfCode2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [lighthouse16/AdventOfCode](https://github.com/lighthouse16/AdventOfCode) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--11-brightgreen)
* [Afstkla/AdventOfCode2020](https://github.com/Afstkla/AdventOfCode2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [richardpineo/AOC2020](https://github.com/richardpineo/AOC2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--22-brightgreen)
* [crmitchelmore/adventofcode2020](https://github.com/crmitchelmore/adventofcode2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--18-brightgreen)
* [altaibayar/AdventOfCode](https://github.com/altaibayar/AdventOfCode) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--22-brightgreen)

#### TypeScript

*Solutions to AoC in TypeScript.*

* [AlexAegis/advent-of-code](https://github.com/AlexAegis/advent-of-code) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [GliderGeek/adventofcode20](https://github.com/GliderGeek/adventofcode20) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--20-brightgreen)
* [RubenVerg/aoc2020](https://github.com/RubenVerg/aoc2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--08-brightgreen)
* [WillGresham/AdventOfCode2020](https://github.com/WillGresham/AdventOfCode2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--12-brightgreen)
* [adaamz/advent-of-code-2020](https://github.com/adaamz/advent-of-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--22-brightgreen)
* [allarallas/aoc2020](https://github.com/allarallas/aoc2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--10-brightgreen)
* [anetz89/adventofcode20](https://github.com/anetz89/adventofcode20) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--22-brightgreen)
* [arnauddrain/advent-of-code-2020](https://github.com/arnauddrain/advent-of-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--13-brightgreen)
* [cheemcheem/adventofcode2020](https://github.com/cheemcheem/adventofcode2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--18-brightgreen)
* [izexi/adventofcode2020](https://github.com/izexi/adventofcode2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--22-brightgreen)
* [marcobiedermann/advent-of-code](https://github.com/marcobiedermann/advent-of-code) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--22-brightgreen)
* [matthewtole/advent-of-code](https://github.com/matthewtole/advent-of-code) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--10-brightgreen)
* [milanosie/adventofcode2020](https://github.com/milanosie/adventofcode2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--16-brightgreen)
* [sanraith/aoc2020](https://github.com/sanraith/aoc2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)
* [ttbowen/advent-of-code-2020](https://github.com/ttbowen/advent-of-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--06-brightgreen)
* [robinpokorny/advent-of-code-2020](https://github.com/robinpokorny/advent-of-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--21-brightgreen)
* [RinkAttendant6/advent-of-code-2020](https://github.com/RinkAttendant6/advent-of-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--22-brightgreen)
* [LoicB/Advent-of-Code-2020](https://github.com/LoicB/Advent-of-Code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--22-brightgreen)

##### Deno

*Solutions to AoC in Deno (TypeScript).*

* [adaamz/advent-of-code-2020](https://github.com/adaamz/advent-of-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--22-brightgreen)
* [ismtabo/advent-of-code-2020](https://github.com/ismtabo/advent-of-code-2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)

#### Unison

*Solutions to AoC in Unison.*

#### VB.NET

*Solutions to AoC in VB.NET.*

* [Virenbar/AdventOfCode2020](https://github.com/Virenbar/AdventOfCode2020) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--23-brightgreen)

#### Zig

*Solutions to AoC in Zig.*

* [fyrchik/aoc2020zig](https://github.com/fyrchik/aoc2020zig) ![Last Commit on GitHub](https://img.shields.io/badge/last%20commit-2020--12--19-brightgreen)

### Live Streams

*Folks who are live streaming their process.*

* [Alca](https://twitch.tv/Alca) (JavaScript)
* [ClysmiC](https://twitch.tv/clysmic) (C++)
* [Pewqazz](https://twitch.tv/Pewqazz) (Python)
* [Ph3rny](https://twitch.tv/anthonywritescode) (Python)
* [SimonBaars](https://www.twitch.tv/simon_baars) (Java + Haskell)
* [anagonlive](https://twitch.tv/anagonlive) (Python)
* [chrisforrence](https://twitch.tv/chrisforrence) (PHP)
* [dr_njitram](https://twitch.tv/dr_njitram) (Python)
* [hurlian](https://twitch.tv/hurlian) (Python)
* [jonathan_paulson](https://www.youtube.com/channel/UCuWLIm0l4sDpEe28t41WITA/videos) (Python)
* [jwise00](https://www.youtube.com/channel/UCBHySN2FtVPxEJxYU1PXTHA) (Lua)
* [lizthegrey](https://twitch.tv/lizthegrey) (Go)
* [lukechampine](https://twitch.tv/nemo1618) (Go/Zig)
* [martinjaniczek](https://twitch.tv/martinjaniczek) (Elm)
* [maryjostaebler](https://www.twitch.tv/maryjostaebler) (JavaScript)
* [nicuveo](https://twitch.tv/nicuveo) (Haskell)
* [pengiswe](https://www.twitch.tv/pengiswe) (Excel)
* [psymar_](https://twitch.tv/psymar_) (Python)
* [spaceboyr00](https://twitch.tv/spaceboyr00) (Python)
* [theypsilon](https://www.youtube.com/playlist?list=PL959l4g0Ko1riV3QU_qcTgue41y4S7ffP) (Rust)
* [vwoo](https://www.twitch.tv/vwoo) (Ruby)
* [yernab](https://twitch.tv/yernab) (APL)
