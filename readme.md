# How to ...?

![How to](http://www.thehappinessfactory.be/blog/images/How.png)

## Remove Section

### remove Remotely

```sh
git push origin :dev
git push origin :test
```

### remove Localy

```sh
git branch -d dev
git branch -d test
```

## Tags Section

### list Tags

```sh
git tag
```

### delete tag locally

```sh
git tag -d v1.7
```

### delete tag remotely

```sh
git push origin :v1.7
```
