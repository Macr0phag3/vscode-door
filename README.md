# vscode-door

> 利用 vscode 配置制作后门

在 `vscode-door` 下：

- 打包：`cd fake-usreagant && python setup.py sdist bdist_wheel; cd ..`
- 上传到 pypi：`twine upload dist/fake-usreagant-0.0.3.tar.gz`
- 搓搓手等待上线


> 触发

点击信任文件夹后：

1. 打开即可弹出计算器（首次打开取决于点击信任的速度，太慢则首次不会触发）
2. 触发格式化代码的时候会弹出计算器

注：`a.out` 是在 m1 的 macos `big sur` 版本中编译的，无法在其他平台执行。兼容问题需自行考虑解决。

其他姿势请自行摸索


## Others
<img src="https://clean-1252075454.cos.ap-nanjing.myqcloud.com/20200528120800990.png" width="500">

[![Stargazers over time](https://starchart.cc/Macr0phag3/vscode-door.svg)](https://starchart.cc/Macr0phag3/vscode-door)
