# Git

## git: tägit

1. Katso tägit

```
git tag
git tag -l
git tag -l "v1.8.5*"
```

2. Luo annotated-tägi

```
git tag -a v1.4 -m "my version 1.4"
```

3. Katso tägin tiedot

```
git show v1.4
```

4. Luo lightweight-tägi

```
git tag v1.4-lw
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
git tag -a v1.2 9fceb02
git tag
```

## Linkkejä

- [Git Basics - Tagging](http://git-scm.com/book/en/v2/Git-Basics-Tagging)