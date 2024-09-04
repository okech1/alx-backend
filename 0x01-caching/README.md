0x01. Caching
What is a Caching System?
A caching system is a component that stores copies of data or computation results in a cache (a temporary storage area) so that future requests for that data can be served faster. Instead of retrieving data from its original, often slower, storage location every time it's needed, a cache allows the system to quickly access frequently used data. Caching is used to improve performance and efficiency in systems like databases, web applications, and computer processors.

What FIFO Means
FIFO stands for "First In, First Out." In the context of caching, this means that the first item added to the cache will be the first one removed when the cache reaches its limit. This method is straightforward but doesn't necessarily prioritize keeping the most useful data in the cache.

What LIFO Means
LIFO stands for "Last In, First Out." In caching, this means that the last item added to the cache will be the first one removed. This strategy is less common in caching systems, as it doesn't consider the frequency or recency of access when evicting items.

What LRU Means
LRU stands for "Least Recently Used." This caching strategy evicts the data that hasn't been accessed for the longest time when the cache is full. The idea is that data that hasn't been used recently is less likely to be needed in the near future, making it a good candidate for removal.

What MRU Means
MRU stands for "Most Recently Used." This is the opposite of LRU. In this strategy, the most recently accessed items are the first to be removed from the cache. MRU might be used in scenarios where older data is more likely to be reused than the most recent data.

What LFU Means
LFU stands for "Least Frequently Used." This strategy removes the data that has been accessed the least frequently when the cache is full. The rationale is that items that are not frequently accessed are less likely to be needed in the future.

The Purpose of a Caching System
The primary purpose of a caching system is to improve performance by reducing the time it takes to access data. By storing frequently accessed data in a fast-access memory (cache), the system can avoid slower operations, such as reading from disk or recalculating values. This leads to faster response times in applications and reduces the load on the underlying data storage or processing systems.

What Limits a Caching System
Caching systems have several limitations, including:

Limited Storage Capacity: Caches have finite storage, which means that not all data can be cached. Once the cache is full, some data must be evicted to make room for new data.

Cache Misses: When the data requested is not in the cache (a "cache miss"), the system must fetch it from the original storage, which can be slower.

Stale Data: Cached data can become outdated if the original data changes, leading to stale reads unless the cache is refreshed or invalidated properly.

Overhead: Maintaining a cache adds complexity to the system. The cache needs to be managed, updated, and occasionally cleared, which can introduce overhead.

Eviction Policy: The effectiveness of a caching system depends heavily on the eviction policy (e.g., FIFO, LRU, LFU). A poor choice of policy can lead to inefficiencies.

Coherency: In distributed systems, ensuring that all caches have consistent data can be challenging, leading to potential coherency issues.

Security: Caches can introduce security risks, such as the exposure of sensitive data if not managed properly.
