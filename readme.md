# Wiki botanique

Un carnet d'apprentissage pour identifier, comprendre et entretenir les plantes.

Le projet est volontairement simple : chaque plante est une fiche Markdown, les photos sont rangees dans `photos/`, et l'index permet de retrouver rapidement les fiches deja creees.

## Catalogue des plantes

| Nom commun | Nom scientifique | Famille | Milieu | Niveau |
| --- | --- | --- | --- | --- |
| [Pigamon de Rochebrune](plantes/thalictrum-rochebrunianum.md) | *Thalictrum rochebrunianum* | Ranunculaceae | Vivace de jardin | Debut |
| [Thym serpolet 'Coccineus'](plantes/thymus-serpyllum-coccineus.md) | *Thymus serpyllum* 'Coccineus' | Lamiaceae | Rocaille et jardin sec | Debut |
| [Thym serpolet 'Elfin'](plantes/thymus-serpyllum-elfin.md) | *Thymus serpyllum* 'Elfin' | Lamiaceae | Rocaille et jardin sec | Debut |
| [Ephemere de Virginie 'Sweet Kate'](plantes/tradescantia-andersoniana-sweet-kate.md) | *Tradescantia* x *andersoniana* 'Sweet Kate' | Commelinaceae | Massif frais et mi-ombre | Debut |
| [Coreopsis 'Moonbeam'](plantes/coreopsis-verticillata-moonbeam.md) | *Coreopsis verticillata* 'Moonbeam' | Asteraceae | Massif ensoleille et jardin sec | Debut |
| [Verveine de Buenos Aires](plantes/verbena-bonariensis.md) | *Verbena bonariensis* | Verbenaceae | Massif ensoleille et bordure | Debut |
| [Origan 'Kent Beauty'](plantes/origanum-kent-beauty.md) | *Origanum vulgare* 'Kent Beauty' | Lamiaceae | Massif sec, rocaille et bordure | Debut |
| [Aster de Frikart 'Monch'](plantes/aster-frikartii-monch.md) | *Aster x frikartii* 'Monch' | Asteraceae | Massif ensoleille | Debut |

Le [catalogue complet](plantes/index.md) permet de consulter les plantes disponibles et de les classer au fur et a mesure.

## Organisation

```text
botanique/
├── plantes/
│   ├── index.md             # Catalogue des plantes
│   ├── modele-fiche.md      # Modele a copier pour chaque nouvelle plante
│   └── thalictrum-rochebrunianum.md
├── photos/
│   └── README.md            # Regles de nommage et emplacement des images
├── ressources/
│   └── README.md            # Livres, sites et sources utiles
└── readme.md
```

## Ajouter une plante

1. Copier `plantes/modele-fiche.md`.
2. Renommer la copie avec le nom scientifique, par exemple `ficus-elastica.md`.
3. Completer les informations et ajouter une photo dans `photos/`.
4. Ajouter un lien vers la nouvelle fiche dans `plantes/index.md`.
5. Noter la source des informations dans la section `Sources`.

## Navigation

- [Catalogue des plantes](plantes/index.md)
- [Modele de fiche](plantes/modele-fiche.md)
- [Organisation des photos](photos/README.md)
- [Ressources et sources](ressources/README.md)

## Principes de classement

- **Nom scientifique** : nom de fichier et classement principal, car il reste stable malgré les noms communs.
- **Nom commun** : utile pour la recherche et l'apprentissage.
- **Famille botanique** : a renseigner quand elle est connue.
- **Niveau de confiance** : distinguer une information verifiee d'une observation personnelle.
- **Date de mise a jour** : garder une trace des progres et des corrections.
