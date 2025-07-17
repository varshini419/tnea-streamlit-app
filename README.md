# 📊 TNEA 2025 Cutoff & Rank Finder App

This is a **Streamlit web application** that allows Tamil Nadu Engineering aspirants to easily access and compare TNEA 2025 cutoff ranks, community ranks, departments, and college zones.

---

## 🌟 Features

✅ Login-based access (Mobile Number + Password)  
✅ Search colleges by name, zone, community, or department  
✅ Compare up to 5 colleges side by side  
✅ Beautiful UI with color-coded rows  
✅ Hosted using [Streamlit Cloud](https://streamlit.io/cloud)

---

## 📂 Files in this Repo

| File | Purpose |
|------|---------|
| `app.py` | Main Streamlit app |
| `config.yaml` | User login data (mobile and password) |
| `requirements.txt` | Python libraries for deployment |
| `README.md` | This file |

---

## 🔐 User Login

Login credentials are stored in `config.yaml`. Format:

```yaml
credentials:
  users:
    "9876543210":
      password: "demo123"
    "8123456789":
      password: "user456"
