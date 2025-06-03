# Jakub Karafa's Umbrel Dev App Store

This is my **private Umbrel Community App Store** for development and testing purposes.
Apps in this repo may be unfinished, experimental, or unstable.

---

## 🚀 How to Add to Umbrel

Since this is a **private repo**, you must use a GitHub token to access it.

Paste this into the Umbrel App Store "Add Store" field:

```
https://jakubkarafa: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@github.com/jakubkarafa/umbrel-dev-app-store.git
```

> 🔐 Replace `<your-token>` with your actual [GitHub token](https://github.com/settings/tokens) generated for read-only access.

Make sure:

* The token has **read-only** access to this repo
* You keep this URL secure (do not share it publicly or commit it anywhere)

---

## 🛠️ App Naming Convention

All dev apps should use the following format for their IDs:

```
id: jakubkarafa-dev-<appname>
```

This avoids conflicts with stable versions and keeps dev apps isolated.

---

## ✅ Example Apps

* `jakubkarafa-dev-jupyter-lab`
* `jakubkarafa-dev-tandoor-recipes`

---

## 🔄 Reminder

This store is for **private use and testing only**.
It is not intended for public or production installations.

Keep access limited and rotate your token regularly if sharing within a team.
