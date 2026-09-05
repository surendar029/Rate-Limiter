# RATE LIMITER SERVICE

## Description

A **high-performance, concurrency-safe Rate Limiter** implemented in Java 17 to control request throughput and prevent system overload under high traffic. The project provides multiple rate-limiting algorithms, including **Token Bucket, Leaky Bucket, Fixed Window, Sliding Window Log, and Sliding Window Counter**, enabling different traffic-control strategies based on application requirements.
The implementation focuses on **concurrency, algorithmic efficiency, and extensibility**, making it suitable for understanding how production-grade API throttling mechanisms can be designed and implemented.

## Key Features

* **Token Bucket** — Allows controlled bursts while maintaining an average request rate.
* **Leaky Bucket** — Smooths traffic by processing requests at a controlled rate.
* **Fixed Window** — Limits requests within predefined time intervals.
* **Sliding Window Log** — Tracks request timestamps for precise rate limiting.
* **Sliding Window Counter** — Provides an efficient approximation of sliding-window rate limiting.
* **Concurrency Support** — Designed to safely handle concurrent requests.
* **Algorithmic Flexibility** — Multiple strategies can be selected depending on traffic patterns and requirements.
* **Extensible Architecture** — Designed to support additional rate-limiting strategies.
* **Thread-Safe Data Handling** — Uses concurrent data structures for safe state management.
* **Design Pattern Driven** — Applies object-oriented design principles for maintainability and extensibility.

## Tech Stack

* **Language**: Java 17
* **Rate-Limiting Algorithms**: Token Bucket, Leaky Bucket, Fixed Window, Sliding Window Log, Sliding Window Counter
* **Concurrency**: ConcurrentHashMap, Thread-safe request handling
* **Core Concepts**: Concurrency, Algorithms, Time-based Request Throttling
* **Design**: Strategy-based extensible architecture, Object-Oriented Design
* **Data Structures**: ConcurrentHashMap, Queues / Timestamp-based tracking
