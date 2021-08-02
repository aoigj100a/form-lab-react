# form-lab-react

測試 React Material-UI 並且實作下載功能。

## 建置環境
1. react-router-dom
2. material-ui/core
3. material-ui/icons
4. react-pdf/renderer v2.0.17

## 安裝與執行步驟 (Installation and Execution)
1. 將專案複製到本機 (兩種方法)
> (1) 打開終端機輸入 
`git clone https://github.com/aoigj100a/form-lab-react`</br>
> (2) 點選 download ZIP 下載

2. 進入專案資料夾安裝工具包
> 打開終端機輸入
`npm install`

3. 啟動專案
> 安裝完畢之後在終端機輸入
`npm start`

### 問題與解決
- [Error “render is a Node specific API” when using the module @react-pdf/renderer](https://stackoverflow.com/questions/67185914/error-render-is-a-node-specific-api-when-using-the-module-react-pdf-renderer)
- [`npm i @react-pdf/renderer` 出現錯誤 ERESOLVE unable to resolve dependency tree 因 npm7 預設"peerDependencies are installed by default" 使用`npm i @react-pdf/renderer --force`安裝成功](https://docs.npmjs.com/cli/v7/configuring-npm/package-json#peerdependencies):ok::heavy_check_mark:
- [使用usePDF 觸發 Error: Invalid hook call. Hooks can only be called inside of the body of a function component -> 將函示元件中 hook 位置調整](https://reactjs.org/link/invalid-hook-call):ok::heavy_check_mark:
- [使用 PDFDownloadLink 會觸發 Error: Argument appears to not be a ReactComponent.](https://www.google.com.tw/search?q=Error:+Argument+appears+to+not+be+a+ReactComponent.+Keys:+type,box,style,props,children&source=lmns&hl=zh-TW&sa=X&ved=2ahUKEwjN6eakjpLyAhXFIqYKHX5wDVAQ_AUoAHoECAEQAA)
<!-- - :joy_cat: :ok::heavy_check_mark: -->

### 參考資料
 - [Material-UI 自訂客製化樣式](https://www.youtube.com/watch?v=bDkB3LoQKxs)
 - [在 React 中使用 Emmet](https://www.youtube.com/watch?v=ph65TPiNmKo)
 - [KendoReact - 需付費](https://www.telerik.com/kendo-react-ui/components/introduction/)
 - [如何使用 Node、React 元件產生 PDF](https://www.pdftron.com/blog/react/react-to-pdf/)
 - [react-pdf v2.0](https://react-pdf.org/blog/announcing-react-pdf-v2)

### 搜尋關鍵字
- material-ui create pdf

## 專案開發人員

>[AOI](https://github.com/aoigj100a)
