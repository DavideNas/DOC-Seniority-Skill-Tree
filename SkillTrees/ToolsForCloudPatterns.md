# ☁️ **Cloud Patterns – Skill Tree (Organizzato per Tool / Technology)**

### 🎯 *Roadmap strutturata per imparare pattern cloud moderni, raggruppati per tecnologia usata*

---

# 🔵 **1. API Gateway & Edge Patterns**

> *Tool: API Gateway, Reverse Proxy, Load Balancer, WAF*

| Pattern                        | Descrizione                                                        |
| ------------------------------ | ------------------------------------------------------------------ |
| **Gatekeeper**                 | Protezione, validazioni e controlli all’ingresso (security edge).  |
| **Gateway Routing**            | Smista traffico verso servizi diversi in base a path, host, rules. |
| **Gateway Aggregation**        | Aggrega risposte da più servizi (Fan-Out / Fan-In).                |
| **Gateway Offloading**         | Sposta su gateway: auth, throttling, caching, transformation.      |
| **Backend for Frontend (BFF)** | API layer dedicato a un singolo frontend.                          |
| **Strangler Fig**              | Migrazione progressiva di un monolite tramite routing selettivo.   |
| **Throttling**                 | Limitazione adattiva del traffico per proteggere i backend.        |
| **Valet Key**                  | Accesso sicuro a risorse via pre-signed URL/SAS token.             |

---

# 🟢 **2. Function-as-a-Service (FaaS) & Serverless Patterns**

> *Tool: AWS Lambda, GCP Cloud Functions, Azure Functions*

| Pattern                           | Descrizione                                   |
| --------------------------------- | --------------------------------------------- |
| **Function Chaining**             | Catena di funzioni in esecuzione sequenziale. |
| **Fan-Out / Fan-In (Serverless)** | Parallelismo massivo con raccolta risultati.  |
| **Async HTTP API**                | API asincrone con callback/eventi.            |
| **Human Interaction**             | Workflow con approvazioni manuali.            |
| **Monitor**                       | Funzioni che verificano stato/processi.       |

---

# 🟣 **3. Message Broker & Event Bus Patterns**

> *Tool: SQS, SNS, Kafka, RabbitMQ, Pub/Sub, EventBridge, EventGrid*

### 📨 **Core Messaging Patterns**

| Pattern                       | Descrizione                                           |
| ----------------------------- | ----------------------------------------------------- |
| **Publish / Subscribe**       | Decoupling tramite eventi broadcast.                  |
| **Queue-Based Load Leveling** | Coda per smussare picchi di carico.                   |
| **Priority Queue**            | Elaborazione con priorità diversa.                    |
| **Competing Consumers**       | Consumatori paralleli per scalabilità.                |
| **Async Request-Reply**       | Correlation ID per risposte asincrone.                |
| **Dead Letter Queue (DLQ)**   | Messaggi falliti reindirizzati per analisi.           |
| **Sequential Convoy**         | Gestione di messaggi correlati in ordine sequenziale. |

### 🧩 **Event-Driven Architecture Patterns**

| Pattern                                 | Descrizione                                        |
| --------------------------------------- | -------------------------------------------------- |
| **Event Carried State Transfer (ECST)** | Stato propagato tramite eventi.                    |
| **Event Sourcing**                      | Persistenza dello stato tramite eventi immutabili. |
| **Saga (Choreography)**                 | Coreografia tramite eventi tra microservizi.       |
| **Saga (Transactional Outbox)**         | Integrazione sicura DB → broker.                   |
| **Outbox**                              | Scrittura atomica nel DB prima del publish.        |
| **Compensating (Event) Transaction**    | Azioni correttive a seguito di eventi falliti.     |

---

# 🟠 **4. Workflow Engine & Orchestration Patterns**

> *Tool: Step Functions, Logic Apps, Temporal.io, Durable Functions*

| Pattern                             | Descrizione                                          |
| ----------------------------------- | ---------------------------------------------------- |
| **Orchestration Pattern**           | Un orchestratore controlla il flusso delle attività. |
| **Saga (Orchestration)**            | Gestione transazioni distribuite con orchestration.  |
| **Compensating Transaction**        | Workflow di undo per step falliti.                   |
| **Fan-Out / Fan-In (Orchestrated)** | Esecuzione parallela controllata.                    |
| **Monitor Workflow**                | Supervisione periodica di processi.                  |
| **Human Interaction**               | Step con approvazione manuale integrata.             |

