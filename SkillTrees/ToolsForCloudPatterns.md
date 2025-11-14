# ☁️ **Cloud Patterns – Skill Tree (Organizzato per Tool / Technology)**

### 🎯 *Roadmap strutturata per imparare pattern cloud moderni, raggruppati per tecnologia usata*

---

# 🔵 **1. API Gateway & Edge Patterns**

*Tool: API Gateway, Reverse Proxy, Load Balancer, WAF*
**Icona:** 🌐

| Pattern                           | Descrizione                                                |
| --------------------------------- | ---------------------------------------------------------- |
| **🌐 Gatekeeper**                 | Protezione, validazioni e controlli all’ingresso.          |
| **🔀 Gateway Routing**            | Smista traffico verso servizi in base a path, host, rules. |
| **🧩 Gateway Aggregation**        | Aggrega risposte da più servizi.                           |
| **⚙️ Gateway Offloading**         | Auth, throttling, caching, transformation sul gateway.     |
| **📱 Backend for Frontend (BFF)** | API layer dedicato a un singolo frontend.                  |
| **🌿 Strangler Fig**              | Migrazione progressiva tramite routing selettivo.          |
| **🚦 Throttling**                 | Limitazione del traffico per proteggere i backend.         |
| **🔑 Valet Key**                  | Accesso sicuro via presigned URL / SAS token.              |

---

# 🟢 **2. Function-as-a-Service (FaaS) & Serverless Patterns**

*Tool: AWS Lambda, GCP Cloud Functions, Azure Functions*
**Icona:** ⚡

| Pattern                  | Descrizione                                |
| ------------------------ | ------------------------------------------ |
| **⛓️ Function Chaining** | Esecuzione sequenziale di funzioni.        |
| **🕸️ Fan-Out / Fan-In** | Parallelismo massivo + raccolta risultati. |
| **📨 Async HTTP API**    | API asincrone con callback o eventi.       |
| **🙋 Human Interaction** | Step manuali nei workflow.                 |
| **🩺 Monitor Function**  | Funzioni schedulate di controllo/sonda.    |

---

# 🟣 **3. Message Broker & Event Bus Patterns**

*Tool: Kafka, RabbitMQ, ActiveMQ, IBM MQ, NATS, SQS, SNS, Pub/Sub, EventBridge, EventGrid*
**Icona:** 📨

### 📨 **Core Messaging Patterns**

| Pattern                          | Descrizione                                   |
| -------------------------------- | --------------------------------------------- |
| **📣 Publish / Subscribe**       | Decoupling tramite eventi broadcast.          |
| **📥 Queue-Based Load Leveling** | Smussamento di picchi tramite coda.           |
| **⭐ Priority Queue**             | Coda con priorità differenziate.              |
| **👥 Competing Consumers**       | Consumatori in parallelo per scalare.         |
| **🔄 Async Request-Reply**       | Comunicazione asincrona con correlation ID.   |
| **🗃️ Dead Letter Queue (DLQ)**  | Destinazione messaggi falliti.                |
| **🚚 Sequential Convoy**         | Elaborazione di messaggi correlati in ordine. |

### 🧩 **Event-Driven Architecture Patterns**

| Pattern                               | Descrizione                                  |
| ------------------------------------- | -------------------------------------------- |
| **📦 Event Carried State Transfer**   | Stato incluso negli eventi.                  |
| **📜 Event Sourcing**                 | Eventi immutabili come sorgente dello stato. |
| **🎭 Saga (Choreography)**            | Transazioni distribuite via eventi.          |
| **🧱 Saga (Transactional Outbox)**    | Integrazione sicura DB → broker.             |
| **📤 Outbox**                         | Scrittura atomica DB + evento.               |
| **↩️ Compensating Event Transaction** | Azioni di correzione tramite eventi.         |

---

# 🟠 **4. Workflow Engine & Orchestration Patterns**

*Tool: Step Functions, Temporal.io, Logic Apps, Durable Functions*
**Icona:** 🕹️

