# MaaResourcesMirror

相关资源：[MaaResourcesSync](https://github.com/LaviniaFalcone/MaaResourceSync)

## 如何修改更新源

如果你想让MRS从自己的仓库拉取更新，需要自己生成一个公钥添加到自己仓库的 `Deploy keys` 列表中，然后将 `sync.bat` 中的：

```shell
git remote add mirror git@github.com:LaviniaFalcone/MaaResourceMirror
```

更改为：

```shell
git remote add mirror git@github.com:你的用户名/你的仓库
```
