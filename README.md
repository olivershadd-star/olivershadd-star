<div align="center">

<img src="assets/anks-hero.jpg" width="100%" alt="ANKS Labs — laboratoire indépendant de développement audio, bleu électrique, noir et écarlate" />

<br>

**AUDIO SOFTWARE // SYNTHESIS // EXPERIMENTAL INSTRUMENTS // MIDI SYSTEMS**

<img src="https://img.shields.io/badge/C%2B%2B-151923?style=for-the-badge&logo=cplusplus&logoColor=EF343E" alt="C++" />
<img src="https://img.shields.io/badge/JUCE-151923?style=for-the-badge&logoColor=19B9FF" alt="JUCE" />
<img src="https://img.shields.io/badge/VST3-151923?style=for-the-badge&logoColor=EF343E" alt="VST3" />
<img src="https://img.shields.io/badge/WINDOWS-151923?style=for-the-badge&logo=windows11&logoColor=19B9FF" alt="Windows" />
<img src="https://img.shields.io/badge/MIDI-151923?style=for-the-badge&logoColor=F5C343" alt="MIDI" />

**BUILD. BREAK. REWIRE. LISTEN.**

</div>

---

## `// 01` — ANKS · ANIKI SHAD

**ANKS Labs** est un laboratoire indépendant consacré à la conception et à l’expérimentation d’outils pour la production musicale électronique : instruments virtuels, moteurs audio, applications Windows, séquenceurs et systèmes de contrôle MIDI.

Le laboratoire explore autant le développement de nouveaux instruments que l’adaptation de projets open source existants. L’objectif est de **tester, comprendre, transformer et partager** des outils utiles à la création sonore, sans démarche commerciale systématique.

**ANKS**, porté par **Aniki Shad**, fait le lien entre la création musicale et l'expérimentation technique. L'idée est simple : développer des outils parce qu'on aime le son, les machines, les synthétiseurs et tout ce qu'il est possible d'en tirer.

ANKS travaille et échange avec des **passionnés de musique, des petits producteurs indépendants**, qui créent avec leurs propres moyens et cherchent une identité sonore personnelle. C'est le cas de **HURk**, projet de musique électronique industrielle : un univers où textures, machines et expérimentations sonores occupent une place importante.

> **Build. Break. Rewire. Listen.**
>
> Des projets concrets, des prototypes expérimentaux et une approche ouverte de la recherche sonore.

## `// 02` — MUSIC CONNECTION · HURk

Pour découvrir la musique de **HURk** :

<div align="center">

