# XTrace MemHub — LLM-Wiki Mindmap Guide

Turn your **ChatGPT**, **Claude**, and **Gemini** history into an **Andrey Karpathy's LLM-Wiki mindmap** — structured Markdown you can browse in Obsidian-style tools and explore as a graph in MemHub.

**MemHub** is your context control panel for AI agents. This guide walks through exporting chat history, importing it into MemHub, exploring the **Mindmap**, and downloading a **Markdown ZIP** (“Mindmap Markdowns”) for your second brain — without writing code or using Claude Code.

MemHub extracts AI memory and context from your chats, stores it in an encrypted vector database, and organizes it in a file layout that tools like Obsidian work well with.

---

## Watch

[![Video walkthrough](https://img.youtube.com/vi/78CBcpO30v0/maxresdefault.jpg)](https://www.youtube.com/watch?v=78CBcpO30v0)

**[Open on YouTube →](https://www.youtube.com/watch?v=78CBcpO30v0)**

[![XTrace MemHub on Product Hunt](https://api.producthunt.com/widgets/embed-image/v1/featured.svg?post_id=1136429&theme=light)](https://www.producthunt.com/products/xtrace-memhub?utm_source=badge-featured&utm_medium=badge&utm_campaign=badge-xtrace-memhub)

---

## Quick links

| Link | Description |
|------|-------------|
| [MemHub](https://mem.xtrace.ai) | Web app |
| [MemHub Chrome extension](https://chromewebstore.google.com/detail/bmfpjofdjjelhnjokoolehikpaaohapj) | Capture context from the browser (including Gemini in-product) |

---

## 1. Install the Chrome Extension

These steps match the in-product **Instructions** panel when **ChatGPT** is selected in MemHub.

1. Go to [MemHub Chrome extension](https://chromewebstore.google.com/detail/bmfpjofdjjelhnjokoolehikpaaohapj) 
2. Add XTrace Memory to your browser.  

---

## 2. Export from ChatGPT (OpenAI) / Claude (Anthropic) / Gemini (Google)

1. Open ChatGPT/Claude/Gemini in your browser.
2. Click the XTrace Memory extension in the Extensions.  
3. Sign in
4. You would see a **Memory** button at your top right, click it
5. Click export the last N chats you have. Recommend you to put a smaller number if you not sure how much

---

## 3. Go to MemHub and Wait

It could take a few minutes for AI to search through your data and extracts memories. Go to [MemHub](https://mem.xtrace.ai) to see your memories getting created in realtime

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
