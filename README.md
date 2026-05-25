# 🧮 Polirubro AI — Intelligent Pricing Agent & Simulator

An elegant, mobile-responsive intelligent pricing engine designed for small business commerce (Polirubros) in Argentina. It automates financial arithmetic, dynamic margin calculation, VAT injection, and localized cash rounding.

🚀 **Live Demo:** [polirubro-pricing-agent.vercel.app](https://polirubro-pricing-agent.vercel.app)

---

## 📌 Core Features
* **Automated VAT Handling:** Toggles between cost prices with or without tax, dynamically auto-calculating a 21% markup when required.
* **Dynamic Margin Breakdown:** Multi-category retail margin strategies (Librería 60%, Perfumería 50%, Regalería 80%, Sueltos 80%).
* **Smart Currency Rounding:** Custom algorithm (`redondear50`) designed specifically for Argentina's cash-flow reality, scaling final pricing to the nearest $50 increment.
* **Batch Processing Interface:** Allows operators to copy/paste unstructured raw listings (`product price`) and process entire inventories in a single click.
* **One-Click Clipboard Export:** Instantly formats results into clean, tab-separated structured data ready to paste into WhatsApp, Excel, or internal CRMs.

## 🛠️ Tech Stack & Architecture
* **Frontend & Logic:** Semantic HTML5, Mobile-First CSS3 (Variables, Custom Grid Systems).
* **Execution Engine:** Pure, Zero-Latency Vanilla JavaScript (ES6+).
* **CI/CD & Serverless Edge:** Automated integration with GitHub and Vercel Deployment Services.

## 🗺️ Roadmap: Turning this into a Cognitive Agent (GenAI)
The repository is structured to scale into a fully autonomous LLM-powered Agent. The next development phases include:
1.  **Unstructured Data Parsing (LLM):** Integrating an OpenAI/Gemini API backend to ingest chaotic, non-standardized invoice texts or supplier messages (e.g., *"Che, me llegaron 3 cajas de repuestos a 1500 c/u"*), automatically extracting entities and prices.
2.  **Autonomous Zero-Shot Classification:** Leveraging a Language Model to automatically assign the correct retail category/margin based purely on the item's semantic name.
