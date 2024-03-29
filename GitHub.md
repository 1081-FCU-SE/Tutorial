# 1081 軟工 Term Project GitHub 操作手冊
- [前言](#前言)
- [GitHub 帳號註冊](#github-帳號註冊)
- [建立小組專案](#建立小組專案)
- [開啟 Issue Tracker](#開啟-issue-tracker)
- [將其他組員設定為協作者](#將其他組員設定為協作者)
- [上傳檔案](#上傳檔案)


## 前言
這一章主要是 GitHub 的操作說明  
但還是要簡單講一下 GitHub 是什麼  
避免有人 Git、GitHub 分不清楚

如果你有印象的話，Git 可以同步所有開發者的 code  
但是實際要怎麼運作的呢？

其實概念很簡單，只需要架設Server，讓所有開發者連線到 Server 來同步就好  
而 GitHub 是一家公司提供免費服務，讓大家把 code 同步到他們的 Server  
（謎之聲：那他們怎麼賺錢（或是說維持營運）？可以自己看一下價格表）  
（謎之聲2：除了 GitHub，也有 Bitbucket、Gitlab、VSTS……其他相似的服務）

## GitHub 帳號註冊
1. 進入 [GitHub](https://github.com/) 網站
2. 填寫 `Username`、`Email`、`Password` ，並點擊 `Sign up for GitHub` 註冊帳號  
![](./img/GitHub/register_01.png)
3. 選擇 `Unlimited public repositories for free.` 並點擊 `Continue` 進入下一步  
![](./img/GitHub/register_02.png)
4. 填寫問卷或直接跳過  
![](./img/GitHub/register_03.png)
5. 請記得到信箱點擊驗證連結  
![](./img/GitHub/register_04.png)
6. 完成後會看到以下畫面
![](./img/GitHub/register_05.png)

## 建立小組專案
1. 進入課程提供之專案  
（請確實確認是 [BaseProject](https://github.com/1081-FCU-SE/BaseProject) 專案，而非現在這個 Tutorial 專案）  
![](./img/GitHub/create_team_01.png)
2. 按下 `Fork` ，若出現以下視窗，請選擇自己的帳號  
![](./img/GitHub/create_team_02.png)
3. 等待專案建立  
![](./img/GitHub/create_team_03.png)
3. 進入剛建立的專案，由專案名稱確認，該專案是由課程提供之專案fork出來的  
![](./img/GitHub/create_team_04.png)

## 開啟 Issue Tracker
由於助教需要透過 Issue Tracker 與大家溝通，請進入 `Settings` → `Options`，勾選 `Issues`  
![](./img/GitHub/issue_01.png)

## 將其他組員設定為協作者
1. 點擊 `Settings` → `Collaborators` 進入協作者設定頁面  
![](./img/GitHub/collaborator_01.png)
2. 輸入組員帳號，並按下 `Add collaborator`  
![](./img/GitHub/collaborator_02.png)
3. 等待組員接受邀請  
（可請組員收信並點擊通知信件中的連結，或點擊 `Copy invite link` 複製連結請組員點擊）  
![](./img/GitHub/collaborator_03.png)  
![](./img/GitHub/collaborator_04.png)
4. 組員點擊 `Accept invitation` 接受邀請連結，並成為協作者  
![](./img/GitHub/collaborator_05.png)
5. 當組員看到以下訊息，即表示已成為該專案之協作者  
![](./img/GitHub/collaborator_06.png)

## 上傳檔案
1. 進入小組作業專案  
![](./img/GitHub/upload_01.png)
2. 進入欲上傳檔案之路徑，點擊右上方的 `Upload files`  
![](./img/GitHub/upload_02.png)
3. 進入上傳介面  
![](./img/GitHub/upload_03.png)
4. 選擇檔案，並於 Commit changes 填寫 commit message 之後，點擊 `Commit changes`  
![](./img/GitHub/upload_04.png)
5. 上傳後，即可於該路徑看到上傳之檔案  
![](./img/GitHub/upload_05.png)
