# Gitee OpenApi
非官方整理Gitee openapi.内容整理于 [https://gitee.com/api/v5/swagger#/getV5ReposOwnerRepoStargazers?ex=no](https://gitee.com/api/v5/swagger#/getV5ReposOwnerRepoStargazers?ex=no)

文件结构符合openapi接口，可直接再swagger中调用。
接口未经验证，并持续整理。欢迎提交PR。

最后更新日期: **2023/11/25**

## Gen
通过工具将`openapi.json`转换成其他格式
```shell
api-spec-converter --from=openapi_3 --to=swagger_2 --syntax=yaml --order=alpha openapi.json > /gen/swagger.yaml
```