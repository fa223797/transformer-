1、克隆仓库；第一步可以省略，cd不能省略：
git clone （复制github里面https://连接）
cd （上面.git的文件夹名）

1.2（可选）拉取最新更新：
git checkout main
git pull origin main

2.添加提交本地：
git add . 
git commit -m "Your commit message"

3、推送github：
git push origin main

4、查看提交记录：
git log