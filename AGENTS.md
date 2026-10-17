# AGENTS.md

## Qui je suis

- **Nom** : Lucien
- **Niveau** : 4ème (collège)
- **Objectif en cours** : être élu **délégué de classe**
- **Langue de travail** : français

Toutes les demandes marketing de ce dossier partent de ce contexte : la
« marque » à vendre, c'est Lucien, et l'audience, ce sont ses camarades de
classe.

### Campagne délégué de classe

- **Slogan principal** : « Lucien délégué. Ce que tu dis en bas, je le dis en haut. »
- **Sous-slogan** : « Je note tout, je remonte tout, et je vous raconte la
  réunion dès le lendemain. »
- **Appel au vote** : « Vote Lucien. »
- **Alternative rimée** : « Un délégué pas moyen : Lucien. »
- **Promesse clé** : présence à chaque conseil de classe, compte rendu
  systématique au groupe de classe, aucune idée laissée de côté.
- **Documents** : `slogan.md` (slogan + pitch de 2 min),
  `campagne-delegue-lucien.pptx` (diaporama de présentation).

## À propos de ce dossier

Espace de travail marketing personnel. Ce dossier embarque la collection
[Marketing Skills](https://github.com/coreyhaines31/marketingskills) (MIT, par
Corey Haines) : ~50 compétences marketing pour agents IA (CRO, copywriting,
SEO, analytics, growth, etc.).

## Structure

```
perso/
├── AGENTS.md                  # Ce fichier
├── slogan.md                  # Slogan + pitch de 2 minutes
├── campagne-delegue-lucien.pptx  # Diaporama de campagne
└── .opencode/skills/          # Skills marketing installés
    ├── product-marketing/     # Skill fondation (à lire en premier)
    ├── cro/
    ├── copywriting/
    ├── seo-audit/
    └── ...                    # 50 skills au total
```

## Comment utiliser les skills

- Chaque skill vit dans `.opencode/skills/<id>/SKILL.md` (spécification
  [Agent Skills](https://agentskills.io)). Invoquez-en un avec l'outil `skill`
  (ID exact, ex. `cro`) ou mentionnez-le en clair dans une demande.
- `product-marketing` est la fondation : tous les autres skills vérifient
  d'abord le document de contexte `.agents/product-marketing.md`
  (produit, audience, positionnement, voix de marque). Si ce fichier n'existe
  pas encore, lancez le skill `product-marketing` pour le créer avant les
  autres tâches marketing.
- Les skills se croisent entre eux (ex. `copywriting` ↔ `cro` ↔ `ab-testing`).
  Chaque skill contient une section *Related Skills* qui indique les
  dépendances.

## Règles

- Respecter la description de chaque skill pour déclencher le bon outil.
- Ne pas inventer de données marché ou client : signaler ce qui manque
  (plusieurs skills exigent de labelliser les entrées manquantes en
  `MISSING` plutôt que d'estimer).
- Licences : la collection est sous licence MIT.
