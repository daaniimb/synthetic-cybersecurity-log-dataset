# 🛡️ Synthetic Cybersecurity Log Dataset (Free Sample)

A high-fidelity, GDPR-compliant synthetic log dataset tailored for security analytics, big data benchmarks, and threat intelligence testing. 

This repository contains a **free sample of 100 logs** to demonstrate the data structure, schema quality, and realistic attack simulation.

---

## 🚀 Need More Data? Choose Your Pack!
If you are running heavy load tests, training AI models, or benchmarking high-throughput platforms, 100 logs won't be enough. We offer flexible packages tailored to your project scale:

### 📊 Pricing & Packages
* **📦 Starter Pack (10,000+ rows):** **€29** — Perfect for quick schema testing and local script validations.
* **📈 Growth Pack (50,000+ rows):** **€69** — Ideal for mid-scale ingestion pipelines and dashboard setup.
* **⚡ Enterprise Pack (100,000+ rows):** **€99** *(Best Value)* — Designed for heavy stress testing, performance benchmarks, and realistic simulation environments.

* **Instant Download:** Automated delivery via Lemon Squeezy.
* **Production Ready:** Plug and play `.json` format into your data pipelines.

👉 **TO DOWNLOAD YOUR PACK CONTACT ME ON LINKEDIN: [LinkedIn Profile](https://www.linkedin.com/in/daniel-miera-bautista-2822662b3/)**

---

## 📊 Dataset Features & Schema

This dataset simulates real-world web application traffic and infrastructure telemetry, embedding sophisticated cyber attack vectors seamlessly.

### Simulated Attack Vectors Included:
* **SQL Injection (SQLi)**
* **Shellshock Vulnerability Exploitation**
* **Path Traversal / Directory Traversal**
* **Brute Force Attacks (via Hydra, etc.)**

### Key Advantages:
* **100% GDPR-Compliant:** Generated entirely from scratch. No real user data, no privacy liabilities, no compliance friction.
* **Built-in Privacy Best Practices:** Includes pre-computed fields like `datos_limpios` demonstrating automated IP obfuscation and credential redacting (`REDACTED`).
* **Technical Explanations:** Every attack vector includes a `explicacion_tecnica` field in Spanish, making it perfect for training environments or SOC analyst onboarding.

---

## 🛠️ Data Schema Example

Here is a quick look at how the JSON structured logs look:

```json
{
  "index": 1,
  "original": "174.130.28.183 - - [2026-06-09T11:17:45.536Z] \"POST /api/users/profile HTTP/1.1\" 401 234 \"user=1500&pass=admin123\" \"Hydra/v9.5 Bruteforce\"",
  "error": null,
  "datos_limpios": "IP_PRIVADA - - [2026-06-09T11:17:45.536Z] \"POST /api/users/profile HTTP/1.1\" 401 234 \"user=REDACTED&pass=REDACTED\" \"Hydra/v9.5 Bruteforce\"",
  "categoria": "security",
  "severidad": "critica",
  "explicacion_tecnica": "Intento de ataque de fuerza bruta detectado contra endpoint de autenticación con herramienta Hydra, credenciales inválidas (401)."
}
