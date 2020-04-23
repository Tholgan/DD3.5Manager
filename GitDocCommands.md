```bash
# Récupérer le répertoire du projet
git clone l_adrese_du_repo
```

```bash
# Créer une branche en local (sur votre poste):
git checkout develop
git pull -r
git checkout -b nom_de_branche/USNuméroTicket
# exemple dans le cadre d'une type de demande feature
# git checkout -b feature/US001
```

```bash
# Pousser votre branche sur le repos distant:
git push --set-upstream origin nom_de_branche
# exemple git push --set-upstream origin feature/US001
```

