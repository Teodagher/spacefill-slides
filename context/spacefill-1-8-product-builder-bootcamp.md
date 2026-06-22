# Spacefill — Session 1/8 · Product Builder AI Bootcamp

> **Source :** Canva "Spacefill - 1/8 Product Builder AI Bootcamp" (51 pages) · Instructeur : Téo Dagher
> **Footer récurrent :** `S15 - Teo Dagher | iq-project.ai`
>
> **À savoir pour la régénération :**
> - Chaque slide a un emplacement image (`images/slide-XX.png`) — remplace par tes exports manuels.
> - Plusieurs liens du deck original sont des **artefacts de find-and-replace** : le texte affiche "claude" mais l'URL pointe ailleurs (ex. `claude.dev` → `lovable.dev`, `claude.new` → `bolt.new`). Conservés tels quels ci-dessous, à nettoyer si besoin.
> - Le découpage en slides est reconstruit à partir du dump texte plat de Canva (pas de frontières de page natives) : fidèle au contenu, l'alignement exact des numéros peut varier de ±1.

---

## Slide 01 — Couverture
- **IQ-Project.ai**
- **1/8 — Product Builder AI Bootcamp**
- Téo Dagher — *AI Product Engineer*

![slide-01](images/slide-01.png)

---

## Slide 02 — Ice-breaker
**Let's get to know each other.**

- Je suis …
- Je viens pour …
- Je repars avec …

*Three words or very short phrases.*

![slide-02](images/slide-02.png)

---

## Slide 03 — L'équipe
**Made by builders, for builders.**

- **Jade Dagher** — Co-founder IQ Education
- **Ouahid Bendaoud** — Security Engineer & Coach @IQ Project
- **Téo Dagher** — Builder & Founder @Astry Agency & Coach @IQ Project
- **Maxime Bournez** — Co-founder & Coach @IQ Project

![slide-03](images/slide-03.png)

---

## Slide 04 — Astry.agency
- Astry.agency

![slide-04](images/slide-04.png)

---

## Slide 05 — Instructeur de la saison
**Season 15 instructor : Téo**

![slide-05](images/slide-05.png)

---

## Slide 06 — Roadmap : 8 sessions to NAIL it 💅
| Session | Contenu |
|---|---|
| **S1** | Start · User flow · Master Prompt · First shot |
| **S2** | Core feature · Prompting · Hack · Iteration ×3 |
| **S3** | API · MCP · Iteration ×4 |
| **S4** | Claude Code Setup · Vibe coding Flow · Iteration ×4 |
| **S5** | Sécurité · Deploy · DNS · Perf · Iteration ×4 |
| **S6** | How to Pitch a Product · Reddit post · First user Traction ? |
| **S7** | Certification · Demo Day · Drink |
| **S8** | Demo Day · Drink |

![slide-06](images/slide-06.png)

---

## Slide 07 — Geniuses
**Geniuses**

![slide-07](images/slide-07.png)

---

## Slide 08 — Geniuses (galerie)
- Leonardo da Vinci
- Isaac Newton
- Albert Einstein
- Alan Turing

![slide-08](images/slide-08.png)

---

## Slide 09 — AI : Input → Output
- **AI**
- Input → Output

![slide-09](images/slide-09.png)

---

## Slide 10 — AI : la question
- **AI** — *What color is a kiwi ?*

![slide-10](images/slide-10.png)

---

## Slide 11 — AI : l'ambiguïté
- *What color is a kiwi ?*
- The kiwi is a brown bird, ranging from light to dark
- ?? ....
- **50:50**

![slide-11](images/slide-11.png)

---

## Slide 12 — LLMs (Large Language Models)
**LLM = Data + Architecture + Training**

- ex : GPT-3.5 → 45 To de data
- ex : architecture GPT = *transformer* (175 milliards de paramètres) — GPT-5 : 635
- Les transformers sont conçus pour comprendre le contexte de chaque mot d'une phrase en considérant sa relation avec tous les autres mots → compréhension globale de la structure et du sens.
- Les transformers sont ensuite entraînés sur cette grande quantité de data. Pendant l'entraînement, le modèle apprend à prédire le mot suivant :
  1. Kiwis are bad
  2. Kiwis are big
  3. Kiwis are green
- ☁️ **En équivalent cloud, 45 To c'est :**
  - 90 000 heures de vidéo
  - 9 millions de fichiers Word
  - 10 millions de photos de smartphone

![slide-12](images/slide-12.png)

---

## Slide 13 — AI : la réponse probable
- *What color is a kiwi ?* → **Output 96 %**
- "The classic kiwi is brown on the outside and green on the inside, but variations exist! 🍃🥝"
- The model often chooses a word near the center of the distribution.
- Modèle : **GPT-4o**

![slide-13](images/slide-13.png)

---

## Slide 14 — Reasoning Models
**Reasoning Models**

![slide-14](images/slide-14.png)

---

