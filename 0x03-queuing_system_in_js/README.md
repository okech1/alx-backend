# 0x03. Queuing System in JS

## Description
This project focuses on implementing a queuing system using JavaScript. You will learn about different queuing mechanisms, how to handle multiple tasks or requests in a queue, and how to manage and optimize these tasks using JavaScript concepts such as promises, callbacks, and event-driven programming.

## Learning Objectives
By the end of this project, you should be able to:
- Understand how queues work and how they can be applied in programming.
- Implement a queuing system to manage asynchronous operations.
- Use JavaScript promises, callbacks, and async/await to handle queued tasks.
- Optimize task execution using event-driven programming in JavaScript.

## Project Requirements
- All your files will be interpreted on Ubuntu 20.04 LTS using `node` (version 14.x)
- Your code should follow JavaScript best practices and style guidelines.
- Each task should be implemented in its own `.js` file.
- You should include a `package.json` file in your repository to manage dependencies.

## Tasks

### 0. Simple Queue
- Implement a simple queue structure using an array.
- Create enqueue and dequeue methods to add and remove elements from the queue.
  
### 1. Queue with Callbacks
- Modify the queue to handle tasks asynchronously using callbacks.
- Ensure that tasks are processed in the order they were added.

### 2. Queue with Promises
- Refactor the queuing system to use JavaScript promises instead of callbacks.
- Each task should return a promise that resolves when the task is completed.

### 3. Queue with Async/Await
- Refactor the queuing system to use `async` and `await` for handling tasks.
- The system should still process tasks in the order they were added, but should make it easier to handle errors and manage code flow.

### 4. Event-Driven Queue
- Implement an event-driven queue using Node.js event emitter.
- Trigger events when a task is added to or removed from the queue, or when the queue is empty.

### 5. Performance Optimization
- Improve the performance of the queuing system by introducing optimizations.
- Avoid blocking the event loop while tasks are being processed.

## Usage
To use this project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/0x03-queuing-system-js.git

