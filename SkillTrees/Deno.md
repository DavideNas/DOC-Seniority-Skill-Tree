## 🦕 Senior Deno Developer – Skill Stack (2025)

---

### ⚙️ 1. **Core Deno & Language Foundations**

| Area                     | Dettagli                                                      |
| ------------------------ | ------------------------------------------------------------- |
| Deno Runtime             | ✅✅✅ (v1.x, built‑in TypeScript support, single executable) |
| ES Modules & Import Maps | ✅✅✅ (`import` specifiers, import_map.json)                 |
| TypeScript               | ✅✅✅ (strict mode, path aliases, decorators)                |
| Standard Library         | ✅✅ (fs, http, encoding, streams)                            |
| Tooling                  | ✅✅✅ (`deno fmt`, `deno lint`, `deno info`, `deno bundle`)  |

---

### 🌐 2. **Web & API Frameworks**

| Framework / Lib | Dettagli                                 |
| --------------- | ---------------------------------------- |
| Oak             | ✅✅✅ (middleware, router, context)     |
| Fresh           | ✅✅ (full‑stack React SSR, zero config) |
| Drash           | ✅✅ (decorators, controllers, services) |
| Opine           | ✅ (Express‑style API)                   |
| GraphQL         | ✅✅ (deno_graphql, Oak integration)     |

---

### 🔌 3. **Module System & Permissions**

| Area              | Dettagli                                             |
| ----------------- | ---------------------------------------------------- |
| URL‑Based Imports | ✅✅✅ (CDN import, version pinning)                 |
| Permission Flags  | ✅✅✅ (`--allow-net`, `--allow-read`, `--unstable`) |
| Sandbox Strategy  | ✅✅ (restrict permissions per script)               |
| Import Caching    | ✅ (optimize cold starts)                            |

---

### 💾 4. **Database & Persistence**

| Driver / ORM        | Dettagli                                    |
| ------------------- | ------------------------------------------- |
| `deno-postgres`     | ✅✅✅ (PostgreSQL client, connection pool) |
| `deno-redis`        | ✅✅ (caching, pub/sub)                     |
| `deno-mongo`        | ✅ (MongoDB driver)                         |
| ORM / Query Builder | ✅ (DenoDB, Denodb)                         |
| Migrations          | ✅ (deno‑migrate, umzug‑deno)               |

---

### 🔄 5. **Microservices & RPC**

| Area                 | Dettagli                                           |
| -------------------- | -------------------------------------------------- |
| REST API             | ✅✅✅ (Oak or Opine handlers, OpenAPI generation) |
| gRPC                 | ✅✅ (deno_grpc, Prost integration)                |
| Pub/Sub / Eventing   | ✅✅ (Redis streams, NATS via deno_nats)           |
| Serverless Functions | ✅✅ (Deno Deploy, AWS Lambda via custom runtime)  |

---

### 🧪 6. **Testing & Quality**

| Area                 | Dettagli                                           |
| -------------------- | -------------------------------------------------- |
| Deno Test            | ✅✅✅ (`Deno.test`, assertions, snapshots)        |
| Mocking & Stubbing   | ✅✅ (Sinon-like with `mock` modules)              |
| Integration Testing  | ✅✅ (superoak for Oak, testcontainers via Docker) |
| Coverage             | ✅✅ (third‑party tools, `deno coverage`)          |
| Linting & Formatting | ✅✅✅ (`deno lint`, `deno fmt`)                   |

---

### 📈 7. **Performance & Observability**

| Area               | Dettagli                                  |
| ------------------ | ----------------------------------------- |
| Benchmarking       | ✅✅ (Benchmark API, `--inspect-brk`)     |
| Structured Logging | ✅✅ (pino‑deno, std log)                 |
| Metrics            | ✅ (Prometheus client libraries for Deno) |
| Health Checks      | ✅ (custom `/healthz` endpoints)          |

---

### 🐳 8. **DevOps & Deployment**

| Area            | Dettagli                                                           |
| --------------- | ------------------------------------------------------------------ |
| Docker          | ✅✅✅ (official `denoland/deno` image, multi‑stage builds)        |
| Kubernetes      | ✅✅ (Deployments, ConfigMaps, Secrets, Ingress for Deno services) |
| CI/CD           | ✅✅✅ (GitHub Actions with `deno task`, caching deps)             |
| Deno Deploy     | ✅✅ (edge hosting, zero config)                                   |
| Cloud Providers | ✅✅ (AWS Lambda custom runtime, GCP Cloud Run, Azure Functions)   |

---

### 🔐 9. **Security & Best Practices**

| Area                  | Dettagli                                                    |
| --------------------- | ----------------------------------------------------------- |
| Permission Model      | ✅✅✅ (least privilege, explicit flags)                    |
| OWASP Top 10          | ✅✅ (input validation, XSS, injection via Oak middlewares) |
| Dependency Security   | ✅✅ (audit third‑party modules, lock import_map)           |
| TLS / HTTPS           | ✅✅ (std tls, reverse proxy via NGINX)                     |
| Environment Variables | ✅✅ (secure loading, `dotenv` support)                     |

