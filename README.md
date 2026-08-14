# Awesome Erlang with stars

A curated list of amazingly awesome Erlang libraries, resources and shiny thing inspired by [awesome-elixir](https://github.com/h4cc/awesome-elixir) ⭐ 13,160 | 🐛 26 | 🌐 Elixir | 📅 2025-10-12.

* [Awesome Erlang](#awesome-Erlang)
  * [Package Management](#package-management)
  * [Release Management](#release-management)
  * [Configuration Management](#configuration-management)
  * [Codebase Maintenance](#codebase-maintenance)
  * [Web Frameworks](#web-frameworks)
  * [Web Framework Components](#web-framework-components)
  * [HTTP](#http)
  * [Testing](#testing)
  * [Logging](#logging)
  * [Monitoring](#monitoring)
  * [Deployment](#deployment)
  * [Distributed Systems](#distributed-systems)
  * [Code Analysis](#code-analysis)
  * [Build Tools](#build-tools)
  * [Geolocation](#geolocation)
  * [Debugging](#debugging)
  * [Actors](#actors)
  * [Date and Time](#date-and-time)
  * [ORM and Datamapping](#orm-and-datamapping)
  * [Queue](#queue)
  * [Authentication](#authentication)
  * [Text and Numbers](#text-and-numbers)
  * [REST and API](#rest-and-api)
  * [Caching](#caching)
  * [Third Party APIs](#third-party-apis)
  * [Networking](#networking)
  * [Internet of Things](#internet-of-things)
  * [Algorithms and Datastructures](#algorithms-and-datastructures)
  * [Translations and Internationalizations](#translations-and-internationalizations)
  * [Miscellaneous](#miscellaneous)
* [Resources](#resources)
  * [Websites](#websites)
  * [Books](#books)
  * [Web Reading](#web-reading)
  * [Erlang Reading](#Erlang-reading)
  * [Screencasts](#screencasts)
* [Other Awesome Lists](#other-awesome-lists)
* [Contributing](#contributing)

## Package Management

*Libraries and tools for package and dependency management.*

* [hex.pm](https://hex.pm/) - A package manager for the Erlang ecosystem.

## Release Management

*Libraries and tools for release management.*

* [relx](https://github.com/erlware/relx) ⭐ 692 | 🐛 83 | 🌐 Erlang | 📅 2026-03-24 - A release assembler for Erlang.

## Configuration Management

*Libraries and tools related to configuration management.*

* [stillir](https://github.com/heroku/stillir) ⚠️ Archived - Cache environment variables as Erlang app variables.

## Codebase Maintenance

*Libraries and tools to maintain a clean codebase.*

* [elvis](https://github.com/inaka/elvis) ⭐ 434 | 🐛 1 | 🌐 Erlang | 📅 2026-07-09 - Erlang Style Reviewer.

## Web Frameworks

*Web development frameworks.*

* [cowboy](https://github.com/ninenines/cowboy) ⭐ 7,523 | 🐛 63 | 🌐 Erlang | 📅 2026-07-28 - A simple HTTP server.
* [MochiWeb](https://github.com/mochi/mochiweb) ⭐ 1,890 | 🐛 11 | 🌐 Erlang | 📅 2026-08-10 - An Erlang library for building lightweight HTTP servers.
* [ChicagoBoss](https://github.com/ChicagoBoss/ChicagoBoss) ⭐ 1,849 | 🐛 81 | 🌐 Erlang | 📅 2022-01-10 - A server framework inspired by Rails and written in Erlang.
* [N2O](https://github.com/synrc/n2o) ⭐ 1,342 | 🐛 1 | 🌐 Erlang | 📅 2026-06-04 - WebSocket Application Server.
* [Nitrogen](https://github.com/nitrogen/nitrogen) ⭐ 983 | 🐛 16 | 🌐 Erlang | 📅 2026-07-26 - Framework to build web applications (including front-end) in pure Erlang.
* [Zotonic](https://github.com/zotonic/zotonic) ⭐ 846 | 🐛 196 | 🌐 Erlang | 📅 2026-08-13 - High speed, real-time web framework and content management system.
* [Axiom](https://github.com/tsujigiri/axiom) ⭐ 266 | 🐛 6 | 🌐 Erlang | 📅 2023-02-16 - A micro-framework, inspired by Ruby's [Sinatra](https://github.com/sinatra/sinatra) ⭐ 12,452 | 🐛 47 | 🌐 Ruby | 📅 2026-07-20.
* [Giallo](https://github.com/kivra/giallo) ⚠️ Archived - A small and flexible web framework on top of [Cowboy](https://github.com/ninenines/cowboy) ⭐ 7,523 | 🐛 63 | 🌐 Erlang | 📅 2026-07-28.

## Web Framework Components

*Standalone component from web development frameworks.*

* [simple\_bridge](https://github.com/nitrogen/simple_bridge) ⭐ 114 | 🐛 17 | 🌐 Erlang | 📅 2026-07-27 - An abstraction layer providing a unified interface to popular Erlang web servers (Cowboy, Inets, Mochiweb, Webmachine, and Yaws).
* [cb\_admin](https://github.com/ChicagoBoss/cb_admin) ⭐ 66 | 🐛 16 | 🌐 CSS | 📅 2016-06-10 - An admin interface for Chicago Boss.
* [giallo\_session](https://github.com/kivra/giallo_session) ⚠️ Archived - A session management library for the Giallo web framework.
* [cb\_websocket\_controller](https://github.com/dkuhlman/cb_websocket_controller) ⭐ 8 | 🐛 0 | 🌐 Erlang | 📅 2013-01-24 - A template for implementing a Websocket controller for ChicagoBoss.

## HTTP

*Libraries for working with HTTP and scraping websites.*

* [hackney](https://github.com/benoitc/hackney) ⭐ 1,416 | 🐛 12 | 🌐 Erlang | 📅 2026-08-12 - Simple HTTP client in Erlang.
* [gun](https://github.com/ninenines/gun) ⭐ 947 | 🐛 24 | 🌐 Erlang | 📅 2026-07-28 - Erlang HTTP client with support for HTTP/1.1, SPDY and Websocket.
* [ibrowse](https://github.com/cmullaparthi/ibrowse) ⭐ 518 | 🐛 19 | 🌐 Erlang | 📅 2026-05-01 - Erlang HTTP client.
* [bullet](https://github.com/ninenines/bullet) ⚠️ Archived - Simple, reliable, efficient streaming for Cowboy.
* [shotgun](https://github.com/inaka/shotgun) ⭐ 168 | 🐛 17 | 🌐 Erlang | 📅 2026-06-17 - For the times you need more than just a gun.
* [lhttpc](https://github.com/esl/lhttpc) ⭐ 128 | 🐛 20 | 🌐 Erlang | 📅 2022-03-29 - A lightweight HTTP/1.1 client implemented in Erlang.

## Testing

*Libraries for testing codebases and generating test data.*

* [PropEr](https://github.com/manopapad/proper) ⭐ 917 | 🐛 50 | 🌐 Erlang | 📅 2026-06-24 - A QuickCheck-inspired property-based testing tool for Erlang.
* [tracerl](https://github.com/esl/tracerl) ⭐ 17 | 🐛 0 | 🌐 Erlang | 📅 2014-07-31 - Dynamic tracing tests and utilities for Erlang/OTP

## Logging

*Libraries for generating and working with log files.*

* [logplex](https://github.com/heroku/logplex) ⚠️ Archived - Heroku log router.
* [lager](https://github.com/basho/lager) ⚠️ Archived - A logging framework for Erlang/OTP.
* [lager\_amqp\_backend](https://github.com/jbrisbin/lager_amqp_backend) ⭐ 34 | 🐛 2 | 🌐 Erlang | 📅 2012-04-13 - AMQP RabbitMQ Lager backend.
* [lager\_loggly](https://github.com/kivra/lager_loggly) ⚠️ Archived - Loggly backend for lager.
* [lager\_smtp](https://github.com/blinkov/lager_smtp) ⭐ 13 | 🐛 0 | 🌐 Erlang | 📅 2012-11-08 - SMTP backend for lager.
* [lager\_hipchat](https://github.com/synlay/lager_hipchat) ⭐ 7 | 🐛 3 | 🌐 Erlang | 📅 2017-01-08 - HipChat backend for lager.
* [lager\_slack](https://github.com/furmanOFF/lager_slack) ⭐ 2 | 🐛 0 | 🌐 Erlang | 📅 2018-05-30 - Simple Slack backend for lager.

## Monitoring

*Libraries for gathering metrics and monitoring.*

* [folsom](https://github.com/boundary/folsom) ⭐ 583 | 🐛 14 | 🌐 Erlang | 📅 2018-11-07 - An Erlang based metrics system inspired by Coda Hale's [metrics](https://github.com/codahale/metrics) ⚠️ Archived.
* [Exometer](https://github.com/Feuerlabs/exometer) ⭐ 528 | 🐛 16 | 🌐 Erlang | 📅 2019-06-14 - An Erlang instrumentation package.
* [eper](https://github.com/massemanet/eper) ⭐ 440 | 🐛 5 | 🌐 Erlang | 📅 2018-07-06 - A loose collection of Erlang Performance related tools.
* [entop](https://github.com/mazenharake/entop) ⭐ 267 | 🐛 3 | 🌐 Erlang | 📅 2019-05-29 - A top-like Erlang node monitoring tool.
* [vmstats](https://github.com/ferd/vmstats) ⭐ 256 | 🐛 1 | 🌐 Erlang | 📅 2025-09-11 - Tiny Erlang app that works in conjunction with statsderl in order to generate information on the Erlang VM for graphite logs.
* [statsderl](https://github.com/lpgauth/statsderl) ⭐ 100 | 🐛 2 | 🌐 Erlang | 📅 2026-06-05 - A statsd Erlang client.

## Deployment

*Libraries and tools related to deployment of Erlang/OTP applications.*

* [docker-erlang](https://github.com/synlay/docker-erlang) ⭐ 14 | 🐛 1 | 📅 2017-11-23 - Basic Docker Container Images for Erlang/OTP.

## Distributed Systems

*Tools for stress/load testing, latency issues, etc. across microservices.*

* [Typhoon](https://github.com/fogfish/typhoon) ⭐ 44 | 🐛 2 | 🌐 Erlang | 📅 2019-08-24 - Stress and load testing tool for distributed systems that simulates traffic from a test cluster toward a system-under-test (SUT) and visualizes related latencies.

## Code Analysis

*Libraries and tools for analysing, parsing and manipulation codebases.*

* [eflame](https://github.com/proger/eflame) ⭐ 429 | 🐛 6 | 🌐 Perl | 📅 2023-12-13 - A Flame Graph profiler for Erlang.
* [Concuerror](https://github.com/parapluu/Concuerror) ⭐ 346 | 🐛 17 | 🌐 Erlang | 📅 2026-06-24 - Concuerror is a systematic testing tool for concurrent Erlang programs.
* [geas](https://github.com/crownedgrouse/geas) ⭐ 111 | 🐛 1 | 🌐 Erlang | 📅 2026-06-14 - Geas is a tool that will detect the runnable official Erlang release window for your project, including its dependencies and provides many useful informations.

## Build Tools

*Project build and automation tools.*

* [rebar3](https://github.com/rebar/rebar3) ⭐ 1,816 | 🐛 229 | 🌐 Erlang | 📅 2026-08-10 - A build tool for Erlang which can manage Erlang packages from [Hex.pm](https://hex.pm/). See more at [rebar3.org](https://www.rebar3.org/)
* [rebar](https://github.com/rebar/rebar) ⚠️ Archived - Erlang build tool that makes it easy to compile and test Erlang applications, port drivers and releases.
* [sync](https://github.com/rustyio/sync) ⭐ 761 | 🐛 17 | 🌐 Erlang | 📅 2025-06-30 - On-the-fly recompiling for Erlang.

## Geolocation

*Libraries for geocoding addresses and working with latitudes and longitudes.*

* [GeoCouch](https://github.com/couchbase/geocouch) ⭐ 516 | 🐛 3 | 🌐 Erlang | 📅 2021-11-10 - A spatial extension for Couchbase and Apache CouchDB.
* [erl-rstar](https://github.com/armon/erl-rstar) ⭐ 58 | 🐛 0 | 🌐 Erlang | 📅 2018-07-11 - An Erlang implementation of the R\*-tree spacial data structure.
* [Teles](https://github.com/armon/teles) ⭐ 15 | 🐛 0 | 🌐 Erlang | 📅 2016-07-22 - An Erlang network service for manipulating geographic data.

## Debugging

*Libraries and tools for debugging code and applications.*

* [tx](https://github.com/kvakvs/tx) ⭐ 83 | 🐛 1 | 🌐 CSS | 📅 2014-10-08 - An HTML Erlang term viewer, starts own webserver and displays any term you give it from your Erlang node.

## Actors

*Libraries and tools for working with actors and such.*

* [poolboy](https://github.com/devinus/poolboy) ⭐ 1,598 | 🐛 45 | 🌐 Erlang | 📅 2023-04-18 - A hunky Erlang worker pool factory.

## Date and Time

*Libraries for working with dates and times.*

* [qdate](https://github.com/choptastic/qdate) ⭐ 248 | 🐛 10 | 🌐 Erlang | 📅 2026-07-26 - Erlang date, time, and timezone management: formatting, conversion, and date arithmetic.
* [erlang\_localtime](https://github.com/dmitryme/erlang_localtime) ⭐ 56 | 🐛 13 | 🌐 Erlang | 📅 2017-02-04 - Erlang library for conversion from one local time to another.

## ORM and Datamapping

*Libraries that implement object-relational mapping or datamapping techniques.*

* [epgsql](https://github.com/epgsql/epgsql) ⭐ 445 | 🐛 48 | 🌐 Erlang | 📅 2026-07-24 - PostgreSQL Driver for Erlang.
* [mysql-otp](https://github.com/mysql-otp/mysql-otp) ⭐ 375 | 🐛 9 | 🌐 Erlang | 📅 2025-06-10 - MySQL/OTP – MySQL driver for Erlang/OTP.
* [boss\_db](https://github.com/ErlyORM/boss_db) ⭐ 276 | 🐛 61 | 🌐 Erlang | 📅 2024-01-05 - A sharded, caching, pooling, evented ORM for Erlang.
* [pgsql\_migration](https://github.com/artemeff/pgsql_migration) ⭐ 19 | 🐛 1 | 🌐 Erlang | 📅 2023-01-20 – PostgreSQL migrations for Erlang.

## Queue

*Libraries for working with event and task queues.*

* [pqueue](https://github.com/okeuday/pqueue) ⭐ 173 | 🐛 0 | 🌐 Erlang | 📅 2023-10-26 - Erlang Priority Queues.
* [tinymq](https://github.com/ChicagoBoss/tinymq) ⭐ 125 | 🐛 3 | 🌐 Erlang | 📅 2021-01-16 - A diminutive, in-memory message queue for Erlang.
* [dq](https://github.com/darach/dq) ⭐ 34 | 🐛 2 | 🌐 Erlang | 📅 2015-02-14 - Distributed Fault Tolerant Queue library.
* [ebqueue](https://github.com/rgrinberg/ebqueue) ⭐ 9 | 🐛 0 | 🌐 Erlang | 📅 2015-01-08 - Tiny simple blocking queue in erlang.

## Authentication

*Libraries for implementing authentications schemes.*

* [oauth2](https://github.com/kivra/oauth2) ⭐ 221 | 🐛 1 | 🌐 Erlang | 📅 2026-07-28 - Erlang Oauth2 implementation.

## Text and Numbers

*Libraries for parsing and manipulating text and numbers.*

* [jiffy](https://github.com/davisp/jiffy) ⭐ 879 | 🐛 0 | 🌐 C | 📅 2026-07-01 - JSON NIFs for Erlang.
* [jsx](https://github.com/talentdeficit/jsx) ⭐ 699 | 🐛 25 | 🌐 Erlang | 📅 2024-06-26 - An erlang application for consuming, producing and manipulating json.
* [eql](https://github.com/artemeff/eql) ⭐ 117 | 🐛 3 | 🌐 Erlang | 📅 2024-01-02 - Erlang with SQL or not.
* [rec2json](https://github.com/lordnull/rec2json) ⭐ 45 | 🐛 3 | 🌐 Erlang | 📅 2024-07-02 - Generate JSON encoder/decoder from record specs.
* [qsp](https://github.com/artemeff/qsp) ⭐ 18 | 🐛 0 | 🌐 Erlang | 📅 2016-10-30 - Enhanced query string parser for Erlang.
* [miffy](https://github.com/expelledboy/miffy) ⭐ 3 | 🐛 0 | 🌐 Erlang | 📅 2018-09-24 - Jiffy wrapper which returns pretty maps.
* [ejsv](https://github.com/patternmatched/ejsv) - Erlang JSON schema validator.

## REST and API

*Libraries and web tools for developing REST-ful APIs.*

* [leptus](https://github.com/s1n4/leptus) ⭐ 346 | 🐛 5 | 🌐 Erlang | 📅 2021-05-13 - Leptus is an Erlang REST framework that runs on top of cowboy.
* [rooster](https://github.com/FelipeBB/rooster) ⚠️ Archived - rooster is a lightweight REST framework that runs on top of mochiweb.

## Caching

*Libraries for caching data.*

* [cache](https://github.com/fogfish/cache) ⭐ 141 | 🐛 4 | 🌐 Erlang | 📅 2022-03-23 - In-memory Segmented Cache

## Third Party APIs

*Libraries for accessing third party APIs.*

* [restc](https://github.com/kivra/restclient) ⭐ 95 | 🐛 4 | 🌐 Erlang | 📅 2026-07-22 - An Erlang REST client
* [oauth2c](https://github.com/kivra/oauth2_client) ⭐ 74 | 🐛 4 | 🌐 Erlang | 📅 2026-07-28 - An Erlang oAuth 2 client (uses restc)
* [google-token-erlang](https://github.com/ruel/google-token-erlang) ⭐ 4 | 🐛 0 | 🌐 Erlang | 📅 2018-05-02 - Google ID token verifier for Erlang.

## Networking

*Libraries and tools for using network related stuff.*

* [ranch](https://github.com/ninenines/ranch) ⭐ 1,242 | 🐛 5 | 🌐 Erlang | 📅 2026-07-28 - Socket acceptor pool for TCP protocols.
* [gen\_rpc](https://github.com/priestjim/gen_rpc) ⭐ 227 | 🐛 9 | 🌐 Erlang | 📅 2025-11-05 - A scalable RPC library for Erlang-VM based languages.
* [barrel\_tcp](https://github.com/benoitc-attic/barrel_tcp) ⭐ 83 | 🐛 1 | 🌐 Erlang | 📅 2015-07-28 - barrel\_tcp is a generic TCP acceptor pool with low latency in Erlang.
* [gossiperl](https://github.com/gossiperl/gossiperl) ⭐ 47 | 🐛 13 | 🌐 Erlang | 📅 2021-09-30 - Language agnostic gossip middleware and message bus written in Erlang.
* [nat\_upnp](https://github.com/benoitc/nat_upnp) ⚠️ Archived - Erlang library to map your internal port to an external using UNP IGD.
* [gen\_tcp\_server](https://github.com/rpt/gen_tcp_server) ⭐ 11 | 🐛 3 | 🌐 Erlang | 📅 2015-04-07 - A library that takes the concept of gen\_server and introduces the same mechanics for operating a TCP server.

## Internet of Things

*Libraries and tools for interacting with the physical world.*

* [GRiSP](https://grisp.org/) - Run the Erlang VM on an IoT board with many hardware interfaces and low-level drivers using a small realtime unikernel called RTEMS
* [lemma\_erlang](https://github.com/noam-io/lemma_erlang) ⭐ 9 | 🐛 0 | 🌐 Erlang | 📅 2017-11-13 - A lemma for IDEO's Noam internet-of-things prototyping platform.

## Algorithms and Datastructures

*Libraries and implementations of algorithms and datastructures.*

* [riak\_dt](https://github.com/basho/riak_dt) ⭐ 357 | 🐛 10 | 🌐 Erlang | 📅 2026-08-14 - Erlang library of state based CRDTs.
* [statebox](https://github.com/mochi/statebox) ⭐ 256 | 🐛 2 | 🌐 Erlang | 📅 2015-02-03 - Erlang state "monad" with merge/conflict-resolution capabilities.
* [datum](https://github.com/fogfish/datum) ⭐ 127 | 🐛 11 | 🌐 Erlang | 📅 2025-07-07 - A pure functional and generic programming for Erlang
* [erlando](https://github.com/travelping/erlando) ⭐ 1 | 🐛 0 | 🌐 Erlang | 📅 2025-09-17 - A set of syntax extensions like currying and monads for Erlang.

## Translations and Internationalizations

*Libraries providing translations or internationalizations.*

## Miscellaneous

*Useful libraries or tools that don't fit in the categories above.*

* [erlang-history](https://github.com/ferd/erlang-history) ⚠️ Archived - Hacks to add shell history to Erlang's shell.
* [erld](https://github.com/ShoreTel-Inc/erld) ⭐ 190 | 🐛 0 | 🌐 C | 📅 2016-05-16 - erld is a small program designed to solve the problem of running Erlang programs as a UNIX daemon.

# Resources

Various resources, such as books, websites and articles, for improving your Erlang development skills and knowledge.

## Websites

*Useful web and Erlang-related websites and newsletters.*

* [Erlang Bookmarks](https://github.com/0xAX/erlang-bookmarks/wiki/Erlang-bookmarks) ⭐ 1,156 | 🐛 0 | 📅 2021-07-31 - All about erlang programming language \[powerd by community].
* [Erlang Central](https://erlangcentral.org/) - An awesome collections of erlang resource along with live community chat for discussing and seeking help.
* [Planet Erlang](http://www.planeterlang.com/) - Planet site/RSS feed of blog posts covering topics across the Erlang ecosystem.
* [Spawned Shelter](http://spawnedshelter.com/) - Erlang Spawned Shelter. A collection of the best articles, videos and presentations related to Erlang.

## Books

*Fantastic books and e-books.*

* [Erlang and Elixir for Imperative Programmers](https://leanpub.com/erlangandelixirforimperativeprogrammers) - Introduction to Erlang and Elixir in the context of functional concepts by Wolfgang Loder (2016)
* [Learn You Some Erlang](http://learnyousomeerlang.com/) - Learn you some Erlang - for great good! A very thorough resource covering everything from beginning Erlang programming to large-scale development and deployment.
* [Stuff Goes Bad - ERLANG IN ANGER](http://www.erlang-in-anger.com/) - This book intends to be a little guide about how to be the Erlang medic in a time of war.

## Web Reading

*General web-development-related reading materials.*

## Erlang Reading

*Erlang-releated reading materials.*

* [The Joy of Erlang; Or, How To Ride A Toruk](http://www.evanmiller.org/joy-of-erlang.html) - The Joy of Erlang; Or, How To Ride A Toruk A fast track introduction to Erlang that teaches the language by walking through a few example projects.

## Screencasts

*Cool video tutorials.*

# Contributing

Please see [CONTRIBUTING](https://github.com/drobakowski/awesome-erlang/blob/master/CONTRIBUTING.md) ⭐ 1,708 | 🐛 23 | 📅 2022-11-17 for details.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-14._
