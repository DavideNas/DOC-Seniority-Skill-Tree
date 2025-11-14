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
