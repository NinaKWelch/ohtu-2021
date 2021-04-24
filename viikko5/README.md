# Git

## git: tägit

1. Katso tägit

```
git tag
git tag -l
git tag -l "tagi1"
```

2. Luo annotated-tägi

```
git tag -a tagi1 -m "my tagi1"
```

3. Katso tägin tiedot

```
git show tagi1
```

4. Luo lightweight-tägi

```
git tag tagi2
```

5. Luo tägi jälkeenpäin

Katso logi, esim:

```
git log --pretty=oneline
9fceb02d0ae598e95dc970b74767f19372d61af8 Update rakefile
964f16d36dfccde844893cac5b347e7b3d44abbc Commit the todo
8a5cbc430f1a9c3d00faaeffd07798508422908a Update readme
```

Luo tägi “Update rakefile” -committiin

```
git tag -a tagi3 9fceb02
git tag
```

6. Pushaa tägi tai tägit repoon

```
git push origin tagi3
git push origin --tags
```

7. Tägin poisto

Paikallisesti:

```
git tag -d v1.4-lw
```

Reposta:

```
git push origin --delete <tagname>

git push origin :refs/tags/v1.4-lw
```

8. Palaa aikaisempaan tägiin

```
git checkout v2.0.0
```




## Linkkejä

- [Git Basics - Tagging](http://git-scm.com/book/en/v2/Git-Basics-Tagging)