---

### 🤝 10. **Soft Skills & Leadership**

| Area          | Dettagli                                               |
| ------------- | ------------------------------------------------------ |
| Code Reviews  | ✅✅✅ (idiomatic Deno/TS patterns, permission checks) |
| System Design | ✅✅ (scalable microservices, event‑driven)            |
| Mentorship    | ✅✅ (pair programming, tech talks)                    |
| Documentation | ✅✅✅ (deno doc, Markdown README, ADRs)               |

---

## 🏁 Sei un **Senior Deno Developer** se:

✅ Hai creato e gestito **microservizi** con **Oak** o **Fresh**  
✅ Conosci a fondo il **modello a permessi** di Deno e lo applichi correttamente  
✅ Sai scrivere **TypeScript** idiomatico e sfruttare `deno fmt`/`lint`  
✅ Automatizzi build, test e deploy (Docker, GitHub Actions, Deno Deploy)  
✅ Applichi best practice di **security**, **observability** e **performance**

---

## 🎁 Starter Kit consigliato:

📦 **Deno Microservice Boilerplate**

- ⚙️ **Deno v1.x** con `import_map.json` e `tsconfig.json`
- 🌐 **Oak** + router + OpenAPI auto‑gen via `std/swagger`
- 💾 **PostgreSQL** via `deno-postgres` + migrations (deno‑migrate)
- 🔄 **gRPC** example con `deno_grpc`
- 🧪 **Deno.test** suite + coverage setup
- 🐳 **Dockerfile** multi‑stage (scratch image) + `docker-compose.yml`
- 🏗️ **Deno Deploy** config + GitHub Actions CI/CD
- 🔐 **Permission Flags** in scripts (`--allow-net`, `--allow-read`)
- 📄 **README** dettagliato + C4 diagram + ADR template

---

## 🦕 Risorse & Libri x studiare:

### _Gratis_

- **YouTube Videos**:

  1. [Deno Tutorial - Full Course 3.5 Hours (2020) – Bitfumes](https://www.youtube.com/watch?v=zU6-8w1IR-I) ▶️  
     Corso completo di 3,5 ore che copre le basi di Deno, incluso l'utilizzo di moduli e la creazione di API.

  2. [Deno For Beginners – Playlist](https://www.youtube.com/playlist?list=PLIZPrus9as4yfWrh1hqz_BBnKcXpbFIl4) ▶️  
     Serie di video introduttivi su Deno, ideali per chi parte da zero.

- **YouTube Channels**:

  1. [Fireship](https://www.youtube.com/@Fireship) 📺  
     Canale noto per tutorial rapidi e informativi su tecnologie moderne, inclusi video su Deno.

  2. [The Net Ninja](https://www.youtube.com/@NetNinja) 📺  
     Offre una varietà di corsi su sviluppo web, con contenuti anche su Deno.

- **Articoli**:

  1. [Deno Basics for Beginners – Daily.dev](https://daily.dev/blog/deno-basics-for-beginners) ✍️  
     Introduzione alle funzionalità chiave di Deno, con esempi pratici per iniziare.

  2. [The Deno Handbook – freeCodeCamp](https://www.freecodecamp.org/news/the-deno-handbook/) ✍️  
     Guida dettagliata che confronta Deno con Node.js e mostra come costruire una REST API.

- **Documentazione ufficiale / Guide utili**:

  - [Deno Documentation](https://docs.deno.com/) 📘  
    Documentazione ufficiale con guide, esempi e API reference.

  - [Deno Deploy Tutorials](https://docs.deno.com/deploy/tutorials/) 📘  
    Raccolta di tutorial per imparare a distribuire applicazioni con Deno Deploy.

- **Best Course**:  
  [Deno Beginner – Awais](https://denobeginner.com/) �  
  Corso gratuito composto da 14 video che insegnano Deno attraverso la costruzione di tre progetti seplici.

---

### _A Pagamento_

- **Libri**:

  - 📕 _Introducing Deno: A First Look at the Newest JavaScript Runtime_ – Fernando Doglio  
    Esplora le caratteristiche principali di Deno e come utilizzarlo per lo sviluppo moderno.

  - 📘 _Deno Web Development_ – Mike Chelen  
    Guida pratica per costruire applicazioni web utilizzando Deno e TypeScript.

- **Corsi Consigliati dalla Community**:

  1. **[Deno Full Course – Fireship.io](https://fireship.io/courses/deno/)**  
     Corso pratico per costruire un'app web completa con Deno, senza dipendenze di terze parti. 🌐

  2. **[Learn Deno – Zero to Mastery](https://zerotomastery.io/courses/learn-deno/)**  
     Corso che copre le basi di Deno fino alla costruzione di un sistema di lancio NASA simulato. 🌐

  3. **[Getting Started with Deno – Udemy](https://www.udemy.com/course/getting-started-with-deno-a-complete-guide-for-beginners/)**  
     Guida completa per principianti su come creare, testare e distribuire applicazioni con Deno. 🌐
