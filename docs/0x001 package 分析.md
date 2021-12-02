# package.json 分析

## main

作为 npm 包的入口文件，当使用 `require` 导入 npm 包时，返回 main 字段列出的文件的 `module.exports` 属性。如果不指定该字段，默认使用项目根目录下的 `index.js`。

这里使用 `src/Lib.js` 作为入口，导出一个 Rect 组件，再加上一堆配置。实际上是引用到了 `src/App.js`，就是编辑器的根组件。

## scripts 启动脚本

TODO:

一共有 8 个脚本。

### start 启动开发

## dependencies

TODO:

- `@sitdown/juejin` 掘金文章 HTML 转 md。
- `@sitdown/wechat` 微信文章 HTML 转 md。
- `@sitdown/zhihu` 知乎文章 HTML 转 md。
- `@uiw/react-codemirror` *** 网页代码编辑器。
- `ali-oss` 阿里云 OSS SDK。
- `antd` *** UI 库。
- `axios` 网络请求库。
- `diff-match-patch` 文本差异比较。
- `highlight.js` 代码语法高亮。
- `juice` 把 CSS 样式变成 HTML 标签内联样式。
- `lodash.debounce`  创建一个 debounced（防抖动）函数，该函数会从上一次被调用后，延迟 `wait` 毫秒后调用 `func` 方法。 
- `lodash.throttle` 频率限制。创建一个节流函数，在 wait 秒内最多执行 `func` 一次的函数。
- `markdown-it` Markdown 语法转换器
- [`markdown-it-deflist`](https://github.com/markdown-it/markdown-it-deflis) `<dl>` 标签插件。
- [`markdown-it-footnote`](https://www.npmjs.com/package/markdown-it-footnote)  footer 注脚插件。
- [`markdown-it-implicit-figures`](https://github.com/markdown-it/markdown-it-footnote#readme) 将图像渲染为 `<figure><img ...></figure>` 标签。
- [`markdown-it-imsize`](https://www.npmjs.com/package/markdown-it-imsize) 用于指定图像大小的插件。
- [`markdown-it-katex`](https://www.npmjs.com/package/markdown-it-katex) 公式插件。
- [`markdown-it-ruby`](https://github.com/lostandfound/markdown-it-ruby) ruby 注解解析插件。
- [`markdown-it-table-of-contents`](https://www.npmjs.com/package/markdown-it-table-of-contents) 表格插件。
- [`mathjax`](https://www.npmjs.com/package/mathjax) 又一个公式插件。
- [`mobx`](https://www.npmjs.com/package/mobx) 状态管理，类似 umi。
- [`mobx-react`](https://www.npmjs.com/package/mobx-react) 状态管理。
- [`prettier`](https://www.npmjs.com/package/prettier) 代码格式化。
- `qiniu-js` 七牛。
- `react`
- `react-dom`
- [`react-helmet`](https://www.npmjs.com/package/react-helmet) 一个 HTML 文档 head 管理工具，管理对文档头的所有更改。React Helmet 采用纯 HTML 标记并输出纯 HTML 标记，非常简单，对React初学者十分友好。
- `sitdown` HTML 转 MD。

## devDependencies

TODO:

- `@babel/cli`  Babel 命令行。
- `@babel/core` 
- [`@storybook/react`](https://www.npmjs.com/package/@storybook/react) React组件的UI开发环境。直接看到 UI 组件的不同状态，并以交互方式开发它们。
- `@svgr/webpack` 把 SVG 转化成 React 组件
- `babel-core`
- `babel-eslint`
- [`babel-jest`](https://www.npmjs.com/package/babel-jest) 测试。
- [`babel-loader`](https://webpack.docschina.org/loaders/babel-loader/) 此 package 允许你使用 Babel 和 webpack 转译 JavaScript 文件。
- `babel-plugin-inline-import`
- `babel-plugin-named-asset-import`
- `babel-preset-react-app`
- `bfj`
- `case-sensitive-paths-webpack-plugin`
- `chalk`
- `chokidar`
- `cross-env`
- `css-loader`
- `dotenv`
- `dotenv-expand`
- `eslint`
- `eslint-config-airbnb`
- `eslint-config-prettier`
- `eslint-config-react-app`
      "eslint-loader": "^2.1.1",
      "eslint-plugin-babel": "^5.3.0",
      "eslint-plugin-flowtype": "2.50.1",
      "eslint-plugin-import": "^2.14.0",
      "eslint-plugin-jsx-a11y": "^6.1.2",
      "eslint-plugin-prettier": "^3.1.1",
      "eslint-plugin-react": "^7.12.4",
      "file-loader": "2.0.0",
      "fork-ts-checker-webpack-plugin-alt": "0.4.14",
      "fs-extra": "7.0.1",
      "html-webpack-plugin": "4.0.0-alpha.2",
      "husky": "^3.0.7",
      "identity-obj-proxy": "3.0.0",
      "jest": "23.6.0",
      "jest-pnp-resolver": "1.0.2",
      "jest-resolve": "23.6.0",
      "jest-watch-typeahead": "^0.2.1",
      "lint-staged": "^9.4.0",
      "mini-css-extract-plugin": "0.5.0",
      "optimize-css-assets-webpack-plugin": "5.0.1",
      "pnp-webpack-plugin": "1.2.1",
      "postcss-flexbugs-fixes": "4.1.0",
      "postcss-loader": "3.0.0",
      "postcss-preset-env": "6.5.0",
      "postcss-safe-parser": "4.0.1",
      "pretty-quick": "^1.11.1",
      "raw-loader": "^4.0.0",
      "react-app-polyfill": "^0.2.1",
      "react-dev-utils": "^7.0.3",
      "resolve": "1.10.0",
      "sass-loader": "7.1.0",
      "shelljs": "^0.8.3",
      "source-map-explorer": "^2.0.1",
      "style-loader": "0.23.1",
      "styled-jsx": "^3.2.1",
      "terser-webpack-plugin": "1.2.2",
      "thread-loader": "^2.1.3",
      "to-string-loader": "^1.1.5",
      "url-loader": "1.1.2",
      "webpack": "4.28.3",
      "webpack-dev-server": "3.1.14",
      "webpack-manifest-plugin": "2.0.4",
      "workbox-webpack-plugin": "3.6.3"

## build

## eslintConfig

eslint 的配置可以写在单独的配置文件. eslintrc.json 中，也可以写在 package.json 文件的 eslintConfig 配置项中。

## browserslist

字段用来告知支持哪些浏览器及版本

## jest 测试

TODO:

## babel

用来指定 Babel 的编译配置

## husky

husky 是一个 Git Hook 工具。husky 其实就是一个为 git 客户端增加 hook 的工具。将其安装到所在仓库的过程中它会自动在 .git/ 目录下增加相应的钩子实现在 pre-commit 阶段就执行一系列流程保证每一个 commit 的正确性。部分 cd 在 commit stage 执行的命令可以挪动到本地执行，比如 lint 检查、比如单元测试。当然，pre-commit 阶段执行的命令当然要保证其速度不要太慢，每次 commit 都等很久也不是什么好的体验。

## lint-staged

lint-staged 是一个在 Git 暂存文件上运行 linters 的工具，配置后每次修改一个文件即可给所有文件执行一次 lint 检查，通常配合 gitHooks 一起使用。

使用 lint-staged 时，每次提交代码只会检查当前改动的文件。

```
{
  "name": "markdown-nice", // 包名，不用讲了
  "author": "mdnice",
  "description": "a markdown editor with the function of style edition",
  "version": "1.8.22",
  "private": false,
  "main": "lib/Lib.js", // 入口文件，重要
  "module": "lib/Lib.js",
  "homepage": "https://www.mdnice.com",
  "license": "GPL-3.0",
  "typings": "./lib/index.d.ts",
  "repository": {
    "type": "git",
    "url": "https://github.com/mdnice/markdown-nice"
  },
  "scripts": {
    "start": "node scripts/start.js", // 开发启动脚本
    "watch": "node ./watch.js",
    "build": "node --max_old_space_size=4096 scripts/build.js",
    "test": "node scripts/test.js",
    "analyze": "source-map-explorer build/static/js/*.js",
    "lint": "eslint src --ext ts,tsx,js --fix",
    "publish:npm": "cross-env NODE_ENV=production && rm -rf lib && mkdir lib && cross-env BABEL_ENV=production npx babel src --out-dir lib --copy-files",
    "storybook": "npm run publish:npm && start-storybook -p 9001 -c .storybook"
  },
  "dependencies": {
    "@sitdown/juejin": "^1.1.1",
    "@sitdown/wechat": "^1.1.4",
    "@sitdown/zhihu": "^1.1.2",
    "@uiw/react-codemirror": "^1.0.28",
    "ali-oss": "^6.1.1",
    "antd": "^3.15.1",
    "axios": "^0.18.0",
    "diff-match-patch": "^1.0.4",
    "highlight.js": "^9.15.6",
    "juice": "^5.2.0",
    "lodash.debounce": "^4.0.8",
    "lodash.throttle": "^4.1.1",
    "markdown-it": "^8.4.2",
    "markdown-it-deflist": "^2.0.3",
    "markdown-it-footnote": "^3.0.1",
    "markdown-it-implicit-figures": "^0.9.0",
    "markdown-it-imsize": "^2.0.1",
    "markdown-it-katex": "^2.0.3",
    "markdown-it-ruby": "^0.1.1",
    "markdown-it-table-of-contents": "^0.4.4",
    "mathjax": "^3.0.1",
    "mobx": "^5.9.0",
    "mobx-react": "^5.4.3",
    "prettier": "^1.19.1",
    "qiniu-js": "^2.5.4",
    "react": "16.10.2",
    "react-dom": "16.10.2",
    "react-helmet": "^5.2.1",
    "sitdown": "^1.1.3"
  },
  "devDependencies": {
    "@babel/cli": "^7.6.2",
    "@babel/core": "7.2.2",
    "@storybook/react": "^4.1.11",
    "@svgr/webpack": "^4.1.0",
    "babel-core": "7.0.0-bridge.0",
    "babel-eslint": "^9.0.0",
    "babel-jest": "23.6.0",
    "babel-loader": "8.0.5",
    "babel-plugin-inline-import": "^3.0.0",
    "babel-plugin-named-asset-import": "^0.3.1",
    "babel-preset-react-app": "^7.0.1",
    "bfj": "6.1.1",
    "case-sensitive-paths-webpack-plugin": "2.2.0",
    "chalk": "^2.4.2",
    "chokidar": "^3.2.1",
    "cross-env": "^6.0.3",
    "css-loader": "^2.1.1",
    "dotenv": "6.0.0",
    "dotenv-expand": "4.2.0",
    "eslint": "^6.5.0",
    "eslint-config-airbnb": "^18.0.1",
    "eslint-config-prettier": "^6.3.0",
    "eslint-config-react-app": "^3.0.7",
    "eslint-loader": "^2.1.1",
    "eslint-plugin-babel": "^5.3.0",
    "eslint-plugin-flowtype": "2.50.1",
    "eslint-plugin-import": "^2.14.0",
    "eslint-plugin-jsx-a11y": "^6.1.2",
    "eslint-plugin-prettier": "^3.1.1",
    "eslint-plugin-react": "^7.12.4",
    "file-loader": "2.0.0",
    "fork-ts-checker-webpack-plugin-alt": "0.4.14",
    "fs-extra": "7.0.1",
    "html-webpack-plugin": "4.0.0-alpha.2",
    "husky": "^3.0.7",
    "identity-obj-proxy": "3.0.0",
    "jest": "23.6.0",
    "jest-pnp-resolver": "1.0.2",
    "jest-resolve": "23.6.0",
    "jest-watch-typeahead": "^0.2.1",
    "lint-staged": "^9.4.0",
    "mini-css-extract-plugin": "0.5.0",
    "optimize-css-assets-webpack-plugin": "5.0.1",
    "pnp-webpack-plugin": "1.2.1",
    "postcss-flexbugs-fixes": "4.1.0",
    "postcss-loader": "3.0.0",
    "postcss-preset-env": "6.5.0",
    "postcss-safe-parser": "4.0.1",
    "pretty-quick": "^1.11.1",
    "raw-loader": "^4.0.0",
    "react-app-polyfill": "^0.2.1",
    "react-dev-utils": "^7.0.3",
    "resolve": "1.10.0",
    "sass-loader": "7.1.0",
    "shelljs": "^0.8.3",
    "source-map-explorer": "^2.0.1",
    "style-loader": "0.23.1",
    "styled-jsx": "^3.2.1",
    "terser-webpack-plugin": "1.2.2",
    "thread-loader": "^2.1.3",
    "to-string-loader": "^1.1.5",
    "url-loader": "1.1.2",
    "webpack": "4.28.3",
    "webpack-dev-server": "3.1.14",
    "webpack-manifest-plugin": "2.0.4",
    "workbox-webpack-plugin": "3.6.3"
  },
  "build": {
    "productName": "Markdown Nice",
    "appId": "com.mdnice.www",
    "mac": {
      "target": [
        "dmg",
        "zip"
      ]
    },
    "win": {
      "target": [
        "nsis",
        "zip"
      ]
    },
    "files": [
      "build",
      "main.js",
      "package.json"
    ]
  },
  "eslintConfig": {
    "extends": "react-app"
  },
  "browserslist": [
    ">0.2%",
    "not dead",
    "not ie <= 11",
    "not op_mini all"
  ],
  "jest": {
    "collectCoverageFrom": [
      "src/**/*.{js,jsx,ts,tsx}",
      "!src/**/*.d.ts"
    ],
    "resolver": "jest-pnp-resolver",
    "setupFiles": [
      "react-app-polyfill/jsdom"
    ],
    "testMatch": [
      "<rootDir>/src/**/__tests__/**/*.{js,jsx,ts,tsx}",
      "<rootDir>/src/**/?(*.)(spec|test).{js,jsx,ts,tsx}"
    ],
    "testEnvironment": "jsdom",
    "testURL": "http://localhost",
    "transform": {
      "^.+\\.(js|jsx|ts|tsx)$": "<rootDir>/node_modules/babel-jest",
      "^.+\\.css$": "<rootDir>/config/jest/cssTransform.js",
      "^(?!.*\\.(js|jsx|ts|tsx|css|json)$)": "<rootDir>/config/jest/fileTransform.js"
    },
    "transformIgnorePatterns": [
      "[/\\\\]node_modules[/\\\\].+\\.(js|jsx|ts|tsx)$",
      "^.+\\.module\\.(css|sass|scss)$"
    ],
    "moduleNameMapper": {
      "^react-native$": "react-native-web",
      "^.+\\.module\\.(css|sass|scss)$": "identity-obj-proxy"
    },
    "moduleFileExtensions": [
      "web.js",
      "js",
      "web.ts",
      "ts",
      "web.tsx",
      "tsx",
      "json",
      "web.jsx",
      "jsx",
      "node"
    ],
    "watchPlugins": []
  },
  "babel": {
    "presets": [
      "@babel/react"
    ],
    "plugins": [
      [
        "@babel/plugin-proposal-decorators",
        {
          "legacy": true
        }
      ],
      [
        "@babel/plugin-proposal-class-properties",
        {
          "loose": true
        }
      ]
    ],
    "env": {
      "production": {
        "plugins": [
          [
            "babel-plugin-inline-import",
            {
              "extensions": [
                ".md"
              ]
            }
          ]
        ]
      }
    }
  },
  "husky": {
    "hooks": {
      "pre-commit": "lint-staged"
    }
  },
  "lint-staged": {
    "src/**/*.{jsx,txs,ts,js,json}": [
      "prettier --write",
      "eslint --fix",
      "git add"
    ]
  }
}
```