# LiraOS 🛸

**Assistant IA personnel pour le bureau** — un compagnon vocal, inspiré de LIRA, l'IA de bord *Star Citizen*. Tout est embarqué : pas de serveur, pas de Docker, rien à installer d'autre que l'application.

> Ce dépôt héberge uniquement les **versions téléchargeables** de LiraOS. Le code source est privé.

## ✨ Fonctionnalités

### Chat & IA
- 💬 **Chat multi-fournisseurs** en streaming : OpenRouter, Anthropic, OpenAI, Ollama (local)
- 🔌 **Tool calling** : l'IA peut appeler des outils automatiquement
- 🔢 **Suivi des tokens et du coût réel** de la session (`/token`)

### Voix
- 🔊 **Synthèse vocale** (Edge TTS) — voix naturelles, lecture dès la première phrase
- 🎤 **Reconnaissance vocale locale** (Whisper) — hors-ligne, avec **Push-to-Talk**

### Personnalités
- 🎭 **Multi-personas** : plusieurs IA, chacune avec son nom, avatar, voix, personnalité
- 🗂️ **World Info** : lore à tags, injecté selon les mots-clés (économise les tokens)
- 🖼️ **Avatars personnalisables** (IA et utilisateur)

### Outils
- 🚀 **UEX Corp (Star Citizen)** : prix des commodités, specs de vaisseaux, routes commerciales en temps réel
- 🎨 **Génération d'images** : OpenRouter, OpenAI (DALL·E / gpt-image), ou **Stable Diffusion local** (AUTOMATIC1111 / Forge, avec LoRAs) — via `/image` ou à la demande
- 🛠️ **Outils HTTP personnalisés** : branche n'importe quelle API

### Commandes & raccourcis
- ⚡ **Commandes vocales** (type Voice Attack) : mot-clé → action (texte, URL, appli, raccourci clavier)
- ⌨️ **Commandes slash** dans le chat (`/help`, `/stats`, `/persona`, `/image`…) avec **autocomplétion**
- 📌 **Réponses rapides** : boutons configurables au-dessus de la saisie

### Avancé
- 🔤 **Regex** (style SillyTavern) : transforme l'affichage et/ou le contexte envoyé à l'IA, indépendamment
- 🔄 **Mises à jour automatiques**

## 📥 Installation

1. Va dans [**Releases**](../../releases) et télécharge le dernier `LiraOS-Setup-x.y.z.exe`
2. Lance l'installeur (Windows peut afficher un avertissement « éditeur inconnu » : *Informations complémentaires* → *Exécuter quand même*)
3. À la première ouverture, va dans **Réglages** pour ajouter ta clé API et choisir ton modèle

Les versions suivantes s'installeront **automatiquement**.

## ⚙️ Configuration requise

- Windows 10 / 11 (64 bits)
- Une connexion internet et une clé API d'un fournisseur LLM (ex. [OpenRouter](https://openrouter.ai))
- (Optionnel) Un serveur Stable Diffusion local pour la génération d'images via LoRAs

---

*Projet personnel — distribué entre amis. 🚀*
