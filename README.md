# Blog
Proyecto de blog ETS


```bash
git checkout main

Ya en 'main'
Tu rama está actualizada con 'origin/main'.

git pull origin main

Desde https://github.com/lerouxgabri/Blog
 
 * branch            main       -> FETCH_HEAD

Ya está actualizado.
```

```bash
git checkout -b version-1

Cambiado a nueva rama 'version-1'

git branch

main
* version-1
```

```bash
git push -u origin version-1

* [new branch]      version-1 -> version-1
rama 'version-1' configurada para rastrear 'origin/version-1'.
```

```bash
git add .
git commit -m "Inicio de la version 1 del proyecto"

En la rama version-1
Tu rama está actualizada con 'origin/version-1'.
```

```bash
git branch -r

 origin/HEAD -> origin/main
 origin/main
 origin/version-1
```

```bash

checkout main
Cambiado a rama 'main'

git merge -version1
Fast-forward
 README.md | 59 +++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 1 file changed, 59 insertions(+)
git push
```
