# MYAN.APP

Application web progressive de gestion des invitations et de contrôle des entrées.

## Fonctions
- Ajouter des invités individuellement.
- Importer une liste Excel (.xlsx/.xls) ou CSV avec les colonnes **Nom**, **Statut**, **Table**.
- Générer un QR individuel contenant uniquement le nom, le statut et la table.
- Scanner les QR avec la caméra du téléphone.
- Accepter une première lecture et refuser une lecture répétée.
- Tableau de bord : personnes attendues, présentes, absentes et places non occupées.
- Un statut **Couple** compte pour 2 personnes ; les autres statuts comptent pour 1.
- Exporter la liste en CSV.

## Déploiement
Dans GitHub : **Settings → Pages → Deploy from a branch → main → /(root) → Save**.

L'application fonctionne sur HTTPS. Autorisez la caméra dans Safari. Les données sont stockées localement dans le navigateur de l'appareil. Faites régulièrement un export CSV de sauvegarde.

## Limites actuelles
Le scanner QR et la lecture Excel utilisent des bibliothèques chargées depuis des CDN : une connexion internet est nécessaire pour charger ces outils. Les données restent sur l'appareil et ne sont pas synchronisées entre plusieurs téléphones.
