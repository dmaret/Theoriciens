# PraxisPro Épistémé

**Ingénierie Clinique Avancée — Analyse Multithéorique**

PraxisPro Épistémé est un outil web d'aide à l'analyse clinique destiné aux professionnels de l'accompagnement (travailleurs sociaux, formateurs, conseillers, cliniciens). À partir d'observations symptomatiques, l'application génère des hypothèses théoriques croisées issues de cinq cadres conceptuels majeurs et propose des pistes d'intervention contextualisées.

## ✨ Fonctionnalités

- **Base symptomatique structurée** — 19 observations cliniques réparties en 5 catégories : Évitement, Résistance, Sabotage, Paradoxe, Émotionnel.
- **Génération d'hypothèses multithéoriques** — croisement dynamique des symptômes sélectionnés pour produire des hypothèses situées dans plusieurs cadres :
  - Approche Systémique (Watzlawick, Minuchin, Satir, Weakland)
  - Constructivisme & Socialisation (Piaget, Dubar, Carré, Mezirow)
  - Approche Psychodynamique (Freud, Winnicott, Balint, Reich)
  - Perspective Sociologique (Bourdieu, Goffman, Lahire, Dubet)
  - Approche Cognitive-Comportementale (Beck, Bandura, Ellis, Meichenbaum)
- **Questions cliniques contextualisées** — suggestions de questions d'entretien adaptées au profil dominant détecté.
- **Notes cliniques libres** — espace de consignation pour observations et hypothèses du professionnel.
- **Historique d'analyses** — sauvegarde locale (localStorage) des sessions antérieures.
- **Export du rapport** — génération d'un rapport texte téléchargeable.
- **Conditions d'utilisation** — modale dédiée accessible depuis le pied de page.

## 🧭 Onglets de l'interface

1. **📍 Observations** — sélection des symptômes observés et saisie des notes cliniques.
2. **🔬 Analyse** — hypothèses théoriques générées et questions cliniques suggérées.
3. **💡 Stratégies** — pistes d'intervention orientées selon le profil.
4. **📚 Historique** — consultation des analyses précédentes.

## 🚀 Utilisation

Le projet est une application web statique qui ne nécessite aucune installation.

### Option 1 — Ouverture directe

Ouvrir `index.html` dans un navigateur moderne (Chrome, Firefox, Safari, Edge).

### Option 2 — Serveur local

```bash
# avec Python 3
python3 -m http.server 8000

# ou avec Node
npx serve .
```

Puis ouvrir `http://localhost:8000` dans le navigateur.

## 🛠️ Stack technique

- **HTML5** + **Tailwind CSS** (via CDN)
- **React 18** (via CDN, sans build)
- **Babel Standalone** pour le JSX en ligne
- **html2pdf.js** pour l'export
- **localStorage** pour la persistance côté client

Aucune dépendance serveur, aucun build, aucune donnée transmise en dehors du navigateur.

## ⚖️ Avertissement

Cet outil est une aide à la réflexion clinique. Il ne se substitue en aucun cas au jugement professionnel, au diagnostic médical ou à la supervision clinique. Les hypothèses générées doivent être considérées comme des pistes d'exploration et non comme des conclusions diagnostiques.

## 📄 Licence & Copyright

© 2025-2026 MARET Davie — PraxisPro Épistémé v2.0

Consulter les conditions d'utilisation directement dans l'application (lien en pied de page).
