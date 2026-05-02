# XTrace MemHub — LLM-Wiki Mindmap Guide

Turn your **ChatGPT**, **Claude**, and **Gemini** history into an **Andrey Karpathy's LLM-Wiki mindmap** — structured Markdown you can browse in Obsidian-style tools and explore as a graph in MemHub.

**MemHub** is your context control panel for AI agents. This guide walks through exporting chat history, importing it into MemHub, exploring the **Mindmap**, and downloading a **Markdown ZIP** (“Mindmap Markdowns”) for your second brain — without writing code or using Claude Code.

MemHub extracts AI memory and context from your chats, stores it in an encrypted vector database, and organizes it in a file layout that tools like Obsidian work well with.

---

## Watch

[![Video walkthrough](https://img.youtube.com/vi/78CBcpO30v0/maxresdefault.jpg)](https://www.youtube.com/watch?v=78CBcpO30v0)

**[Open on YouTube →](https://www.youtube.com/watch?v=78CBcpO30v0)**
[![XTrace MemHub on Product Hunt](https://ph-files.imgix.net/fba354dc-f385-4538-8805-5e3e6e72cf09.png?auto=format&fit=crop&w=240&h=240)](https://www.producthunt.com/products/xtrace-memhub?utm_source=github&utm_medium=readme)

---

## Quick links

| Link | Description |
|------|-------------|
| [MemHub (sign in)](https://mem.xtrace.ai) | Web app |
| [MemHub Chrome extension](https://chromewebstore.google.com/detail/bmfpjofdjjelhnjokoolehikpaaohapj) | Capture context from the browser (including Gemini in-product) |

---

## End-to-end flow

1. **Export** your data from ChatGPT or Claude (see below).  
2. **Import** the file into MemHub (**Memories** → **Import Memory**).  
3. Wait for processing; your **Beliefs (Facts)** and **Artifacts** populate over time.  
4. Open the **Mindmap** tab to explore the graph (when enabled for your workspace).  
5. Click **Export** → **Export Markdown** → **Confirm export** to download a **ZIP of Markdown** for Obsidian / LLM-Wiki workflows.

Screenshots live in [`docs/screenshots/`](docs/screenshots/README.md) — add your own step images there and reference them from this README if you like.

---

## 1. Export from ChatGPT (OpenAI)

These steps match the in-product **Instructions** panel when **ChatGPT** is selected in MemHub.

1. Open ChatGPT in your browser.  
2. Go to **Settings** → **Data controls**.  
3. Click **Export data** and wait for the download.  
4. Extract the ZIP and find **`conversations.json`** inside the exported folder.

**Upload to MemHub:** either `conversations.json` or the whole export **`.zip`** (MemHub accepts `.json` and `.zip`).

Official reference: [OpenAI — Export your data](https://help.openai.com/en/articles/7260999-how-do-i-export-my-chatgpt-history-and-data).

---

## 2. Export from Claude (Anthropic)

These steps match the in-product **Instructions** panel when **Claude** is selected in MemHub.

1. Open Claude in your browser.  
2. Go to **Settings** → **Privacy**.  
3. Click **Export data** and wait for the download.  
4. Extract the ZIP and find **`conversations.json`**.

**Upload to MemHub:** same as ChatGPT — **`conversations.json`** or **`.zip`**.

Official reference: [Anthropic — Exporting your Claude data](https://support.anthropic.com/en/articles/7996846-how-can-i-export-my-claude-ai-data) (verify current UI labels in your account).

---

## 3. Gemini (Google)

Bulk ZIP import in the web UI is centered on **ChatGPT** and **Claude** exports today. For **Gemini** and other in-browser assistants, use the **[MemHub Chrome extension](https://chromewebstore.google.com/detail/bmfpjofdjjelhnjokoolehikpaaohapj)** to capture context as you chat, so memories accumulate in MemHub with **`gemini`** (and other) source labels — then use **Mindmap** and **Export Markdown** the same way.

For Google-wide exports, see Google’s account export tools (e.g. Google Takeout) and any Gemini-specific export options in your Google account settings; formats change over time, so prefer the extension for a repeatable MemHub path.

---

## 4. Export Markdown (LLM-Wiki ZIP)

1. On **Memories**, click **Export** (download icon).  
2. The modal title is **Export Markdown** — subtitle *ZIP for Mindmap Markdowns*.  
3. Adjust optional filters:
   - **Scope:** Beliefs (facts), Artifacts, Episodes  
   - **Date range** (leave empty for all time)  
   - **Platform:** memhub, chatgpt, gemini, claude, other  
   - **Belief type** / **Artifact type**  
   - **Content density:** Full (YAML + body) vs Compact  
   - **Link style:** Standard vs Relationship (wikilinks for supersession, linked facts, etc.)
   - We suggest keep everything as default
   <img width="2428" height="1193" alt="image" src="https://github.com/user-attachments/assets/20f01a01-f6e8-43f9-a783-03759bff6bbf" />

4. Click **Confirm export** and save the ZIP.  
5. Unzip into your Obsidian vault or any Markdown wiki.

---

## 5. View on Obsidian

1. Make sure your downloaded file is unzipped
2. Open your Obsidian app
3. On the top of the window, File -> Open Vault -> select the unzipped folder -> Open
<img width="645" height="406" alt="image" src="https://github.com/user-attachments/assets/e360d909-f4a4-4d4f-ad3e-aec04b5a995a" />
<img width="815" height="662" alt="image" src="https://github.com/user-attachments/assets/8ef02c38-e164-4b9f-901b-68eddd911e98" />
4. On the left sidebar, click Open graph view
   <img width="1501" height="882" alt="image" src="https://github.com/user-attachments/assets/5b4a3577-9ed2-4b4a-a6cc-da581ef61989" />


## License

Documentation in this repository is licensed under [CC BY 4.0](LICENSE).

**XTrace**, **MemHub**, and related trademarks belong to their owners. This repo is an unofficial community/education guide unless explicitly published by XTrace.
