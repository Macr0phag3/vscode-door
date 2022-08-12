# vscode-door

> 利用 vscode 配置制作后门

在 `vscode-door` 下：

- 打包：`cd fake-usreagant && python setup.py sdist bdist_wheel; cd ..`
- 上传：`twine upload dist/fake-usreagant-0.0.3.tar.gz`


> 触发

1. 点击信任文件夹后即可弹出计算器
2. 触发格式化代码的时候也会弹出计算器

注：`a.out` 是在 m1 的 macos `big sur` 版本中编译的，无法在其他平台执行。兼容问题需自行考虑解决。
