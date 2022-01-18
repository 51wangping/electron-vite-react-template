#### electron-vite-react-template

### 技术架构

electron16 + react17 + vite

### 目录解构

```bash

├── dist/            # 打包文件
|  ├── assets/
|  └── mac-arm64/
├── electron/        # electron
|   ├── main.js      # 主进程
|   └── preload.js   # 渲染进程
└── src/             # 源码
├── vite.config.js   # vite 配置文件
```

### 命令

- `npm run dev`: web 端启动
- `npm run electron`: 开发环境启动 electron
- `npm run pack`: 构建生产环境调试文件
- `npm run dev:win64`: 构建生产 windows64 环境包
- `npm run dev:macArm`: 构建生产 mac --arm 环境包