[![HURk Spotify](https://img.shields.io/badge/SPOTIFY-LISTEN_TO_HURk-10151E?style=for-the-badge&logo=spotify&logoColor=1ED760)](https://open.spotify.com/intl-fr/artist/35kgknATs5ibL9zNGeA8ui)
[![HURk SoundCloud](https://img.shields.io/badge/SOUNDCLOUD-LISTEN_TO_HURk-10151E?style=for-the-badge&logo=soundcloud&logoColor=FF6033)](https://soundcloud.com/hurk666)

</div>

---

# ⚡ PROJECTS & DEVELOPMENT

**Synthétiseurs, grooveboxes, effets VST3 et outils MIDI pour Windows.** Des adaptations de code ouvert et des instruments originaux, conçus comme un laboratoire de création sonore.

**Les versions proposées sont expérimentales et les builds de test ne sont pas des versions stables.** Chaque dépôt détaille les fonctions, les limites et les conditions de réutilisation.

<div align="center">

[![KICK LAB WINDOWS](https://img.shields.io/badge/KICK_LAB-TEST_BUILD-EF343E?style=for-the-badge&labelColor=10151E)](https://github.com/olivershadd-star/Berhinger-Kick/releases)
[![PUBLIC REPOS](https://img.shields.io/badge/PROJECTS-EXPLORE_ALL-19B9FF?style=for-the-badge&labelColor=10151E)](https://github.com/olivershadd-star?tab=repositories)

</div>

## `// 03` — OPEN-SOURCE ADAPTATIONS

### KICK LAB — WINDOWS GROOVEBOX

<a href="https://github.com/olivershadd-star/Berhinger-Kick"><img src="assets/kick-lab-card.png" alt="KICK Lab — groovebox Windows" width="100%" /></a>

![Windows x64](https://img.shields.io/badge/WINDOWS-x64-19B9FF?style=flat-square&labelColor=10151E)
![Preview 0.24.0](https://img.shields.io/badge/PREVIEW-0.24.0-EF343E?style=flat-square&labelColor=10151E)
![AGPL](https://img.shields.io/badge/LICENSE-AGPL--3.0--or--later-F5C343?style=flat-square&labelColor=10151E)

**Groovebox autonome Windows**, adaptée à partir des sources ouvertes KICK de Music Tribe : 16 pads, huit patterns A–H, séquenceur graphique, mixeurs, effets, export WAV et contrôle MIDI.

**Pourquoi ce portage ?** Explorer comment le code open source KICK peut devenir une groovebox autonome pour Windows, avec une prise en main concrète sur des contrôleurs MIDI que l'on possède déjà.

**Maschine+**, **LPD8** et **MPK Mini** peuvent être exploités comme contrôleurs via les entrées MIDI prévues dans le projet. Maschine+ pilote notamment les pads et les encodeurs ; LPD8 sélectionne les patterns A–H et contrôle huit macros ; MPK Mini peut servir au jeu mélodique. **Les appareils sont connectés au PC et leurs entrées MIDI sont ouvertes en parallèle.** KICK Lab fonctionne aussi à la souris et au clavier, sans hardware dédié.

**Statut : public test build (0.24.0 preview) — non stable.** Objectifs à venir : poursuite du portage, validation VST3, puis étape alpha et tests plus larges.

**[⬇ Télécharger KICK Lab 0.24.0 preview](https://github.com/olivershadd-star/Berhinger-Kick/releases/tag/v0.24.0-preview)** · **[Code et documentation](https://github.com/olivershadd-star/Berhinger-Kick)**

---

## `// 04` — ORIGINAL ANKS LABS INSTRUMENTS

### MS1 — WAVETABLE INSTRUMENT

![VST3](https://img.shields.io/badge/INSTRUMENT-VST3-19B9FF?style=flat-square&labelColor=10151E)
![JUCE](https://img.shields.io/badge/FRAMEWORK-JUCE-EF343E?style=flat-square&labelColor=10151E)

**[MS1](https://github.com/olivershadd-star/MS1)** — expérimentation originale née d'une idée de **croisement des approches musicales de Massive et Serum**, sans reprise de leur code ou de leurs interfaces. Instrument wavetable JUCE : **unison, filtre, LFO, enveloppe de modulation, séquenceur pas à pas et banque de presets**.

**Statut : experimental test build — non stable.** Des artefacts peuvent être récupérés via GitHub Actions selon les compilations réussies et leur durée de conservation.

**[Code et documentation](https://github.com/olivershadd-star/MS1)** · **[GitHub Actions](https://github.com/olivershadd-star/MS1/actions)**

---

### MOOGER — SEMI-MODULAR SYNTHESIZER

![Windows build](https://img.shields.io/badge/WINDOWS-BUILD_VALIDATED-19B9FF?style=flat-square&labelColor=10151E)
![Version](https://img.shields.io/badge/PROTOTYPE-V0.5-EF343E?style=flat-square&labelColor=10151E)
![Ableton](https://img.shields.io/badge/DAW_TEST-TO_CONFIRM-F5C343?style=flat-square&labelColor=10151E)

**[MOOGER](https://github.com/olivershadd-star/MOOGER)**

Synthétiseur semi-modulaire original : **deux oscillateurs, filtre résonant, patching virtuel, séquenceur huit pas et voix de percussion indépendante**. La V0.5 développe un panneau de modulation avec LFO, bruit, sample & hold, atténuateurs, mélangeur CV et lag.

Compilation Windows et tests automatisés réussis ; l'écoute et l'intégration dans Ableton restent à valider.

**[Projet et sources](https://github.com/olivershadd-star/MOOGER)** · **[Builds Windows VST3 / EXE](https://github.com/olivershadd-star/MOOGER/actions)**

---

### MODULAR — HYBRID SOUND LAB

![C++ JUCE](https://img.shields.io/badge/C%2B%2B_%2F_JUCE-SYNTH_ENGINE-19B9FF?style=flat-square&labelColor=10151E)
![Version](https://img.shields.io/badge/ALPHA-1.3.4-EF343E?style=flat-square&labelColor=10151E)

**[MODULAR / ANKS Resonant Lab](https://github.com/olivershadd-star/MODULAR)**

Un laboratoire de synthèse hybride **VST3 et standalone Windows** : import WAV, 36 excitations intégrées, double corps résonant, source FM à deux opérateurs et rack de traitements réordonnables. Semi-modulaire, décalage de fréquence, freeze spectral et expériences granulaires font partie des explorations du moteur.

**[Explorer le code, les modules et la documentation](https://github.com/olivershadd-star/MODULAR)**

---

### SWARM / 01 — DUAL-SWARM SYNTH

<a href="https://github.com/olivershadd-star/SWARM"><img src="assets/swarm-card.png" alt="SWARM / 01 — synthétiseur expérimental à morphing XY" width="100%" /></a>

![Prototype](https://img.shields.io/badge/PROTOTYPE-v0.2-EF343E?style=flat-square&labelColor=10151E)
![DSP](https://img.shields.io/badge/DSP-AUDIO_TESTED-19B9FF?style=flat-square&labelColor=10151E)

**[SWARM / 01](https://github.com/olivershadd-star/SWARM)** — synthétiseur original à deux bancs de **7 oscillateurs PolyBLEP**, détune, panoramique stéréo et filtre résonant, avec **morphing XY entre quatre scènes**. Le moteur DSP a été testé ; la validation finale du VST3 et du standalone sur Windows reste à faire.

**[Architecture, code et état du prototype](https://github.com/olivershadd-star/SWARM)**

---

### FRAGMENT ENGINE — RHYTHMIC STUTTER FX

![VST3](https://img.shields.io/badge/FX-VST3-19B9FF?style=flat-square&labelColor=10151E)
![Version](https://img.shields.io/badge/PROTOTYPE-0.3.0-EF343E?style=flat-square&labelColor=10151E)

**[FRAGMENT ENGINE](https://github.com/olivershadd-star/FRAGMENT-ENGINE)**

Effet audio **stutter / repeat** synchronisé au transport : capture de courts fragments, répétitions rythmiques, réglages Stutter / Refresh, dry/wet, automation et variations de hauteur en mode **Pattern** ou **Step**. Moteur C++20 indépendant du SDK et adaptation VST3 Steinberg ; le projet reste expérimental.

**[Découvrir le moteur et sa documentation](https://github.com/olivershadd-star/FRAGMENT-ENGINE)**

---

## `// 05` — AUTOMATION & MIDI TOOLS

| Projet | Description | État visible |
|:--|:--|:--|
| **[CURVE-PILOT](https://github.com/olivershadd-star/CURVE-PILOT)** | Hébergement VST et exploration de courbes d'automatisation | Dépôt public, documentation à compléter |
| **[CURVE-MINI](https://github.com/olivershadd-star/Curve-Mini)** | Expérimentation autour du contrôle et des courbes | Dépôt public ; fichier LICENSE MIT |
| **[CURVE-EDITOR-M4L](https://github.com/olivershadd-star/CURVE-EDITOR-M4L)** | Piste de développement Max for Live pour l'édition des courbes | Dépôt encore vide |

Ces dépôts sont des chantiers ou des espaces techniques ; ils ne correspondent pas nécessairement à des logiciels téléchargeables.

---

## `// 06` — PRIVATE RESEARCH

### MANGO — MODULAR GLITCH & MANGLING (PRIVATE RESEARCH)

![Private research](https://img.shields.io/badge/ANKS_WORK-PRIVATE_EXPERIMENT-EF343E?style=flat-square&labelColor=10151E)
![Upstream](https://img.shields.io/badge/ORIGINAL-ODOARE_%2F_MANGO-19B9FF?style=flat-square&labelColor=10151E)

**MANGO** est étudié comme base d'adaptation à partir du projet open source de **[Olivier Doaré / FX-Mechanics](https://github.com/odoare/Mango)** : séquenceur d'effets par blocs, glitch, mangling et hasard reproductible.

**Statut ANKS Labs : dépôt de travail encore privé.** Aucune version ANKS Labs n'est actuellement annoncée comme téléchargeable. Les crédits et conditions de licence du projet original sont conservés.

---

## `// 07` — OPEN SOURCE, LICENCES & ATTRIBUTION

**Public ne veut pas automatiquement dire libre de droits.** Chaque dépôt et chaque dépendance conservent leurs conditions de licence.

- **KICK Lab** est un portage indépendant sous **AGPL-3.0-or-later**, avec des composants tiers sous leurs propres licences. L'AGPL autorise le partage et la modification sous des obligations précises, y compris relatives au code source.
- **Curve-Mini** contient un fichier de licence **MIT** : cette licence autorise largement la réutilisation, sous condition notamment de conserver l'avis de copyright et la licence.
- Les autres projets ne sont **pas automatiquement open source** du seul fait que leurs sources sont visibles. Vérifier chaque dépôt et les licences des dépendances, notamment JUCE, avant redistribution.

Les marques **Behringer, Music Tribe, Native Instruments et Maschine** appartiennent à leurs titulaires. Les portages et prototypes ANKS Labs ne sont pas des produits officiels de ces fabricants.

---

## `// 08` — CONTACT & EXCHANGE

ANKS Labs est ouvert aux échanges autour de la synthèse, du DSP, des outils MIDI et du développement audio indépendant. Pour un projet public, utiliser ses **Issues** ou **Discussions** lorsque disponibles.

<div align="center">

---

**ANKS LABS**

`AUDIO SOFTWARE  //  EXPERIMENTAL INSTRUMENTS  //  ELECTRONIC MUSIC`

[**ALL PUBLIC REPOSITORIES**](https://github.com/olivershadd-star?tab=repositories)

</div>