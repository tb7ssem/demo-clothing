# Demo Store — Mode (boutique de démonstration)

Version **mode & accessoires** du magasin de démonstration, présentée aux boutiques de vêtements.

- Catalogue : 35 produits (femme, homme, chaussures, accessoires) avec photos réelles issues de sources publiques (dummyjson.com), prix indicatifs en DT.
- Bilingue : `/` (français) et `/ar` (arabe).
- Commandes enregistrées puis ouvertes sur WhatsApp (numéro configurable dans **Admin → Paramètres**).
- Paiement à la livraison, livraison 24–48h.

## Accès admin

| | |
|---|---|
| URL | `/admin` |
| Mot de passe | `demostore2026` (ou `DEMO_ADMIN_PASSWORD`) |

## Déploiement

Hébergé sur Vercel : https://demo-clothing-self.vercel.app — persistance via Vercel Blob (store privé `demo-clothing-data`).

```bash
vercel deploy --prod --yes
```
