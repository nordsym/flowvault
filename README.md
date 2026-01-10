# FlowVault

n8n workflow library powering [flowvault.se](https://flowvault.se) - NordSym's curated marketplace för produktionsklara automationer.

## 📦 What's Here

150+ battle-tested n8n workflows from community creators and YouTube tutorials. Each workflow is:
- ✅ Validation-ready (use with NordSym MCP tools)
- 📊 Metadata-enriched (complexity, nodes used, use case)
- 🎯 Categorized for quick discovery

**Note:** These raw workflow files are available here for direct import. For searchable marketplace, metadata, and PRO features → [flowvault.se](https://flowvault.se)

## 🔥 Live Product

**FlowVault.se** - n8n marketplace
- **Free tier:** Browse & download workflows via UI
- **PRO (299 SEK/mån):** Priority support, custom templates, early access
- **Current MRR:** ~100 SEK (1 PRO user, 5 FREE trials)

## 🏗️ Architecture

Workflow repository powers:
1. [flowvault.se](https://flowvault.se) marketplace frontend
2. n8n MCP search tools (`search_templates`, `get_template`)
3. Internal NordSym automation library

## 📂 File Naming

YouTube video ID format: `{video_id}_{part_number}.json`
- Example: `0qf0blCB4Mc_1.json` = First workflow from YouTube video `0qf0blCB4Mc`
- Multi-part videos numbered sequentially

## 🚀 Usage

```bash
# Clone repo
git clone https://github.com/nordsym/flowvault.git

# Import to n8n
# Copy any .json file → Import in n8n UI
```

**Want metadata, search, and categorization?** → Use [flowvault.se](https://flowvault.se) instead.

## 🛠️ Tech Stack

- **Source:** Community n8n workflows (YouTube, forums, GitHub)
- **Validation:** NordSym n8n MCP tools
- **Frontend:** [flowvault.se](https://flowvault.se)
- **Backend:** n8n Cloud (nordsym.app.n8n.cloud)

## 📊 Stats

- **Workflows:** 150+
- **Categories:** API integrations, data processing, webhooks, AI automation, notifications
- **Average complexity:** Medium (5-15 nodes)
- **Live since:** Dec 2024

## 🎯 Purpose

Lead generation engine for NordSym custom automation. Users discover workflows → need custom implementation → contact NordSym for 60-120k SEK projects.

## 🔗 Links

- **Live site:** https://flowvault.se
- **NordSym:** https://nordsym.com
- **Support:** info@nordsym.se

---

**Built by NordSym AB** | Stockholm | 559535-5768
