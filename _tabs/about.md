---
# the default layout is 'page'
icon: fas fa-info-circle
order: 4
---

title: About me
layout: page
permalink: /about/
---

# Hey, 👋

I'm a software engineer passionate about **high-performance systems**, **Rust**, low-level programming, and making software fast, safe, and reliable.

I live in Québec, Canada — currently writing code, reading way too many RFCs, benchmarking things that probably don't need benchmarking, and occasionally yelling at the compiler (lovingly).

## What I usually work on

- Rust — performance, async, zero-copy patterns, serialization, embedded-ish things
- Binary protocols & formats (bincode, postcard, cap'n proto, custom wire formats…)
- Systems programming, networking, databases internals
- Making slow things fast (and fast things stupidly fast)
- Occasionally: Go, C++, Zig, TypeScript (when I have to)

## What you'll find here

This blog is mostly about:

- Deep dives into Rust crates & patterns
- Performance optimization stories (with actual numbers)
- Serialization, encoding, zero-copy techniques
- Lessons learned from real production systems
- Random thoughts on software design, tools, and developer experience

I try to write the kind of articles I wish I had found when I was trying to understand borrow checker fights, cache-line contention, or why my protobuf messages suddenly became 3× bigger.

## Tech stack I enjoy in 2026

- Language: **Rust** (obviously), sometimes Zig or C for very specific reasons
- Async runtime: **tokio** (mostly), smol occasionally
- Serialization: bincode-next, postcard, rkyv, abomonation (when I'm feeling dangerous)
- Storage / databases: sled, rocksdb, sqlite (with love), sometimes custom on-disk formats
- Monitoring: prometheus + grafana, or just `tracing` + `console-subscriber`
- Editor: Neovim + rust-analyzer + too many plugins

## Say hi!

If you have questions about something I wrote, found a typo, want to argue about varint vs fixed encoding, or just want to chat about Rust — feel free to open an issue, send a PR, or reach out on 

Looking forward to geeking out with you.

— Owen  
Québec, February 2026
