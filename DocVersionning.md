# Versionning/Changelog

Pour pouvoir suivre les règles de commit et mettre à jour le changelog suivez cette doc.

## Procédure de commit :

# utiliser git cz

```bash
git cz
```

- selectionner le type de changement (fix ou feature)

- (facultatif) rentrer le scope du changement

- rentrer la description du commit

- (facultatif) si besoin rentrer plus d'infos sur le commit

## - ATTENTION ICI METTRE YES SEULEMENT SI C'EST UN GROS CHANGEMENT (nouvelle version des guid lines), CELA CHANGERA LE VERSION MAJEUR DE L'APPLICATION.

- enter yes if only you have a ticket for this change

### Procédure de MAJ du changelog :

# utiliser npm run release

```bash
npm run release
git push --follow-tags 
```

