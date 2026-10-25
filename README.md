# akio CMS — versions publiées

Ce dépôt ne contient que les versions publiées d'akio CMS : chaque *release* porte le zip du dossier `cms/` et un `latest.json` (version, empreinte SHA-256, nouveautés).

Les sites qui utilisent akio CMS lisent `releases/latest/download/latest.json` pour proposer la mise à jour dans leur admin. Les versions sont publiées par `tools/release.mjs` depuis le dépôt du CMS.
