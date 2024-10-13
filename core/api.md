# Node.js Core — **API**

## Overview
The Node.js API includes a wide range of built-in modules that provide tools for working with networking, file systems, streams, and the event-driven model. Understanding these modules is crucial for building efficient Node.js applications. The deeper the knowledge of the API, the more optimized and scalable solutions a developer can create.

---

### 🌱 Novice
At the novice level, the developer is familiar with fundamental modules that are commonly used for basic tasks. Knowledge focuses on fundamental operations without in-depth understanding of the underlying mechanisms.

- **http**: Ability to create a simple HTTP server, understand basic request methods (GET, POST), and handle routing.
- **fs**: Ability to perform basic file system operations: reading, writing, and creating files. Understanding synchronous vs. asynchronous file operations (e.g., fs.readFile).
- **path**: Using the module to work with file system paths (e.g., creating absolute and relative paths).
console: Basic logging and debugging using the built-in console module.
- **util**: Basic usage, such as `util.format` for string formatting. Utilized mainly for basic logging.

#### Skills:
Understanding of the event-driven model in Node.js and basic usage of asynchronous functions with callbacks.
Ability to build simple APIs by interacting with the http and fs modules to process requests and handle data.

---

### 🌿 Intermediate:
At this level, the developer expands their knowledge and learns to handle more complex modules and approaches. The focus is on improving the management of asynchronous code and understanding the mechanisms behind the event-driven model.

- **Promise** and **async/await**: Applying modern syntax for managing asynchronous code, understanding promises, and avoiding "callback hell."
- **events**: Ability to create and manage custom events, which is essential for building complex systems using the event-driven model.
- **crypto**: Working with basic cryptographic operations (e.g., password hashing, data encryption) using built-in algorithms (crypto.createHash()).
- **stream**: Understanding streams and working with streaming data, for example, processing large files or data streams.
- **net**: Basics of working with network connections (e.g., setting up simple TCP servers).
- **os**: Retrieving system information (e.g., platform, system resources).
- **util**: More advanced usage, such as `util.promisify` for turning callback functions into promises.

#### Skills:
Building more complex network applications with event-driven architecture.
Experience working with asynchronous data streams.
Basic understanding of encryption and security at the Node.js level.

---

### 🌳 Advanced:
At this level, the developer understands the internal workings of Node.js and effectively uses built-in modules to optimize application performance.

- **http2**: Ability to work with the `HTTP/2` protocol, offering better performance characteristics compared to `HTTP/1.1`.
- **worker_threads**: Understanding how to handle multithreaded applications in Node.js and parallelize tasks for increased performance.
- **stream**: Deep understanding of streams, including creating custom transforming streams and managing complex streaming operations.
- **cluster**: Using the cluster module to scale applications by distributing load across multiple processes.
- **util**: Advanced usage, such as `util.inspect()` for deep object inspection and logging configuration.
- **net** and **dgram**: Optimizing network connections, including working with low-level `TCP` and `UDP` protocols.

#### Skills:
Application optimization through load distribution across CPU cores and multithreading.
Building high-performance servers using HTTP/2 and clustering.
Profiling and deep debugging of applications using built-in tools.

---

### 🚀 Expert:
An expert has a deep understanding of the internal architecture of Node.js and can write and optimize code for maximum performance and scalability.

- **worker_threads** and **cluster**: Maximizing efficiency in parallelizing tasks and distributing requests across multiple processes.
- **C++ modules**: Using native modules to extend Node.js functionality or improve performance.
- **tls** and **https**: Creating secure servers and managing certificates for encrypted connections.
- **perf_hooks**: Using built-in tools to profile application performance and optimize the Event Loop.

#### Skills:
In-depth knowledge of the Event Loop and its impact on application performance.
Ability to build complex network applications using low-level protocols.
Applying optimizations at the native code level and memory management.
