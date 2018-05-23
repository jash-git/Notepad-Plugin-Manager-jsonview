Notepad++ 7.5 取消預設安裝 Plugin Manager (在Notepad++7.5.6 Portable 安裝jsonview元件) 實驗筆記

資料來源:http://blog.darkthread.net/post-2017-11-05-npp-removed-pluginmanager.aspx

目前的狀況，要安裝插件我們有兩種選擇:

第一種選擇是自己手動把 Plugin Manager 裝回來。到 Github 下載 nppPluginManager ZIP 檔[ https://github.com/bruderstein/nppPluginManager/releases ]，解壓縮後有兩個目錄，將 plugins 下的 PluginManager.dll 放到 C:\Program Files (x86)\Notepad++\plugins，將 updater 下的 gpup.exe 放在 C:\Program Files (x86)\Notepad++\updater，Plugin Manager 就回來了。

第二種選擇則是自己下載插件手動安裝。在 Notepad++ 官網有一份完整的 Plugin 清單[ http://docs.notepad-plus-plus.org/index.php?title=Plugin_Central ]，找到所需項目，連結到下載網頁取得檔案，再依各插件的安裝說明將所需檔案放到 C:\Program Files (x86)\Notepad++ 的 plugins 目錄及程式主目錄即可。

實驗心得
	我在7.5.6的Portable版選擇第一個方法