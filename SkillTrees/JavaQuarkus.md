## 🧬 Senior Quarkus Developer – Skill Stack (2025)

---

### ☕ 1. **Core Java & Modern Java Features**

| Area                                  | Dettagli                                                          |
| ------------------------------------- | ----------------------------------------------------------------- |
| Java 17+ / GraalVM Ready              | ✅✅✅ (Records, Sealed Classes, Switch pattern, Virtual Threads) |
| OOP + Functional Programming          | ✅✅✅ (Streams, Lambdas, Immutabilità, Optional)                 |
| Project Lombok                        | ✅✅ (se usato, meglio se limitatamente)                          |
| CDI (Contexts & Dependency Injection) | ✅✅✅ (Quarkus usa CDI invece di Spring IoC)                     |

---

### 🧱 2. **Quarkus Core & Framework Ecosystem**

| Area                       | Dettagli                                                        |
| -------------------------- | --------------------------------------------------------------- |
| Quarkus Core               | ✅✅✅ (Hot reload, Dev UI, Live reload)                        |
| Dependency Injection (CDI) | ✅✅✅ (Bean lifecycle, Scopes, Producers, Qualifiers)          |
| RESTEasy Reactive          | ✅✅✅ (JAX-RS + Reactive extensions)                           |
| Panache ORM                | ✅✅✅ (Active Record & Repository pattern)                     |
| Hibernate Reactive / ORM   | ✅✅ (tradizionale o reactive in base al caso)                  |
| SmallRye APIs              | ✅✅✅ (JWT, Config, Health, Metrics, OpenAPI, Fault Tolerance) |

---

### 🧬 3. **Reactive, Eventing & Messaging**

| Area         | Dettagli                                                  |
| ------------ | --------------------------------------------------------- |
| Mutiny       | ✅✅✅ (API reattiva proprietaria, alternative a Reactor) |
| Kafka / AMQP | ✅✅✅ (Quarkus Kafka + SmallRye Messaging)               |
| Event-Driven | ✅✅✅ (channel-based + backpressure)                     |
| WebSockets   | ✅ (per comunicazioni bidirezionali real-time)            |

---

### 🔐 4. **Security & Identity**

| Area                      | Dettagli                                 |
| ------------------------- | ---------------------------------------- |
| JWT                       | ✅✅✅ (SmallRye JWT, roles & scopes)    |
| OAuth2 / OpenID Connect   | ✅✅✅ (Keycloak, Auth0, Google, etc.)   |
| RBAC / Annotations        | ✅✅ (SecurityIdentity, @RolesAllowed)   |
| TLS / mTLS / HTTPS config | ✅✅ (application.properties + keystore) |

---

### 🧰 5. **Persistence & Database Access**

| Area               | Dettagli                                     |
| ------------------ | -------------------------------------------- |
| Panache ORM        | ✅✅✅ (simplified entity layer)             |
| Panache Reactive   | ✅✅ (per Reactive PG/MySQL/Mongo)           |
| Flyway / Liquibase | ✅✅ (migrazioni DB supportate nativamente)  |
| MongoDB / Redis    | ✅✅ (Quarkus MongoDB client / Redis client) |

---

### ⚙️ 6. **DevOps, CI/CD & Observability**

| Area                      | Dettagli                                          |
| ------------------------- | ------------------------------------------------- |
| Docker & Jib              | ✅✅✅ (image native & JVM based)                 |
| Kubernetes / OpenShift    | ✅✅✅ (CRDs, Helm, Dev Services)                 |
| Quarkus Dev Services      | ✅✅✅ (DB/Redis/Kafka automatici via Docker)     |
| GraalVM Native Image      | ✅✅✅ (build native + footprint minimo)          |
| Metrics & Tracing         | ✅✅✅ (Micrometer, OpenTelemetry, Jaeger/Zipkin) |
| Health & Readiness Probes | ✅✅✅ (SmallRye Health)                          |

---

### 🧪 7. **Testing**

| Tipo                          | Dettagli                         |
| ----------------------------- | -------------------------------- |
| JUnit 5                       | ✅✅✅ (base di test)            |
| REST Assured                  | ✅✅ (test delle API REST)       |
| Testcontainers                | ✅✅ (DB, Kafka, Redis simulati) |
| MockK / Mockito               | ✅✅✅ (mocking service layer)   |
| QuarkusDevTest + @QuarkusTest | ✅✅✅ (test native Quarkus)     |

---

### 🧠 8. **Architecture & Design**

| Area                    | Dettagli                                              |
| ----------------------- | ----------------------------------------------------- |
| REST API Design         | ✅✅✅ (stateless, versioning, status codes)          |
| DDD                     | ✅✅ (Entity, Value Object, Aggregate)                |
| Microservices / Modular | ✅✅✅ (Quarkus è perfetto per architetture modulari) |
| Clean Code & SOLID      | ✅✅✅ (best practices di architettura e design)      |

---

### 🌩️ 9. **Cloud Native Skills**

