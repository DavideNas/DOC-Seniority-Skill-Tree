## ☁️ **Cloud Patterns – Skill Tree (Organizzato per Tool / Technology)**

Una roadmap dei principali pattern cloud, organizzata per tecnologia, con tabelle uniformi e sezioni consolidate.

---

### 🔵 **1. API Gateway & Edge Patterns**

*Tool:* API Gateway, Reverse Proxy, Load Balancer, WAF
*Icona:* 🌐

| Pattern                           | Descrizione                                          |
| --------------------------------- | ---------------------------------------------------- |
| 🌐 **Gatekeeper**                 | Validazioni, controlli e protezione all’ingresso.    |
| 🔀 **Gateway Routing**            | Smistamento del traffico basato su path/host/regole. |
| 🧩 **Gateway Aggregation**        | Aggregazione di risposte da più servizi.             |
| ⚙️ **Gateway Offloading**         | Auth, throttling, caching, trasformazioni.           |
| 📱 **Backend for Frontend (BFF)** | API layer dedicato a uno specifico frontend.         |
| 🌿 **Strangler Fig**              | Migrazione progressiva tramite routing.              |
| 🚦 **Throttling**                 | Limitazione del traffico verso backend.              |
| 🔑 **Valet Key**                  | Accesso sicuro tramite presigned URL/SAS.            |

---

### ⚡ **2. Function-as-a-Service (FaaS) & Serverless Patterns**

*Tool:* Lambda, Cloud Functions, Azure Functions
*Icona:* ⚡

| Pattern                  | Descrizione                                         |
| ------------------------ | --------------------------------------------------- |
| ⛓️ **Function Chaining** | Invocazione sequenziale di funzioni.                |
| 🕸️ **Fan-Out / Fan-In** | Parallelizzazione massiva + aggregazione risultati. |
| 📨 **Async HTTP API**    | API asincrone basate su callback/eventi.            |
| 🙋 **Human Interaction** | Step umani nei workflow.                            |
| 🩺 **Monitor Function**  | Funzioni schedulate di controllo.                   |

---

## 📨 **3. Message Broker & Event Bus Patterns**

*Tool:* Kafka, RabbitMQ, ActiveMQ, NATS, SQS/SNS, Pub/Sub, EventBridge, EventGrid
*Icona:* 📨

#### **Core Messaging**

| Pattern                          | Descrizione                              |
| -------------------------------- | ---------------------------------------- |
| 📣 **Publish / Subscribe**       | Decoupling tramite eventi broadcast.     |
| 📥 **Queue-Based Load Leveling** | Smussamento picchi tramite coda.         |
| ⭐ **Priority Queue**             | Messaggi con priorità.                   |
| 👥 **Competing Consumers**       | Consumatori paralleli per scalare.       |
| 🔄 **Async Request-Reply**       | Comunicazione con correlation ID.        |
| 🗃️ **Dead Letter Queue**        | Messaggi falliti.                        |
| 🚚 **Sequential Convoy**         | Ordine garantito per messaggi correlati. |

#### **Event-Driven Architecture**

| Pattern                             | Descrizione                          |
| ----------------------------------- | ------------------------------------ |
| 📦 **Event Carried State Transfer** | Stato incluso negli eventi.          |
| 📜 **Event Sourcing**               | Stato derivato da eventi immutabili. |
| 🎭 **Saga (Choreography)**          | Transazioni distribuite via eventi.  |
| 🧱 **Transactional Outbox**         | Integrazione sicura DB → broker.     |
| 📤 **Outbox**                       | Scrittura atomica DB+evento.         |
| ↩️ **Compensating Event**           | Azioni correttive via eventi.        |

---

#### 🕹️ **4. Workflow Engine & Orchestration Patterns**

*Tool:* Step Functions, Temporal, Logic Apps, Durable Functions
*Icona:* 🕹️

| Pattern                         | Descrizione                          |
| ------------------------------- | ------------------------------------ |
| 🕹️ **Orchestration**           | Controllo centralizzato del flusso.  |
| 🎭 **Saga (Orchestration)**     | Transazioni distribuite orchestrate. |
| ↩️ **Compensating Transaction** | Undo delle operazioni.               |
| 🕸️ **Fan-Out / Fan-In**        | Parallelismo orchestrato.            |
| 👁️ **Monitor Workflow**        | Supervisione con workflow dedicato.  |
| 🙋 **Human Interaction**        | Step manuali.                        |

---

### 🏗️ **5. Background Worker / Compute Patterns**

*Tool:* Worker Services, Cron, ECS, K8s Jobs, Cloud Tasks
*Icona:* 🏗️

| Pattern                               | Descrizione                    |
| ------------------------------------- | ------------------------------ |
| 🔁 **Retry**                          | Ritentativi automatici.        |
| 📈 **Backoff**                        | Backoff esponenziale o jitter. |
| 🧱 **Bulkhead**                       | Isolamento risorse.            |
| ⚡ **Circuit Breaker**                 | Stop verso servizi instabili.  |
| 📥 **Queue-Based Worker Consumption** | Worker scalabili tramite code. |

---

### 🕸️ **6. Service Mesh & Networking Patterns**

*Tool:* Istio, Linkerd, Envoy
*Icona:* 🕸️

| Pattern                       | Descrizione                                     |
| ----------------------------- | ----------------------------------------------- |
| 🛰️ **Sidecar**               | Container satellite per policy e osservabilità. |
| 🤝 **Ambassador**             | Proxy per chiamate esterne.                     |
| 🔐 **Service-to-Service TLS** | mTLS end-to-end.                                |
| ⏱️ **Retry/Timeout Policies** | Resilienza lato mesh.                           |

