
## Getting Started

### 安装：

```bash
npm install -g @fast-learn/core
```

### 创建项目

项目/组件初始化

```bash
fast-learn init
```

强制清空当前文件夹

```bash
fast-learn init --force
```

### 发布项目

发布项目/组件

```bash
fast-learn publish
```

强制更新所有缓存

```bash
fast-learn publish --force
```

正式发布

```bash
fast-learn publish --prod
```

手动指定build命令

```bash
fast-learn publish --buildCmd "npm run build:test"
```


## More

清空本地缓存：

```bash
fast-learn clean
```

DEBUG 模式：

```bash
fast-learn --debug
```

调试本地包：

```bash
fast-learn init --packagePath /Users/sam/Desktop/fast-learn/packages/init/
```
