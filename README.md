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

## Carton réponse (RSVP)

Les réponses sont enregistrées dans la table `public.mariage_rsvp` du projet Supabase « maisonno's Project » (oalmrauioqztacxemfto).
Le site utilise la clé publishable (publique par conception). La sécurité au niveau des lignes (RLS) n'autorise que l'ajout de réponses : personne ne peut les lire ni les modifier depuis le site.
Pour consulter les réponses : Table Editor de Supabase, ou `select * from mariage_rsvp order by created_at;`.
