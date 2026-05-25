# 🧮 Polirubro AI — Intelligent Pricing Agent & Simulator

[English Version Below]

Un motor inteligente de cálculo de precios y simulador financiero, diseñado con enfoque mobile-first para comercios minoristas (polirubros) en Argentina. Automatiza la aritmética financiera, la inyección de IVA, el cálculo de márgenes dinámicos y el redondeo adaptado al flujo de caja local.

🚀 **Demo en Vivo:** [polirubro-pricing-agent.vercel.app](https://polirubro-pricing-agent.vercel.app)

---

## 📌 Características Principales
* **Gestión Automatizada de IVA:** Alterna entre precios de costo con o sin impuesto, auto-calculando el 21% de recargo de forma exacta cuando es requerido.
* **Desglose de Márgenes Dinámicos:** Aplica estrategias de recargo minorista por categorías preconfiguradas (Librería 60%, Perfumería 50%, Regalería 80%, Sueltos 80%).
* **Redondeo Monetario Inteligente:** Algoritmo personalizado (`redondear50`) diseñado específicamente para la realidad del manejo de efectivo en Argentina, aproximando el precio final a incrementos de $50.
* **Interfaz de Procesamiento por Lotes (Batch):** Permite al operador copiar y pegar listados de texto plano desestructurados (`producto precio`) y procesar inventarios enteros en un solo clic.
* **Exportación al Portapapeles:** Formatea instantáneamente los resultados en datos estructurados limpios (separados por tabulaciones), listos para pegar en WhatsApp, Excel o sistemas internos.

## 🛠️ Stack Tecnológico y Arquitectura
* **Frontend y Lógica:** HTML5 semántico, CSS3 Responsivo (Variables nativas, Sistemas de Grid personalizados).
* **Motor de Ejecución:** JavaScript Vanilla puro (ES6+), garantizando latencia cero en el cliente.
* **CI/CD y Servidores Edge:** Integración automatizada con servicios de despliegue continuo entre GitHub y Vercel.

## 🗺️ Roadmap: Evolución hacia un Agente Cognitivo (GenAI)
El repositorio está estructurado para escalar hacia un Agente Autónomo potenciado por modelos de lenguaje (LLMs). Las próximas fases de desarrollo incluyen:
1.  **Parseo de Datos No Estructurados (LLM Backend):** Integración de la API de OpenAI/Gemini para procesar textos caóticos de proveedores o mensajes de WhatsApp (ej: *"Che, me llegaron 3 cajas de repuestos a 1500 c/u"*), extrayendo automáticamente entidades y costos.
2.  **Clasificación Autónoma Zero-Shot:** Uso de modelos fundacionales para asignar automáticamente la categoría y el margen minorista correcto basándose puramente en el análisis semántico del nombre del producto.

---

# 🇺🇸 English Version

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
1.  **Unstructured Data Parsing (LLM):** Integrating an OpenAI/Gemini API backend to ingest chaotic, non-standardized invoice texts or supplier messages, automatically extracting entities and prices.
2.  **Autonomous Zero-Shot Classification:** Leveraging a Language Model to automatically assign the correct retail category/margin based purely on the item's semantic name.
