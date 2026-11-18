# artfilms-media

Hebergement de fichiers pour la publication Meta, rien d'autre.

Meta ne recoit pas d'octets : elle va CHERCHER la video a une URL publique. Ce
depot sert uniquement de Releases, ou `scripts/meta_publish.py` depose le master
d'un Short avant de donner le lien a Facebook ou Instagram.

Chaque fichier porte les 16 premiers signes du SHA-256 de la video. Une URL ne
peut donc jamais pointer sur un autre montage que celui qui l'a produite — c'est
l'incident du 2026-10-31, ou quatre clips portaient la copie d'une version
anterieure du master.

Aucun code ici. Le depot doit rester PUBLIC : Meta telecharge sans jeton.
