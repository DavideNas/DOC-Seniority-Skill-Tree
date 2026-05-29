## 🪵 NoSQL Mastery – Skill Tree (MongoDB, Redis, DynamoDB & Cloud DBs)

---

### 📚 1. **Fondamenti NoSQL & Modelli di Dato**

| Area                  | Dettagli                                                             |
| --------------------- | -------------------------------------------------------------------- |
| Tipi di NoSQL         | ✅✅✅ (Documentale, Key-Value, Wide-Column, Graph)                  |
| Denormalizzazione     | ✅✅✅ (modello "embed vs reference", data duplication consapevole)  |
| CAP Theorem           | ✅✅✅ (Consistenza, Disponibilità, Partizionamento)                 |
| Consistenza Eventuale | ✅✅ (vs strong consistency, gestire latenze in sistemi distribuiti) |
| Schema-Less Design    | ✅✅✅ (flex schema, versionamento dati, fallback fields)            |
| Use Case Mapping      | ✅✅✅ (quando usare NoSQL vs SQL)                                   |

---

### 🍃 2. **MongoDB – Document-Oriented**

| Area                   | Dettagli                                                         |
| ---------------------- | ---------------------------------------------------------------- |
| Query Language         | ✅✅✅ (`find()`, `aggregate()`, `$match`, `$group`, `$project`) |
| Indici                 | ✅✅✅ (compound, TTL, text search, partial, hashed)             |
| Aggregation Pipeline   | ✅✅✅ (multi-stage pipeline, `$lookup`, `$unwind`)              |
| Sharding & Replica Set | ✅✅ (shard key design, primary/secondary failover)              |
| Transactions ACID      | ✅✅ (multi-document ACID da MongoDB 4.0+)                       |
| Change Streams         | ✅✅ (streaming real-time updates via `watch()`)                 |
| Mongoose ODM (Node.js) | ✅✅✅ (schema, hooks, validators, virtuals, population)         |
| Atlas Cloud            | ✅✅✅ (progetti, cluster, triggers, backup automatizzati)       |

---

### 🧠 3. **Redis – In-Memory Key-Value Store**

| Area                    | Dettagli                                                                  |
| ----------------------- | ------------------------------------------------------------------------- |
| Tipi di Dato            | ✅✅✅ (`STRING`, `LIST`, `SET`, `ZSET`, `HASH`, `BITMAP`, `HYPERLOGLOG`) |
| TTL e Expiry            | ✅✅✅ (`EXPIRE`, `SETEX`, `PERSIST`)                                     |
| Pub/Sub                 | ✅✅ (event-driven architetture, canali, broker leggeri)                  |
| Streams                 | ✅✅ (simil Kafka, `XADD`, `XREADGROUP`)                                  |
| Persistence             | ✅✅ (`RDB`, `AOF`, `Hybrid persistence`, `SAVE`)                         |
| Redis Cluster           | ✅✅ (sharding automatico, hash slots, replica failover)                  |
| RedisJSON & RedisSearch | ✅✅ (query strutturate e indicizzazione su documenti JSON)               |
| Client Libraries        | ✅✅✅ (`ioredis`, `node-redis`, `lettuce`, `Jedis`)                      |

---

### ☁️ 4. **DynamoDB – Serverless Wide-Column AWS DB**

| Area                      | Dettagli                                                          |
| ------------------------- | ----------------------------------------------------------------- |
| Partizionamento           | ✅✅✅ (hash key + sort key, partition awareness)                 |
| Access Pattern Design     | ✅✅✅ (one table design, anticipo query prima di modellare dati) |
| Secondary Indexes         | ✅✅✅ (GSI, LSI – global vs local index, pro/contro)             |
| Capacity Mode             | ✅✅✅ (on-demand vs provisioned, autoscaling throughput)         |
| Query e Scan              | ✅✅✅ (`Query`, `Scan`, `BatchGet`, `TransactWriteItems`)        |
| TTL & Streams             | ✅✅ (time-to-live + integrazione con Lambda per reactive design) |
| PartiQL                   | ✅✅ (SQL-like per DynamoDB, compatibile con strumenti DevOps)    |
| Integr. con AWS Ecosystem | ✅✅✅ (IAM, Lambda, AppSync, EventBridge, Step Functions)        |

---

### 🔥 5. **Cloud-native NoSQL DB (multi-cloud)**

| Database      | Dettagli Chiave                                                                |
| ------------- | ------------------------------------------------------------------------------ |
| **Firestore** | ✅✅✅ (Realtime DB, ACID su doc, query avanzate, perfetto per mobile/Flutter) |
| **Cosmos DB** | ✅✅ (multi-model: SQL, Mongo, Cassandra API; latenza < 10ms garantita da SLA) |
| **Cassandra** | ✅✅ (wide-column, alta scalabilità, perfect write-heavy workloads)            |
| **Neptune**   | ✅ (Graph DB AWS, supporto Gremlin/SPARQL, per social graph e recommendation)  |
| **Couchbase** | ✅ (documentale distribuito, indexing + query SQL-like `N1QL`)                 |

---

### 🔒 6. **Sicurezza & Access Control**

| Area                  | Dettagli                                                                |
| --------------------- | ----------------------------------------------------------------------- |
| MongoDB Auth          | ✅✅✅ (`SCRAM`, IP Whitelist, RBAC, TLS, Field-Level Encryption)       |
| Redis Security        | ✅✅ (password, ACL per utenti, `renaming` comandi sensibili)           |
| DynamoDB IAM Policies | ✅✅✅ (fine-grain permission su risorse, integrazione con STS e Roles) |
| Audit & Logging       | ✅✅ (CloudWatch, Atlas logs, stream verso sistemi esterni)             |

