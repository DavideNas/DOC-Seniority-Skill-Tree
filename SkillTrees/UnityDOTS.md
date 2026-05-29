## 🕹️ Unity DOTS Developer – Skill Stack (2025)

---

### ⚙️ 1. **Core concetti Data-Oriented**

| Area                          | Dettagli                                                      |
| ----------------------------- | ------------------------------------------------------------- |
| ECS (Entity Component System) | ✅✅✅ (Entity, ComponentData, Systems, Archetypes, Queries)  |
| Jobs System                   | ✅✅✅ (IJob, IJobParallelFor, scheduling, Burst Compilation) |
| Burst Compiler                | ✅✅✅ (ottimizzazione nativa, SIMD, determinismo)            |
| Memory Layout                 | ✅✅ (cache-friendly struct layout, SOA vs AOS)               |
| Debugging DOTS                | ✅✅ (Entity Debugger, Profiler, Logging)                     |

---

### 🧠 2. **Progettazione architetturale in DOTS**

| Area                           | Dettagli                                                        |
| ------------------------------ | --------------------------------------------------------------- |
| Separazione logica e dati      | ✅✅✅ (decoupling completo via Systems)                        |
| Performance-first mindset      | ✅✅✅ (allocazioni, parallelismo, determinismo)                |
| Gestione del ciclo di vita ECS | ✅✅ (spawning, pooling, disattivazione logica)                 |
| Sistemi custom & gruppi        | ✅✅ (SystemBase, ISystem, UpdateBefore/After, World lifecycle) |

---

### 🔌 3. **Interoperabilità con Unity tradizionale**

| Area                     | Dettagli                                                          |
| ------------------------ | ----------------------------------------------------------------- |
| Hybrid Rendering         | ✅✅✅ (conversione GameObject → Entity, materiali compatibili)   |
| Interazione Input        | ✅✅ (Input System in ambienti DOTS)                              |
| Physics DOTS             | ✅✅ (Unity Physics, Havok Physics, collisioni & trigger)         |
| Bridge con MonoBehaviour | ✅✅ (EntityManager, ComponentObject, IConvertGameObjectToEntity) |

---

### 🧪 4. **Testing, Profilazione e Debug**

| Area             | Dettagli                                                          |
| ---------------- | ----------------------------------------------------------------- |
| Unit Testing     | ✅✅ (testing di logica pura nei System, job isolati)             |
| Burst Profiler   | ✅✅✅ (usare Profiler con Jobs/Burst, tempi reali di esecuzione) |
| Entity Debugger  | ✅✅✅ (monitoraggio in runtime di archetipi e entità)            |
| Performance Logs | ✅✅ (tempi job, memory allocations, frame cost)                  |

---

## 🏁 Sei un **Senior Unity DOTS Developer** se:

✅ Sai **strutturare un progetto DOTS da zero**  
✅ Hai esperienza **con gameplay complesso senza MonoBehaviour**  
✅ Conosci **profondamente i limiti e vantaggi della Jobification e del memory layout**  
✅ Hai gestito **conversione da GameObject a Entity in progetti ibridi**  
✅ Usi **Burst, profiler e chunk inspector regolarmente per ottimizzare**  
✅ Sai **testare in isolamento i tuoi Systems con dati deterministicamente replicabili**

---

## 🎁 Starter Kit consigliato

🧱 **Unity DOTS 2025 Project Template**

- 🎮 **Unity**: 2022 LTS o 2023.x con supporto ECS
- 💾 **Packages**: `com.unity.entities`, `com.unity.physics`, `com.unity.burst`, `com.unity.jobs`
- 📦 **Rendering**: URP + Hybrid Renderer V2
- 📜 **Scripting**: DOTS-only Systems, Jobs, ComponentData
- 🧪 **Debug Tools**: Entity Debugger, Profiler Timeline, Chunk Debugger
- 🧠 **Test Tools**: Unity Test Framework + DOTS-specific unit test setup
- 🧰 **Build Tools**: Custom build script con profiler flag e burst configurato

---

## 🎓 Risorse per imparare Unity DOTS

### _Gratuite_

- **YouTube Videos**:

  - [Unity DOTS Explained – Turbo Makes Games](https://www.youtube.com/watch?v=fqxYkSGNFLo)
  - [Creating a DOTS Project from Scratch – Code Monkey](https://www.youtube.com/watch?v=f2tbDlRBrJ4)

- **YouTube Channels**:

  - **Code Monkey** – uno dei migliori per DOTS e gameplay tutorial
  - **Turbo Makes Games** – profondo, pratico e ben spiegato
  - **Unity** (official) – playlist ufficiale DOTS e ECS

- **Articoli**:

  - [Unity DOTS Overview – Unity Blog](https://blog.unity.com/technology/project-tiny-and-dots)
  - [ECS vs OOP – Turbo Makes Games](https://turbomakesgames.com/posts/ecs/)
  - [The Road to High Performance DOTS](https://blog.unity.com/technology/a-roadmap-for-high-performance-dots-development)

- **Documentazione ufficiale**:

  - [Unity ECS Documentation](https://docs.unity3d.com/Packages/com.unity.entities@latest)
  - [Unity Physics Manual](https://docs.unity3d.com/Packages/com.unity.physics@latest)

- **Best Course**:
  - [Unity Learn – DOTS Sample Project (Free)](https://learn.unity.com/project/megacity)

---

### _A Pagamento_

- **Libri**:

  - _Mastering DOTS in Unity_ – ancora in sviluppo (consigliato seguire le preview)
  - _High Performance Unity Games_ – uscito nel 2023, include una sezione DOTS
  - _Game Programming Patterns_ – non specifico DOTS ma utile per ragionare a componenti

- **Corsi Consigliati dalla Community**:
  - [**GameDev.tv – Unity DOTS Course (Udemy)**](https://www.udemy.com/course/unity-dots/)
  - [**Turbo Makes Games – Advanced DOTS (Gumroad)**](https://turbomakesgames.gumroad.com/)
  - [**CG Cookie – Game Architecture with DOTS**](https://cgcookie.com/course/ecs-dots-architecture-unity)
  - [**Skillshare – Unity DOTS Beginners**](https://www.skillshare.com/en/browse/unity)
