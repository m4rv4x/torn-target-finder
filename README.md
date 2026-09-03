# Baldr Custom — Torn Target List

Une **liste de cibles personnalisée** pour Torn, construite depuis **tes propres logs d'attaques** via l'API officielle. Hébergée sur GitHub Pages, 100% côté client.

## 🔗 Accès

**Page :** https://m4rv4x.github.io/torn-baldr-custom/

## ✨ Fonctionnalités

- **BYO API key** — tu renseignes **ta** clé API Torn (stockée uniquement dans ton navigateur, jamais envoyée ailleurs)
- **Logs d'attaques** — la liste est construite depuis ton historique d'attaques (`attacksfull`)
- **Pagination** — charge les attaques plus anciennes en continu
- **Enrichissement** — niveau + stats de combat de chaque cible
- **Filtres** — victoires / défaites / mugs / hosp
- **Recherche** — par nom ou ID
- **Tri** — par nom, niveau, nombre d'attaques, résultat, dernière attaque
- **Export CSV**

## 🚀 Utilisation

1. Ouvre la page
2. Colle ta clé API Torn (scopes `Public` + `User`)
3. Clique **« Charger mes logs d'attaques »**
4. Clique **« Charger plus »** pour remonter plus loin dans l'historique

## 🔒 Confidentialité

- La clé API est stockée en `localStorage` (ton navigateur uniquement)
- Les requêtes vont **directement** à `api.torn.com` — aucun serveur intermédiaire
- Aucune donnée n'est collectée par ce site

## 🛠️ Développement local

```bash
# Clone
git clone https://github.com/m4rv4x/torn-target-finder.git
cd torn-target-finder

# Sers localement (n'importe quel serveur statique)
python3 -m http.server 8000
# → http://localhost:8000
```

## 📄 Licence

MIT — outil indépendant, non affilié à Torn City.