---

### 📈 7. **Scalabilità & Performance**

| Area             | Dettagli                                                               |
| ---------------- | ---------------------------------------------------------------------- |
| MongoDB          | ✅✅✅ (replica set + sharding, query profilers, `explain()`, `$hint`) |
| Redis            | ✅✅✅ (eviction policy, memory tuning, Redis Cluster per scalabilità) |
| DynamoDB         | ✅✅✅ (scalabilità automatica + throttling, design key-aware)         |
| Firestore/Cosmos | ✅✅ (autoscale write ops/sec, cold start evitabile con caching)       |

---

## 🧪 Testing & Debugging Tools

| Tool                    | Dettagli                                          |
| ----------------------- | ------------------------------------------------- |
| **MongoDB Compass**     | GUI per query, aggregation builder, stats DB      |
| **RedisInsight**        | Tool visuale per performance, stream, chiavi      |
| **DynamoDB Local + UI** | Testing offline con AWS CLI e console browser     |
| **Postman / Insomnia**  | Ottimo per test API con backend NoSQL             |
| **Fake DB generators**  | ✅ (`faker`, `mockaroo`, `mongomock`, `dynalite`) |

---

## 🏁 Sei un **Senior NoSQL Developer** se:

✅ Hai **esperienza solida con almeno un DB NoSQL tra MongoDB, Redis, Cassandra o DynamoDB**  
✅ Sai **progettare modelli di dati denormalizzati e ottimizzati per la query**  
✅ Hai implementato **strategie di sharding, replica e resilienza**  
✅ Sai quando **_non_ usare un NoSQL** e proporre ibridi o fallback relazionali  
✅ Hai **monitorato performance, ottimizzato indici, TTL, e query complesse**  
✅ Hai gestito **migrazioni e versioning schema-less in ambienti production**

---

## 🎁 Starter Kit consigliato:

🧱 **Production-ready NoSQL Stack**

- 🛠️ **DB principali**:
  - **MongoDB**: document-store generalista
  - **Redis**: key-value super veloce, TTL & pub/sub
  - **Cassandra**: wide-column, per Big Data
  - **DynamoDB**: serverless, autoscalabile (AWS)
- 🔗 **ORM / ODM**:
  - MongoDB: Mongoose, Prisma (v4+)
  - DynamoDB: Dynamoose, AWS SDK V3
- 🔍 **Query e indicizzazione avanzata**
  - Mongo Aggregation Pipeline
  - Redis sorted sets, streams, pub/sub
  - TTL, compound indexes, geospatial queries
- 🧪 **Testing**: Testcontainers + mock/fake DB in RAM
- 📈 **Monitoring**:
  - MongoDB Atlas Dashboard
  - RedisInsight
  - Prometheus + Grafana integration

---

## 🎓 Risorse & Libri x studiare:

### _Gratuite_

#### 📺 YouTube Videos

1. [MongoDB Crash Course – Traversy Media](https://www.youtube.com/watch?v=-56x56UppqQ)
2. [Redis in 100 Seconds – Fireship](https://www.youtube.com/watch?v=Hbt56gFj998)
3. [DynamoDB Explained – Be A Better Dev](https://www.youtube.com/watch?v=vfJF2UNQ4XE)
4. [Cassandra for Beginners – Simplilearn](https://www.youtube.com/watch?v=IPdEsmHn2hc)
5. [Mongo Aggregation Explained – Web Dev Simplified](https://www.youtube.com/watch?v=yoeI-tb5Rs4)

#### 📘 Documentazione ufficiale

- [MongoDB Docs](https://www.mongodb.com/docs/)
- [Redis Docs](https://redis.io/docs/)
- [Apache Cassandra Docs](https://cassandra.apache.org/doc/latest/)
- [Amazon DynamoDB Docs](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/Introduction.html)

#### ✍️ Articoli & Guide

- [The Little MongoDB Book – Karl Seguin](https://openmymind.net/mongodb.pdf) _(free PDF)_
- [MongoDB University Courses (free)](https://university.mongodb.com/)
- [Redis in Action (sample chapters)](https://www.manning.com/books/redis-in-action)
- [When to use NoSQL vs SQL – DigitalOcean](https://www.digitalocean.com/community/tutorials/sql-vs-nosql)

---

### 💸 _A Pagamento_

#### 📕 Libri

- _MongoDB: The Definitive Guide_ – Kristina Chodorow
- _Mastering MongoDB_ – Alex Giamas
- _Redis Essentials_ – Maxwell Dayvson Da Silva
- _The Definitive Guide to Cassandra_ – Jeff Carpenter
- _DynamoDB Applied Design Patterns_ – Uchit Vyas
- _Designing Data-Intensive Applications_ – Martin Kleppmann (must-read 🔥)

#### 🎥 Corsi online

1. [**MongoDB – The Complete Developer’s Guide** – Udemy](https://www.udemy.com/course/mongodb-the-complete-developers-guide/)
2. [**NoSQL Databases – Coursera (University of Michigan)**](https://www.coursera.org/learn/nosql-databases)
3. [**Mastering DynamoDB** – Pluralsight](https://www.pluralsight.com/courses/mastering-dynamodb)
4. [**Redis University (Free but premium-level)**](https://university.redis.com/)
5. [**Cassandra Crash Course** – Educative.io](https://www.educative.io/courses/apache-cassandra-crash-course)