| Area                      | Dettagli                                        |
| ------------------------- | ----------------------------------------------- |
| Quarkus on Kubernetes     | ✅✅✅ (dev mode, OpenShift, configmap/secrets) |
| Native Image in the Cloud | ✅✅ (image building, deploy rapido e leggero)  |
| Quarkus + AWS/GCP/Azure   | ✅ (S3, DynamoDB, PubSub, KeyVault, etc.)       |
| Serverless con Quarkus    | ✅✅ (AWS Lambda, Azure Functions)              |

---

## ✅ Sei un **Senior Quarkus Developer** se:

✅ Usi Quarkus in modalità **Dev + Prod** con efficacia  
✅ Hai esperienza su **native image**, **Reactive stack** e **messaging**  
✅ Sai realizzare microservizi resilienti con SmallRye + Panache  
✅ Conosci i dettagli di **CDI**, Mutiny, e Quarkus CLI  
✅ Sei in grado di fare **observability avanzata** e tuning in cloud

---

## 🎁 Starter Kit consigliato:

📦 **Quarkus Clean Microservice Template**

- ☕ Java 17 + Quarkus 3.x
- 🌐 REST API con RESTEasy Reactive
- 🧰 Panache ORM + PostgreSQL + Flyway
- 🧪 JUnit 5 + QuarkusTest
- 🔐 SmallRye JWT + OAuth2
- 📊 Micrometer + Prometheus
- 🐳 Dockerfile + DevServices
- 🌩️ Helm Chart ready per Kubernetes deploy

---

## 🎓 Risorse & Libri x studiare:

### _Gratuite_

- **YouTube Videos**:

  1. [Quarkus Framework Full Course – freeCodeCamp](https://www.youtube.com/watch?v=YoLfPbN6gTk) ▶️  
     Un corso che copre Quarkus e come sviluppare applicazioni ad alte prestazioni con Java, concentrandosi sulla creazione di microservizi.

  2. [Introduction to Quarkus – TechWorld with Nana](https://www.youtube.com/watch?v=r4f1_0KXmyM) ▶️  
     Un'introduzione a Quarkus, che spiega perché è una scelta eccellente per sviluppare applicazioni Java moderne.

- **YouTube Channels**:

  1. [Quarkus](https://www.youtube.com/c/Quarkusio) 📺  
     Il canale ufficiale di Quarkus, dove puoi trovare tutorial, demo e altre risorse ufficiali su come utilizzare Quarkus per lo sviluppo di microservizi e applicazioni cloud-native.

  2. [Java Brains](https://www.youtube.com/c/JavaBrains) 📺  
     Canale che offre tutorial dettagliati su Quarkus, con un focus sulle best practices nello sviluppo di applicazioni microservizi.

- **Articoli**:

  1. [Getting Started with Quarkus](https://quarkus.io/guides/getting-started) ✍️  
     Una guida ufficiale che ti introduce passo dopo passo nella creazione della tua prima applicazione Quarkus.

  2. [Quarkus: Java Microservices Made Easy](https://dzone.com/articles/quarkus-java-microservices-made-easy) ✍️  
     Un articolo che esplora come Quarkus semplifica lo sviluppo di microservizi e li rende più veloci ed efficienti rispetto ad altri framework Java.

- **Documentazione ufficiale / Guide utili**:

  - [Quarkus Official Documentation](https://quarkus.io/documentation/) 📘  
    La documentazione ufficiale di Quarkus, dove troverai tutte le informazioni necessarie per imparare a utilizzare il framework e le sue caratteristiche avanzate.

  - [Quarkus Guides](https://quarkus.io/guides/) 📘  
    Una raccolta di guide pratiche che ti aiuteranno a imparare Quarkus affrontando diversi scenari e casi d'uso.

- **Best Course**:  
  [Learn Quarkus - The Modern Java Framework](https://www.udemy.com/course/quarkus-the-modern-java-framework/) 🎥  
  Un corso completo che ti introduce nel mondo di Quarkus, esplorando i principi fondamentali e le applicazioni reali. 🌐

---

### _A Pagamento_

- **Libri**:

  - 📘 _Quarkus: A Practical Guide_ – Venkat Subramaniam  
    Una guida pratica che esplora come costruire applicazioni moderne e ad alte prestazioni utilizzando Quarkus.

  - 📕 _Kubernetes for Java Developers_ – Arun Gupta  
    Questo libro esplora Quarkus in combinazione con Kubernetes per costruire soluzioni Java cloud-native scalabili.

- **Corsi Consigliati dalla Community**:

  1. **[Quarkus: A Modern Java Framework – Pluralsight](https://www.pluralsight.com/courses/quarkus-modern-java-framework)**  
     Questo corso di Pluralsight è altamente raccomandato dalla community, in quanto offre una panoramica completa di Quarkus e delle sue caratteristiche principali. 🌐

  2. **[Mastering Quarkus Framework – Udemy](https://www.udemy.com/course/mastering-quarkus-framework/)**  
     Un altro corso su Udemy che viene frequentemente menzionato per approfondire le tecniche avanzate di Quarkus, inclusi la gestione di microservizi e l'integrazione con Kubernetes. 🌐

  3. **[Quarkus Microservices – Coursera](https://www.coursera.org/learn/quarkus-microservices)**  
     Questo corso su Coursera, raccomandato da molti professionisti del settore, ti insegnerà come costruire microservizi scalabili utilizzando Quarkus. 🌐