| Pattern                         | Descrizione                          |
| ------------------------------- | ------------------------------------ |
| **🕹️ Orchestration**           | Controllo centralizzato del flusso.  |
| **🎭 Saga (Orchestration)**     | Transazioni distribuite orchestrate. |
| **↩️ Compensating Transaction** | Azioni di annullamento.              |
| **🕸️ Fan-Out / Fan-In**        | Parallelismo orchestrato.            |
| **👁️ Monitor Workflow**        | Workflow di supervisione.            |
| **🙋 Human Interaction**        | Step manuali integrati.              |

---

# 🟡 **5. Background Worker / Compute Patterns**

*Tool: Worker Services, Cron, ECS, Kubernetes Jobs, Cloud Tasks*
**Icona:** 🏗️

| Pattern                               | Descrizione                                    |
| ------------------------------------- | ---------------------------------------------- |
| **🔁 Retry**                          | Ritentativi automatici.                        |
| **📈 Retry with Backoff**             | Backoff esponenziale o jitter.                 |
| **🧱 Bulkhead**                       | Isolamento risorse per evitare domino failure. |
| **⚡ Circuit Breaker**                 | Stop temporaneo verso servizi instabili.       |
| **📥 Queue-Based Worker Consumption** | Worker scalabili basati su coda.               |

---

# 🟤 **6. Service Mesh & Networking Patterns**

*Tool: Istio, Linkerd, Envoy*
**Icona:** 🕸️

| Pattern                            | Descrizione                                   |
| ---------------------------------- | --------------------------------------------- |
| **🛰️ Sidecar**                    | Container satellite per osservabilità/policy. |
| **🤝 Ambassador**                  | Proxy locale per chiamate esterne.            |
| **🔐 Service-to-Service TLS**      | Comunicazione mTLS end-to-end.                |
| **⏱️ Mesh Retry/Timeout Policies** | Resilienza configurata lato mesh.             |

---

# 🟧 **7. Storage, Cache & Data Access Patterns**

*Tool: Redis, DynamoDB, CosmosDB, RDS, BigTable, S3, Blob Storage*
**Icona:** 🗄️

| Pattern                      | Descrizione                                    |
| ---------------------------- | ---------------------------------------------- |
| **🧊 Cache-Aside**           | Cache caricata on-demand.                      |
| **🌍 Geode**                 | Cache distribuita su più region.               |
| **⚙️ External Config Store** | Configurazioni centralizzate esterne.          |
| **📦 Claim Check**           | Payload grande su storage + messaggio leggero. |
| **⚔️ CQRS**                  | Separazione tra write e read model.            |

---

# 🟩 **8. Identity, Security & Access Patterns**

*Tool: OAuth2, OIDC, Cognito, AD, STS*
**Icona:** 🔐

| Pattern                               | Descrizione                                  |
| ------------------------------------- | -------------------------------------------- |
| **🌍 Federation Identity**            | Trust tra provider diversi.                  |
| **🔑 Valet Key**                      | Accesso delegato temporaneo.                 |
| **🛡️ Gateway Offloading (Security)** | Auth e policy sul gateway.                   |
| **🌿 Strangler + Auth Migration**     | Migrazione graduale dei sistemi di identità. |

---

# ⚪ **9. Modernizzazione & Migration Patterns**

*Tool: API Gateway, Proxies, Blue/Green, Canary*
**Icona:** 🧬

| Pattern                             | Descrizione                                           |
| ----------------------------------- | ----------------------------------------------------- |
| **🌿 Strangler Fig**                | Migrazione progressiva di componenti legacy.          |
| **🛡️ Anti-Corruption Layer (ACL)** | Protezione del dominio applicativo da sistemi legacy. |
| **📦 Deployment Stamp**             | Ambienti clonati per tenant/region.                   |

---

# 🧭 **10. Roadmap Finale (Percorso Consigliato)**

**Icona:** 🗺️

