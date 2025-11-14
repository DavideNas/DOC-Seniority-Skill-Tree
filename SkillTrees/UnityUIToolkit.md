## 🧩 Unity UI Toolkit Developer – Skill Stack (2025)

---

### 🧱 1. **Core Concepts**

| Area                       | Dettagli                                                                   |
| -------------------------- | -------------------------------------------------------------------------- |
| UI Document (`UIDocument`) | ✅✅✅ (entry point per l'interfaccia UI, referenza in scene e prefabs)    |
| UXML                       | ✅✅✅ (markup simile all’HTML, struttura dichiarativa dell’interfaccia)   |
| USS                        | ✅✅✅ (stile via fogli simili a CSS, gestione responsive & stato)         |
| C# Binding                 | ✅✅✅ (binding di eventi, manipolazione UI runtime via `Query`, `Q<T>()`) |
| VisualElement & Template   | ✅✅✅ (container UI, clonazione da template, slot system)                 |

---

### 🎛️ 2. **Layout & Stili**

| Area                     | Dettagli                                                                     |
| ------------------------ | ---------------------------------------------------------------------------- |
| Flexbox Layout           | ✅✅✅ (simile a CSS Flexbox: direction, alignment, wrap, grow)              |
| StyleSheets Runtime      | ✅✅ (modifica stili dinamicamente da C#)                                    |
| Style Classes            | ✅✅✅ (aggiunta e rimozione classi runtime per animazioni o effetti visivi) |
| Transizioni & Animazioni | ✅✅ (limitato ma possibile via style change + coroutine)                    |

---

### 🧠 3. **Interazione, Logica e Tooling**

| Area              | Dettagli                                                                           |
| ----------------- | ---------------------------------------------------------------------------------- |
| Eventi UI         | ✅✅✅ (`RegisterCallback`, `ClickEvent`, `ChangeEvent`, bubbling/capturing)       |
| Binding Data      | ✅✅✅ (binding di proprietà con `BindableElement`, `INotifyValueChanged`)         |
| Custom Controls   | ✅✅ (creazione di nuovi VisualElement personalizzati)                             |
| Editor UI Toolkit | ✅✅✅ (UI personalizzate per tool/editor via `EditorWindow` e `InspectorElement`) |

---

### 🧪 4. **Testing e Debug**

| Area               | Dettagli                                                                     |
| ------------------ | ---------------------------------------------------------------------------- |
| Debug Visual Tree  | ✅✅✅ (UI Debugger integrato, hierarchy visuale, classi e margini visibili) |
| Modularità UI      | ✅✅ (componentizzazione tramite template UXML e documenti multipli)         |
| Playmode vs Editor | ✅✅✅ (UI Toolkit funziona in entrambi i contesti, ottimo per dev tools)    |
| Responsive Design  | ✅✅ (possibilità di layout adattivo tramite USS + Flexbox)                  |

---

## ✅ Sei un **Senior UI Toolkit Developer** se:

- ✅ Usi **UXML+USS come standard base** e scrivi interfacce scalabili
- ✅ Usi **binding e componenti reattivi** con `BindableElement` o `SerializedObject`
- ✅ Sai creare **Editor tools complessi** con Inspector personalizzati
- ✅ Sai costruire **UI modulari e riusabili** con `TemplateContainer`
- ✅ Sfrutti **flexbox + classi dinamiche** per gestire layout reattivi
- ✅ Usi **UI Toolkit anche per runtime**, non solo editor

---

## 🚀 Starter Kit consigliato

🧩 **Unity 2022+**  
📦 **Packages**:

- `com.unity.ui`
- `com.unity.ui.builder` (Editor UI Builder)

📁 **Setup Base**:

- `/Assets/UI/UXML`
- `/Assets/UI/USS`
- `/Assets/UI/Scripts/UIController.cs`

🔧 **Tools**:

- **UI Builder** (visivo, WYSIWYG)
- **UI Debugger** (Inspector in playmode)
- **USS Live Reload** (Unity 2022.2+)

---

## 📚 Risorse per Unity UI Toolkit

### _Gratuite_

- **YouTube Videos**:

  - [Unity UI Toolkit Tutorial – Code Monkey](https://www.youtube.com/watch?v=fy8xB5Hsx_Y)
  - [Create Custom Inspectors – Brackeys (UI Toolkit Edition unofficial)](https://www.youtube.com/watch?v=QmY5SZGQjW4)
  - [Unity UI Toolkit from Scratch – Game Dev Guide](https://www.youtube.com/watch?v=WUEH1lG5Wj8)

- **YouTube Channels**:

  - **Code Monkey** – Tutorials passo-passo UI Runtime
  - **Game Dev Guide** – UI Toolkit avanzato
  - **Unity** (Official) – serie UI Toolkit 2022+

- **Articoli**:

  - [Unity Blog – Introducing UI Toolkit](https://blog.unity.com/technology/introducing-unitys-new-ui-toolkit)
  - [Runtime UI with UI Toolkit](https://blog.unity.com/technology/using-ui-toolkit-for-runtime-uis)
  - [Flexbox Layout Rules in UI Toolkit](https://docs.unity3d.com/Manual/UIE-USS-Flex.html)

- **Documentazione ufficiale**:

  - [Unity UI Toolkit Manual](https://docs.unity3d.com/Manual/UIElements.html)
  - [UXML Syntax Reference](https://docs.unity3d.com/Manual/UIE-UXML.html)
  - [USS Reference (Style Rules)](https://docs.unity3d.com/Manual/UIE-USS.html)

- **Best Course**:
  - [Unity Learn – Create UI with UI Toolkit (Free)](https://learn.unity.com/project/ui-toolkit)

---

### _A Pagamento_

- **Libri**:

  - _Unity UI Toolkit – Pro UI Design for Games and Tools_ (in arrivo 2025)
  - _Unity UI Development_ (Capitolo dedicato a UI Toolkit, Packt Publishing)
  - _Hands-On Unity 2023 Game Development_ – include sezione editor UI Toolkit

- **Corsi Consigliati dalla Community**:
  - [**Udemy – Unity UI Toolkit Masterclass** (GameDev.tv)](https://www.udemy.com/course/unity-ui-toolkit/)
  - [**Skillshare – UI Toolkit per Tool Editor**](https://www.skillshare.com/en/browse/unity-ui-toolkit)
  - [**CG Cookie – Unity Editor Scripting** (con UI Toolkit)](https://cgcookie.com/course/unity-editor-scripting)
  - [**Domestika – UI Design for Games (Runtime/UI Toolkit)**](https://www.domestika.org/en/courses/)
