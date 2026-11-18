# Story Archive & Screenplay Repository

Welcome to the centralized screenplay and story vault. All scripts are formatted in clean, human-readable Markdown with beat-by-beat visual prompts, multi-character dialogue cues, and YouTube packaging metadata.

---

## 📚 Story Catalog

| Story Title | Genre / Theme | Languages | Directory Path |
| :--- | :--- | :--- | :--- |
| **The Lion and the Mouse (शेर और नन्हा चूहा)** | Folktale / Fable | Hindi & English | [`folktales_and_fables/the-lion-and-the-mouse`](folktales_and_fables/the-lion-and-the-mouse) |
| **The Mother Goat and the Tiger (गौरी और शेरा)** | Folktale / Bravery | Hindi & English | [`folktales_and_fables/the-mother-goat-and-the-tiger`](folktales_and_fables/the-mother-goat-and-the-tiger) |
| **The Tortoise and the Hare (कछुआ और खरगोश)** | Classic Fable | Hindi & English | [`folktales_and_fables/the-tortoise-and-the-hare`](folktales_and_fables/the-tortoise-and-the-hare) |
| **The Monkey and the Crocodile (बंदर और मगरमच्छ)** | Panchatantra | Hindi | [`folktales_and_fables/bandar-aur-magarmach`](folktales_and_fables/bandar-aur-magarmach) |
| **The Innocent Donkey and Clever Goat (भोला गधा और चालाक बकरी)** | Folktale / Humor | Hindi & English | [`folktales_and_fables/bhola-gadha-aur-chalak-bakri`](folktales_and_fables/bhola-gadha-aur-chalak-bakri) |
| **The Clever Rabbit and King Lion (भासुरक शेर और चतुर खरगोश)** | Panchatantra | Hindi | [`folktales_and_fables/panchatantra-lion-and-clever-rabbit`](folktales_and_fables/panchatantra-lion-and-clever-rabbit) |
| **The Clever Fox and the Wise Owl** | Fable / Wisdom | English | [`folktales_and_fables/the-clever-fox-and-the-wise-owl`](folktales_and_fables/the-clever-fox-and-the-wise-owl) |
| **Will Autonomous AI Agents Replace Developers?** | Modern Tech Debate | English | [`modern_and_tech_debates/ai-agents-developer-debate`](modern_and_tech_debates/ai-agents-developer-debate) |

---

## 🎬 Screenplay Format Standard

Every markdown story follows this standardized structure:

```markdown
# Story Title

## Scene 1: Scene Name
[VISUAL: Cinematic description with camera angle, lighting, and style]

NARRATOR: Narrative beat setting the scene.
CHARACTER_NAME: Spoken dialogue line.
```

## 🚀 Running Production from Video Engine
You can directly produce videos from any script in this repository using the production engine:

```bash
# In ~/projects/ai-video-generation-project:
python3 tools/create_multicharacter_video.py --script /home/it/projects/stories/folktales_and_fables/the-lion-and-the-mouse/story_hi.md
```