1. 🌐 **API Gateway Patterns**
2. ⚡ **Serverless / FaaS**
3. 📨 **Message Brokers & Event Bus**
4. 🗄️ **Data & Storage Patterns**
5. 🕹️ **Workflow & Distributed Transactions**
6. 🕸️ **Service Mesh**
7. 🧬 **Modernizzazione (Strangler + ACL)**

---

# 📚 **11. Risorse, Libri & Corsi Consigliati**

*(Nuova sezione aggiuntiva basata sulla skill tree GitHub)*

---

# 🎓 **Corsi di Formazione (Cloud Patterns & EDA)**

## ☁️ **AWS**

* **Advanced Architecting on AWS**
  [https://aws.amazon.com/training/classroom/advanced-architecting-aws/](https://aws.amazon.com/training/classroom/advanced-architecting-aws/)

* **AWS Serverless Developer / Architect Learning Plan**
  [https://explore.skillbuilder.aws/learn/paths](https://explore.skillbuilder.aws/learn/paths)

* **AWS Event-Driven Architectures**
  [https://serverlessland.com/eda](https://serverlessland.com/eda)

* **AWS EDA Workshop**
  [https://catalog.workshops.aws/eda/en-US](https://catalog.workshops.aws/eda/en-US)

---

## ☁️ **Google Cloud**

* **Professional Cloud Architect Certification**
  [https://cloud.google.com/learn/certification/cloud-architect](https://cloud.google.com/learn/certification/cloud-architect)

* **Google Cloud Pub/Sub Deep Dive**
  [https://cloud.google.com/pubsub/docs](https://cloud.google.com/pubsub/docs)

* **Google Cloud Eventarc Training**
  [https://cloud.google.com/eventarc/docs](https://cloud.google.com/eventarc/docs)

---

## ☁️ **Microsoft Azure**

* **AZ-305 – Architecting Azure Infrastructure**
  [https://learn.microsoft.com/en-us/credentials/certifications/exams/az-305/](https://learn.microsoft.com/en-us/credentials/certifications/exams/az-305/)

* **Event-Driven Architectures on Azure**
  [https://learn.microsoft.com/en-us/azure/architecture/guide/](https://learn.microsoft.com/en-us/azure/architecture/guide/)

* **Azure Durable Functions Course**
  [https://learn.microsoft.com/en-us/azure/azure-functions/durable/durable-functions-overview](https://learn.microsoft.com/en-us/azure/azure-functions/durable/durable-functions-overview)

---

## 🕸️ **Kubernetes**

* **Kubernetes Patterns – Udemy**
  [https://www.udemy.com/course/kubernetes-patterns-and-advanced-deployment-techniques/](https://www.udemy.com/course/kubernetes-patterns-and-advanced-deployment-techniques/)

* **Google Kubernetes Engine (GKE) – Architect Track**
  [https://cloud.google.com/training/gke](https://cloud.google.com/training/gke)

* **Kubernetes Architecture & Patterns – CNCF**
  [https://www.cncf.io/training/](https://www.cncf.io/training/)

---

# 📘 **Libri Fondamentali (Cloud Pattern + Event-Driven)**

### 📗 *Cloud Native Patterns* – Cornelia Davis

[https://www.manning.com/books/cloud-native-patterns](https://www.manning.com/books/cloud-native-patterns)

### 📘 *Designing Event-Driven Systems* – Ben Stopford (Kafka)

[https://www.confluent.io/designing-event-driven-systems/](https://www.confluent.io/designing-event-driven-systems/)

### 📙 *Building Event-Driven Microservices* – Adam Bellemare

[https://www.oreilly.com/library/view/building-event-driven-microservices/](https://www.oreilly.com/library/view/building-event-driven-microservices/)

### 📕 *Software Architecture: The Hard Parts* – Richards & Ford

[https://www.oreilly.com/library/view/software-architecture-the/](https://www.oreilly.com/library/view/software-architecture-the/)

### 📗 *Designing Data-Intensive Applications* – Martin Kleppmann

[https://dataintensive.net/](https://dataintensive.net/)

### 📚 *Kubernetes Patterns* – Bilgin Ibryam (O’Reilly)

[https://www.oreilly.com/library/view/kubernetes-patterns/](https://www.oreilly.com/library/view/kubernetes-patterns/)

### 📘 *Microservices Patterns* – Chris Richardson

[https://microservices.io/book](https://microservices.io/book)

---

# 🌐 **Risorse Gratuite Ufficiali (Cloud Providers)**

## ☁️ AWS

* **AWS Well-Architected Framework**
  [https://docs.aws.amazon.com/wellarchitected/latest/framework/welcome.html](https://docs.aws.amazon.com/wellarchitected/latest/framework/welcome.html)

* **Serverless Land (pattern, esempi, EDA)**
  [https://serverlessland.com/](https://serverlessland.com/)

* **AWS Prescriptive Guidance**
  [https://docs.aws.amazon.com/prescriptive-guidance/](https://docs.aws.amazon.com/prescriptive-guidance/)

---

## ☁️ Google Cloud

* **Google Cloud Architecture Framework**
  [https://cloud.google.com/architecture/framework](https://cloud.google.com/architecture/framework)

* **Patterns for Event-Driven Architectures in GCP**
  [https://cloud.google.com/architecture](https://cloud.google.com/architecture)

---

## ☁️ Microsoft Azure

* **Azure Cloud Adoption Framework**
  [https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/)

* **Azure Architecture Center (pattern, EDA, integration)**
  [https://learn.microsoft.com/en-us/azure/architecture/](https://learn.microsoft.com/en-us/azure/architecture/)

---

# 📨 **Messaging & Event Bus – Risorse Specifiche**

## Apache Kafka

* **Kafka Patterns & Internals**
  [https://kafka.apache.org/documentation/](https://kafka.apache.org/documentation/)

* **Confluent Developer Learning Path**
  [https://developer.confluent.io/learn/](https://developer.confluent.io/learn/)

---

## RabbitMQ

* **RabbitMQ Tutorials (ufficiali)**
  [https://www.rabbitmq.com/getstarted.html](https://www.rabbitmq.com/getstarted.html)

* **RabbitMQ Patterns Guide**
  [https://www.rabbitmq.com/tutorials/](https://www.rabbitmq.com/tutorials/)

---

## EventBridge / EventGrid / Pub/Sub

* **AWS EventBridge Patterns Collection**
  [https://serverlessland.com/eventbridge/patterns](https://serverlessland.com/eventbridge/patterns)

* **Azure EventGrid Concepts & Patterns**
  [https://learn.microsoft.com/en-us/azure/event-grid/](https://learn.microsoft.com/en-us/azure/event-grid/)

* **GCP Pub/Sub Patterns**
  [https://cloud.google.com/pubsub/docs](https://cloud.google.com/pubsub/docs)

---

# 📺 **YouTube & Video Series**

### 🌐 *TechWorld with Nana*

Serverless, Kubernetes Patterns, EDA
[https://www.youtube.com/@TechWorldwithNana](https://www.youtube.com/@TechWorldwithNana)

### 📦 *Confluent Kafka Playlist*

[https://www.youtube.com/c/confluent](https://www.youtube.com/c/confluent)

### 🏗️ *Google Cloud – Architecture Framework*

[https://www.youtube.com/@googlecloudplatform](https://www.youtube.com/@googlecloudplatform)

### ☁️ *AWS Events / Serverless Bytes*

[https://www.youtube.com/@AWSEvents](https://www.youtube.com/@AWSEvents)

---

# 🧪 **Hands-on Labs e Progetti Guided**

* **AWS Workshops (Serverless, EDA, Patterns)**
  [https://workshops.aws](https://workshops.aws)

* **Google Cloud Skills Boost**
  [https://www.cloudskillsboost.google/](https://www.cloudskillsboost.google/)

* **Azure Hands-on Labs**
  [https://learn.microsoft.com/en-us/training/](https://learn.microsoft.com/en-us/training/)

* **Kubernetes Katacoda Scenarios**
  [https://www.katacoda.com/courses/kubernetes](https://www.katacoda.com/courses/kubernetes)
