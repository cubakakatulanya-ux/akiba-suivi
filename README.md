# Akiba Suivi

Application de suivi des AVEC pour les **animateurs de terrain**, les **organisations** et
l'**administration d'Ubora**. Elle s'installe sur le téléphone ou l'ordinateur et fonctionne sans réseau.

👉 **https://avec.uborardc.com**

Les groupes, eux, travaillent sur **Akiba** : https://akiba.uborardc.com

## Ce dépôt

Il ne contient **que le résultat de la construction**. Le code source vit dans
[`akiba-avec`](https://github.com/cubakakatulanya-ux/akiba-avec), d'où les deux applications sont
construites à partir des mêmes fichiers :

    node build.js docs              # Akiba, pour les groupes
    node build.js docs-suivi suivi  # Akiba Suivi, ce dépôt

Pour publier une nouvelle version : reconstruire `docs-suivi/` dans `akiba-avec`, copier son contenu ici,
puis valider et pousser. Ne modifiez rien directement dans ce dépôt : la prochaine construction
l'écraserait, et les règles de calcul de l'AVEC doivent rester à un seul endroit.

## Mise en ligne

GitHub Pages sert la branche `main` depuis la racine. Le fichier `CNAME` fixe le domaine
`avec.uborardc.com`, qui demande chez le fournisseur du domaine un enregistrement **CNAME** :
`avec` → `cubakakatulanya-ux.github.io`.

---

Développée par l'**Entreprise Sociale Ubora** (Lubumbashi, RDC) · 0998 275 144
