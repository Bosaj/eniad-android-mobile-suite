# Welcome to the ENIAD Native Android Mobile Architecture Suite Documentation Wiki 📖

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](https://opensource.org/licenses/MIT)
[![Institution: ENIAD Berkane](https://img.shields.io/badge/Institution-ENIAD%20Berkane-FF6B00?style=flat-square)](https://github.com/Bosaj/native-android-multilingual-suite)
[![Project Board](https://img.shields.io/badge/Project_Board-Project_36-blue?style=flat-square&logo=github)](https://github.com/users/Bosaj/projects/36)
[![Curated List](https://img.shields.io/badge/Curated_List-ENIAD_Academic_Projects-gold?style=flat-square&logo=github)](https://github.com/stars/Bosaj/lists/eniad-academic-projects)

Welcome to the official technical documentation and engineering reference for **ENIAD Native Android Mobile Architecture Suite**.

---

## 🎯 Academic & Technical Mission

Native Android Engineering Suite featuring Clean Architecture, Material Design UI, Full Trilingual Localization (Arabic RTL, French, English), and SQLite Data Persistence.

Developed within the **State Engineering Degree in Artificial Intelligence & Digital Systems** at the **École Nationale d'Intelligence Artificielle et du Digital (ENIAD)**, Berkane, Morocco.

---

## 📚 Wiki Documentation Chapters

| Chapter | Description | Primary Topics |
| :--- | :--- | :--- |
| **[[Architecture]]** | Deep architectural design & component topology | Mermaid diagrams, component interactions, runtime environment |
| **[[Getting-Started]]** | Developer setup & workstation configuration | Prerequisites, toolchain setup, execution commands |
| **[[Curriculum-Guide]]** | Detailed syllabus and laboratory breakdown | Lab objectives, expected outputs, deliverables |

---

## 🏛️ System Architecture Snapshot

```mermaid
graph TD
    A[Mobile UI / XML Layouts] --> B[Activity / Fragment Controller]
    B --> C[ViewModel & Business Logic]
    C --> D[Data Layer Repository]
    D --> E[(SQLite Database)]
    D --> F[SharedPreferences]
    subgraph Localization [Multilingual Resource Bundles]
        AR[Arabic - values-ar / RTL]
        FR[French - values-fr]
        EN[English - values / Default]
    end
    Localization --> A
    style A fill:#00D9FF,stroke:#333,stroke-width:1px,color:#000
    style B fill:#FF6B00,stroke:#333,stroke-width:1px,color:#fff
    style D fill:#3C873A,stroke:#333,stroke-width:1px,color:#fff
    style Localization fill:#1E293B,stroke:#7928CA,stroke-width:2px,color:#fff

```

---

## 📱 Android Architecture & Best Practices

- **Separation of Concerns**: UI rendering is decoupled from data retrieval and state manipulation.
- **RTL Support**: Native bidirectional layout handling via `android:supportsRtl="true"` and `start/end` attributes.
- **Storage Layer**: SQLiteOpenHelper pattern implementing safe database migrations and parameterized queries to prevent SQL injection.
- **Resource Management**: Extracted string, color, and dimension resources for effortless theme adaptation.


---

*Maintained with ❤️ by [Oussama EL HADJI](https://github.com/Bosaj) • ENIAD Berkane*
