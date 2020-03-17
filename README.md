# Compass 指北針

這個專案是我個人網頁的專案，將會放上我個人的經歷和技術分享，跟一些我關注的議題的子頁面！因為是從 Vue.js 轉過來學習的關係，專案架構剛開始會長得很像用 vue.js 思考出來的長相，以後在透過 Refactoring 慢慢修改囉～

## 技術實作

目前規劃是這樣，因為我還在學 React，不是很想直接使用 Server-Side Rendering 的 next.js，所以單純用 React.js 的 Template 來實作囉

### 專案相關指令
```zsh
# 因為 create-react-app 不支援包含大寫的專案名稱，所以就先用小寫囉～
npx create-react-app compass

# Start Developmemt Server with Hot Reload Functionality.
npm start
```

### Git Version Control

目前只有我一個人在開發，所以沒必要分 Master 跟 Dev Branch。但基於所有的 Commit 都在 Master Branch 上也不是很好，所以每個 Feature 還是回獨立出去不同的 Branch，等完成到一個 Mile Stone 的時候在 Merge 回去 Master