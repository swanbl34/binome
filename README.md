# Binôme — séances de salle à deux

Copie **publique** de l'app présentée sur
[swanbadol.com/labo/binome](https://www.swanbadol.com/labo/binome).

Une web app à installer sur l'écran d'accueil : elle ouvre la séance du jour,
on coche chaque série, le repos démarre tout seul, et la charge notée est
reprise la fois suivante. Toutes les données restent dans le navigateur : aucun
compte, aucun serveur, rien qui sorte du téléphone.

## Ce qui a été changé pour la mise en ligne

Cette copie est **générée** depuis la version privée par un script
(`build-public.mjs`) qui échoue plutôt que de publier s'il retrouve une des
données retirées. Ce dépôt ne contient que le build.

- Les **prénoms** des deux personnes pour qui l'app a été faite sont remplacés
  par deux prénoms fabriqués, Alex et Sam, jusque dans les clés de stockage.
- L'app est servie sous `/binome/` au lieu de la racine.

Les programmes, les exercices et la logique de séance ne sont pas touchés.
