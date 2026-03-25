# — Moteur Heuristique v5.7

Analyseur de prompts IA, 100% offline, zéro dépendance, un seul fichier HTML.

## C'est quoi ?

Un outil qui analyse la qualité d'un prompt avant de l'envoyer à une IA.
Il donne un score, un verdict, et des conseils pour améliorer ta demande.

## Comment ça marche ?

1. Ouvre `index.html` dans ton navigateur
2. Colle ton prompt dans la zone de texte
3. Clique sur **Analyser**
4. Lis le verdict 🟢 🟠 🔴

## Les verdicts

| Verdict | Score | Signification |
|---|---|---|
| 🟢 OPTIMAL | > 2.3 | Prompt solide, envoie-le |
| 🟠 ADMISSIBLE | > 1.0 | Correct mais améliorable |
| 🔴 INCOHÉRENCE | < 1.0 | Trop vague, à reformuler |

## Les tenseurs

- **β (Axionté)** — solidité de la structure du prompt
- **ΔC (Gradient)** — clarté de l'intention
- **λ (Entropie)** — niveau de bruit

Score : `S = (β × ΔC) / λ`

## Fonctionnalités

- 📊 Score S_Ω en temps réel
- 🧮 Tenseurs β / ΔC / λ
- 🧑‍🏫 Mode **Vulgariser** — explication en langage simple
- 📋 Logs heuristiques
- 🧪 Batterie de 50 tests intégrée
- 📤 Export rapport

## Démo en ligne

👉 https://modelingsolver.github.io/V5/

## Intégration iframe

```html
<iframe 
  src="https://modelingsolver.github.io/ZORANV5/" 
  width="100%" 
  height="850px" 
  style="border:none; border-radius:16px;">
</iframe>
```

## Tech

- HTML / CSS / JS vanilla
- Zéro framework, zéro API, zéro serveur
- Fonctionne hors ligne une fois chargé

---

*v5.7*
