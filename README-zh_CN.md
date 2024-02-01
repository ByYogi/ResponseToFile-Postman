修改参考自issue： https://github.com/sivcan/ResponseToFile-Postman/issues/6#issuecomment-1261704791

这个东西是postman发送请求获取文件流 可以自动保存文件到目录。 不需要手动保存了。 只要不断点击请求就好了。 测试非常方便。

`npm`运行这个脚本。`npm script.js` 保持运行
复制 `postmanTestScript.txt` 里面的代码到文件夹里面的b`Test script`.
该文件夹下面的所有请求都会被代理到 这个脚本处理。 然后保存响应文件夹
