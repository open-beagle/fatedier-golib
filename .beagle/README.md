# version

<!-- https://github.com/fatedier/golib -->

```bash
git remote add upstream git@github.com:fatedier/golib.git

git fetch upstream

git merge upstream/dev
```

## dev

```bash
# 新建一个Tag
git tag v0.2.0-beagle.0

# 推送一个Tag ，-f 强制更新
git push -f origin v0.2.0-beagle.0

# 删除本地Tag
git tag -d v0.2.0-beagle.0
```

## realse

```bash
# 新建一个Tag
git tag v0.2.0-beagle

# 推送一个Tag ，-f 强制更新
git push -f origin v0.2.0-beagle

# 删除本地Tag
git tag -d v0.2.0-beagle
```

## debug

```bash
go vet ./...
```
