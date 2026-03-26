# Flux CRM - Personal-use (Empironics) 🚀

A high-performance, local-first Lead Management System (CRM) built with **Flutter** and **SQLite**. Designed to streamline the sales funnel for elevator installation and maintenance services.

---

## 🛠 Key Features

* **Pipeline Management:** Track leads through 4 stages: *New, Contacted, Responded, and Follow-up*.
* **WhatsApp Integration:** One-click messaging using customizable templates with dynamic placeholders like `{name}`.
* **Data Portability:** * **Import:** Bulk upload leads via CSV.
    * **Export/Edit:** Full CRUD (Create, Read, Update, Delete) capabilities for every contact.
* **Desktop Optimized:** Native Windows application with a responsive "Navigation Rail" sidebar.
* **Local Security:** All data is stored locally in an encrypted-ready SQLite database (`flux_crm.db`).

---

## 🚀 Getting Started (For Developers)

### Prerequisites
* **Flutter SDK:** ^3.0.0
* **Visual Studio 2022:** With "Desktop development with C++" workload (Required for Windows build).

### Installation
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/AAdelMM/simple_crm.git](https://github.com/AAdelMM/simple_crm.git)
    ```
2.  **Install dependencies:**
    ```bash
    flutter pub get
    ```
3.  **Run the app:**
    ```bash
    flutter run -d windows
    ```

---

## 📦 Production & Distribution

### Building the Executable (.exe)
To generate the standalone Windows version:
```bash
flutter build windows
