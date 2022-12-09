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

- rentrer yes si c'est un gros changement (nouvelle version des guide lines)

- enter yes if only you have a ticket for this change

### Procédure de MAJ du changelog :

# utiliser npm run release

```bash
npm run release
git push --follow-tags 
```

