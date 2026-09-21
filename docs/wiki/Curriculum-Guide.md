# Academic Curriculum & Laboratory Guide 📂

This guide presents the complete educational structure, competency mapping, and lab sequence for **ENIAD Native Android Mobile Architecture Suite**.

---

## 📑 Curriculum Matrix

| Module / Lab | Architecture Focus | Features & Deliverables |
|---|---|---|
| `Activity Lifecycles` | Android Fundamentals | State preservation, intent navigation, bundle parameter passing |
| `Layouts & Material UI` | UI/UX Engineering | ConstraintLayout, CoordinatorLayout, RecyclerView with custom adapters |
| `Multilingual Support` | Internationalization | Dynamic runtime localization: Arabic (RTL), French, and English |
| `Data Persistence` | Storage Architecture | SQLite Database helper, CRUD operations, SharedPreferences settings |
| `Build Automation` | Gradle Kotlin DSL | `build.gradle.kts`, `settings.gradle.kts`, dependency version management |


---

## 📱 Android Architecture & Best Practices

- **Separation of Concerns**: UI rendering is decoupled from data retrieval and state manipulation.
- **RTL Support**: Native bidirectional layout handling via `android:supportsRtl="true"` and `start/end` attributes.
- **Storage Layer**: SQLiteOpenHelper pattern implementing safe database migrations and parameterized queries to prevent SQL injection.
- **Resource Management**: Extracted string, color, and dimension resources for effortless theme adaptation.

