# 构成

- Vue3
- Vite@2.8
- TypeScript
- Prettier + Husky + Lint-Staged + Eslint
- pnpm@6.x
- Git

# 多环境

对于所有环境通用的，写入 `.env` 中。

对于不同的开发环境，使用 `.env.dev_[your_env_name]`，例如深圳 1 号测试环境，使用 `.env.dev_sztest01`

对于不同的生产环境，使用 `.env.prod_[your_env_name]`，例如广州部署环境，使用 `.env.prod_gz`

拉取项目下来后 **第一件事** 就是创建自己本机的环境文件。


# 参考

- [woai3c/vite-vue3-eslint-stylelint-demo](https://github.com/woai3c/vite-vue3-eslint-stylelint-demo)


# eslint

加上 `--fix` 可以自动修复，替代一些 prettier 的功能

# stylelint

postcss-html 包是 stylelint-plugin-recommend-vue 必须的一个 peerDeps，否则没法解析 .vue 文件里的 style 标签

加上 `--fix` 可以自动修复，替代一些 prettier 的功能
