<p align="center">
  <a href="https://opensource.finance">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://opensource.finance/logo.png">
      <img src="https://opensource.finance/logo.png" alt="opensource.finance" width="88" height="88" style="border-radius: 20px;">
    </picture>
  </a>
</p>

<h1 align="center">opensource.finance</h1>

<p align="center">
  <strong>Sovereign financial technologies for the next generation of fintech.</strong><br>
  Open-source infrastructure for financial vigilance — real-time transaction monitoring, AML/CFT rules, and AI compliance automation.
</p>

<p align="center">
  <a href="https://opensource.finance"><img src="https://img.shields.io/badge/website-opensource.finance-0A0A0A?style=flat-square&logo=safari" alt="Website"></a>
  <a href="https://opensource.finance/llms.txt"><img src="https://img.shields.io/badge/llms.txt-available-0A0A0A?style=flat-square" alt="llms.txt"></a>
  <a href="https://github.com/opensource-finance/osprey/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-Apache%202.0-0A0A0A?style=flat-square" alt="License"></a>
  <a href="https://huggingface.co/josephgoksu/osprey-narrator-v0.1"><img src="https://img.shields.io/badge/%F0%9F%A4%97%20HuggingFace-osprey--narrator-FFD21E?style=flat-square" alt="HuggingFace"></a>
  <a href="https://ollama.com/josephgoksu/osprey-narrator"><img src="https://img.shields.io/badge/%F0%9F%A6%99%20Ollama-osprey--narrator-black?style=flat-square" alt="Ollama"></a>
</p>

---

## 🦅 Osprey

Our flagship project. A single-binary, real-time transaction monitoring engine.

- **60-Second Deploy** — No Kubernetes. No microservices. Just download and run.
- **Secure by Design** — Built with lessons from protecting national payment rails.
- **Open Source** — Apache 2.0. Run it on your infrastructure. Own your data.

> *Transaction monitoring for everyone who isn't a bank.*

🔗 **[View Project →](https://github.com/opensource-finance/osprey)** • **[Quickstart Guide →](https://github.com/opensource-finance/osprey/blob/main/docs/QUICKSTART.md)**

---

## 🤖 Osprey Narrator

**AI-powered SAR narrative generation.** A fine-tuned LLM that transforms Osprey's raw alert output into structured, analyst-ready compliance narratives — replacing hours of manual report writing with seconds of inference.

- **Instant Narratives** — Feed it an Osprey alert JSON, get a complete SAR-style report
- **12 FATF Rules + 6 Typologies** — Full coverage of AML/CFT compliance framework
- **Run Anywhere** — Available as LoRA adapter (HuggingFace) or quantized GGUF (Ollama)
- **Trained on Synthetic Data** — No real customer data used, fully reproducible

> *From alert to narrative in seconds, not hours.*

**Get the model:**

| Platform | Link | Format |
|----------|------|--------|
| 🤗 HuggingFace | [josephgoksu/osprey-narrator-v0.1](https://huggingface.co/josephgoksu/osprey-narrator-v0.1) | LoRA adapter |
| 🦙 Ollama | [josephgoksu/osprey-narrator](https://ollama.com/josephgoksu/osprey-narrator) | Q4_K_M GGUF |

```bash
# Try it now with Ollama
ollama run josephgoksu/osprey-narrator
```

---

## 🎨 Studio

Visual rule IDE and simulation environment for Osprey rules. Compose CEL expressions visually, run test transaction payloads, and inspect match decisions in real-time.

---

## Our Heritage

We're engineers who built fraud detection systems for national payment infrastructure. Now we're making that same rigor accessible to everyone.

🌐 **[opensource.finance](https://opensource.finance)**

---

<p align="center">
  <a href="https://opensource.finance">Website</a> •
  <a href="https://github.com/opensource-finance/osprey">Osprey</a> •
  <a href="https://github.com/opensource-finance/osprey/blob/main/docs/QUICKSTART.md">Quickstart</a> •
  <a href="https://huggingface.co/josephgoksu/osprey-narrator-v0.1">HuggingFace</a> •
  <a href="https://ollama.com/josephgoksu/osprey-narrator">Ollama</a> •
  <a href="https://github.com/opensource-finance">All Repos</a>
</p>
