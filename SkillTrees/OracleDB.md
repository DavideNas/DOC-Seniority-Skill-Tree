## 🛢️ Oracle DB – Skill Tree per Java Developer Senior (2025)

---

### 🔍 1. **Fondamenta SQL in Oracle**

| Area                    | Dettagli                                                    |
| ----------------------- | ----------------------------------------------------------- |
| SQL base                | ✅✅✅ (`SELECT`, `JOIN`, `GROUP BY`, `HAVING`, `ORDER BY`) |
| Data Types Oracle       | ✅✅✅ (`VARCHAR2`, `NUMBER`, `DATE`, `CLOB`, `BLOB`)       |
| Constraints             | ✅✅✅ (`PK`, `FK`, `UNIQUE`, `CHECK`, `NOT NULL`)          |
| Functions & Expressions | ✅✅✅ (`NVL`, `COALESCE`, `DECODE`, `CASE`, date math)     |
| DDL                     | ✅✅ (`CREATE TABLE`, `ALTER`, `DROP`, `RENAME`)            |
| DML                     | ✅✅✅ (`INSERT`, `UPDATE`, `DELETE`, `MERGE`)              |

---

### 🔄 2. **PL/SQL & Stored Logic**

| Area                 | Dettagli                                                      |
| -------------------- | ------------------------------------------------------------- |
| PL/SQL Basics        | ✅✅✅ (`DECLARE`, `BEGIN`, `EXCEPTION`, `END`)               |
| Stored Procedures    | ✅✅✅ (`CREATE PROCEDURE`, `IN/OUT` params, `EXEC`)          |
| Functions & Packages | ✅✅✅ (funzioni invocabili da SQL, pacchetti modulari)       |
| Triggers             | ✅✅ (before/after insert/update/delete, row/statement level) |
| Cursors              | ✅✅✅ (espliciti, impliciti, `FOR LOOP`, `FETCH`, `CLOSE`)   |
| Exception Handling   | ✅✅✅ (`WHEN OTHERS`, `SQLCODE`, `SQLERRM`)                  |

---

### ⚙️ 3. **Performance & Tuning**

| Area               | Dettagli                                           |
| ------------------ | -------------------------------------------------- |
| Execution Plans    | ✅✅✅ (`EXPLAIN PLAN`, `AUTOTRACE`, `DBMS_XPLAN`) |
| Indexes            | ✅✅✅ (B-tree, bitmap, function-based, composite) |
| Partitioning       | ✅✅ (range, list, hash, subpartitioning)          |
| Statistics & Hints | ✅✅ (`ANALYZE`, `DBMS_STATS`, `/*+ INDEX */`)     |
| Materialized Views | ✅✅ (refresh on demand/commit, query rewrite)     |
| Parallel Queries   | ✅✅ (parallel degree, DOP, query hint)            |

---

### 🔐 4. **Security & Access Control**

| Area                     | Dettagli                                                   |
| ------------------------ | ---------------------------------------------------------- |
| User Management          | ✅✅✅ (`CREATE USER`, `GRANT`, `REVOKE`, `ALTER USER`)    |
| Roles & Privileges       | ✅✅✅ (`RESOURCE`, `CONNECT`, `DBA`, object-level GRANTs) |
| Auditing                 | ✅✅ (fine-grained auditing con `DBMS_FGA`, audit logs)    |
| VPD & Row-Level Security | ✅ (Virtual Private Database con `DBMS_RLS`)               |

---

### 🔌 5. **Integrazione con Java**

| Area                 | Dettagli                                                     |
| -------------------- | ------------------------------------------------------------ |
| JDBC (Driver Oracle) | ✅✅✅ (`ojdbc8.jar`, `OracleDataSource`, `Connection`)      |
| Connection Pooling   | ✅✅✅ (HikariCP, Apache DBCP, Oracle UCP)                   |
| Transactions         | ✅✅✅ (`setAutoCommit(false)`, `commit`, `rollback`)        |
| CallableStatement    | ✅✅✅ (invocare stored procedures da Java)                  |
| ORM con Oracle       | ✅✅✅ (Hibernate + Oracle Dialect, JPA tuning per `ROWNUM`) |

---

### ☁️ 6. **Tooling & Backup**

| Area          | Dettagli                                                             |
| ------------- | -------------------------------------------------------------------- |
| SQL Developer | ✅✅✅ (GUI ufficiale Oracle, debugging PL/SQL, export/import)       |
| RMAN          | ✅✅ (Oracle Recovery Manager per backup completo/incrementale)      |
| Data Pump     | ✅✅✅ (`expdp`, `impdp`, parallelo, filtering)                      |
| APEX          | ✅ (Oracle Application Express – app web su Oracle)                  |
| OEM           | ✅ (Oracle Enterprise Manager – monitoraggio e tuning centralizzato) |