---

# 🟡 **5. Background Worker / Compute Patterns**

> *Tool: Worker Services, Cron, ECS, Kubernetes Jobs, Cloud Tasks*

| Pattern                            | Descrizione                                        |
| ---------------------------------- | -------------------------------------------------- |
| **Retry**                          | Tentativi ripetuti automatici.                     |
| **Retry with Backoff**             | Retry esponenziale / jitter.                       |
| **Bulkhead**                       | Isolamento risorse per evitare cascading failures. |
| **Circuit Breaker**                | Disattiva temporaneamente servizi instabili.       |
| **Queue-Based Worker Consumption** | Consumo scalabile da coda.                         |

---

# 🟤 **6. Service Mesh & Networking Patterns**

> *Tool: Istio, Linkerd, Envoy sidecar*

| Pattern                               | Descrizione                                                |
| ------------------------------------- | ---------------------------------------------------------- |
| **Sidecar**                           | Container satellite per osservabilità, networking, policy. |
| **Ambassador**                        | Proxy locale che media le chiamate verso esterno.          |
| **Service-to-Service TLS**            | Comunicazione protetta end-to-end.                         |
| **Retry/Timeout Policies Mesh-Based** | Gestione resilienza lato mesh.                             |

---

# 🟧 **7. Storage, Cache & Data Access Patterns**

> *Tool: Redis, DynamoDB, CosmosDB, RDS, BigTable, S3, Blob Storage*

| Pattern                          | Descrizione                                             |
| -------------------------------- | ------------------------------------------------------- |
| **Cache-Aside**                  | Carica dati in cache on-demand.                         |
| **Geode**                        | Cache distribuita geografica.                           |
| **External Configuration Store** | Configurazioni esterne e runtime.                       |
| **Claim Check**                  | Payload grande spostato su storage + messaggio leggero. |
| **CQRS**                         | Write model separato dal read model.                    |

---

# 🟩 **8. Identity, Security & Access Patterns**

> *Tool: OAuth2, OIDC, Cognito, Auth0, AD, STS*

| Pattern                           | Descrizione                                     |
| --------------------------------- | ----------------------------------------------- |
| **Federation Identity**           | Trust tra identity provider diversi.            |
| **Valet Key**                     | Accesso delegato tramite token temporaneo.      |
| **Gateway Offloading (Security)** | Autenticazione e autorizzazione esternalizzate. |
| **Strangler + Auth Migration**    | Migrazione identità graduale.                   |

---

# ⚪ **9. Modernizzazione & Migration Patterns**

> *Tool: API Gateway, Proxies, Blue/Green, Canary, Cloud Migration Tools*

| Pattern                         | Descrizione                                                                   |
| ------------------------------- | ----------------------------------------------------------------------------- |
| **Strangler Fig**               | Migrazione step-by-step di componenti legacy.                                 |
| **Anti-Corruption Layer (ACL)** | Adattatore per integrare sistemi legacy senza “contaminare” il nuovo dominio. |
| **Deployment Stamp**            | Ambienti clonati per tenant/region.                                           |

---

# 🧭 **10. Roadmap Finale (Percorso Consigliato)**

1. **Iniziare con API Gateway Patterns**
   → Gateway Routing, Aggregation, Offloading, Gatekeeper, BFF
2. **Aggiungere FaaS & Serverless Patterns**
   → Fan-Out/Fan-In, Function Chaining
3. **Passare ai Message Broker Patterns**
   → Pub/Sub → Queue Leveling → DLQ → Competing Consumers
4. **Approfondire Data & Storage Patterns**
   → Cache-Aside → CQRS → Claim Check
5. **Studiare Workflow Engine & Distributed Transactions**
   → Saga (Choreography/Orchestration)
6. **Avanzare verso Service Mesh Patterns**
   → Sidecar, Ambassador
7. **Chiudere con Modernizzazione e ACL/Strangler**
