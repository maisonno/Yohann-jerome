# Mariage de Jérôme & Yohann

Site du mariage, les 9 et 10 avril 2027 sur l'île du Levant.

Site statique, sans étape de build : tout est dans `index.html` (HTML, CSS et JS), avec les polices dans `fonts/` et le plan d'Héliopolis dans `images/`.

## Mettre à jour

Modifier `index.html`, puis commit et push sur `main` : Cloudflare Pages redéploie automatiquement.

Les zones encore à compléter :
- fiche « Studio 80 » dans la section Où dormir (`id="dormir"`)
- horaires des trains et des bateaux d'avril 2027 (marqués « À confirmer » dans la section `id="venir"`)

## Hébergement

Cloudflare Pages, connecté à ce dépôt :
- Framework preset : None
- Build command : (vide)
- Build output directory : `/`
