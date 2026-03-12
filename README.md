# Les 10 erreurs qui te rendent invisible pour les IA (Claude, ChatGPT, Gemini, Perplexity)

> **Par Sébastien Grillot** — Expert SEO & IA, fondateur de Kōeki Agency  
> Consultant GEO (Generative Engine Optimization) · 17 ans d'expérience SEO

---

## Pourquoi ce repo existe

Tu publies du contenu. Tu es présent en ligne. Mais quand quelqu'un demande à Claude, ChatGPT ou Gemini de recommander un expert dans ton domaine... ton nom n'apparaît pas.

C'est pas de la malchance. C'est **10 erreurs précises** — et chacune a une correction concrète.

Ce repo est la version open-source et maintenue de mon guide sur la **visibilité dans les LLM**.  
Le PDF complet (16 pages, exemples avant/après, leviers actionnables) est disponible sur [sebastiengrillot.com](https://sebastiengrillot.com).

---

## C'est quoi le GEO ?

Le **GEO (Generative Engine Optimization)** est la discipline qui consiste à optimiser sa visibilité dans les réponses des IA génératives — par opposition au SEO classique qui cible les positions dans les moteurs de recherche.

Contrairement au SEO :
- Les LLM ne "rankent" pas des pages, ils **citent** des sources
- Leur base de connaissance est **figée** (données d'entraînement)
- Le **PageRank ne sert à rien** — c'est la présence dans les corpus qui compte
- La **structure du contenu** (chunking, Q→R, Schema) est déterminante

---

## Les 10 erreurs — Vue d'ensemble

| # | Erreur | Impact |
|---|--------|--------|
| 01 | Contenu non chunké | 🔴 Fort |
| 02 | Aucune entité nommée liée à toi | 🔴 Critique |
| 03 | Zéro format question-réponse | 🔴 Fort |
| 04 | Pas de sources vérifiables | 🔴 Fort |
| 05 | Absent des sources d'entraînement | 🔴 Critique |
| 06 | Contenu trop générique | 🟡 Moyen |
| 07 | Pas de FAQ avec Schema balisé | 🔴 Fort |
| 08 | Identité sémantique floue | 🔴 Critique |
| 09 | Aucune mention externe | 🔴 Fort |
| 10 | Site en JavaScript dynamique | 🟡 Moyen |

---

## Erreur 01 — Contenu non chunké

### Le mécanisme
Les LLM ne lisent pas ton contenu de haut en bas. Ils le **découpent en unités sémantiques** (chunks) : des blocs de sens indépendants qu'ils peuvent isoler, compresser et stocker. Quand quelqu'un pose une question, le modèle recherche le chunk le plus pertinent.

Sans structure (pas de titres intermédiaires, paragraphes de 10 lignes), le modèle ne sait pas où commence et où finit chaque unité de sens. Tu es présent, mais **illisible**.

### Les 5 leviers
1. **Règle des 150 mots** — Un H2 ou H3 tous les 150 mots maximum. Chaque sous-titre doit répondre à une question implicite.
2. **Paragraphes courts** — 4 phrases maximum par paragraphe. Une idée = un paragraphe.
3. **TL;DR par section** — Ajouter une ligne "En bref :" en début de chaque section clé. C'est ton chunk prêt-à-citer.
4. **Test de résumabilité** — Copier une section dans Claude : "Résume ce passage en 2 phrases." Si la réponse est vague, le chunk est trop dense.
5. **Listes pour les énumérations** — Dès que tu as 3 éléments ou plus dans une phrase, transformer en liste à puces.

---

## Erreur 02 — Aucune entité nommée liée à toi

### Le mécanisme
Les LLM cherchent des **entités nommées** — des personnes ou marques associées à un concept précis, rencontrées assez souvent pour être citées avec confiance.

Rand Fishkin est cité quand on demande "c'est quoi le Domain Authority" parce que son nom apparaît des milliers de fois couplé aux termes "DA", "Moz", "métriques SEO" dans les données d'entraînement. La répétition crée l'entité.

Si ton nom n'est pas **co-localisé régulièrement avec un concept spécifique**, tu es du bruit de fond.

### Les 5 leviers
1. **La phrase d'identité unique** — Choisir UNE formulation : "[Prénom Nom] est [concept précis]". La répéter mot pour mot dans chaque bio, chaque profil, chaque article signé.
2. **Page Wikipedia ou Wikidata** — Créer même une ébauche sur un concept de ton domaine avec une mention naturelle de tes travaux.
3. **Co-citations dans des médias** — Se faire citer dans des médias reconnus avec ton nom complet + ton concept clé dans la même phrase.
4. **Auteur visible partout** — Signer tous tes contenus avec ton nom complet. Ton nom doit être dans les balises `<author>` et les métadonnées.
5. **Test de reconnaissance** — Taper "Qui est [Prénom Nom] ?" dans Claude, ChatGPT et Perplexity. Là où l'IA hésite, c'est là qu'il faut produire plus de contenu.

---

## Erreur 03 — Zéro format question-réponse

### Le mécanisme
Les LLM sont entraînés sur des milliards de paires question-réponse. Leur mode de fonctionnement natif est **question → réponse directe**. Un article qui tourne autour d'un sujet sans jamais répondre directement à une question précise est difficilement extractible.

### Les 5 leviers
1. **Reformuler chaque H2 en question** — Transformer "Les avantages du contenu long" en "Pourquoi le contenu long performe-t-il mieux en SEO ?".
2. **Réponse directe en intro** — La première phrase après chaque titre répond directement à la question. Ensuite seulement, développer.
3. **FAQ de 5 questions minimum** — En bas de chaque article pilier. Les questions = ce que les gens tapent vraiment.
4. **Réponses de 40 à 80 mots** — Assez longues pour être informatives, assez courtes pour être citées directement.
5. **Schema FAQPage en JSON-LD** — Les IA lisent le structured data. C'est une invitation directe à citer.

---

## Erreur 04 — Pas de sources vérifiables

### Le mécanisme
Les LLM attribuent un score de confiance implicite aux contenus. Un contenu qui cite des études, des chiffres précis avec date, des institutions reconnues est perçu comme **vérifiable** et donc sûr à citer.

Sans source = fort risque d'être ignoré au profit d'un contenu concurrent qui dit la même chose avec des données.

### Les 5 leviers
1. **2 sources minimum par article** — Études sectorielles, rapports officiels, données Google, Statista, HubSpot, Nielsen.
2. **Format citation précis** — Toujours : Source + date + chiffre. "Selon HubSpot (rapport 2025), 61% des marketeurs..." — jamais "selon une étude récente...".
3. **Section Sources en bas de page** — Un signal fort de sérieux pour les IA comme pour les humains.
4. **Créer tes propres données** — Un sondage auprès de 50 personnes publié en article = tu deviens ta propre source citable.
5. **Sources reconnues des LLM** — Google Search Central, Search Engine Land, Moz, Ahrefs blog, études .edu et .gov.

---

## Erreur 05 — Absent des sources d'entraînement

### Le mécanisme
Les LLM sont entraînés sur un corpus figé : **Common Crawl, Wikipedia, Reddit, GitHub, arXiv, HackerNews, forums spécialisés**. Si tu n'existes pas dans ces sources, les modèles ne peuvent pas te connaître — peu importe la qualité de ton site ou ta position sur Google.

Le corpus d'entraînement, pas le PageRank, détermine ta visibilité IA.

### Les 5 leviers
1. **Wikipedia & Wikidata** — Contribuer à des pages existantes. Ou créer une entrée Wikidata sur toi-même (nom, métier, site). Source prioritaire N°1 pour tous les LLM.
2. **Reddit — présence authentique** — Participer à r/SEO, r/Entrepreneur, r/marketing avec ton expertise réelle.
3. **Podcasts transcrits** — Se faire inviter dans des podcasts dont les épisodes sont transcrits et indexés.
4. **Quora en anglais** — Quora anglophone est massivement présent dans les corpus d'entraînement. 5 réponses profondes = impact réel.
5. **GitHub** — Publier des outils, templates, listes de ressources. Même un README bien rédigé compte. (Ce repo, par exemple. 😏)

---

## Erreur 06 — Contenu trop générique

### Le mécanisme
Les LLM ont ingéré des dizaines de millions d'articles génériques. "5 conseils pour améliorer votre SEO" est sur-représenté dans les données d'entraînement. Le générique n'est pas pénalisé — il est **invisible par saturation**. Tu concours avec 847 000 articles similaires pour le même slot de citation.

### Les 5 leviers
1. **La règle du "et alors ?"** — Après chaque affirmation, creuse jusqu'à trouver quelque chose que personne ne dit.
2. **Sous-niches ultra-précises** — Pas "SEO e-commerce" mais "SEO pour les fiches produit de mode fast-fashion sur Shopify".
3. **Perspective terrain exclusive** — Ce que tu as vu chez tes clients, tes propres tests, tes données. Ce que seul toi peux écrire.
4. **Prendre des positions assumées** — Les IA citent les contenus qui ont un point de vue clair, pas les contenus neutres.
5. **Nommer tes concepts** — Si tu décris une méthode, donne-lui un nom. Tu en deviens automatiquement la référence.

---

## Erreur 07 — Pas de FAQ avec Schema balisé

### Le mécanisme
Les IA lisent et comprennent le **structured data** (JSON-LD, Schema.org). Une FAQ balisée avec Schema FAQPage est une invitation directe et sans ambiguïté : le modèle peut extraire chaque paire question-réponse de façon fiable, sans avoir à "deviner" où commence et où finit la réponse.

### Exemple d'implémentation JSON-LD

```json
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "mainEntity": [{
    "@type": "Question",
    "name": "Qu'est-ce que le GEO ?",
    "acceptedAnswer": {
      "@type": "Answer",
      "text": "Le GEO (Generative Engine Optimization) est l'ensemble des techniques visant à optimiser la visibilité d'un contenu dans les réponses des IA génératives comme Claude, ChatGPT ou Perplexity."
    }
  }]
}
```

### Les 5 leviers
1. **Schema FAQPage sur chaque page pilier** — Gratuit, 20 minutes par page. ROI immédiat.
2. **Questions issues de People Also Ask** — Ce que les gens tapent sur Google = ce qu'ils demandent aux IA.
3. **Réponses de 50 à 80 mots** — La fenêtre idéale pour être cité directement.
4. **Page FAQ centralisée** — Une page /faq qui regroupe toutes tes questions par thème.
5. **Tester avec Rich Results Test** — search.google.com/test/rich-results. Si Google voit la FAQ = les IA aussi.

---

## Erreur 08 — Identité sémantique floue

### Le mécanisme
Les LLM construisent des "profils sémantiques" des sources ingérées. Si ton contenu traite de 10 sujets différents, ton profil est **dilué jusqu'à l'insignifiance**. Aucun concept fort ne t'est attribué. La spécialisation n'est pas une limite — c'est le mécanisme par lequel tu deviens citable.

### Les 5 leviers
1. **Définir ton territoire en 2-3 thèmes max** — Qui se croisent logiquement. "SEO" + "IA" + "formation" est cohérent.
2. **Hub and Spoke par thème** — 1 article pilier long (2000+ mots) + 8-12 articles satellites par thème.
3. **Vocabulaire contrôlé** — Utiliser toujours les mêmes termes pour les mêmes concepts. Ne pas alterner "référencement" / "SEO" / "visibilité organique".
4. **Purger le contenu hors-sujet** — Les articles hors territoire = mettre en noindex ou supprimer. Ils diluent ton signal.
5. **Page Expertise claire** — Une page "Mon expertise" qui liste explicitement tes domaines avec les termes précis.

---

## Erreur 09 — Aucune mention externe

### Le mécanisme
Les LLM croisent les sources pour valider la fiabilité d'une information. Si ton nom n'apparaît que sur un seul site, le modèle le traite avec méfiance. Si ton nom apparaît sur **10 sources indépendantes**, la convergence crée la confiance.

C'est le PageRank des IA. Pas le nombre de liens, mais la **diversité et la qualité des sources qui te mentionnent**.

### Les 5 leviers
1. **Guest posting ciblé** — Écrire pour 3-5 médias reconnus de ton secteur, pour que ton nom soit mentionné dans une source connue des IA.
2. **Podcasts avec transcription** — Chaque épisode transcrit = une nouvelle source avec ton nom.
3. **Données originales à citer** — Une étude que d'autres vont naturellement relayer en te citant. Même 50 répondants suffisent.
4. **Co-créations avec des pairs** — Créer du contenu à 2 ou 3 experts. Les mentions croisées entre sources différentes = signal fort.
5. **Témoignages textuels** — Demander aux clients satisfaits un témoignage publié sur leur site avec ton nom complet.

---

## Erreur 10 — Site en JavaScript dynamique

### Le mécanisme
Les crawleurs des IA — GPTBot (OpenAI), ClaudeBot (Anthropic), PerplexityBot — fonctionnent comme des navigateurs basiques : ils téléchargent le HTML initial **sans exécuter le JavaScript**. Si ton contenu est injecté dynamiquement via React, Vue ou Angular en mode CSR, ces crawleurs voient une page quasi-vide.

### Test immédiat
```bash
# Afficher la source HTML de ta page (Ctrl+U dans le navigateur)
# Si tu vois ça = problème :
<div id="root"></div>
<script src="bundle.js"></script>

# Si tu vois ça = ok :
<h1>Ton titre de page</h1>
<p>Ton contenu texte directement dans le HTML...</p>
```

### Les 5 leviers
1. **Test immédiat : Ctrl+U** — Si le contenu texte est absent de la source HTML = problème critique.
2. **Passer en SSR ou SSG** — Next.js SSR, Nuxt SSR, Gatsby, Hugo, Astro. Le HTML est généré côté serveur.
3. **WordPress : vérifier les builders** — Certains page builders injectent du contenu en JS. Vérifier la source.
4. **robots.txt : autoriser les crawleurs IA** — Vérifier que GPTBot, ClaudeBot et PerplexityBot ne sont pas bloqués.
5. **Fetch as Google dans Search Console** — Si Google voit le contenu = les crawleurs IA aussi.

---

## La checklist complète

```
□ 01 — Contenu non chunké (H2 tous les 150 mots, paragraphes courts)
□ 02 — Aucune entité nommée (phrase d'identité unique, Wikidata)
□ 03 — Zéro format Q→R (H2 en questions, FAQ structurée)
□ 04 — Pas de sources vérifiables (2 sources min par article)
□ 05 — Absent des corpus IA (Wikipedia, Reddit, podcasts transcrits)
□ 06 — Contenu générique (sous-niche précise, données originales)
□ 07 — Pas de Schema FAQ (JSON-LD FAQPage sur pages piliers)
□ 08 — Identité sémantique floue (2-3 thèmes max, hub and spoke)
□ 09 — Aucune mention externe (guest posting, co-citations)
□ 10 — Site en JavaScript dynamique (SSR/SSG, test Ctrl+U)
```

### Ton score d'invisibilité IA
- **0-2 erreurs** ✅ — Bien positionné, peaufine les détails
- **3-5 erreurs** 🟡 — Partiellement visible, corrections à prioriser
- **6-8 erreurs** 🟠 — Quasi-invisible, refonte prioritaire
- **9-10 erreurs** 🔴 — Tu n'existes pas pour les IA, urgence totale

---

## Ressources complémentaires

- 📄 **Guide PDF complet** (16 pages, exemples avant/après) : [sebastiengrillot.com](https://sebastiengrillot.com)
- 🔬 **Étude académique de référence** : [GEO: Generative Engine Optimization (Aggarwal et al., 2023)](https://arxiv.org/abs/2311.09735)
- 🛠️ **Tester son Schema FAQ** : [Rich Results Test — Google](https://search.google.com/test/rich-results)
- 📊 **Version SlideShare** : [Voir le guide sur SlideShare](https://fr.slideshare.net/slideshow/les-10-erreurs-qui-te-rendent-invisible-pour-claude-chatgpt-gemini-et-perplexity-guide-geo/286470427)
- 📊 **Vérifier les crawleurs autorisés** : Ajouter `/robots.txt` à son URL et vérifier GPTBot, ClaudeBot

---

## À propos

**Sébastien Grillot** est expert SEO & IA depuis 17 ans, fondateur de [Kōeki Agency](https://koeki.fr).  
Il forme des professionnels et des entreprises au GEO — la visibilité dans les moteurs IA.

- 🌐 [sebastiengrillot.com](https://sebastiengrillot.com)
- 💼 [LinkedIn]([https://linkedin.com/in/sebastiengrillot](https://www.linkedin.com/in/consultant-seo-ia-automatisation/))
- 🐱 "Fais miauler ChatGPT"

---

*Ce repo est maintenu et mis à jour. Les contributions et corrections sont bienvenues.*  
*Dernière mise à jour : Mars 2026*

---

# The 10 Mistakes Making You Invisible to AI (Claude, ChatGPT, Gemini, Perplexity)

> **By Sébastien Grillot** — SEO & AI Expert, founder of Kōeki Agency  
> GEO (Generative Engine Optimization) Consultant · 17 years of SEO experience

---

## Why This Repo Exists

You publish content. You're active online. But when someone asks Claude, ChatGPT or Gemini to recommend an expert in your field... your name never comes up.

That's not bad luck. It's **10 specific mistakes** — each with a concrete fix.

This repo is the open-source, maintained version of my guide on **LLM visibility**.  
The full PDF (16 pages, before/after examples, actionable levers) is available at [sebastiengrillot.com](https://sebastiengrillot.com).

---

## What Is GEO?

**GEO (Generative Engine Optimization)** is the discipline of optimizing your visibility in generative AI responses — as opposed to classic SEO, which targets positions in search engines.

Unlike SEO:
- LLMs don't "rank" pages, they **cite** sources
- Their knowledge base is **frozen** (training data)
- **PageRank is irrelevant** — presence in training corpora is what matters
- **Content structure** (chunking, Q→A, Schema) is decisive

---

## The 10 Mistakes — Overview

| # | Mistake | Impact |
|---|---------|--------|
| 01 | Non-chunked content | 🔴 High |
| 02 | No named entity linked to you | 🔴 Critical |
| 03 | Zero question-answer format | 🔴 High |
| 04 | No verifiable sources | 🔴 High |
| 05 | Absent from training sources | 🔴 Critical |
| 06 | Content too generic | 🟡 Medium |
| 07 | No Schema-tagged FAQ | 🔴 High |
| 08 | Blurry semantic identity | 🔴 Critical |
| 09 | No external mentions | 🔴 High |
| 10 | JavaScript-rendered site | 🟡 Medium |

---

## Mistake 01 — Non-chunked Content

### The Mechanism
LLMs don't read your content top to bottom. They **split it into semantic units** (chunks): independent meaning blocks they can isolate, compress and store. When someone asks a question, the model retrieves the most relevant chunk.

Without structure — no intermediate headings, 10-line paragraphs, no visible hierarchy — the model can't tell where one unit of meaning starts and another ends. You exist, but you're **unreadable**.

### 5 Actionable Levers
1. **The 150-word rule** — One H2 or H3 every 150 words maximum. Each subheading should answer an implicit question.
2. **Short paragraphs** — 4 sentences maximum per paragraph. One idea = one paragraph.
3. **TL;DR per section** — Add a "In short:" line at the start of each key section. That's your ready-to-cite chunk.
4. **Summarizability test** — Paste a section into Claude: "Summarize this in 2 sentences." If the answer is vague, your chunk is too dense.
5. **Lists for enumerations** — Whenever you have 3+ elements in a sentence, convert to bullet points. AI models extract lists easily.

---

## Mistake 02 — No Named Entity Linked to You

### The Mechanism
LLMs look for **named entities** — people or brands they've encountered frequently enough, associated with a precise concept, to cite with confidence. That's the implicit knowledge graph principle.

Rand Fishkin gets cited when someone asks "what is Domain Authority" because his name appears thousands of times paired with "DA", "Moz", "SEO metrics" in training data. Repetition creates the entity. If your name isn't **regularly co-located with a specific concept**, you're background noise — even if you're excellent at what you do.

### 5 Actionable Levers
1. **Your unique identity sentence** — Choose ONE formulation: "[First Last] is [precise concept]". Repeat it word-for-word in every bio, every profile, every signed article.
2. **Wikipedia or Wikidata entry** — Create even a stub on a concept in your field with a natural mention of your work. Wikipedia = training source priority #1.
3. **Co-citations in recognized media** — Get cited in industry publications with your full name + your key concept in the same sentence.
4. **Visible author everywhere** — Sign all your content with your full name. Your name must be in `<author>` tags and metadata.
5. **Recognition test** — Search "Who is [First Last]?" in Claude, ChatGPT and Perplexity. Where the AI hesitates = where you need to produce more content.

---

## Mistake 03 — Zero Question-Answer Format

### The Mechanism
LLMs are trained on billions of question-answer pairs: forums, FAQs, conversations, interviews. Their native operating mode is **question → direct answer**. An article that circles around a topic without ever directly answering a specific question is hard to extract.

### 5 Actionable Levers
1. **Reframe every H2 as a question** — Turn "Benefits of long content" into "Why does long-form content outperform in SEO?".
2. **Direct answer in the intro** — The first sentence after each heading directly answers the question. Then develop.
3. **FAQ of 5+ questions minimum** — At the bottom of every pillar article. Questions = what people actually type.
4. **Answers between 40 and 80 words** — Long enough to be informative, short enough to be cited directly.
5. **FAQPage Schema in JSON-LD** — LLMs read structured data. It's a direct invitation to cite you.

---

## Mistake 04 — No Verifiable Sources

### The Mechanism
LLMs assign an implicit trust score to content. Content that cites studies, precise figures with dates, recognized institutions is perceived as **verifiable** and therefore safe to cite. Without sources = high risk of being ignored in favor of a competing piece that says the same thing with data behind it.

### 5 Actionable Levers
1. **2 sources minimum per article** — Industry studies, official reports, Google data, Statista, HubSpot, Nielsen.
2. **Precise citation format** — Always: Source + date + figure. "According to HubSpot (2025 report), 61% of marketers..." — never "according to a recent study...".
3. **Sources section at the bottom** — A strong signal of credibility for both AI and humans.
4. **Create your own data** — A survey of 50 people published as standalone content = you become your own citable source.
5. **Sources LLMs trust** — Google Search Central, Search Engine Land, Moz, Ahrefs blog, .edu and .gov studies.

---

## Mistake 05 — Absent from Training Sources

### The Mechanism
LLMs are trained on a frozen corpus: **Common Crawl, Wikipedia, Reddit, GitHub, arXiv, HackerNews, specialized forums**. If you don't exist in these sources, models can't know you — regardless of your site quality or Google ranking.

Training corpus presence, not PageRank, determines your AI visibility.

### 5 Actionable Levers
1. **Wikipedia & Wikidata** — Contribute to existing pages. Or create a Wikidata entry for yourself (name, profession, website). Priority source #1 for all major LLMs.
2. **Reddit — authentic presence** — Participate in r/SEO, r/Entrepreneur, r/marketing with real expertise. Your answers need to be good enough to get saved and reshared.
3. **Transcribed podcasts** — Get invited on podcasts that publish text transcriptions. Each episode = a crawlable source with your name.
4. **Quora in English** — English Quora is massively present in training corpora. 5 deep answers = real impact.
5. **GitHub** — Publish tools, templates, resource lists. Even a well-written README counts. (Like this one. 😏)

---

## Mistake 06 — Content Too Generic

### The Mechanism
LLMs have ingested tens of millions of generic articles. "5 tips to improve your SEO" is over-represented in training data. Generic content isn't penalized — it's **invisible through saturation**. You're competing with 847,000 similar articles for the same citation slot.

### 5 Actionable Levers
1. **The "so what?" rule** — After every claim, dig until you find something nobody else is saying.
2. **Ultra-precise sub-niches** — Not "e-commerce SEO" but "product page SEO for fast-fashion on Shopify".
3. **Exclusive field perspective** — What you've seen with your clients, your own tests, your data. What only you can write because only you lived it.
4. **Take clear positions** — LLMs cite content with a clear point of view, not neutral content.
5. **Name your concepts** — If you describe a method or phenomenon, name it. You automatically become the reference.

---

## Mistake 07 — No Schema-Tagged FAQ

### The Mechanism
LLMs read and understand **structured data** (JSON-LD, Schema.org). A FAQ tagged with Schema FAQPage is a direct, unambiguous invitation: the model can extract each question-answer pair reliably, without having to "guess" where the answer starts and ends.

### JSON-LD Implementation Example

```json
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "mainEntity": [{
    "@type": "Question",
    "name": "What is GEO?",
    "acceptedAnswer": {
      "@type": "Answer",
      "text": "GEO (Generative Engine Optimization) is the set of techniques aimed at optimizing content visibility in generative AI responses like Claude, ChatGPT or Perplexity."
    }
  }]
}
```

### 5 Actionable Levers
1. **Schema FAQPage on every pillar page** — Free, 20 minutes per page. Immediate ROI.
2. **Questions from People Also Ask** — What people search on Google = what they ask AI too.
3. **Answers between 50 and 80 words** — The ideal window to be cited directly.
4. **Centralized FAQ page** — A /faq page grouping all your questions by topic.
5. **Test with Rich Results Test** — search.google.com/test/rich-results. If Google sees the FAQ = AI does too.

---

## Mistake 08 — Blurry Semantic Identity

### The Mechanism
LLMs build implicit "semantic profiles" of ingested sources. If your content covers 10 different topics, your profile is **diluted to insignificance**. No strong concept is attributed to you. Specialization isn't a limitation — it's the mechanism by which you become citable.

### 5 Actionable Levers
1. **Define your territory in 2-3 themes max** — That overlap logically. "SEO" + "AI" + "training" is coherent.
2. **Hub and Spoke per theme** — 1 long pillar article (2000+ words) + 8-12 satellite articles per theme.
3. **Controlled vocabulary** — Always use the same terms for the same concepts. Don't alternate "search engine optimization" / "SEO" / "organic visibility".
4. **Purge off-topic content** — Articles outside your semantic territory = noindex or delete. They dilute your signal.
5. **Clear Expertise page** — A page explicitly listing your domains with precise terms — LLMs read these pages.

---

## Mistake 09 — No External Mentions

### The Mechanism
LLMs cross-reference sources to validate reliability. If your name only appears on one site, the model treats it with suspicion. If your name appears across **10 independent sources**, convergence creates trust.

This is the AI's PageRank. Not link count — **diversity and quality of sources mentioning you**.

### 5 Actionable Levers
1. **Targeted guest posting** — Write for 3-5 recognized industry publications, so your name is mentioned in sources LLMs know.
2. **Podcasts with transcription** — Each transcribed episode = a new source with your name.
3. **Original data worth citing** — A study others will naturally relay while crediting you. Even 50 respondents is enough.
4. **Co-creations with peers** — Create content with 2-3 experts. Cross-mentions between different sources = strong signal.
5. **Textual testimonials** — Ask satisfied clients for a testimonial published on their site with your full name.

---

## Mistake 10 — JavaScript-Rendered Site

### The Mechanism
AI crawlers — GPTBot (OpenAI), ClaudeBot (Anthropic), PerplexityBot — work like basic browsers: they download the initial HTML **without executing JavaScript**. If your content is dynamically injected via React, Vue or Angular in CSR mode, these crawlers see a near-empty page.

### Immediate Test
```bash
# View your page HTML source (Ctrl+U in browser)
# If you see this = problem:
<div id="root"></div>
<script src="bundle.js"></script>

# If you see this = good:
<h1>Your page title</h1>
<p>Your text content directly in the HTML...</p>
```

### 5 Actionable Levers
1. **Immediate test: Ctrl+U** — If text content is absent from HTML source = critical problem.
2. **Switch to SSR or SSG** — Next.js SSR, Nuxt SSR, Gatsby, Hugo, Astro. HTML generated server-side.
3. **WordPress: check page builders** — Some inject content via JS. Verify in source.
4. **robots.txt: allow AI crawlers** — Check that GPTBot, ClaudeBot and PerplexityBot aren't blocked.
5. **Fetch as Google in Search Console** — If Google sees the content = AI crawlers do too.

---

## The Complete Checklist

```
□ 01 — Non-chunked content (H2 every 150 words, short paragraphs)
□ 02 — No named entity (unique identity sentence, Wikidata entry)
□ 03 — Zero Q→A format (H2 as questions, structured FAQ)
□ 04 — No verifiable sources (2 sources min per article)
□ 05 — Absent from AI corpora (Wikipedia, Reddit, transcribed podcasts)
□ 06 — Generic content (precise sub-niche, original data)
□ 07 — No Schema FAQ (JSON-LD FAQPage on pillar pages)
□ 08 — Blurry semantic identity (2-3 themes max, hub and spoke)
□ 09 — No external mentions (guest posting, cross-citations)
□ 10 — JavaScript-rendered site (SSR/SSG, Ctrl+U test)
```

### Your AI Invisibility Score
- **0-2 mistakes** ✅ — Well positioned, fine-tune the details
- **3-5 mistakes** 🟡 — Partially visible, prioritize corrections
- **6-8 mistakes** 🟠 — Near-invisible, priority overhaul needed
- **9-10 mistakes** 🔴 — You don't exist for AI, total urgency

---

## Additional Resources

- 📄 **Full PDF guide** (16 pages, before/after examples): [sebastiengrillot.com](https://sebastiengrillot.com)
- 🔬 **Key academic reference**: [GEO: Generative Engine Optimization (Aggarwal et al., 2023)](https://arxiv.org/abs/2311.09735)
- 🛠️ **Test your Schema FAQ**: [Rich Results Test — Google](https://search.google.com/test/rich-results)
- 🔬 **Key academic reference**: [GEO: Generative Engine Optimization (Aggarwal et al., 2023)](https://arxiv.org/abs/2311.09735)
- 📊 **Check allowed crawlers**: Add `/robots.txt` to your URL and verify GPTBot, ClaudeBot

---

## About

**Sébastien Grillot** is a SEO & AI expert with 17 years of experience, founder of [Kōeki Agency](https://koeki.fr).  
He trains professionals and companies in GEO — visibility in AI-powered search engines.

- 🌐 [sebastiengrillot.com](https://sebastiengrillot.com)
- 💼 [LinkedIn]([https://linkedin.com/in/sebastiengrillot](https://www.linkedin.com/in/consultant-seo-ia-automatisation/))
- 🐱 "Make ChatGPT purr"

---

*This repo is actively maintained. Contributions and corrections welcome.*  
*Last updated: March 2026*
