# Event Booking

A highly scalable event booking platform built with a modern microservices architecture to handle high traffic and guarantee zero overselling.

## Key Features

- **Microservices Architecture:** Independently deployed Go microservices for users, events, search, and booking logic.
- **High Availability:** Deployed to an AWS EKS cluster spanning multiple availability zones for fault tolerance.
- **Concurrency Control:** Employs optimistic locking on ticket checkouts. This eliminates race conditions and guarantees zero overselling during severe traffic spikes.
- **High-Performance Search:** Offloads search traffic to Elasticsearch, significantly speeding up event discovery and reducing database load.
- **Modern Frontend:** Fast, responsive UI built with React.

## Tech Stack

- **Backend:** Go (Golang)
- **Frontend:** React
- **Databases:** PostgreSQL (Relational Data), Redis (Caching), Elasticsearch (Search Engine)
- **Infrastructure:** AWS EKS (Kubernetes), Docker

---
*Engineered to provide a seamless booking experience under massive scale.*
