## 🐘 PostgreSQL DBA – Skill Tree (Ops + Dev, 2025)

---

### 🔰 1. **Fondamenti SQL & RDBMS**

| Area                 | Dettagli                                                         |
| -------------------- | ---------------------------------------------------------------- |
| SQL Base             | ✅✅✅ (`SELECT`, `INSERT`, `UPDATE`, `DELETE`, `WHERE`, `JOIN`) |
| Funzioni Aggregate   | ✅✅✅ (`SUM`, `COUNT`, `AVG`, `GROUP BY`, `HAVING`)             |
| Subquery & CTE       | ✅✅✅ (`WITH`, subquery nidificate, correlated)                 |
| Transazioni          | ✅✅✅ (`BEGIN`, `COMMIT`, `ROLLBACK`, `SAVEPOINT`)              |
| Constraints & Chiavi | ✅✅✅ (`PRIMARY`, `FOREIGN`, `UNIQUE`, `CHECK`)                 |
| Normalizzazione      | ✅✅✅ (1NF → 3NF, decomposizione, dipendenze funzionali)        |

---

### ⚙️ 2. **PostgreSQL Core Features**

| Area                  | Dettagli                                                              |
| --------------------- | --------------------------------------------------------------------- |
| Tipi di Dato Avanzati | ✅✅✅ (`JSONB`, `ARRAY`, `UUID`, `TSVECTOR`, `HSTORE`)               |
| Indici                | ✅✅✅ (`BTREE`, `GIN`, `GiST`, `BRIN`, indici parziali/multipli)     |
| Stored Procedures     | ✅✅✅ (`FUNCTION`, `DO`, PL/pgSQL, `RETURN QUERY`)                   |
| Trigger & Eventi      | ✅✅ (AFTER/BEFORE, su `INSERT`, `UPDATE`, `DELETE`)                  |
| Performance Tuning    | ✅✅ (parametri `work_mem`, `shared_buffers`, `effective_cache_size`) |
| `EXPLAIN` & `ANALYZE` | ✅✅✅ (analisi piani d'esecuzione, `cost`, `rows`, `loops`)          |

---

### 📈 3. **Ottimizzazione & Performance**

| Area                     | Dettagli                                                           |
| ------------------------ | ------------------------------------------------------------------ |
| Query Tuning             | ✅✅✅ (index scan vs seq scan, `LIMIT`, `OFFSET`, `IN` vs `JOIN`) |
| Index Strategy           | ✅✅✅ (uso selettivo, copertura, multi-colonna, condizionale)     |
| Vacuum & Autovacuum      | ✅✅✅ (`VACUUM`, `ANALYZE`, tuning `autovacuum_*`)                |
| Parallel Query Execution | ✅✅ (sfruttamento multi-core su join, aggregate, scan)            |
| Caching Layer            | ✅✅ (integrazione con Redis/Memcached)                            |

---

### 🧱 4. **Architettura & Replicazione**

| Area                          | Dettagli                                                         |
| ----------------------------- | ---------------------------------------------------------------- |
| WAL (Write-Ahead Logging)     | ✅✅✅ (fondamenta per recovery e replica)                       |
| Logical Replication           | ✅✅✅ (`pgoutput`, `CREATE SUBSCRIPTION`, `PUBLICATION`)        |
| Streaming Replication         | ✅✅✅ (replica sincrona/asincrona tra master/standby)           |
| Point-in-Time Recovery (PITR) | ✅✅ (backup con `pg_basebackup` + WAL replay)                   |
| Connection Pooling            | ✅✅ (PgBouncer, gestione delle connessioni ad alte prestazioni) |
| HA & Failover                 | ✅✅ (Patroni, repmgr, keepalived)                               |

---

### 🛡️ 5. **Sicurezza**

| Area                     | Dettagli                                                           |
| ------------------------ | ------------------------------------------------------------------ |
| Autenticazione           | ✅✅✅ (`md5`, `scram-sha-256`, LDAP, GSSAPI, certificati TLS)     |
| Ruoli & Permessi         | ✅✅✅ (`GRANT`, `REVOKE`, `ALTER ROLE`, `DEFAULT PRIVILEGES`)     |
| Row-Level Security (RLS) | ✅✅ (policy con `USING`, `WITH CHECK`, `SECURITY DEFINER`)        |
| Audit & Log              | ✅✅ (estensioni tipo `pgAudit`, logging query e errori sensibili) |
| Data Encryption          | ✅✅ (supporto TLS, filesystem-level encryption, Transparent Data) |

---

### 🧪 6. **Testing, Backup & Disaster Recovery**

| Area              | Dettagli                                                                      |
| ----------------- | ----------------------------------------------------------------------------- |
| Backup Strategie  | ✅✅✅ (`pg_dump`, `pg_basebackup`, `custom` vs `directory` format)           |
| Restore Procedure | ✅✅✅ (`pg_restore`, PITR, verifiche di integrità e checksum)                |
| Disaster Recovery | ✅✅ (replica promozione, test failover, `recovery.conf` → `postgresql.conf`) |
| Test Data Setup   | ✅✅✅ (fixture, `pgbench`, script SQL custom per simulazione carico)         |
| Continuous Backup | ✅ (WAL archiving via `archive_command`, gestione storage)                    |

---

### 🧩 7. **Tooling & Ecosistema**

| Area               | Dettagli                                                            |
| ------------------ | ------------------------------------------------------------------- |
| pgAdmin            | ✅✅✅ (GUI per query, monitoraggio, backup e permessi)             |
| psql               | ✅✅✅ (CLI potente, scripting avanzato)                            |
| Extensions         | ✅✅✅ (`pg_stat_statements`, `uuid-ossp`, `PostGIS`, `citext`)     |
| Monitoring         | ✅✅✅ (Prometheus + Grafana, `pgwatch2`, `pg_stat_activity`)       |
| ETL & Integration  | ✅✅ (connettori con Kafka, RabbitMQ, Python/Pandas, Airflow)       |
| DevOps Integration | ✅✅ (Docker, Helm chart PostgreSQL, backup auto con cron/K8s Jobs) |

---

## 🎓 Risorse & Libri per studiare:

### _Gratuite_

- **YouTube Videos**:

  1. [PostgreSQL Full Course – freeCodeCamp](https://www.youtube.com/watch?v=qw--VYLpxG4) ▶️  
     Corso completo da zero a intermedio con esercizi pratici.

  2. [PostgreSQL Performance Tuning](https://www.youtube.com/watch?v=p7zbuIc_NWU) ▶️  
     Video tecnico sulla gestione delle performance e tuning avanzato.

- **Articoli & Docs**:

  1. [PostgreSQL Official Docs](https://www.postgresql.org/docs/) ✍️  
     Manuale ufficiale PostgreSQL, aggiornato per ogni versione.

  2. [PostgreSQL Exercises](https://pgexercises.com/) ✍️  
     Esercizi interattivi di SQL pensati per PostgreSQL.

  3. [PostgreSQL Internals](https://wiki.postgresql.org/wiki/Category:Internals) ✍️  
     Approfondimenti tecnici su come funziona il motore internamente.

### _A Pagamento_

- **Libri**:

  - 📘 _PostgreSQL: Up and Running_ – Regina O. Obe  
    Una guida rapida ma completa per amministratori e sviluppatori.

  - 📕 _Mastering PostgreSQL in Application Development_ – Dimitri Fontaine  
    Approccio moderno all’uso di PostgreSQL nel mondo reale.

  - 📙 _High Performance PostgreSQL_ – Gregory Smith  
    Focus su ottimizzazione, scalabilità e gestione di grandi volumi.

- **Corsi Consigliati**:

  1. **[The Complete SQL Bootcamp 2024 – Udemy](https://www.udemy.com/course/the-complete-sql-bootcamp/)**
     Ottimo per chi vuole diventare SQL power user, incluso PostgreSQL. 🌐

  2. **[PostgreSQL Administration – Pluralsight](https://www.pluralsight.com/courses/postgresql-administration)**
     Un corso pensato per DBA professionisti. 🌐
