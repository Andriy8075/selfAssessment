## Node.js and backend

- Internals and concepts
  🎓 known Strong and weak sides of node.js
  - Stateful and stateless servers
  - Nonblocking I/O and slocking code
  - Event loop: phases
  - Event loop: microtasks and macrotasks
  - Garbage collection
  - Node.js LTS schedule
  - I/O-bound, CPU-bound, memory-bound tasks
  - Interactive applications (close to real-time)
- Modularity, layers and dependencies
  🖐 used CommonJS modules
  🖐 used ECMAScript modules
  🖐 used node:module
  - Caching in CJS and ESM
  - Modules as singletons
  - Contexts and scripts node:vm
    🖐 used Dependencies: npm, node_modules
  - Dependencies: package.json and package lock
  - Module-based permissions model
  - Isolation with modularity
  - Dependency injection
  - DI containers
    👂 heard Coupling and cohesion
  - Framework agnostic approach
- Environment
  🎓 known Command line arguments
  - Node.js CLI
  - Process-based permissions
  - Graceful shutdown
  - Clustering
    👂 heard Watch filesystem changes with --watch
- Internal API
  - Streams API
  - Web Streams API
  - Crypto API
  - Password hashing with node:crypto.scrypt
  - Web Crypto API
  - File system API: sync and async
  - Copy folder recursively
  - Worker threads
  - Performance hooks
    👂 heard Native fetch and nodejs/undici
  - node:async_hooks
  - AsyncLocalStorage
  - AsyncResource
  - Deprecated domain API
  - Node.js single executable
  - Stream back pressure
  - SharedArrayBuffer
  - node:worker_threads
  - node:child_process
  - MessageChannel, MessagePort
  - BroadcastChannel
  - Generating crypto random UUID
  - node:url vs new URL
  - node:assert
  - Internationalization
    🎓 known Blob, File, Buffer, node:buffer
  - Module node:zlib
- Application structure and architecture
  - Isolation between layer
    👂 heard Multilayer approach
  - Separation of concerns
  - Inversion of control
  - Dependency injection
  - GRASP
  - SOLID
  - GoF patterns
  - Distributed systems
  - Highload applications
  - Clean architecture
  - DDD
  - Message Queue
  - CQS
  - CQRS
  - Event sourcing
  - Load balancing
  - Serverless clouds
  - FaaS clouds
  - Fat controller
  - GoF for Node.js
  - Leaking abstractions
- Network
  - IP sticky sessions
  - Endpoint throttling
    🎓 known HTTP(S)
    🎓 known TCP/SSL
    🎓 known UDP
  - TLS
    🖐 used Websocket
  - SSE
  - HTTP/3 (QUIC)
  - Long polling
  - REST
  - RPC
  - Routing
  - DoS
    👂 heard DDoS
  - XSS
  - Path traversal
  - CSRF
  - DNS
  - Fetch API
  - IncomingMessage
  - SQL injection
  - noDelay
  - keep-alive
  - ALPN
  - SNI callback
  - SSL certificates
  - Protocol agnostic approach
- Technique and tools
  - Native test runner
  - Logging
  - Application configuring
    👂 heard Testing
  - CI/CD
  - Readable
  - Writable
  - Transform
  - back pressure
  - Buffer
  - Console
  - Inspector
  - Reliability
  - Quality
    Availability
  - Flexibility
- Data access
  - Data access layer
    👂 heard Repository
  - Active record
  - Query builder
  - Object-Relational Mapping
- Error handling and debugging
  🎓 known Error
  - error.cause
  - error.code
  - error.message
  - error.stack
  - How to avoid mixins
  - Error.captureStackTrace
    👂 heard Uncaught exceptions
  - Heap dump
  - Debugging tools
  - Flame graph
  - Memory leaks
  - Resource leaks
  - Data race
- Integrations and bindings
  - Native addons
  - C and C++ addons
  - Rust addons
  - Zig addons
  - NAN (Native Abstractions for Node.js)
  - Node-API (formerly N-API)
  - NAPI C and C++
  - NAPI Rust
  - NAPI Zig
  - Webassembly WAT
  - Webassembly C and C++
  - Webassembly Rust
  - Webassembly Zig
  - Webassembly AssemblyScript
  - Shared memory
  - SharedArrayBuffer
  - V8 binary serialization