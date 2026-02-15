本地测试打开方式：
在你的项目文件夹打开 Git Bash，运行：

python -m http.server 8000


然后浏览器打开：

http://localhost:8000/

当你在网页里添加新单词后：

点击 导出 CSV（下载到电脑/手机）

回到 GitHub 仓库，上传这个新的 vocab.csv 覆盖旧的（同名上传即可）

Commit changes

手机/电脑刷新页面 → 全部同步

这就是“免费又安全”的同步方法。



因为网页不能直接把修改写回 GitHub（除非用 token，不建议你现在搞），所以同步方式是：



你在网页里增删改



点击 导出 CSV（它会导出为 vocab.csv）



把这个 vocab.csv 上传覆盖 GitHub 仓库里的 vocab.csv



手机刷新网页 → 全部同步

