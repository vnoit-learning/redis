# Redis

## Why Redis

Redis is blazingly fast it's written in C, runs entirely in memory and is optimized to deliver millions of operations with sub millisecond latency with single standard server.

Pre-built data structures for popular use cases which are used by developer like LEGO building blocks when creating new apps.

These built-in data structures include lists, sets, sorted sets, hashes, hyperloglogs, bitmaps, geospatial indexes, bitfields, streams and strings.

Redis commends allow data to be processed on the database level rather then the application level, reducing coding effort, code complexity and bandwidth requirements.

Redis can be extend infinitely.

With Redis Modules that expand Redis infinitely, and it allows to add custom functionality and structures.

And Modules that do everything from search to machine learning, security, JSON to graph data processing and more.

Has client libraries for every languages.

The hottest Redis uses includes real time analytics, High speed transactions, High speed data ingest, Message queues, Session storage, In-app social functionality, Application job management, Search, Machine learning and caching.

Redis has been benchmarked as the world's fastest data base.

## What is Redis

Redis is an open source, in-memory data structure store used as database, cache and message broker

NoSQL Key/Value Store with some advance features.

The different between MongoDB and Redis is Mongo DB is a disk based document store while Redis is a memory based.

Redis does not support any built-in data encryption

## Data types

1. Lists
2. Sets
3. Sorted sets
4. Hashes
5. Hyperlogs
6. Bitmaps
7. Geospatial indexes
8. Bitfields
9. Streams
10. Strings

## Installing Redis

Check the internet!

Basic commends to install redis.

```bash
$ sudo apt-get update
$ sudo apt-get upgrade
$ sudo apt-get install redis-server
$ cd /etc/redis/redis.config
$ sudo cp redis.config redis.config.default
$ redis-server
```

## Redis CLI

```bash
$ redis-cli
$ ping
```
