---
layout: page
title: Storage
permalink: /learn/storage
---

Software frequently needs to store data out of the process on disk. Plain CSV
and JSON files work well for this at a very small scale (like a command-line
app), but larger programs, web servers, any software that has multiple users,
etc., will usually use a database.

There are several different types of databases: relational, key-value, graph,
NoSQL, and more. We're not going to go into detail on the tradeoffs between
types of database systems here, but the Wikipedia articles on each are good
introductions.

The most commonly used type of database system is a relational DB, such as
PostgreSQL, MySQL, or SQL Server, or the embedded SQLite used in mobile apps
and desktop software. The language family used to interact with relational
databases is called SQL (Structured Query Language, pronounced "sequel"
or "ess-queue-ell").

## How to Learn

* [SQLBolt](https://sqlbolt.com/) teaches you SQL in the browser.
* [PostgreSQL Tutorial](https://www.postgresqltutorial.com/) will teach you
    more advanced Postgres-specific operations, as well as how to install
    and configure the software.
* [MongoDB University](https://university.mongodb.com/) (requires signup)
    teaches Mongo, a document-based NoSQL datastore popular for demo apps,
    startups, and projects that don't have highly relational data.
