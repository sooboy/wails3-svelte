# clone 下来后 首先修改 go.mod 中的 module 名称
```
module github.com/xxx/xxx
```
[]: # 然后执行 go mod tidy 生成 go.mod 和 go.sum
```
go mod tidy
```
# 可以去build 目录下 修改 logo 文件 替换成自己的

·