# TV Store Data Feed

Welcome to the official public repository for the **TV Store** App Catalog (part of the **TV Brew** ecosystem). 

Any developer can submit their Android TV apps to be listed in the store. Submissions must be done via a **Pull Request** and must strictly follow the directory structure and security requirements below. All applications must be placed inside the `apps` folder.

---

## ⚠️ Important Disclaimer for Users
Apps listed here are submitted by the community. They are **not automatically verified** by the TV Store administration unless specifically marked with a verification badge in the app. Install and use them at your own risk.

---

## 📁 Required Directory Structure

To list your app, your submission must be placed inside the `apps/` directory and follow this exact structure:

```text
apps/
└── [Your-App-Name]/
    ├── apk/
    │   └── app.apk
    └── info/
        ├── description.txt
        └── privacy.txt
```

### 🔹 1. The APK Folder (`/apk/`)
* Contains your compiled Android application package.
* **Requirement:** The file must be named exactly **`app.apk`** (lowercase).

### 🔹 2. The Info Folder (`/info/`)
This folder must contain exactly two configuration files:

#### `description.txt`
The first line must be the official display name of your app. Everything below is the description shown on the TV screen.
```text
[Your App Name]
This is a short, concise description of what your Android TV application does and its main features.
```

#### `privacy.txt` (Data Safety Requirements)
For security and privacy transparency, you **must** answer the following data questions exactly using this template:
```text
DATA_COLLECTED: [Yes / No]
DATA_STORAGE_COUNTRY: [e.g., Germany / USA / None]
DATA_DELETION_REQUEST: [Yes / No / Link to deletion form]
```

---

## 🚀 How to Submit

1. **Fork** this repository.
2. Navigate to the `apps/` directory and create a new folder for your app following the structure above.
3. Upload your `app.apk`, `description.txt`, and `privacy.txt`.
4. Open a **Pull Request** (PR) to the main repository.

Once the PR is merged, your app will instantly become visible and installable on all TV Store devices worldwide.
