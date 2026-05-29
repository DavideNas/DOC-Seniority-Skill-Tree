## 🐘 PHP Developer – Skill Tree (Legacy + Modern PHP, 2025)

---

### 🔰 1. **Fondamenta PHP (Legacy PHP 5–7)**

| Area                   | Dettagli                                                        |
| ---------------------- | --------------------------------------------------------------- |
| Sintassi Base          | ✅✅✅ (variabili, tipi base, operatori, array, loop, funzioni) |
| OOP Legacy             | ✅✅✅ (classi, ereditarietà, `__construct`, `public/private`)  |
| PDO                    | ✅✅✅ (connessione sicura al DB con prepared statements)       |
| Sessions & Cookies     | ✅✅✅ (gestione stato utente e login base)                     |
| Include/Require        | ✅✅ (inclusione moduli, approccio modulare pre-framework)      |
| Globali & Superglobali | ✅✅✅ (`$_GET`, `$_POST`, `$_SESSION`, `$_SERVER`, ecc.)       |

---

### 🚀 2. **Modern PHP (PHP 8.0 → 8.3)**

| Area                       | Dettagli                                                  |
| -------------------------- | --------------------------------------------------------- | ---------------------- | --- |
| Type Declarations          | ✅✅✅ (tipi per argomenti, ritorni, proprietà)           |
| Union Types / Mixed        | ✅✅ (`int                                                | float`, `mixed`, `null | T`) |
| Named Arguments            | ✅✅ (`foo(x: 10, y: 20)`)                                |
| Match Expression (8.0)     | ✅✅ (switch moderno)                                     |
| Attributes / Annotations   | ✅✅✅ (`#[Route("/home")]`) – simili ai decoratori       |
| Constructor Property Promo | ✅✅ (`public function __construct(public string $name)`) |
| Nullsafe Operator (`?->`)  | ✅✅✅ (`$user?->profile?->email`)                        |
| Readonly & Final Classes   | ✅✅✅ (`readonly`, `final`)                              |
| Fibers (8.1)               | ✅ (`Fiber` → primitive per async I/O)                    |
| Deprecation Handling       | ✅✅ (handling dei warning e fallback strategy)           |

---

### 🌐 3. **Web Dev + API**

| Area                         | Dettagli                                                          |
| ---------------------------- | ----------------------------------------------------------------- |
| RESTful API                  | ✅✅✅ (routing, controller, response JSON, HTTP status)          |
| GraphQL (Laravel Lighthouse) | ✅✅ (schema-first GraphQL API)                                   |
| Autenticazione JWT / OAuth   | ✅✅✅ (token-based auth, Laravel Passport/Sanctum)               |
| Webhooks / Callback Handling | ✅✅ (gestione API esterne async)                                 |
| Rate Limiting & Middleware   | ✅✅✅ (Throttle, IP limit, custom middleware in Laravel/Symfony) |

---

### 🧩 4. **Framework Mastery**

#### Laravel (9–11)

| Area                       | Dettagli                                                          |
| -------------------------- | ----------------------------------------------------------------- |
| Routing & Controllers      | ✅✅✅ (`Route::get/post`, `Controller@action`)                   |
| Blade Templating           | ✅✅✅ (`@foreach`, `@extends`, componenti)                       |
| Eloquent ORM               | ✅✅✅ (query fluente, relazioni, eager/lazy load, `with`, `has`) |
| Migrations & Seeder        | ✅✅✅ (schema versioning, test DB, dati fake)                    |
| Laravel Queues             | ✅✅ (jobs async via Redis, DB, RabbitMQ, ecc.)                   |
| Laravel Events & Listeners | ✅✅ (observer, domain events, hook customi)                      |
| Laravel Livewire / Inertia | ✅✅ (interazione realtime, reattività full-stack)                |
| Laravel Nova / Filament    | ✅ (pannelli admin pronti all’uso, backend low-code)              |

#### Symfony (facoltativo)

| Area                 | Dettagli                                                   |
| -------------------- | ---------------------------------------------------------- |
| Routing              | ✅✅ (YAML/PHP/XML-based routes)                           |
| Dependency Injection | ✅✅✅ (Container potente, service auto-wiring)            |
| Doctrine ORM         | ✅✅✅ (DB access con entity manager, relazioni complesse) |
| Console Commands     | ✅✅ (CLI tool estendibile)                                |

---

### 🔐 5. **Sicurezza**

| Area                         | Dettagli                                                   |
| ---------------------------- | ---------------------------------------------------------- |
| XSS / CSRF / SQLi Protection | ✅✅✅ (Blade escaping, middleware CSRF, PDO safe queries) |
| Autenticazione 2FA           | ✅✅ (OTP via app/email)                                   |
| Password Hashing             | ✅✅✅ (`bcrypt`, `argon2`, `password_hash()`)             |
| HTTPS / CORS Headers         | ✅✅ (gestione header e policy sicure)                     |
| Laravel Security Updates     | ✅✅✅ (follow-up CVE e release)                           |

---

### 🧪 6. **Testing**

| Area              | Dettagli                                                 |
| ----------------- | -------------------------------------------------------- |
| PHPUnit           | ✅✅✅ (unit test, assert, test-driven)                  |
| Laravel Pest      | ✅✅✅ (DSL elegante per testing moderno)                |
| Laravel Dusk      | ✅ (testing e2e browser-driven)                          |
| Factory & Mocking | ✅✅✅ (model factory, mocking repository/service layer) |

