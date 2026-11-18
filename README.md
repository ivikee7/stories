# Centralized Stories & Screenplays Vault (Bilingual JSON Standard)

All stories are stored in **clean, structured JSON format containing BOTH Hindi (`hi`) and English (`en`)**, alongside cinematic visual prompts (`prompt`) and character audio definitions.

---

## 📚 Story Catalog

### 🦁 Folktales & Fables (`folktales_and_fables/`)
- [`the-lion-and-the-mouse.json`](folktales_and_fables/the-lion-and-the-mouse.json) — शेर और नन्हा चूहा (Hindi + English)
- [`the-tortoise-and-the-hare.json`](folktales_and_fables/the-tortoise-and-the-hare.json) — कछुआ और खरगोश (Hindi + English)
- [`the-mother-goat-and-the-tiger.json`](folktales_and_fables/the-mother-goat-and-the-tiger.json) — बुद्धिमान माँ बकरी और शेर (Hindi + English)
- [`bandar-aur-magarmach.json`](folktales_and_fables/bandar-aur-magarmach.json) — बंदर और मगरमच्छ की कहानी (Hindi + English)
- [`panchatantra-lion-and-clever-rabbit.json`](folktales_and_fables/panchatantra-lion-and-clever-rabbit.json) — भासुरक शेर और चतुर खरगोश (Hindi + English)
- [`the-clever-fox-and-the-wise-owl.json`](folktales_and_fables/the-clever-fox-and-the-wise-owl.json) — The Clever Fox and the Ancient Owl (Hindi + English)

### 🎙️ Modern & Tech Debates (`modern_and_tech_debates/`)
- [`ai-agents-developer-debate.json`](modern_and_tech_debates/ai-agents-developer-debate.json) — Will Autonomous AI Agents Replace Developers? (Hindi + English)

### 📋 Templates (`templates/`)
- [`story_template.json`](templates/story_template.json) — Standard bilingual JSON template for adding new stories.

---

## 🚀 Producing Videos Directly from Stories

```bash
# In ~/projects/ai-video-generation-project:

# 1. Produce in Hindi:
python3 tools/create_multicharacter_video.py --story the-lion-and-the-mouse --lang hi

# 2. Produce in English:
python3 tools/create_multicharacter_video.py --story the-lion-and-the-mouse --lang en
```
