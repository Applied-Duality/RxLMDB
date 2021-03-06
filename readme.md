# RxLMDB
[![Build Status](https://travis-ci.org/deephacks/RxLMDB.svg?branch=master)](https://travis-ci.org/deephacks/RxLMDB)

RxLMDB provide a [RxJava](https://github.com/ReactiveX/RxJava) API to [LMDB](http://symas.com/mdb/) (through [lmdbjni](https://github.com/deephacks/lmdbjni)) which is an ultra-fast, ultra-compact key-value embedded data store developed by Symas for the OpenLDAP Project. LMDB uses memory-mapped files, so it has the read performance of a pure in-memory database while still offering the persistence of standard disk-based databases. Transactional with full ACID semantics and crash-proof by design. No corruption. No startup time. No dependencies.

Extending LMDB with RxJava makes it possible for asynchronous and event-based programs to process data from LMDB as sequences and adds operators that allow you to compose sequences together declaratively while abstracting away concerns about things like low-level threading, synchronization, thread-safety and concurrent data structures.
