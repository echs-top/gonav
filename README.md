# gonav

源项目 https://github.com/dengxiwang/go-nav ，action构建并生成方便linux_64平台运行(server模式)的文件，使用[bun](https://github.com/oven-sh/bun)作为启动器

# 目录

```
——目录
————.next
————data  #数据目录
————node_modules
————public  #文件目录
————.env.local  #环境变量
————package.json
————server.js
————bun  #运行器
```

# 运行
```
./bun --smol server.js
```

# 备份
需要备份 data文件夹、public文件夹、.env.local
