# Junmin Gu

**Senior Frontend / Node.js Full-Stack / Platform Engineer**

📱 +86-159-0094-8714  
📧 gujunmin84@gmail.com  
🎓 B.S. in Information Security, Hunan University of Science and Technology (2018)  
💻 GitHub: https://github.com/SPxiaomin  

---

## Summary

Senior Frontend & Node.js Full-Stack Engineer with **7+ years of experience** building and owning  
**large-scale, high-concurrency platform systems from 0 to 1**.

Hands-on experience in **high-traffic event systems, lottery & reward distribution, customer service platforms**,  
with solid understanding of **Redis Cluster, Kafka / RocketMQ, database sharding, idempotency, and eventual consistency**.

Comfortable with React Wallet Integration / Smart Contract Interaction, using Indexers to make on-chain data queryable for a high-performance UI.

Proven **system owner** with experience leading **small teams (3–5 engineers)**, driving architecture decisions,  
and delivering stable, scalable systems in production.

---

## Technical Skills

- **Web3**: RainbowKit, Wagmi/Viem, The Graph, Solidity/Rust
- **Frontend**: React/Next.js, TypeScript, Umi, Qiankun, Micro-Frontend
- **Backend**: Node.js, NestJS, Golang (go-zero)
- **Middleware**: Redis Cluster, Kafka, RocketMQ
- **Databases**: MySQL (Sharding, Year-based Partitioning)
- **Engineering**: System Design, Performance Optimization, Reliability, Tech Leadership

---

## Professional Experience

### Hypergryph Network — Platform Engineering  
**Apr 2024 – Present**

#### Gift Package & Lottery Platform (System Owner)

- **Background**: Company-wide reusable platform decoupling business activities from reward distribution
- **Scale**:
  - Up to **1M users per activity**
  - **Tens of millions of lottery records**
  - Peak traffic: **130K QPS (draw)** / **500K QPS (info)**
- **Key Design**:
  - Redis Cluster (16 × 16GB), **1024 virtual shards per activity** to eliminate hot keys
  - Kafka for reliable message delivery; Redis ZSet for pending state tracking and idempotent retries
  - MySQL sharded by **year + 12 partitions** to control table size
- **Outcome**:
  - **10M Kafka messages processed and rewards issued within 10 minutes**
  - Significantly reduced onboarding and development cost for new activities

#### Direct Gift Distribution & CD-Key System

- Supported **~1M QPS pure read traffic** using multi-shard Redis duplication
- Implemented async retry mechanism via RocketMQ  
  (10 min / 6 h / 12 h / 24 h)
- CD-Key redemption built on **pure DB + year-based 20-shard design** for high throughput

#### Others

- official websites / h5 landing pages ...

---

### Lilith Games — Platform / Middleware Team  
**Mar 2021 – Jan 2024**

#### PSP Customer Service Platform (0-1, System Owner)

- Built a **company-wide customer service platform** serving multiple games and CS teams
- Adopted **micro-frontend architecture (Qiankun)** for independent development and deployment
- Designed **WebSocket + Protobuf** communication protocol  
  (auth, retry, exponential backoff, heartbeat)
- Performance optimization for large ticket datasets:  
  **page response improved from 30s+ to ~700ms**
- Acted as **tech lead for a 3–5 engineer team**, system ran stably for years in production

#### Content Management Platform & Low-Code Email Editor

- Designed and implemented a **low-code email editor from scratch**  
  (DSL, canvas interaction, property system)
- Solved multi-client rendering issues: dark mode, layout shift, performance bottlenecks
- Supported both **micro-frontend and iframe-based integrations**

#### Static Asset Service (Golang)

- Unified upload service for **Aliyun OSS / AWS / Google Cloud**
- Implemented layered security strategies: rate limiting, file size control, manual risk blocking

---

### ByteDance — Commercialization Engineering  
**Apr 2019 – Mar 2021**

#### Image Editing & Ad Creative Platform

- Contributed to the **image editing ecosystem** used by multiple ad business lines
- Extracted the editor canvas into a reusable **iframe-based component**
- Explored **Puppeteer-based image rendering** and UI automation testing

---

### Ele.me (Alibaba Group) — Frontend Engineer  
**Dec 2017 – Apr 2019**

- Developed **high-traffic consumer H5 pages** (daily DAU: millions to tens of millions)
- Built and maintained **B-side insurance & claims management systems**
- Strong focus on **performance optimization and stability** for large-scale traffic

---

## Strengths

- Strong experience in **high-concurrency, high-reliability platform systems**
- Frontend-rooted engineer with **solid backend & distributed systems mindset**
- Comfortable owning systems end-to-end: design, implementation, and long-term evolution
- Proven ability to lead small teams and collaborate across functions

---

## Open Source

- GitHub: https://github.com/SPxiaomin
