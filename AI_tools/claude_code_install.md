
```
https://registry.npmjs.org/@anthropic-ai/claude-code/-/claude-code-1.0.58.tgz
https://registry.npmjs.org/@anthropic-ai/claude-code/-/claude-code-1.0.64.tgz // 使用这个可以下载
```

## npm 官方包
[@anthropic-ai/claude-code - npm](https://www.npmjs.com/package/@anthropic-ai/claude-code/v/1.0.64)

[registry.npmjs.org](https://registry.npmjs.org/@anthropic-ai/claude-code/-/claude-code-1.0.72.tgz)

## 安装方式
pnpm add -g xx.tgz

更新失败之后的处理
  1. 首先卸载当前版本

  pnpm uninstall -g @anthropic-ai/claude-code

  2. 从本地tgz文件安装1.0.72版本

  pnpm install -g "d:\Users\Downloads\claude-code-1.0.72.tgz"

  3. 验证安装

  claude --version

  注意事项：
  - 使用完整的文件路径并加引号
  - 确保tgz文件路径正确
  - 如果仍有问题，可能需要清理pnpm缓存：pnpm store prune

