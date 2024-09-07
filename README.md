# Awesome PostgreSQL Hacking [![awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="https://wiki.postgresql.org/images/a/a4/PostgreSQL_logo.3colors.svg" align="right"  width="100">](https://www.postgresql.org/)

> A curated list of awesome PostgreSQL hacking resources, inspired by [awesome-postgres](https://github.com/dhamaniasad/awesome-postgres)

 :elephant: Contributions welcome. Add links through [pull requests](https://github.com/pghacking/awesome/pulls) or create an [issue](https://github.com/pghacking/awesome/issues) to start a discussion.

## Contents

- [Core Hacking](#core-hacking)
    - [Books](#books)
    - [Community](#community)
    - [Contributing](#contributing)
    - [General](#general)
    - [Mailing Lists](#mailing-lists)
    - [Parser](#parser)
    - [Planner](#planner)
    - [Executor](#executor)
    - [Storage](#storage)
    - [Performance Analysis](#performance-analysis)
    - [Tools](#tools)
- [Extension Hacking](#extension-hacking)

## Core Hacking

### Books

* [The Internals of PostgreSQL](https://www.interdb.jp/pg/index.html) - Hironobu SUZUKI - The main purposes of this document are to explain how each subsystem works, and to provide the whole picture of PostgreSQL.
* [PostgreSQL 14 Internals](https://edu.postgrespro.com/postgresql_internals-14_en.pdf) - Egor Rogov - This book is for those who will not settle for a black-box approach when working with a database.

### Community

* [PostgreSQL Hacker Mentoring](https://discord.gg/bx2G9KWyrY)
* [People, Postgres, Data](https://discord.com/invite/bW2hsax8We)
* [PostgreSQL Slack workspace](https://pgtreats.info/slack-invite)

### Contributing

* [So, you want to be a developer?](https://wiki.postgresql.org/wiki/So,_you_want_to_be_a_developer%3F)
* [Submitting a Patch](https://wiki.postgresql.org/wiki/Submitting_a_Patch)
* [Walk-through of implementing simple Postgres patch. From sources to CI.](https://www.youtube.com/watch?v=rihfAnd_leM) 📹 - Andrey Borodin
* [PGConf.EU 2023, Making your patch more committable](https://www.youtube.com/watch?v=oXJbFy0JJkI) 📹 - Melanie Plageman
* [PGConf.EU 2023, PostgreSQL Hacker Tips](https://www.youtube.com/watch?v=hIBwLGLsqKI) 📹 - Michael Paquier

### General

* [A Tour of PostgreSQL Internals](https://www.postgresql.org/files/developer/tour.pdf) - Tom Lane, 2000
* [PostgreSQL Backend Flowchart](https://www.postgresql.org/developer/backend/)
* [A Comprehensive Overview of PostgreSQL Query Processing Stages](https://www.highgo.ca/2024/01/26/a-comprehensive-overview-of-postgresql-query-processing-stages/) - Cary Huang
* [Hooks in PostgreSQL](https://wiki.postgresql.org/images/e/e3/Hooks_in_postgresql.pdf) - Guillaume Lelarge
* [Unofficial documentation for PostgreSQL hooks](https://github.com/taminomara/psql-hooks) - Tamika Nomara

### [Mailing Lists](https://www.postgresql.org/list/)

* [pgsql-hackers](https://www.postgresql.org/list/pgsql-hackers/) - The PostgreSQL developers team lives here. Discussion of current development issues, problems and bugs, and proposed new features. If your question cannot be answered by people in the other lists, and it is likely that only a developer will know the answer, you may re-post your question in this list. You must try elsewhere first!
* [pgsql-committers](https://www.postgresql.org/list/pgsql-committers/) - Notification of git commits are sent to this list. Do not post here!
* [pgsql-bugs](https://www.postgresql.org/list/pgsql-bugs/) - If you find a bug, please use the [bug reporting form](http://www.postgresql.org/support/submitbug).
* [Posting Your Patch On pgsql-hackers](https://rhaas.blogspot.com/2024/08/posting-your-patch-on-pgsql-hackers.html) - Robert Haas
* [Will Postgres development rely on mailing lists forever?](https://vondra.me/posts/will-postgres-rely-on-mailing-lists-forever/) - Tomas Vondra
* [Understanding the Postgres Hackers Mailing List Language](https://www.crunchydata.com/blog/understanding-the-postgres-hackers-mailing-list) - Greg Sabino Mullane
* Tip: you get moderated if you post to more than one mailing list on the same message.

### Parser

### Planner

* [Recent PostgreSQL Optimizer Improvements](https://www.postgresql.org/files/developer/optimizer.pdf) - Tom Lane, 2003
* [Inside the PostgreSQL Query Optimizer](https://www.neilconway.org/talks/optimizer/optimizer.pdf) - Neil Conway, 2005
* [Understand PostgreSQL’s Planner – Simple Scan Paths vs Plans](https://www.highgo.ca/2024/03/22/understand-postgresqls-planner-simple-scan-paths-vs-plans/) - Cary Huang
* [CMU Database Group, PostgreSQL Optimizer Methodology](https://www.youtube.com/watch?v=XA3SBgcZwtE) 📹 - Robert Haas
* [PGCon 2019, Learning to Hack on Postgres Planner](https://www.youtube.com/watch?v=j7UPVU5UCV4) 📹 - Melanie Plageman

### Executor

* [Query Evaluation Techniques in PostgreSQL](https://www.neilconway.org/talks/executor.pdf) - Neil Conway, 2007

### Storage

* [PGCon 2022, Breaking away from FREEZE and Wraparound](https://www.youtube.com/watch?v=4tfyT9Putzo) 📹 - Masahiko Sawada
* [PGConf.dev 2024, Problem in PostgreSQL SLRU - And how we are optimizing it](https://www.youtube.com/watch?v=74xAqgS2thY) 📹 - Dilip Kumar

### Performance Analysis

* [Dynamic Tracing](https://www.postgresql.org/docs/current/dynamic-trace.html)
* [Citus Con 2022, Analyzing Postgres performance problems using perf and eBPF](https://www.youtube.com/watch?v=HghP4D72Noc) 📹 - Andres Freund - [slides](https://anarazel.de/talks/2022-04-12-cituscon/perf-bpf.pdf)

### Tools

* [pg_plugins](https://github.com/michaelpq/pg_plugins) - Michael Paquier - Gathering of template plugins for PostgreSQL: background workers, logical replication things, etc.
* [.devcontainer](https://github.com/pghacking/.devcontainer) - Junwang Zhao - Unofficial devcontainer config for Postgres

## Extension Hacking

* [pgrx](https://github.com/pgcentralfoundation/pgrx) - Build Postgres Extensions with Rust!
* [pgzx](https://github.com/xataio/pgzx) - Create PostgreSQL extensions using Zig.
* [PGCon 2023, Writing a Foreign Data Wrapper](https://www.youtube.com/watch?v=7wuDJxpU7Fo) 📹 - Christophe Pettus
