# 快速上手

> 在開始之前，推薦先學習[React](http://facebook.github.io/react/) 、 [ES2015+](http://es6.ruanyifeng.com/) 、 [Antd Design](https:/ /ant.design/docs/react/introduce-cn) , 了解[UmiJS](https://umijs.org/) 、[Dva](http://github.com/dvajs/dva) ，並正確安裝和配置了[Node.js](https://nodejs.org/) v8 或以上、[Git](https://git-scm.com/)。提前了解和學習這些知識會非常有幫助。

## 安裝

```bash
git clone https://github.com/zuiidea/antd-admin.git my-project
cd my-project
```

## 目錄結構

應用的目錄結構如下

```bash
├── dist/               # 默認build輸出目錄
├── mock/               # Mock文件目錄
├── public/             # 靜態資源文件目錄
├── src/                # 源碼目錄
│ ├── components/       # 組件目錄
│ ├── e2e/              # e2e目錄
│ ├── layouts/          # 佈局目錄
│ ├── locales/          # 國際化文件目錄
│ ├── models/           # 數據模型目錄
│ ├── pages/            # 頁面組件目錄
│ ├── services/         # 數據接口目錄
│ │ ├── api.js          # 接口配置
│ │ └── index.js        # 接口輸出
│ ├── themes/           # 項目樣式目錄
│ │ ├── default.less    # 樣式變量
│ │ ├── index.less      # 全局樣式
│ │ ├── mixin.less      # 樣式函數
│ │ └── vars.less       # 樣式變量及函數
│ ├── utils/            # 工具函數目錄
│ │ ├── config.js       # 項目配置
│ │ ├── constant.js     # 靜態常量
│ │ ├── index.js        # 工具函數
│ │ ├── request.js      # 異步請求函數(axios)
│ │ └── theme.js        # 項目需要在js中使用到樣式變量
├── .editorconfig       # 編輯器配置
├── .env                # 環境變量
├── .eslintrc           # ESlint配置
├── .gitignore          # Git忽略文件配置
├── .prettierignore     # Prettier忽略文件配置
├── .prettierrc         # Prettier配置
├── .stylelintrc.json   # Stylelint配置
├── .travis.yml         # Travis配置
└── .umirc.js           # Umi配置
└── package.json        # 項目信息
```

## 本地開發

1. 進入目錄安裝依賴，國內用戶推薦使用 [cnpm](https://cnpmjs.org) 進行加速

```bash
yarn install
```

或者

```bash
npm install
```

2. 啟動本地服務器

```bash
npm run start
```

3. 啟動完成後打開瀏覽器訪問 [http://localhost:7000](http://localhost:7000)，如果需要更改啟動端口，可在 `.env` 文件中配置。