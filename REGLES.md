# Règles d'usage et de contribution — Sources SID

## 1. Principes généraux

- Ce repository est un **inventaire de métadonnées**, pas une bibliothèque de fichiers.
- **Aucun PDF** ne doit être uploadé ici (droits d'auteur).
- Chaque institution ou apprenant doit acquérir ses propres copies selon les droits applicables.

## 2. Système d'identification canonique

Chaque œuvre a un **ID canonique unique** qui doit être utilisé dans tous les documents du curriculum :

```
[auteur-annee-sujet-abrege]
```

Exemples : `[sweller-1998-cognitive-architecture]`, `[pettersson-id5-cognition]`

## 3. Hiérarchie des sources

```
sid_foundation.md            → Source de vérité unique
sid_body_of_knowledge.md     → Opérationnalisation
sid_standard.md              → Exigences de conformité
sid_position_paper.md        → Justification académique
sid_manifeste.md             → Vision officielle
SID_Foundational_Paper.md    → Papier fondateur
```

## 4. Statuts des sources

| Statut | Marquage | Description |
|--------|----------|-------------|
| Canonique | `[CANONIQUE]` | 21 œuvres de référence, validées par le corpus |
| Extension à sourcer | `[EXTENSION — À SOURCER]` | Recommandées mais non encore intégrées au corpus |
| Rejetée | `[HORS PÉRIMÈTRE]` | Ne relève pas du périmètre SID |

## 5. Format de fiche source

Chaque fiche source DOIT contenir :
- ID canonique
- Référence bibliographique complète (APA 7e)
- Domaine BoK associé
- Piliers SID associés
- Score SID (0-100)
- Apport principal (2-3 phrases)
- Disponibilité (URL, DOI, payant/open access)
- Instructions d'acquisition
- Éléments du curriculum qui la citent (P, M, F, CL, H, etc.)

## 6. Contribution

Pour ajouter une source :
1. Créer une Issue décrivant la source et sa justification
2. Attendre la validation par le Chief Knowledge Architect
3. Soumettre une Pull Request avec la fiche source au format requis