## Slide 15 — AI vs AI Agent
- **Genius** → A genius supported by a multi-skilled team
- While AI can be just the "thinking" part, an AI Agent is the "thinking + doing" part that uses its smarts to take action.

![slide-15](images/slide-15.png)

---

## Slide 16 — Agent example
- **Agent example**
- Your turn 🫵

![slide-16](images/slide-16.png)

---

## Slide 17 — 5 AI Agent components
**AI Agent — 5 composants**

- Instruction
- Outils & Actions
- Database
- Memory
- *(+ l'agent lui-même)*

![slide-17](images/slide-17.png)

---

## Slide 18 — AI Agent (mapping concret)
| Composant | Notre stack |
|---|---|
| Online code editor | — |
| LLM | Claude OPUS 4.7 |
| Utilisateur | You ! |
| Database | Database |
| Instruction / contexte | Context Window of your prompt |

![slide-18](images/slide-18.png)

---

## Slide 19 — Ce qu'on va faire
- Basically, we're going to use a developer AI agent.
- **Target :** Create the first screen of your app

![slide-19](images/slide-19.png)

---

## Slide 20 — Anatomie du prompt
- Context Window of your prompt
- Prompt
- Online Code Editor
- LLM : **OPUS 4.5**

![slide-20](images/slide-20.png)

---

## Slide 21 — AI Agent VS Multi AI Agent
- **AI agent** : Input → Output
- **Multi AI Agent** : Input → (agent 1 · agent 2 · agent 3 · agent 4 · agent 5) → Output

![slide-21](images/slide-21.png)

---

## Slide 22 — Exemple : Partoo
- Exemple : **Partoo** — Multi agent "Jim"

![slide-22](images/slide-22.png)

---

## Slide 23 — Le bon timing
- **Congrats! You're about to discover something big**
- Now is the time to build before everyone jumps in and the number of SaaS solutions skyrockets.

![slide-23](images/slide-23.png)

---

## Slide 24 — The IQ Method (KISS)
1. Start with an Idea (5 min) — [IQ Project Master Prompt](https://chatgpt.com/g/g-681c7a321cd8819192284799dd92fbce-iq-project-master-prompt)
2. Design your user flow, focus on the core idea (30 min) — [whimsical.com](https://whimsical.com)
3. Build the master prompt by hand, 2 pages (~2h) — [dribbble.com](https://dribbble.com)
4. Find design inspiration, think shapes/colors (5 min) — [dribbble.com](https://dribbble.com)
5. Give your master prompt to Claude, include userflow, design inspo and select a theme
6. Let Claude build it out !
7. Test, iterate, repeat. DO NOT be afraid to break stuff.

![slide-24](images/slide-24.png)

---

## Slide 25 — The IQ Method (KISS) — variante "JK"
1. Start with an Idea (5 min) — [IQ Project Master Prompt](https://chatgpt.com/g/g-681c7a321cd8819192284799dd92fbce-iq-project-master-prompt)
2. Design your user flow, focus on the core idea (30 min) — [whimsical.com](https://whimsical.com)
3. *JK, ChatGPT will do it with this tool* 👇
4. Find design inspiration, think shapes/colors (5 min) — [dribbble.com](https://dribbble.com)
5. Give your master prompt to Claude, include userflow, design inspo and select a theme — [whimsical.com](https://whimsical.com)
6. Let Claude build it out !
7. Test, iterate, repeat. DO NOT be afraid to break stuff.

![slide-25](images/slide-25.png)

---

## Slide 26 — What are we building ?
- **What are we building ?**
- But first !

![slide-26](images/slide-26.png)

---

## Slide 27 — 💻 VS. 📱
**The Dream Vs. Reality**

- "I want to build a mobile app"
- "You probably shouldn't build a mobile app"

![slide-27](images/slide-27.png)

---

## Slide 28 — Web Apps Vs. Mobile Apps
- Both are valid, but one is faster to start.

![slide-28](images/slide-28.png)

---

## Slide 29 — Should it be a mobile app ? (1/2)
**Ask :**
- Is my primary user going to be on a mobile device ?
- Is your target user looking for your product on an app store ?

→ If **no** → Build a web app first
→ If **yes** → Okay, but you have been warned 😅

*You can always build a mobile app later, once you have users.*

![slide-29](images/slide-29.png)

---

## Slide 30 — Should it be a mobile app ? (2/2)
**Ask :**
- Does it need realtime GPS ? Camera ? Push notifications ?
- Does it absolutely need to work offline ?
- Will consumers use it multiple times a day ?
- Does your product lose all its value if it is not a mobile app ?

→ If **no** → Build a web app first
→ If **yes** → Okay, but you have been warned 😅

*You can always build a mobile app later, once you have users.*

![slide-30](images/slide-30.png)

---

## Slide 31 — 1) User Flow
- Onwards ! →
- **1) User Flow**
- Your turn 🫵
- **FOCUS ON CORE FEATURE**

![slide-31](images/slide-31.png)

---

## Slide 32 — Example : User flow
- Example — User flow
- [Référence : podcast GDIY — Stanislas Niox-Château](https://www.gdiy.fr/podcast/stanislas-niox-chateau/)

![slide-32](images/slide-32.png)

---

## Slide 33 — User flow (schéma)
*(slide visuelle — schéma de user flow)*

![slide-33](images/slide-33.png)

---

## Slide 34 — Every user flow starts like this
- Every user flow starts like this
- [Référence : podcast GDIY](https://www.gdiy.fr/podcast/stanislas-niox-chateau/)

![slide-34](images/slide-34.png)

---

## Slide 35 — 2) Design inspiration (Dribbble)
- **2) Find design inspiration on Dribbble**
- Your turn 🫵
- Take a screenshot

![slide-35](images/slide-35.png)

---

## Slide 36 — 3) Build your master prompt
- **3) Build your master prompt**
- Your turn 🫵
- GPT's > "IQ Project - Master Prompt"

![slide-36](images/slide-36.png)

---

## Slide 37 — 5) Claude Permissions
- **5) Claude Permissions**
- Supabase > settings > connectors > claude cloud > permissions > Enable Cloud "Never Allow"

![slide-37](images/slide-37.png)

---

## Slide 38 — 5.5) Connect GitHub
- **5.5) Connect GitHub**
- Supabase > settings > connectors > browse connectors > supabase > connect supabase > sign in with GitHub

![slide-38](images/slide-38.png)

---

## Slide 39 — 5.5) Connect Supabase
- **5.5) Connect Supabase**
- Supabase > settings > connectors > browse connectors > supabase > connect supabase > sign in with GitHub

![slide-39](images/slide-39.png)

---

## Slide 40 — Récap avant build
- Votre user flow
- Votre inspiration design
- Le master prompt en format markdown
- **2 : Master Prompt → Claude**
- Don't forget this :
  - 👉 Add your user journey flow
  - 👉 Add your design from Dribbble

![slide-40](images/slide-40.png)

---

## Slide 41 — 9) Copy/Paste Master Prompt into Claude
- **9) Copy Paste Master Prompt into Claude**
- https://claude.dev/?via=productbuilders *(artefact : pointe en réalité vers lovable.dev)*

![slide-41](images/slide-41.png)

---

## Slide 42 — Do you have any idea ?
- Do you have any idea ?
- [Référence : podcast GDIY](https://www.gdiy.fr/podcast/stanislas-niox-chateau/)

![slide-42](images/slide-42.png)

---

## Slide 43 — (visuel)
*(slide visuelle)*

![slide-43](images/slide-43.png)

---

## Slide 44 — Your Turn 🫵
- **Your Turn 🫵**

![slide-44](images/slide-44.png)

---

## Slide 45 — La plateforme IQ
- Voir les cours
- Suivre votre avancement
- Voir le programme
- Accès au playground

![slide-45](images/slide-45.png)

---

## Slide 46 — RDV
- **RDV > app.iq-project.ai**

![slide-46](images/slide-46.png)

---

## Slide 47 — Connect to GitHub
- **Connect to GitHub**

![slide-47](images/slide-47.png)

---

## Slide 48 — Our virtual office
- **Our virtual office**
- (MVP) < 500 users → Do we still need a tech team ? → **No**
- \> 500 users → **Yes**
- Users

![slide-48](images/slide-48.png)

---

## Slide 49 — Time to build live ! (ressources)
- 👉 Faire le perfect prompt : [IQ Project Master Prompt](https://chatgpt.com/g/g-681c7a321cd8819192284799dd92fbce-iq-project-master-prompt)
- 👉 Trouver LA core feature : [IQ Project Core Feature Finder](https://chatgpt.com/g/g-681c8c380b10819185f83697146836e8-iq-project-core-feature-finder)
- 👉 Base de données gratuite Firebase : [console.firebase.google.com](https://console.firebase.google.com)
- 👉 Base de données gratuite Supabase : [supabase.com](https://supabase.com)
- 👉 Interface exemple : [dribbble.com](https://dribbble.com)
- 👉 2 codes couleur : [htmlcolorcodes.com](https://htmlcolorcodes.com)
- 👉 Stocker des ressources visuelles : [Cloudinary](https://console.cloudinary.com)
- 👉 Clé API OpenAI : [platform.openai.com](https://platform.openai.com)
- 👉 Claude / Bolt : [claude.new](https://bolt.new/?rid=btxxu6) *(artefact : pointe vers bolt.new)*
- 👉 Claude / Lovable : [claude.dev](https://lovable.dev/?via=productbuilders) *(artefact : pointe vers lovable.dev)*

![slide-49](images/slide-49.png)

---

## Slide 50 — Status board (Kanban)
- ✅ Done
- 🔄 En cours
- ❌ Ne fonctionne pas
- 🆘 Je suis bloqué

![slide-50](images/slide-50.png)

---

## Slide 51 — Clôture
- **app.iq-project.ai**
- **S15 Product Builder Bootcamp**
- Prochaines étapes : LA core feature — 2ème itération

![slide-51](images/slide-51.png)
