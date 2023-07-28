> 复现方式

1. 使用taro-cli 内置默认模板 初始化项目，详细见下面日志
2. 执行yarn dev:tt
3. 使用tt dev tool打开构建好的项目代码
4. 首页白屏


> 初始化日志

```bash
taro init learn-taro
👽 Taro v3.6.9

⚠ 获取 taro 全局配置文件失败，不存在全局配置文件：/Users/somebody/.taro-global-config/index.json


Taro 即将创建一个新项目!
Need help? Go and open issue: https://tls.jd.com/taro-issue-helper

? 请输入项目介绍 blah blah
? 请选择框架 React
? 是否需要使用 TypeScript ？ Yes
? 请选择 CSS 预处理器（Sass/Less/Stylus） Less
? 请选择编译工具 Webpack5
? 请选择包管理工具 yarn
? 请选择模板源 CLI 内置默认模板

✔ 创建项目: learn-taro
✔ 创建文件: /Users/somebody/workspace/learn-taro/.editorconfig
✔ 创建文件: /Users/somebody/workspace/learn-taro/.env.dev
✔ 创建文件: /Users/somebody/workspace/learn-taro/.env.prod
✔ 创建文件: /Users/somebody/workspace/learn-taro/.env.test
✔ 创建文件: /Users/somebody/workspace/learn-taro/.eslintrc
✔ 创建文件: /Users/somebody/workspace/learn-taro/.gitignore
✔ 创建文件: /Users/somebody/workspace/learn-taro/babel.config.js
✔ 创建文件: /Users/somebody/workspace/learn-taro/jest.config.ts
✔ 创建文件: /Users/somebody/workspace/learn-taro/package.json
✔ 创建文件: /Users/somebody/workspace/learn-taro/project.config.json
✔ 创建文件: /Users/somebody/workspace/learn-taro/project.tt.json
✔ 创建文件: /Users/somebody/workspace/learn-taro/tsconfig.json
✔ 创建文件: /Users/somebody/workspace/learn-taro/__tests__/index.test.js
✔ 创建文件: /Users/somebody/workspace/learn-taro/config/dev.ts
✔ 创建文件: /Users/somebody/workspace/learn-taro/config/index.ts
✔ 创建文件: /Users/somebody/workspace/learn-taro/config/prod.ts
✔ 创建文件: /Users/somebody/workspace/learn-taro/types/global.d.ts
✔ 创建文件: /Users/somebody/workspace/learn-taro/src/app.config.ts
✔ 创建文件: /Users/somebody/workspace/learn-taro/src/app.less
✔ 创建文件: /Users/somebody/workspace/learn-taro/src/app.ts
✔ 创建文件: /Users/somebody/workspace/learn-taro/src/index.html
✔ 创建文件: /Users/somebody/workspace/learn-taro/src/pages/index/index.config.ts
✔ 创建文件: /Users/somebody/workspace/learn-taro/src/pages/index/index.less
✔ 创建文件: /Users/somebody/workspace/learn-taro/src/pages/index/index.tsx

✔ cd learn-taro, 执行 git init
yarn install v1.22.19
info No lockfile found.
[1/4] Resolving packages...
⚠ warning @tarojs/cli > request@2.88.2: request has been deprecated, see https://github.com/request/request/issues/3142
⚠ warning @tarojs/cli > request > har-validator@5.1.5: this library is no longer supported
⚠ warning @tarojs/cli > request > uuid@3.4.0: Please upgrade  to version 7 or higher.  Older versions may use Math.random() in certain circumstances, which is known to be problematic.  See https://v8.dev/blog/math-random for details.
⚠ warning @tarojs/webpack5-runner > vm2@3.9.19: The library contains critical security issues and should not be used for production! The maintenance of the project has been discontinued. Consider migrating your code to isolated-vm.
⚠ warning @tarojs/webpack5-runner > stylus > css > source-map-resolve@0.6.0: See https://github.com/lydell/source-map-resolve#deprecated
⚠ warning @tarojs/webpack5-runner > vue-loader > @vue/component-compiler-utils > consolidate@0.15.1: Please upgrade to consolidate v1.0.0+ as it has been modernized with several long-awaited fixes implemented. Maintenance is supported by Forward Email at https://forwardemail.net ; follow/watch https://github.com/ladjs/consolidate for updates and release changelog
⚠ warning @tarojs/webpack5-runner > webpack-dev-server > webpack-dev-middleware > memfs@3.6.0: this will be v4
⚠ warning @tarojs/webpack5-runner > @tarojs/runner-utils > scss-bundle > @types/sass@1.45.0: This is a stub types definition. sass provides its own type definitions, so you do not need this installed.
⚠ warning @tarojs/webpack5-runner > css-minimizer-webpack-plugin > cssnano > cssnano-preset-default > postcss-svgo > svgo > stable@0.1.8: Modern JS already guarantees Array#sort() is a stable sort, so this library is deprecated. See the compatibility table on MDN: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/sort#browser_compatibility
[2/4] Fetching packages...
[3/4] Linking dependencies...
[4/4] Building fresh packages...
success Saved lockfile.
Done in 60.16s.
✔ 安装成功
创建项目 learn-taro 成功！
请进入项目目录 learn-taro 开始工作吧！😝
```

> 截图
![image](https://github.com/duibu05/learn-taro/assets/10591960/b0e3b9a7-0d33-4d7f-b7cd-e4d5caaecac8)
