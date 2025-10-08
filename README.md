# Project Ideas

A curated list of challenging, systems-level project ideas I plan to build.

### 1. ORC Protocol Implementation

- **Status:** `Not Started`
- **Concept:** A lightweight server and client for the [ORC Protocol](https://github.com/RickCarlino/orc-protocol/tree/main)

### 2. Smart Cache API Gateway

- **Status:** `Not Started`
- **Concept:** A standalone, intelligent caching layer. It would act as a gateway that uses a declarative configuration (e.g., YAML) to define complex caching and invalidation rules based on API routes, request headers, and data dependencies.

### 3. WASM based serverless platform

- **Status:** `Not Started`
- **Concept:** A distributed, self-hosted serverless platform using WebAssembly for its core runtime.
- **Components:**
  - **Control Plane:** Manages function deployments and schedules invocations.
  - **Worker Nodes:** Execute functions in a secure, sandboxed WASM runtime.
  - **CLI Tool:** For deploying and managing functions.
- **Challenge:** Building a distributed system, leveraging WASM for fast/secure cold starts, and designing the custom protocols for node communication.

### 4. Animated fetch script

- **Status:** `Not Started`
- **Concept:** A terminal fetch script that displays some sort of animation, be it just a random moving thing, or like a
  game of snake.
- **Challenge:** Creating complex interaction with a terminal.