---

### 🗄️ **7. Storage, Cache & Data Access Patterns**

*Tool:* Redis, DynamoDB, CosmosDB, RDS, BigTable, S3
*Icona:* 🗄️

| Pattern                      | Descrizione                             |
| ---------------------------- | --------------------------------------- |
| 🧊 **Cache-Aside**           | Cache on-demand.                        |
| 🌍 **Geode**                 | Cache distribuita multi-region.         |
| ⚙️ **External Config Store** | Config centralizzate.                   |
| 📦 **Claim Check**           | Payload su storage + messaggio leggero. |
| ⚔️ **CQRS**                  | Separazione read/write model.           |

---

### 🔐 **8. Identity, Security & Access Patterns**

*Tool:* OAuth2, OIDC, Cognito, AD, STS
*Icona:* 🔐

| Pattern                             | Descrizione                  |
| ----------------------------------- | ---------------------------- |
| 🌍 **Federation Identity**          | Trust tra identity provider. |
| 🔑 **Valet Key**                    | Accesso delegato temporaneo. |
| 🛡️ **Gateway Security Offloading** | Auth/Policy lato gateway.    |
| 🌿 **Strangler + Auth Migration**   | Modernizzazione identità.    |

---

### 🧬 **9. Modernizzazione & Migration Patterns**

*Tool:* Proxy, Blue/Green, Canary
*Icona:* 🧬

| Pattern                       | Descrizione                         |
| ----------------------------- | ----------------------------------- |
| 🌿 **Strangler Fig**          | Migrazione progressiva.             |
| 🛡️ **Anti-Corruption Layer** | Protezione dal legacy.              |
| 📦 **Deployment Stamp**       | Ambienti clonati per tenant/region. |

---

## 🗺️ **10. Roadmap Consigliata**

1. 🌐 API Gateway
2. ⚡ Serverless / FaaS
3. 📨 Event Bus & Messaging
4. 🗄️ Storage & Data
5. 🕹️ Workflow & Transazioni Distribuite
6. 🕸️ Service Mesh
7. 🧬 Modernizzazione (Strangler + ACL)

---

## 📚 **11. Risorse Essenziali (Cloud Patterns & EDA)**

---

### 🎓 **Corsi Online Core**

#### ☁️ **AWS**

* **AWS Serverless Developer / Architect Learning Plan**
  [https://explore.skillbuilder.aws/learn/paths](https://explore.skillbuilder.aws/learn/paths)
* **AWS Event-Driven Architectures Workshop**
  [https://serverlessland.com/eda](https://serverlessland.com/eda)

#### ☁️ **Google Cloud**

* **Professional Cloud Architect (Focus Event-Driven / Pub/Sub)**
  [https://cloud.google.com/learn/certification/cloud-architect](https://cloud.google.com/learn/certification/cloud-architect)
* **Google Cloud Pub/Sub Deep Dive**
  [https://cloud.google.com/pubsub/docs](https://cloud.google.com/pubsub/docs)

#### ☁️ **Microsoft Azure**

* **Azure Durable Functions Course**
  [https://learn.microsoft.com/en-us/azure/azure-functions/durable/durable-functions-overview](https://learn.microsoft.com/en-us/azure/azure-functions/durable/durable-functions-overview)

#### 🕸️ **Kubernetes**

* **Kubernetes Patterns – Udemy**
  [https://www.udemy.com/course/kubernetes-patterns-and-advanced-deployment-techniques/](https://www.udemy.com/course/kubernetes-patterns-and-advanced-deployment-techniques/)

---

### 📘 **Libri Fondamentali (Core Reading)**

* **Cloud Native Patterns** – Cornelia Davis
  [https://www.manning.com/books/cloud-native-patterns](https://www.manning.com/books/cloud-native-patterns)
* **Designing Event-Driven Systems** – Ben Stopford
  [https://www.confluent.io/designing-event-driven-systems/](https://www.confluent.io/designing-event-driven-systems/)
* **Designing Data-Intensive Applications** – Martin Kleppmann
  [https://dataintensive.net/](https://dataintensive.net/)

---

### 🌐 **Risorse Ufficiali & Documentazione**

* **AWS Serverless Land** – pattern ed esempi: [https://serverlessland.com/](https://serverlessland.com/)
* **GCP Architecture & Event-Driven Patterns**: [https://cloud.google.com/architecture](https://cloud.google.com/architecture)
* **Azure Architecture Center**: [https://learn.microsoft.com/en-us/azure/architecture/](https://learn.microsoft.com/en-us/azure/architecture/)

---

### 📨 **Messaging & Event Bus – Risorse Core**

* **Kafka – Confluent Developer Learning Path**: [https://developer.confluent.io/learn/](https://developer.confluent.io/learn/)
* **RabbitMQ Tutorials (ufficiali)**: [https://www.rabbitmq.com/getstarted.html](https://www.rabbitmq.com/getstarted.html)
* **AWS EventBridge Patterns**: [https://serverlessland.com/eventbridge/patterns](https://serverlessland.com/eventbridge/patterns)

---

### 🧪 **Hands-on Labs Essenziali**

* **AWS Workshops (Serverless / EDA)**: [https://workshops.aws](https://workshops.aws)
* **Google Cloud Skills Boost**: [https://www.cloudskillsboost.google/](https://www.cloudskillsboost.google/)
* **Azure Hands-on Labs**: [https://learn.microsoft.com/en-us/training/](https://learn.microsoft.com/en-us/training/)
