# Real-Time-Geo-Spatial-Driver-Rider-Matching-Engine
  Technologies: Go (Goroutines), Redis, RESTful API, Docker, PostgreSQL (for initial data load).
Real-Time Geo-Spatial Driver-Rider Matching Engine (Backend System)
Developed a proof-of-concept for a low-latency service to match riders and drivers using Go (Golang) microservices.

Implemented a k-d tree spatial partitioning index to efficiently handle millions of concurrent geo-location updates, achieving an O(logn) nearest-neighbor search time complexity.

Utilized Redis Cache for storing driver availability and real-time location data, successfully simulating and handling 5,000 requests per second with average latency under 50ms.

Technologies: Go (Goroutines), Redis, RESTful API, Docker, PostgreSQL (for initial data load).
