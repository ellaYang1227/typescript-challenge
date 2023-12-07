# typescript-challenge

## 開發環境

1. Node：v18.16.0
2. NPM：v9.5.1

## 安裝流程

### 安裝 NPM

```
npm install
```

### 開發環境

```
npm run dev
```

### 執行測試檔

```
npm run test
```

### 執行測試檔 - 生成測試覆蓋率報告

```
npm run test:coverage
```

## 開啟測試覆蓋率報告網頁

使用 VS Code Live Server 套件，開啟本機端網站

```
coverage/index.html
```

## 如何下載

將專案 git push 至 GitHub main 分支時，使用 GitHub Actions 執行 TypeScript 專案測試的 workflow 文件，當 jobs 完成後，將自動產生測試覆蓋率報告，可至 GitHub Actions 下的 Artifacts 專區下載其壓縮檔(檔名：coverage-report)。

### 使用 VS Code Live Server 套件，開啟本機端網站

```
coverage-report/index.html
```

![image](https://github.com/ellaYang1227/typescript-challenge/blob/main/FireShot%20Capture%20063%20-%20Code%20coverage%20report%20for%20All%20files%20-%20127.0.0.1.png?raw=true)
