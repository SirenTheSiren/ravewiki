.. _init-repo:

Git Repository initialisieren
=====================================================

Schritte
--------

1. Creating a new repository on the command line
```
touch README.md
git init
git checkout -b main
git add README.md
git commit -m "first commit"
git remote add origin https://git.sirenthesiren.xyz/SirenTheSiren/berufsschule.git
git push -u origin main
```

2. Pushing an existing repository from the command line
```
git remote add origin https://git.sirenthesiren.xyz/SirenTheSiren/berufsschule.git
git push -u origin main
```
