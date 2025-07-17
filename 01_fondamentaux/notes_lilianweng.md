# Lecture : Autonomous Agents (Lilian Weng, OpenAI)
📅 Date : [à remplir]

## 🔍 Objectif de la lecture

Comprendre la structure, la logique, les composants et les enjeux de la création d’un agent IA autonome.

---

## 🧠 Idées clés

- Les LLMs sont le cerveau des agents IA 
- Ces cerveaux sont connectés à 3 "parties" afin d'être un agent
- Ces 3 parties sont : la mémoire, la planification (des taches), les outils
- Cachunes de ces parties est divisible en sous parties
- La mémoire : courte (le contexte qui a une taille finie), longue (mémoire infinie mais plus compliquée à utiliser car il faut "chercher" dans la mémoire pour retrouver des informations)
- La planification : cela permet de diviser un gros objectif complexe en de multiples petits sous objectifs afin de simplifier la réalisation de l'objectif initial
Inclusion de la self-reflection dans la planification afin d'évaluer la planification
- les outils : ils sont appelés par le LLM afin de l'aider à résoudre les problèmes de l'utilisateur 
- Un agent IA fonctionne souvent en boucle : il observe → raisonne → agit → observe les résultats → etc.
Ce n’est pas une simple requête LLM, mais une séquence récurrente et dynamique.
## 🧠 Idées clés enrichies

- Les LLMs sont le cerveau des agents IA : ils analysent, planifient, décident.
- Pour devenir "agents", ils doivent être connectés à :
  - 🧠 une mémoire (court terme = contexte limité ; long terme = historique global avec récupération active)
  - 📋 un planificateur (pour diviser une tâche complexe en sous-tâches autonomes)
  - 🛠️ des outils (navigateurs, APIs, bases de données, fonctions custom…)
- Ces composants permettent à l’agent d’agir en boucle :
  → observer → raisonner → agir → observer → ajuster
- La planification peut inclure la *self-reflection*, pour améliorer les résultats ou corriger les erreurs.
- L’agent devient ainsi autonome et évolutif, en apprenant de ses erreurs et en adaptant ses actions.


---

## 🧩 Architecture d’un agent

- 🎯 Objectif : ...
- 🔁 Boucle perception → décision → action : ...
- 🧰 Tools : ...
- 🧠 Memory : ...
- 🧠 Planning : ...
- 📦 Long-term memory / task management : ...

---

## 🧭 Ce que j’ai appris

- (Tes propres mots, même approximatifs. Tu peux résumer ce que tu “ressens avoir compris”)

---

## ❓Questions / doutes à creuser

- (Tu peux mettre ici des zones floues, concepts à revoir ou exemples manquants)

---

## 🔗 Liens connexes / extraits utiles

- [Autonomous Agents - Lilian Weng](https://lilianweng.github.io/posts/2023-06-23-agent/)
