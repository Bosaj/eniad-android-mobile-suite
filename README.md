<div align="center">

<!-- Header Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,3,5,30&height=200&section=header&text=ENIAD%20Native%20Android%20Mobile%20Architecture%20Suite&fontSize=32&animation=twinkling&fontAlignY=35&desc=ENIAD%20Berkane%20%7C%20Engineering%20Curriculum%20Laboratory%20Suite&descSize=14&descAlignY=55" alt="ENIAD Native Android Mobile Architecture Suite Banner" width="100%" />

<!-- Typing Animation -->
<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3000&pause=1000&color=00D9FF&center=true&vCenter=true&repeat=true&width=800&height=40&lines=Native%20Android%20Mobile%20Development;Modern%20Material%20Design%20Components;Full%20Trilingual%20Localization%20AR/FR/EN;SQLite%20and%20SharedPreferences%20Storage" alt="Typing SVG" />
</p>

<!-- Quality & Community Badges -->
<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square" alt="MIT License" /></a>
  <a href="https://github.com/Bosaj/eniad-android-mobile-suite/actions"><img src="https://img.shields.io/badge/CI%20Pipeline-Passing-brightgreen?style=flat-square&logo=githubactions" alt="CI Status" /></a>
  <a href="https://github.com/Bosaj/eniad-android-mobile-suite/stargazers"><img src="https://img.shields.io/github/stars/Bosaj/eniad-android-mobile-suite?style=flat-square&logo=github&color=00d9ff" alt="Stars" /></a>
  <a href="https://github.com/users/Bosaj/projects/36"><img src="https://img.shields.io/badge/Project_Board-Project_36-blue?style=flat-square&logo=github" alt="Project Board" /></a>
  <a href="https://github.com/stars/Bosaj/lists/eniad-academic-projects"><img src="https://img.shields.io/badge/Curated_List-ENIAD_Academic_Projects-gold?style=flat-square&logo=github" alt="Curated List" /></a>
  <img src="https://img.shields.io/badge/Institution-ENIAD%20Berkane-FF6B00?style=flat-square" alt="ENIAD Berkane" />
</p>

</div>

<!-- Divider -->
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" alt="Divider" width="100%" />

## 📖 Overview

**ENIAD Native Android Mobile Architecture Suite** is an official engineering laboratory suite developed within the **State Engineering Degree in Artificial Intelligence & Digital Systems** at the **École Nationale d'Intelligence Artificielle et du Digital (ENIAD)**, Mohammed First University, Berkane, Morocco.

Native Android Engineering Suite featuring Clean Architecture, Material Design UI, Full Trilingual Localization (Arabic RTL, French, English), and SQLite Data Persistence.

---

## 🏗️ Technical Architecture

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

## 📂 Curriculum & Laboratory Breakdown

| Module / Lab | Architecture Focus | Features & Deliverables |
|---|---|---|
| `Activity Lifecycles` | Android Fundamentals | State preservation, intent navigation, bundle parameter passing |
| `Layouts & Material UI` | UI/UX Engineering | ConstraintLayout, CoordinatorLayout, RecyclerView with custom adapters |
| `Multilingual Support` | Internationalization | Dynamic runtime localization: Arabic (RTL), French, and English |
| `Data Persistence` | Storage Architecture | SQLite Database helper, CRUD operations, SharedPreferences settings |
| `Build Automation` | Gradle Kotlin DSL | `build.gradle.kts`, `settings.gradle.kts`, dependency version management |


---

## 📚 Technical Wiki & Documentation

Comprehensive architectural explanations, step-by-step lab walk-throughs, and methodology guides are available:
- **In-Repository Wiki Mirror**: [`docs/wiki/Home.md`](docs/wiki/Home.md)
- **Architecture Overview**: [`docs/ARCHITECTURE.md`](docs/ARCHITECTURE.md)
- **Curriculum Matrix**: [`docs/CURRICULUM_MATRIX.md`](docs/CURRICULUM_MATRIX.md)
- **GitHub Wiki**: [https://github.com/Bosaj/eniad-android-mobile-suite/wiki](https://github.com/Bosaj/eniad-android-mobile-suite/wiki)

---

## 🚀 Getting Started

### Prerequisites
- Git installed on your local workstation
- Development runtime corresponding to the target laboratory (Python 3.10+, Java JDK 17+, Android Studio, or C++ compiler)

### Installation & Cloning
```bash
git clone https://github.com/Bosaj/eniad-android-mobile-suite.git
cd eniad-android-mobile-suite
```

---

## 📜 DevSecOps Governance & Standards

This repository adheres to strict open-source engineering and academic integrity standards:
- [LICENSE](LICENSE): Open-source MIT License.
- [CONTRIBUTING.md](CONTRIBUTING.md): Guidelines for submitting contributions, issue templates, and code formatting.
- [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md): Contributor Covenant v2.1 code of conduct.
- [SECURITY.md](SECURITY.md): Responsible vulnerability reporting procedures.
- [CHANGELOG.md](CHANGELOG.md): Version history following Keep a Changelog standards.
- [CITATION.cff](CITATION.cff): Machine-readable academic citation metadata.

---

## 👤 Author & Academic Credits

- **Engineer / Researcher**: **Oussama EL HADJI** ([@Bosaj](https://github.com/Bosaj))
- **Role**: AI & Automation Engineer @ Circet Morocco | ENIAD Engineering Graduate
- **Institution**: École Nationale d'Intelligence Artificielle et du Digital (ENIAD), Berkane, Morocco
- **Portfolio**: [bosaj.vercel.app](https://bosaj.vercel.app) • [LinkedIn](https://www.linkedin.com/in/oussama-elhadji)

---

<div align="center">
  <sub>Maintained with ❤️ by <a href="https://github.com/Bosaj">Oussama EL HADJI</a> • ENIAD Berkane</sub>
</div>
