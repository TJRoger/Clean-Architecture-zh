# Clean-Architecture-zh

《架构整洁之道》中文翻译

在线阅读：[http://gdut_yy.gitee.io/doc-cleanarch/](http://gdut_yy.gitee.io/doc-cleanarch/)
GitHub Pages：[https://tjroger.github.io/Clean-Architecture-zh/](https://tjroger.github.io/Clean-Architecture-zh/)

<img src="./docs/cover.jpg" width=24% />

## 前言

## Index

- [第一部分 概述](docs/part1.md)
- [第 1 章 设计与架构究竟是什么](docs/ch1.md)
- [第 2 章 两个价值维度](docs/ch2.md)

---

- [第二部分 从基础构件开始：编程范式](docs/part2.md)
- [第 3 章 编程范式总览](docs/ch3.md)
- [第 4 章 结构化编程](docs/ch4.md)
- [第 5 章 面向对象编程](docs/ch5.md)
- [第 6 章 函数式编程](docs/ch6.md)

---

- [第三部分 设计原则](docs/part3.md)
- [第 7 章 SRP：单一职责原则](docs/ch7.md)
- [第 8 章 OCP：开闭原则](docs/ch8.md)
- [第 9 章 LSP：里氏替换原则](docs/ch9.md)
- [第 10 章 ISP：接口隔离原则](docs/ch10.md)
- [第 11 章 DIP：依赖反转原则](docs/ch11.md)

---

- [第四部分 组件构建原则](docs/part4.md)
- [第 12 章 组件](docs/ch12.md)
- [第 13 章 组件聚合](docs/ch13.md)
- [第 14 章 组件耦合](docs/ch14.md)

---

- [第五部分 软件架构](docs/part5.md)
- [第 15 章 什么是软件架构](docs/ch15.md)
- [第 16 章 独立性](docs/ch16.md)
- [第 17 章 划分边界](docs/ch17.md)
- [第 18 章 边界剖析](docs/ch18.md)
- [第 19 章 策略与层次](docs/ch19.md)
- [第 20 章 业务逻辑](docs/ch20.md)
- [第 21 章 尖叫的软件架构](docs/ch21.md)
- [第 22 章 整洁架构](docs/ch22.md)
- [第 23 章 展示器和谦卑对象](docs/ch23.md)
- [第 24 章 不完全边界](docs/ch24.md)
- [第 25 章 层次与边界](docs/ch25.md)
- [第 26 章 Main 组件](docs/ch26.md)
- [第 27 章 服务：宏观和微观](docs/ch27.md)
- [第 28 章 测试边界](docs/ch28.md)
- [第 29 章 整洁的嵌入式架构](docs/ch29.md)

---

- [第六部分 实现细节](docs/part6.md)
- [第 30 章 数据库只是实现细节](docs/ch30.md)
- [第 31 章 Web 是实现细节](docs/ch31.md)
- [第 32 章 应用程序框架是实现细节](docs/ch32.md)
- [第 33 章 案例分析：视频销售网站](docs/ch33.md)
- [第 34 章 拾遗](docs/ch34.md)

## 本地开发 & 阅读

本项目基于 vuepress 进行开发，以提供比 github mardown 更佳的阅读体验

### 环境要求

- Node.js v16.x (推荐使用 nvm 管理 Node.js 版本)
- Yarn 包管理器
- Git

### 安装步骤

1. 安装 Node.js v16
```sh
# 使用 nvm 安装 Node.js v16
nvm install 16
nvm use 16
```

2. 安装 Yarn
```sh
# 使用 npm 安装 Yarn
npm install -g yarn
```

3. 克隆项目
```sh
git clone https://github.com/tjroger/Clean-Architecture-zh.git
cd Clean-Architecture-zh/
```

4. 安装依赖
```sh
yarn install
```

### 本地开发

```sh
# 启动开发服务器
yarn docs:dev

# 访问本地开发环境
http://localhost:8080/doc-cleanarch/
```

### 构建部署

#### 部署到 GitHub Pages

1. 确保已经配置好 GitHub SSH 密钥
2. 运行部署脚本
```sh
./github-deploy.sh
```

#### 部署到 Gitee Pages

1. 确保已经配置好 Gitee SSH 密钥
2. 运行部署脚本
```sh
./gitee-deploy.sh
```

### 常见问题

1. 如果遇到 OpenSSL 相关错误，请确保使用 Node.js v16
2. 如果遇到权限问题，请检查 SSH 密钥配置
3. 部署后可能需要等待几分钟才能在 Pages 上看到更新

## License

[MIT](https://github.com/gdut-yy/Clean-Architecture-zh/blob/master/LICENSE)