---

### 🔄 7. **Migrazione / Interoperabilità**

| Area                      | Dettagli                                                         |
| ------------------------- | ---------------------------------------------------------------- |
| Oracle → PostgreSQL       | ✅ (usare ora2pg, compatibilità PL/pgSQL)                        |
| Oracle + Liquibase/Flyway | ✅✅ (migrazione schema versionata in CI/CD)                     |
| Legacy Forms → REST       | ✅ (interfacciare vecchi sistemi Oracle con servizi Spring Boot) |

---

Perfetto! Integro la tua struttura **standardizzata** delle risorse alla fine della guida Oracle. Ecco come apparirà il **blocco finale** per la sezione Oracle:

---

## 🎓 Risorse & Libri x studiare:

### _Gratuite_

- **YouTube Videos**:

  1. [Oracle Database Tutorial for Beginners – freeCodeCamp](https://www.youtube.com/watch?v=ojKGEcD7w6M) ▶️  
     Introduzione a Oracle DB, coprendo le nozioni di base, la configurazione e la gestione dei database.

  2. [Oracle Database Full Course – Programming with Mosh](https://www.youtube.com/watch?v=VJ1diGe_TlE) ▶️  
     Un corso completo che esplora i concetti di base di Oracle DB e le sue applicazioni nel mondo reale.

- **YouTube Channels**:

  1. [Oracle Developers](https://www.youtube.com/c/OracleDevelopers) 📺  
     Canale ufficiale di Oracle che offre tutorial, webinar e approfondimenti sul database e altre tecnologie Oracle.

  2. [Oracle Academy](https://www.youtube.com/c/OracleAcademy) 📺  
     Un canale educativo che fornisce corsi e risorse sulla gestione di Oracle DB e altre tecnologie Oracle.

- **Articoli**:

  1. [Oracle Database Documentation](https://docs.oracle.com/en/database/) ✍️  
     La documentazione ufficiale di Oracle, una risorsa completa per approfondire l’utilizzo del database, dall’installazione alla gestione avanzata.

  2. [Oracle Database: What It Is & How It Works](https://www.oracle.com/database/what-is-oracle-database/) ✍️  
     Articolo introduttivo che descrive Oracle DB e come viene utilizzato per gestire i dati aziendali.

- **Documentazione ufficiale / Guide utili**:

  - [Oracle Database 19c Documentation](https://docs.oracle.com/en/database/oracle/oracle-database/19/) 📘  
    La documentazione ufficiale per Oracle Database 19c, che offre tutte le informazioni dettagliate su configurazione, gestione e ottimizzazione del database.

  - [Oracle Database Express Edition (XE)](https://www.oracle.com/database/technologies/appdev/xe.html) 📘  
    Guida su Oracle XE, la versione gratuita di Oracle Database, utile per sviluppatori e principianti.

- **Best Course**:  
  [Oracle Database for Beginners – Udemy](https://www.udemy.com/course/oracle-database-for-beginners/) 🎥  
  Corso completo su Oracle Database, ideale per chi inizia a lavorare con Oracle, coprendo installazione, operazioni e ottimizzazione. 🌐

---

### _A Pagamento_

- **Libri**:

  - 📘 _Oracle Database 12c: The Complete Reference_ – Bob Bryla, Kevin Loney  
    Una guida completa che copre ogni aspetto di Oracle Database 12c, incluse le caratteristiche avanzate e le best practices.

  - 📕 _Learning Oracle PL/SQL_ – Bill Pribyl, Steven Feuerstein  
    Un libro fondamentale per imparare PL/SQL, il linguaggio di programmazione integrato in Oracle Database.

  - 📙 _Oracle SQL by Example_ – Alice Rischert  
    Un libro pratico che fornisce esempi di SQL in Oracle Database per sviluppatori e DBA.

- **Corsi Consigliati dalla Community**:

  1. **[Oracle Database 19c: SQL, PL/SQL and DBA – Udemy](https://www.udemy.com/course/oracle-database-sql-plsql-and-dba/)**
     Un corso completo che copre SQL, PL/SQL e la gestione del database in Oracle 19c, molto apprezzato per la sua completezza e chiarezza. 🌐

  2. **[Oracle Database Administration 101 – Pluralsight](https://www.pluralsight.com/courses/oracle-database-administration-101)**
     Corso su Pluralsight che offre una panoramica su come amministrare Oracle Database, utile per chi si occupa di gestione di database aziendali. 🌐

  3. **[Oracle Certified Associate (OCA) – Oracle](https://education.oracle.com/oracle-certified-associate/pexam_1Z0-071)**
     Certificazione Oracle che prepara a diventare Oracle Certified Associate (OCA), utile per sviluppatori e amministratori di database Oracle. 🌐
