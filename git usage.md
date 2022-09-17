# 通过具体使用来总结命令(Updating)
## clone GitHub仓库到本地
```git clone git@github.com:woxinpengpai/note.git ```
将note仓库clone到本地，完成后可以看见新增了 ```note``` 文件夹
## 上传文件
```
cd note
touch test.txt
vi test.txt
git status git log # 随时可用来查看状态和日志
git add test.txt # 将文件添加到临时缓冲区
git commit -m "提交信息" # -m用于提交暂存区的文件；-am用于提交跟踪过的文件
git log / git status # 查看日志和状态
git push origin main # 提交到GitHub
```
总结就3步：
1. git add filename
2. git commit -m "commit information"
3. git push origin main


关于git commit 参考[这里](https://blog.csdn.net/lovedingd/article/details/115139025)
有时是 -m 有时是 -am,具体视文件状态而定
"commit information"最终会出现在github 相应文件预览页面最上面
git push 参考[here](https://www.zhihu.com/question/27712995)