---

### ⚙️ 7. **Tooling & DevOps**

| Area                     | Dettagli                                               |
| ------------------------ | ------------------------------------------------------ |
| Composer                 | ✅✅✅ (gestione pacchetti, autoloading PSR-4)         |
| Docker                   | ✅✅✅ (Laravel/Symfony in container, override `.env`) |
| CI/CD (GitHub Actions)   | ✅✅ (lint + test + deploy)                            |
| Laravel Forge / Envoyer  | ✅✅ (deploy Laravel su VPS/cloud)                     |
| Redis & Cache            | ✅✅✅ (caching route, query, view, tag-based cache)   |
| Queues & Background Jobs | ✅✅✅ (Laravel Jobs con Redis, RabbitMQ, Beanstalkd)  |

---

### 📦 8. **Database & Architettura**

| Area               | Dettagli                                        |
| ------------------ | ----------------------------------------------- |
| MySQL/PostgreSQL   | ✅✅✅ (DB relazionali più comuni)              |
| SQLite             | ✅✅ (usato per test o app leggere)             |
| NoSQL (MongoDB)    | ✅ (Laravel + Mongo plugin, repository pattern) |
| CQRS/Service Layer | ✅✅ (clean arch, domain separation, DTOs)      |
| DDD (lightweight)  | ✅ (aggregate, entity, service logic)           |

---

## 🎓 Risorse & Libri per studiare:

### _Gratuite_

- **YouTube Videos**:

  1. [PHP for Beginners – freeCodeCamp](https://www.youtube.com/watch?v=OK_JCtrrv-c) ▶️  
     Corso completo di PHP per principianti, coprendo tutto, dalla sintassi di base alla creazione di progetti web.

  2. [PHP Tutorial – Traversy Media](https://www.youtube.com/watch?v=8kK-cA3B4Ck) ▶️  
     Corso che esplora PHP dal livello base ad avanzato, compresa la creazione di applicazioni web con database MySQL.

- **YouTube Channels**:

  1. [Codecourse](https://www.youtube.com/c/Codecourse) 📺  
     Canale che fornisce tutorial pratici su PHP e sviluppo web, con esempi reali di codice.

  2. [PHP Academy](https://www.youtube.com/user/phpacademy) 📺  
     Un canale dedicato agli sviluppatori PHP, con tutorial su framework, gestione database e ottimizzazione delle performance.

- **Articoli**:

  1. [PHP Manual – Official Documentation](https://www.php.net/manual/en/) ✍️  
     La documentazione ufficiale di PHP, che fornisce una guida completa su funzioni, classi, e best practices.

  2. [PHP for Beginners: A Step-by-Step Guide](https://www.tutorialrepublic.com/php-tutorial/) ✍️  
     Una guida dettagliata per chi inizia con PHP, che copre concetti come variabili, loop, array e gestione dei form.

- **Simphony (Focus)**:

  1. [Oracle Simphony Overview](https://www.oracle.com/industries/hospitality/simphony.html) ✍️  
     Introduzione a Oracle Simphony, un sistema di gestione per il settore hospitality, utile per chi sviluppa software per ristoranti e hotel.

  2. [Oracle Simphony: Developer's Guide](https://docs.oracle.com/cd/E50540_01/PSMSD/hospitality-simphony-developers-guide.html) ✍️  
     Guida per sviluppatori che desiderano integrarsi con il sistema Oracle Simphony, incluse le API e le best practices.

- **Best Course**:  
  [PHP for Web Development – LinkedIn Learning](https://www.linkedin.com/learning/php-for-web-development-2) 🎥  
  Corso completo di PHP per lo sviluppo web, che copre le basi di PHP e come usarlo in applicazioni complesse, incluse interazioni con database. 🌐

---

### _A Pagamento_

- **Libri**:

  - 📘 _Modern PHP: New Features and Good Practices_ – Josh Lockhart  
    Un libro che esplora le nuove funzionalità di PHP e le migliori pratiche per lo sviluppo moderno.

  - 📕 _PHP & MySQL: Novice to Ninja_ – Tom Butler  
    Una guida completa per imparare PHP e MySQL, con esempi pratici e progetti concreti.

  - 📙 _Laravel Up & Running_ – Matt Stauffer  
    Una guida completa per imparare Laravel, uno dei framework PHP più usati per lo sviluppo web, con esempi di codice e progetti reali.

- **Corsi Consigliati dalla Community**:

  1. **[Complete PHP for Beginners – Udemy](https://www.udemy.com/course/php-for-beginners/)**
     Corso consigliato dalla community che insegna le basi di PHP e come utilizzarlo per creare siti web dinamici. 🌐

  2. **[Oracle Simphony Developer Training – Oracle University](https://education.oracle.com/simphony-developer-training)**
     Corso specifico per sviluppatori che desiderano imparare a integrare e utilizzare Oracle Simphony. 🌐

  3. **[PHP 7 Fast Track – Pluralsight](https://www.pluralsight.com/courses/php7-fast-track)**
     Corso su Pluralsight che copre PHP 7, ottimizzando il codice e migliorando la gestione delle performance. 🌐
