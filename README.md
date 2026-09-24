# Relayeo Protocol — Sovereign Answer Engine Optimization (AEO)

[![AEO Protocol v1.0.0](https://img.shields.io/badge/AEO_Protocol-v1.0.0-0284c7.svg)](https://www.relayeo.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-emerald.svg)](LICENSE)
[![Website](https://img.shields.io/badge/Live_Engine-relayeo.com-38bdf8.svg)](https://www.relayeo.com)
[![CLI Tool](https://img.shields.io/badge/CLI-relayeo--audit-indigo.svg)](https://www.npmjs.com)

> **The Sovereign Machine Discovery & Entity Authority Protocol.**  
> Transform ambiguous marketing prose into deterministic, high-citation machine feeds for **ChatGPT Search**, **Perplexity Sonar**, **Google AI Overviews**, and **Claude**.

---

## ⚡ Quick Start: Audit Your Domain in 5 Seconds

Run the zero-dependency Relayeo AEO diagnostic tool directly in your terminal:

```bash
npx relayeo-audit yourcompany.com
```

Or run against any live domain:

```bash
# Audit Linear
npx relayeo-audit linear.app

# Audit Apollo Healthcare
npx relayeo-audit apollohealthcare.com
```

### Sample Terminal Output:

```text
▲ RELAYEO SOVEREIGN AEO AUDIT REPORT
───────────────────────────────────────────────────────────────────────
Target Entity:    linear.app (Linear)
Industry:         Developer Tooling & Issue Tracking
Composite Score:  94/100 [GRADE: A]
Perplexity Sonar: #1 Primary Cited Source (Zero Drift)
ChatGPT Search:   Primary Recommendation Authority (92% Share)
Edge Latency:     34ms (Sub-50ms target: PASSED)
───────────────────────────────────────────────────────────────────────
Verification: PASSED · Sovereign Entity Status Confirmed
Full Report:  https://www.relayeo.com/report/linear.app
```

---

## 🧠 Why AEO Matters in 2026: The Shift from Blue Links to Answers

Traditional SEO was built for a world of **10 blue links**. When users searched, Google returned a list of URLs, and users clicked through.

In 2026, **the discovery paradigm has permanently transformed**:
* **Conversational Synthesizers**: ChatGPT, Perplexity, Claude, and Gemini synthesize complete answers directly on-screen.
* **The 74% Vector Discard Rate**: Modern RAG (Retrieval-Augmented Generation) pipelines chunk web pages into 512-token embeddings. Fluffy marketing copy, hero banners, and unstructured text get discarded by embedding models.
* **Competitor Displacement**: When a prospect asks: *"What is the best alternative to Jira for fast engineering teams?"* — the AI engine does not show an ad. It cites **one single primary authority**. If your brand is not calibrated, your competitors get 100% of that qualified buyer intent.

---

## 📐 The Relayeo Architecture: The 4 Machine Pillars

Relayeo replaces guesswork with 4 deterministic machine files:

### 1. Canonical `/llms.txt` Manifest
Exposes your brand identity, transparent pricing, core capability, and API endpoints at the domain root in token-optimized plain text.
- See example: [`examples/llms-sample.txt`](examples/llms-sample.txt)

### 2. Disambiguated Schema.org `@graph`
Injects polymorphic, deeply nested JSON-LD schema with canonical W3C `@id` URI resolution. Prevents AI hallucination across multi-model crawls.
- See example: [`examples/schema-graph-sample.json`](examples/schema-graph-sample.json)

### 3. Autonomous Agent Manifest (`/.well-known/agent-manifest.json`)
Compliant with Agentic Discovery Protocol (ADP v2.0), allowing autonomous AI purchasing agents to understand your product, capabilities, and checkout endpoints without scraping.

### 4. Permissive AI `robots.txt` Directive
Explicitly grants indexing and token extraction permissions to frontier crawlers:
```text
User-agent: GPTBot
Allow: /
User-agent: ClaudeBot
Allow: /
User-agent: PerplexityBot
Allow: /
```

---

## 🔬 The 14-Point AEO Diagnostic Criteria

When you run `relayeo-audit`, your domain is evaluated against 14 mission-critical benchmarks:

| # | Criteria | Engine Impact | Target Benchmark |
| :--- | :--- | :--- | :--- |
| **01** | **Root /llms.txt Presence** | High RAG token retention | `200 OK` at `/llms.txt` |
| **02** | **Disambiguated Schema @graph** | Eliminates entity confusion | 3+ interconnected nodes |
| **03** | **Transparent Pricing Anchor** | Prevents AI pricing hallucination | Verifiable tier within 100 tokens |
| **04** | **Agent Manifest (ADP v2.0)** | Autonomous agent discoverability | `/.well-known/agent-manifest.json` |
| **05** | **Permissive AI Crawler Rules** | Guarantees crawl access | GPTBot & PerplexityBot allowed |
| **06** | **Sub-50ms Machine Latency** | Prevents crawler timeout | Edge CDN response < 50ms |
| **07** | **Zero-Click Extractability** | Answers rendered cleanly | 50-word declarative node |
| **08** | **Reverse-Vector Competitor Defense** | Displaces legacy incumbents | Explicit differentiator anchor |

---

## 🌐 Full Automated Platform & Live Scanners

To generate complete, copy-paste machine assets for your production domain, visit:

👉 **[https://www.relayeo.com](https://www.relayeo.com)**

* **Free Live Scanner**: Instant 14-point audit for any domain.
* **Autonomous Generator**: Compiles production-ready `/llms.txt`, Schema `@graph`, and `agent-manifest.json` in under 45 seconds.
* **Instant Deployment**: Copy and paste into Next.js, WordPress, Webflow, Shopify, or static sites.

---

## 📄 License

This open-source specification and diagnostic CLI are licensed under the **[MIT License](LICENSE)**.  
Built with sovereign engineering by **Ghanashyam Prabhakar** · [Relayeo.com](https://www.relayeo.com).
